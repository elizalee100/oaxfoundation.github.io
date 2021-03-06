---
layout: post
author: OAX Foundation
image: /img/blog-images/Parachain Tech Summary-General.jpeg
---

![]({{ site.baseurl }}/img/blog-images/Parachain Tech Summary-General.jpeg)

<b>OAX Foundation – OAX Parachain Technology Summary</b>

<b>General Industry Background:</b>

As blockchain has continued to evolve over the last few years, we’ve seen the shift from digital currencies to exchanges, ICOs to IEOs and STOs. While still speculative, we can see more practical use cases being developed and now as applications can distribute rewards to stakeholders while remaining decentralized, DeFi has built on the fundamental qualities of blockchain. 

One of the main points of consideration, however, circulates around the scalability and interoperability needed to ensure mass adoption. Projects such as Polkadot are building unprecedented economic scalability by enabling a common set of validators to secure and spread transactions across multiple parallel blockchains (Parachain). 

This scalability, combined with lower transaction fees can help DeFi DApps to reach mass adoption while stakeholders from the real economy will have stronger incentives to increasingly accept digital assets. 

<b>Why Polkadot:</b>

OAX, over the course of the last three years, has approached the digital asset industry by identifying its weaknesses and sought to address their challenges through technological solutions, and working with likeminded partners and platforms.

The key attraction of Polkadot is its goals of tackling interoperability with a scalable network and shared security. Its structure design allows multi-chain application environments that in turn can enable highly scalable systems, in contrast to many other existing blockchain-based systems.

![]({{ site.baseurl }}/img/blog-images/Parachain Tech Summary-Why Polkadot.jpeg)

Polkadot is designed to enable scalable decentralized applications and smart contracts on one blockchain to seamlessly transact with data and assets on other chains, while benefiting from shared security. Hence, Polkadot network has three key pillars:
•	<b>Interoperability:</b> designed to enable applications and smart contracts on one blockchain to seamlessly transact with data and assets on other chains
•	<b>Scalability:</b> gives the ability to run several Parachains, each processing multiple transactions in parallel, which allows networks to obtain “infinite” scalability
•	<b>Shared Security:</b> security is pooled within the network, which means that individual chains can leverage collective security without having to start from scratch to gain traction and trust

![]({{ site.baseurl }}/img/blog-images/OAX-Polkadot.png)

<b>OAX Parachain</b>

OAX Foundation aims to remedy the limited utility of OAX ERC20 tokens by building OAX’s own blockchain, built on Substrate as part of the Polkadot network. The parachain should support DeFi APIs and allow for the creation of UX friendly DApps. 

![]({{ site.baseurl }}/img/blog-images/Parachain Tech Summary-OAX Parachain.jpeg)

The current development of the OAX Parachain is a coordinated dance between the team and existing technology and the Polkadot advancements. At present, the team is focusing on four key features: ERC20 functionality, atomic swap, fee delegation and MultiTransfer.

•	<b>ERC20 functionality:</b> representing other tokens on the OAX Parachain, 
To support DeFi use cases such as lending or swaps, this will be akin to ERC20 on Ethereum or eosio.token on EOS.

•	<b>Atomic swap:</b> allowing swap between two tokens with one single transaction

Traditional blockchains have an API to transfer tokens between wallets. Swaps involve two transfers and atomic swaps are done to ensure that both legs of a swap are guaranteed. Atomic swaps are done using smart contracts involving the swap of two distinct tokens. In the case of a swap between two ERC20 tokens, the chain for both tokens would be Ethereum, but still require two transactions. A native swap substrate runtime module (SRM) would provide the same guaranteed execution, but in one transaction rather than two.

•	<b>Fee delegation:</b> allowing the gas cost to be paid by a third-party

This feature eases adoption for DApps because users do not need to have native OAX tokens in order to transact with the OAX Chain. Ideally, this feature allows the opportunity for users that do not have a particular token, to still pay for gas fees, thereby removing a significant hurdle for DApp adoption.

•	<b>MultiTransfer:</b> allowing developers to batch multiple transactions into one 
By avoiding repeated fields (such as the “from:” address which would be identical for each inner transaction), minimizing duplicate fields would allow for batched transactions to be smaller, hence resulting in a lower gas cost.

The hope is that these features will the only serve as the initial functionalities of the OAX chain, and will include more in the future. The team also believes that they will improve UX and DApps to attract users, a step towards reaching mass adoption. 

<b>OAX Token</b>

OAX has placed the highest priority on addressing the four fundamental challenges that the digital asset ecosystem faces. The work done thus far has existed thanks to the support of the community through reviewing our work and giving feedback on our open source code, but also through our existing OAX ERC20 token. 

Moving forward, we will be exploring a discretionary 1-to-1 token swap when the parachain is complete and stable. The intention would be to keep current supply;
meaning that any OAX token circulating on Polkadot would have been burned on Ethereum beforehand. The primary focus for the team is to ensure that we enhance the utility of the OAX token.


<b>Conclusion</b>

While we’re still in early stages with Polkadot, and the building of the OAX Parachain, the team believes the proposition aligns with the work that has been done since the founding of OAX. Between the vision that Polkadot has, to the strong community that has driven its progress so far, we look forward to bringing additional value and playing our role in the addressing the shortcomings of the digital asset industry: speed, scalability, trust, and now, interoperability. 


