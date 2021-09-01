# The first fully decentralized ecosystem for digital social interactions 


_Everyday people and businesses rely on social media to connect with friends, family, colleagues or clients, making internet social interactions a cornerstone of modern civilization. We envision a new ecosystem, fully decentralized, without gatekeepers or intermediaries, in which its community thrives in a fair and unconstrained environment, making our digital world a better place_

<br />

## Overview
Internet social media are controlled by unavoidable middlemen centralizing all its essential services and capturing financial incentives. The social ecosystem has been developing around those few players and is now restrained by their policies and bends to their agendas. Inevitably everyone must entrust to them their social interactions, their privacy and security and face inequitable practices.This situation has created an unprecedented monopoly on internet communication, which greatly harms individual freedoms and fair competition. In this paper we present a decentralized approach to social interactions in which the monopolizing middlemen are completely removed from the ecosystem. We describe how it can be replaced by a network of trustless nodes working together to provide all the necessary technologies, while ensuring network neutrality.
In doing so, our purpose is to:
- Free social internet interactions from privacy invasion, abuse of dominant position, or any risks of a monopolized market. 
- Bring back the Internet’s control-less user-driven form and revive it as a universal tool for innovation and creativity.
- Restore a fair competition environment and balanced revenue distribution for all the ecosystem actors.

<br />

## Current de facto standards 

After two decades of development, the situation is unbalanced between the contribution actors bring to the ecosystem core value and the responsibility they take in it / the incentive they receive.

Actor | Contribution | Return | 
--- | --- | --- |
General Human User | **HIGH** - Engage, share and interact with contents, representing the essence of the ecosystem and its core value | **NONE** - No incentive for their contribution, nor weight in the ecosystem control | 
Content Creator | **HIGH** - Deliver dedicated contents with entertaining or informative value, enriching and diversifying the ecosystem | **LOW** - mostly marketing value, channeled by centralized authorities and intermediaries  | 
Storage Provider | **LOW** - Handle all contents in the ecosystem. While mandatory, storage offerings are many and costs have greatly decreased over the years | **HIGH** - Capture important shares of revenue by centralizing all authority on storage access  | 
Application Layer | **LOW** - Applications provide and regularly create new interfaces for users to interact with the contents | **HIGH** - Capture important share of revenue by centralizing all authority on user interface access  | 
Advertiser | **MEDIUM** - Advertisers are the main source of financing for the ecosystem and allow large development and scaling without incurring cost for other actors | **MEDIUM LOW** - Digital marketing has proven highly efficient, and advertisers obtain a fair amount of users’ attention through it. However, their return is greatly limited by a complex and monopolized market.  | 

Storage & application providers concentrate all authority over the functionment of the ecosystem and capture most part of its incentives. However, the actual value they bring to the ecosystem has kept on decreasing and has become negligible.
On the other hand, Human users by their attention, engagement and creativity make the core value of the ecosystem. Yet, they do not enjoy a position as essential player within the ecosystem but rather as a product of it. 
Overall, the ecosystem middlemen occupy a technological dominant position allowing them to capture the distribution of control and incentive. 

<br />

## The Decentralized Approach 

In order to overcome monopoly power, Ichigo network transforms the core technology behind social interactions while keeping the existing social ecosystem dynamics. By breaking technical dominance, we remove the necessity to rely on a central authority and enable fair redistribution of the ecosystem control and incentives to every actor. 
To accomplish this, ichigo network relies on cryptography, blockchain and peer-to-peer technologies and provide ecosystem’s essential services:
-	actor’s profile and identification decentralization
-	distributed on-demand storage provision
-	trustless advertising market and promotion
-	dissociated and re-usable application layer

<br />

## Profile and Identification

Every actor of the ecosystem has a unique profile. We rely on cryptographic identity to remove the need for a centralized authority to secure those profiles. Instead, every profile is represented by the profile key-pair and accessible by its cryptographic address. The ichigo nodes will store and distribute user profiles in a user profiles ledger stored in their own peer-to-peer network (i.e. off-chain) while relying on blockchain for its security (similar to a layer-2 solution). 
This profile can be used by human users to maintain profile information and point to a feed of contents present in flash storages. Users can maintain a list of profiles to stay in contact with other users of the network. As we will present hereafter, the application layer will also be able to make use of this profile to provide social interaction interfaces. 
Other actors of the ichigo ecosystem will also rely on a profile to make themselves known to the network and demonstrate their honest services (ichigo nodes, application layer providers and advertisers)

<br />

## Decentralized on-demand storage

Flash storage works on a peer-to-peer network of nodes. It consists in agreements to lease storage space from a node to a user focusing on content of relatively small size and limited period of storage time. This use-case is the most optimized for social interaction and allows greater speed and flexibility. 
For every flash storage lease, the user and the node concur on data size, time frame and cost. The node will then be responsible to make the data available on the network for the specified time frame. Flash storage uses blockchain to ensure security of the network and peer-to-peer technology to make data available to any users. Nodes will be incentivized to work honestly using collaterals / stacking obligations and a reputation system. 

### Flash Storage Security

**General concept**
To provide flash storage the nodes have an obligation to stake tokens in the blockchain, which will be used to lock collaterals, as well as calculating node reputation. An on-chain market marker functionality allows to initiate the flash storage agreement. In there the nodes maintain bids where they specify the conditions (minimum cost, maximum size/period, location, etc). Users can retrieve the most suitable bid for its content. The agreement is established between the node and the user and is sent to be stored along with the payment. The contract will lock user payment and node collateral until the agreement is completed. The node role is to make the data available on the peer-to-peer network until the end of the agreement. It will then be able to retrieve the full amount from the contract as compensation and may garbage collect the user content if needed.

**Dispute resolution system**
The purpose of the dispute resolution system is to discourage dishonest nodes financially and reputationally. When a node enters a flash storage agreement a significant amount of the node’s tokens will be locked as collateral from its stack. If the file becomes unavailable at some point within the agreement time frame anyone can raise a claim to the network. The nodes will then be able to participate in a consensus vote to establish whether the file is available or not. If the file is not available, the responsible node in breach of its agreement will lose all its collateral and its reputation score will be greatly decreased. The user in agreement and the user raising the claim will both be compensated by receiving tokens from the node collateral. Every node who correctly participated in the consensus will also receive a part of the collateral and their reputation score will increase.

**reputation system**
The purpose of the reputation system is to keep track of honest and well performing nodes. The ichigo architecture includes a contract dedicated to keeping a reputation score for every registered node. Honest and helpful activity on the network will increase this score, while breach will drastically decrease it.  In parallel, stacking tokens will also increase the reputation score logarithmically. This can be used by a node with low reputation score to increase its chance to win flash storage bids (for example if the node is new to the network). As the node history builds up and the reputation score increases, they will be able to reduce the amount of token stacked while keeping a satisfactory reputation score.

<br />

## Equitable Advertising marketplace

Advertisement represents the biggest part of the social ecosystem financing. Ichigo ecosystem maintains this source of financing but the distribution of incentives is made fair and transparent between the human user for its attention and engagement, the content creator for the added-value it brings and the application-layer for the interface it provides. Application layer providers can propose to sell ad impressions. They declare their business model to the network which defines the calculation for incentives distribution between ecosystem actors. To avoid deceptions, business models are locked for a certain period before they can be updated again. On the other side, Advertiser can register bids for ad impression specifying their requirements in terms of impression cost, application reputation, business-model, frequency of impression, etc.  Applications that meets those requirements can display the ad to their user. They register the amount of attention the ad gets in the user attention ledger. The settlement of incentives for all actors will be calculated by the ecosystem based on those user attention metrics and the registered application’s business model. A reputation score is kept for all application. This helps advertisers avoid poorly performing or deceptive applications. For example, Third-party services can propose human-readable access to applications’ business-model, their reputation and previous performances and advertisers can maintain black/shite list.

<br />

## Application Layer

Applications provide the human user facing layer to access the network and interact with it. The ichigo ecosystem sets conventions on how to implement 2 key-functionalities: the encryption / decryption routine and the content formatting.
This approach dissociates completely the interface, the storage, and the content itself. Only the human user owns and can access and manage their content. The contents are not locked-in by a specific application, but any applications can commonly interact with it if the user allows it. As seen above, the application layer can be incentivized for this service with advertisement impressions. It will also be possible to allow the apparition of other business models such as subscription, pay per access, etc.

<br />

## Roadmap

2021 Q3 - **Testnet**
*Run ecosystem on test chain*
- Ichigo node v0
- Test wallet
- JS tes SDK

2021 Q4 - **Pre-production**
*Prepare for release*
- Ichigo token launch
- Test wallet v1
- Ichigo node v1

2022 Q2 - **Core Product**
*Real-world launch*
- Ichigo node v2
- Mainnet release
- SDK: js, C#, java

2022 Q3 - **Governance**
*Run ecosystem on test chain*
- Community Governance
- Stacking & validation
- Ad market place launch

<br />

## Project outlines

##### Expanding Team
The ichigo original team is made of early cryptocurrency enthusiasts with accumulated years of experience in infrastructure design, system security, peer-to-peer technology, and smart-contract coding. However, our team is not limited to a few but shall grow and extend to an open community as does the ichigo ecosystem. As our team knows no limit, contributors join and will keep joining from around the world and help build our ecosystem. As the community thrives, a special fund is put in place to distribute financial incentive for every contributor.

##### Community based governance
The governance of the ecosystem should belong to its community including developers, service providers and end-users. While ichigo ecosystem already ensures that the financial incentives are shared in a fair way between all, we aim to achieve the same approach in terms of governance. To do so, the governance will gradually shift from the original team to its community until it achieves a 100% community-based decentralized ecosystem.

##### Tokenomics
Total Supply: 150 billion

Allocation | Share | Tokens(B) | Comment | 
--- | --- | --- | --- |
Public Fund | 51% | 76.5 | Used as financial incentive in the ichigo ecosystem, to purchase storage or ad impression. | 
User growth & startup reward  | 17% | 25.5 |To promote engagement and support ichigo to its early adopter (marketing, airdrop, faucet, etc.) and reward early service providers (storage, consensus nodes, etc.). 20% unlocked on day 0, then monthly unlocking over 12. | 
Ichigo foundation | 15% | 22.5 |To boost development, anticipate future strategic needs and reward all contributors.10% unlocked after 6 months, then monthly unlocking over 12 months. | 
Team | 13% | 19.5 | *see above* | 
Partners & Advisors | 4% | 6 | *see above* | 
