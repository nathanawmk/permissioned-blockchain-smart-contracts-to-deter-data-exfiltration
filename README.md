# permissioned-blockchain-smart-contracts-to-deter-data-exfiltration
A permissioned blockchain with robust smart contract capabilities could be further extended to ensure read access to data is also consensus driven. This way, data exfiltration will require significant effort by the malicious actors. The blockchain solution of today ensures that data that is already written to the blockchain cannot be tampered easily. In addition, the consensus mechanism process of ensuring majority nodes agree before a data can be written to the blockchain means that write operation is secured to a large extent. However, read operation (i.e., privacy) has not been addressed. In this paper, we will explore how read operation can be secured through consensus as an additional layer of protection against data exfiltration by malicious hackers. 

Context

Singapore was hit by the worst data breach known. More than 1.5 million records are affected, presumably exfiltrated. 

SOURCE:
https://www.bbc.com/news/world-asia-44900507
https://www.theverge.com/2018/7/20/17594578/singapore-health-data-hack-sing-health-prime-minister-lee-targeted

Gap

Currently, blockchain only secures write operation and not read operation. To ensure a read only operation can take place, consensus driven mechanism needs to be implemented. With read-only operation secured through a consensus driven mechanism, data exfiltration becomes a lot more difficult -- not impossible, however. 
