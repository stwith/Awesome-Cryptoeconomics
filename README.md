# Awesome-Cryptoeconomics


[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Welcome Aboard the Crypto World

What's Cryptoeconomics?

Some of our friends say Cryptoeconomics approaches combine Cryptography and Economics, but it can not explain the entire of Cryptoeconomics. While we received too many infomations, that make us confused. So we attempt to build a project for organize more knowlege in this area, we believe under the teamwork in this project, we can establish a clear and useful path for our beautiful Crypto future. And here's [How to Contribute.](https://github.com/awesome-cryptoeconomics/awesome-cryptoeconomics/blob/master/CONTRIBUTING.md)


# List Components of Cryptoeconomics

- [Cryptography](#Cryptography)
- [P2P-Network](#P2P-Network)
- [Consensus](#Consensus)
- [Mining](#Mining) 
- [Blockchain](#Blockchain)  
- [Token-Economics](#Token-Economics)  
- [Governance](#Governance)  
- [Privacy](#Privacy)
- [Security](#Security)
- [Adoption](#Adoption)

---



## Cryptography

Brief

To achieve a well-development crypto economy, we need lots of factor. And Cryptography is the most important factor for the entire industry. The most important thing in the blockchain is the Trust, and the trust is from the algorithm, so that we can bring something important thing to the blockchain.

Thats the reason we always say: "Don't Trust, Verify"
you also can try this [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography#readme)

Articles

- [Explaining public-key cryptography to non-geeks](https://medium.com/@vrypan/explaining-public-key-cryptography-to-non-geeks-f0994b3c2d5)
- [What is the math behind elliptic curve cryptography?](https://hackernoon.com/what-is-the-math-behind-elliptic-curve-cryptography-f61b25253da3)
- [How Cryptography Redefines Private Property](https://medium.com/@hugonguyen/how-cryptography-redefines-private-property-34cd93d86036)
- [Introduction to zk-SNARKs with examples](https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b)
- [zksnarks and blockchain scalability](https://hackernoon.com/zksnarks-and-blockchain-scalability-af85e350a93a)
- [Pretty Good Cryptography](https://hackernoon.com/pretty-good-cryptography-2b11959c397c)
- [Public-key (asymmetric) Cryptography using GPG](https://hackernoon.com/public-key-asymmetric-cryptography-using-gpg-5a8d914c9bca)
- [How does RSA work?](https://hackernoon.com/how-does-rsa-work-f44918df914b)
- [How Schnorr signatures may improve Bitcoin](https://medium.com/cryptoadvance/how-schnorr-signatures-may-improve-bitcoin-91655bcb4744)
- [BLS signatures: better than Schnorr](https://medium.com/cryptoadvance/bls-signatures-better-than-schnorr-5a7fe30ea716)
- [ECDSA is not that bad: two-party signing without Schnorr or BLS](https://medium.com/cryptoadvance/ecdsa-is-not-that-bad-two-party-signing-without-schnorr-or-bls-1941806ec36f)

Videos

- [Cryptography For Beginners](https://www.youtube.com/watch?v=cqgtdkURzTE)
- [Lecture 1: Introduction to Cryptography by Christof Paar](https://www.youtube.com/watch?v=2aHkqB2-46k)
- [Introduction to Cryptoeconomics - Vitalik Buterin](https://www.youtube.com/watch?v=pKqdjaH1dRo)
- [Public Key Cryptography: RSA Encryption Algorithm](https://www.youtube.com/watch?v=wXB-V_Keiu8)
- [Cryptography: Crash Course Computer Science #33](https://www.youtube.com/watch?v=jhXCTbFnK8o)
- [Cryptography for Cryptocurrency (covers Ethereum and Bitcoin)](https://www.youtube.com/watch?v=Fyqtl7eGQZY)
- [Bitcoin - Cryptographic hash function](https://www.youtube.com/watch?v=0WiTaBI82Mc)

Lessons

- [crypto-textbook](http://www.crypto-textbook.com/)
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography)


## P2P-Network 

Brief

Peer-to-peer (P2P) computing or networking is a distributed application architecture that partitions tasks or workloads between peers. Peers are equally privileged, equipotent participants in the application.

Articles

- [Peer to peer](https://en.wikipedia.org/wiki/Peer-to-peer)
- [Distributed hash table](https://en.wikipedia.org/wiki/Distributed_hash_table)
- [Kazaa](https://en.wikipedia.org/wiki/Kazaa)
- [BitTorrent -- The Original BitTorrent Client](https://www.bittorrent.com/)
- [Crypto Tokens: A Breakthrough in Open Network Design](https://medium.com/@cdixon/crypto-tokens-a-breakthrough-in-open-network-design-e600975be2ef)
- [Why Decentralization Matter](https://medium.com/s/story/why-decentralization-matters-5e3f79f7638e)
- [A Guide to Building Your First Decentralized Application](https://www.youtube.com/watch?v=gSQXq2_j-mw&t=3s)
- [How the Bitcoin protocol actually works](http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/)
- [The Byzantine Generals Problem](https://www.microsoft.com/en-us/research/publication/byzantine-generals-problem/)

Videos

- [Forget Cloud: The Peer-to-Peer Web](https://www.youtube.com/watch?v=ZrUHx-bnfZI)
- [Peer-to-peer (P2P) Networks - Basic Algorithms](https://www.youtube.com/watch?v=kXyVqk3EbwE&list=PL_rf_lwCV7MDXeXLobnsP2uYeiv07AVKV)
- [Lecture: P2P Networking in Bitcoin and tinybitcoinpeer.py](https://www.youtube.com/watch?v=seGwYw2u3TY)
- [Peer-to-Peer Networking on Ethereum](https://www.youtube.com/watch?v=RA7wPpyUGJw)


## Consensus

Brief

Before the blockchain technology, we use Byzantine fault tolerance (BFT) on distributed computing systems, and we have Practical Byzantine fault tolerance (PBFT) at 1999, which provides high-performance Byzantine state machine replication, processing thousands of requests per second with sub-millisecond increases in latency.

One example of BFT in use is bitcoin, a peer-to-peer digital cash system. The bitcoin network works in parallel to generate a blockchain with proof-of-work allowing the system to overcome Byzantine failures and reach a coherent global view of the system's state.

And that is the Consensus when we have a coherent global state in one system. There's more than one way to reach consensus, such like PoW/PoS/DPoS, no matter what kind of ways, we use encryption algorithm to protect the procedure.

Articles

- [ConsensusPedia: An Encyclopedia of 30 Consensus Algorithms](https://hackernoon.com/consensuspedia-an-encyclopedia-of-29-consensus-algorithms-e9c4b4b7d08f)
- [The Problem with Proof of Work](https://medium.com/@OhGodAGirl/the-problem-with-proof-of-work-da9f0512dad9)
- [On consensus](https://medium.com/@jcliff/on-consensus-e47920cd8914)
- [How Does Distributed Consensus Work?](https://medium.com/s/story/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95)
- [A Hitchhiker’s Guide to Consensus Algorithms](https://hackernoon.com/a-hitchhikers-guide-to-consensus-algorithms-d81aae3eb0e3)
- [Frontend in 2018: More consensus, less complexity](https://blog.logrocket.com/what-im-looking-for-from-frontend-in-2018-2f1de300b548)
- [Consensus Compare: Casper vs. Tendermint](https://blog.cosmos.network/consensus-compare-casper-vs-tendermint-6df154ad56ae)
- [Consensus in Blockchain Systems. In Short.](https://medium.com/@chrshmmmr/consensus-in-blockchain-systems-in-short-691fc7d1fefe)
- [A Guide to 99% Fault Tolerant Consensus](https://vitalik.ca/general/2018/08/07/99_fault_tolerant.html)

Understanding Blockchain Fundamentals

- [Part 1: Byzantine Fault Tolerance](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-1-byzantine-fault-tolerance-245f46fe8419)
- [Part 2: Proof of Work & Proof of Stake](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-2-proof-of-work-proof-of-stake-b6ae907c7edb)
- [Part 3: Delegated Proof of Stake](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-3-delegated-proof-of-stake-b385a6b92ef)

Videos

- [Protocol and Consensus: A High Level Overview](https://www.youtube.com/watch?v=fgSvXFZ1GuU)
- [What is Consensus: Rules without Rulers](https://www.youtube.com/watch?v=2tqo7PX5Pyc)
- [Consensus and Mining on the Blockchain](https://www.youtube.com/watch?v=2HcmwfVzPEU)
- [Bitcoin - Proof of work](https://www.youtube.com/watch?v=9V1bipPkCTU)
- [Consensus Algorithms, Blockchain Technology and Bitcoin UCL - by Andreas M. Antonopoulos](https://www.youtube.com/watch?v=fw3WkySh_Ho)
- [Proof of Work vs Proof of Stake - Clearly Explained](https://www.youtube.com/watch?v=y_hEezRilCY)
- [Proof of Work vs Proof of Stake - Explained for Beginners](https://www.youtube.com/watch?v=5x1X_mdo2mY)


## Mining

Articles

- [What is Bitcoin Mining?](https://www.weusecoins.com/en/mining-guide/) A basic article introducing Bitcoin Mining with video and pictures.
- [Mining Centralization Scenarios](https://medium.com/@jimmysong/mining-centralization-scenarios-b74102adbd36) Describe some Scenarios of Mining Centralization
- [Bitcoin Mining Guide - Getting started with Bitcoin mining](https://www.bitcoinmining.com/getting-started/) Detailed the steps for bitcoin mining
- [The State of Cryptocurrency Mining](https://blog.sia.tech/the-state-of-cryptocurrency-mining-538004a37f9b) An article about the whole mining industry. 
- [Decoding the enigma of Bitcoin Mining — Part I : Mechanism](https://medium.com/all-things-ledger/decoding-the-enigma-of-bitcoin-mining-f8b2697bc4e2) An Introduction of Bitcoin Mining through PoW
- [The Bitcoin Mining Network](https://coinshares.co.uk/wp-content/uploads/2018/11/Mining-Whitepaper-Final.pdf) A paper about mining Trends, Marginal Creation Cost, Electricity Consumption & Sources 
- [An Honest Explanation of Price, Hashrate & Bitcoin Mining Network Dynamics](https://medium.com/coinshares/an-honest-explanation-of-price-hashrate-bitcoin-mining-network-dynamics-f820d6218bdf)
- [Beware of Lazy Research: Let’s Talk Electricity Waste & How Bitcoin Mining Can Power A Renewable Energy Renaissance](https://medium.com/coinshares/beware-of-lazy-research-c828c900b7d5)
- [A Introduction of ethereum mining](http://ethdocs.org/en/latest/mining.html)
- [Why Ethereum should adjust algo on next planned Hardfork? From a Miner’s perspective](https://medium.com/@bitsbetrippin/why-ethereum-should-adjust-algo-on-next-planned-hardfork-from-a-miners-perspective-aa0afeef05b9) Miner's influence on the hardfork.

Website of Tools

- [Explore](https://www.blockchain.com/explorer)
- [Some pool suppliers](https://pool.bitcoin.com/en/)

Videos
- [Blockchain Basics Explained - Hashes with Mining and Merkle trees](https://www.youtube.com/watch?v=lik9aaFIsl4)
- [Probability in Bitcoin Mining: The Hashing Function](https://www.youtube.com/watch?v=mMxkxwPSfvo)
- [What Bitcoin Miners Actually Do](https://www.youtube.com/watch?v=TD09UhjIeK8)
- [Bitcoin Mining Explained](https://www.youtube.com/watch?v=iyq4od8MBoE)
- [Blockchain tutorial 24: Blockchain and miners](https://www.youtube.com/watch?v=s7-8a71KgT4)a video who explains bitcoin and miners so clearly
- [Noob's Guide To Bitcoin Mining - Super Easy & Simple](https://www.youtube.com/watch?v=Q5hfr5poLl0)
- [How to start Bitcoin mining for beginners (SUPER EASY) - ULTIMATE GUIDE](https://www.youtube.com/watch?v=lAW5fqkL-Fo)
- [How Much Can You Make Mining Bitcoin With 6X 1080 Ti Beginners Guide](https://www.youtube.com/watch?v=woxKtAnmwEY)


## Blockchain

Brief

Blockchain provides an immutable & decentralized ledger.

Articles

- [A Beginner’s Guide to Blockchain](https://hackernoon.com/a-beginners-guide-to-blockchain-d04266844e7)
- [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
- [Monero Research](https://ww.getmonero.org/resources/research-lab/)
- [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
- [The Blockchain Economy: A beginner’s guide to institutional cryptoeconomics](https://medium.com/cryptoeconomics-australia/the-blockchain-economy-a-beginners-guide-to-institutional-cryptoeconomics-64bf2f2beec4)

Videos

- [Blockchain Technology Explained (2 Hour Course)](https://www.youtube.com/watch?v=qOVAbKKSH10)
- [How does a blockchain work - Simply Explained](https://www.youtube.com/watch?v=SSo_EIwHSd4)


## Token-Economics

Articles

- [The Token Economy](https://thecontrol.co/the-token-economy-81becd26b9de) Understanding the power of network ownership effects
- [A beginner’s guide to Ethereum tokens](https://blog.coinbase.com/a-beginners-guide-to-ethereum-tokens-fbd5611fe30b) This beginner’s guide should help those who are new to digital assets to understand Ethereum tokens at a high level and how they are different than Ethereum.
- [Analyzing Token Sale Models](https://vitalik.ca/general/2017/06/09/sales.html)
- [Tokenomics — A Business Guide to Token Usage, Utility and Value](https://medium.com/@wmougayar/tokenomics-a-business-guide-to-token-usage-utility-and-value-b19242053416)
- [Cryptoasset Valuations](https://medium.com/@cburniske/cryptoasset-valuations-ac83479ffca7)
- [UNDERSTANDING TOKEN VELOCITY](https://multicoin.capital/2017/12/08/understanding-token-velocity/)
- [multi-dimensional tool for understanding and classifying crypto tokens](http://www.untitled-inc.com/the-token-classification-framework-a-multi-dimensional-tool-for-understanding-and-classifying-crypto-tokens/)
- [The Quantity Theory of Money for Tokens
](https://blog.coinfund.io/the-quantity-theory-of-money-for-tokens-dbfbc5472423)
- [Token Engineering Case Studies](https://blog.oceanprotocol.com/token-engineering-case-studies-b44267e68f4)
- [History Is Rhyming: Fitness Functions & Comparing Blockchain Tokens To The Web](https://hackernoon.com/history-is-rhyming-fitness-functions-comparing-blockchain-tokens-to-the-web-3c117239f4c)
- [IN THE FUTURE, EVERYONE WILL HAVE THEIR OWN CRYPTOCURRENCY.](http://simondlr.com/post/70089813484/in-the-future-everyone-will-have-their-own)
- [Does your dapp need a token?](https://medium.com/@simondlr/does-your-dapp-need-a-token-39412fd3c62c)
- [The perfect token sale structure](https://blog.coinbase.com/the-perfect-token-sale-structure-63c169789491) It's about the perfect structure of the token sale
- [Blockchain Tokens and the dawn of the Decentralized Business Model](https://blog.coinbase.com/app-coins-and-the-dawn-of-the-decentralized-business-model-8b8c951e734f)
- [Crypto Narrative Watch: Crypto Winter Edition](https://tokeneconomy.co/crypto-narrative-watch-crypto-winter-edition-bf1cf584def2) 

Videos

- [Token Economies](https://www.youtube.com/watch?v=XatEoU36U-o) Explained the workings of the blockchain, tokens, distributed markets and token investments.

## Governance

Articles

- [Blockchain Governance: Programming Our Future](https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74)
- [Notes on Blockchain Governance](https://vitalik.ca/general/2017/12/17/voting.html)
- [Thoughts On Governance and Network Effects](https://blog.aragon.org/thoughts-on-governance-and-network-effects-f40fda3e3f98/)
- [Against on-chain governance](https://medium.com/@Vlad_Zamfir/against-on-chain-governance-a4ceacd040ca)
- [On Public and Private Blockchains](https://blog.ethereum.org/2015/08/07/on-public-and-private-blockchains/)


## Privacy

Articles

- [Privacy on the blockchain by Vitalik Buterin](https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain/)
- [Privacy on the blockchain](https://hackernoon.com/privacy-on-the-blockchain-7549b50160ec)
- [How the Bitcoin protocol actually works](http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/)
- [A brief history of Bitcoin hacks and frauds](https://arstechnica.com/tech-policy/2017/12/a-brief-history-of-bitcoin-hacks-and-frauds/)
- [Ethereum: Signing and Validating](https://medium.com/@angellopozo/ethereum-signing-and-validating-13a2d7cb0ee3)


## Security

attack
- [Crypto51](https://www.crypto51.app/)
- [51% Attack Calculator: New Site Exposes Major Weaknesses in Small Coins, Shocks Community](https://blockonomi.com/51-attack-calculator/)
- [Blockchain: how a 51% attack works](https://medium.com/coinmonks/what-is-a-51-attack-or-double-spend-attack-aa108db63474)
https://blog.peckshield.com/blog.html
- [How the winner got Fomo3D prize — A Detailed Explanation](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f)


articles

- [MEDIA Protocol And Blockchain Security — Part 1-8](https://medium.com/@mediaprotocolsm/media-protocol-and-blockchain-security-part-1-31b42de2bf07)
- [Blockchain Security Mechanisms](https://towardsdatascience.com/mechanisms-securing-blockchain-data-9e762513ae28)
- [Engineering Security Through Coordination Problems](https://vitalik.ca/general/2017/05/08/coordination_problems.html)
- [Keepers — Workers that Maintain Blockchain Networks](https://medium.com/@rzurrer/keepers-workers-that-maintain-blockchain-networks-a40182615b66)
- [Understanding Crypto-Economic Security through Game Theory](https://blockchainatberkeley.blog/understanding-crypto-economic-security-through-game-theory-526e810c7736)
- [How to secure your digital currency](https://blog.coinbase.com/how-to-secure-your-digital-currency-4f63539837d0)
- [STARKs, Part I: Proofs with Polynomials](https://vitalik.ca/general/2017/11/09/starks_part_1.html)
- [STARKs, Part II: Thank Goodness It's FRI-day](https://vitalik.ca/general/2017/11/22/starks_part_2.html)
- [PeckShield Blog](https://blog.peckshield.com/blog.html)


## Adoption

Brief

This is the early stage for crypto industry. Base on blockchain 1.0/2.0, more possiblities are coming, with more government trying to adopt and recognize this improvement. There's still some obstacles on the way, sometimes we compromise, sometimes we have to build a bridge, and here's some info for you to understand the difficulties currently.

Articles

- [We already know blockchain’s killer apps](https://hackernoon.com/we-already-know-blockchains-killer-apps-f2d443eba35)
- [Blockchain Adoption in the Energy Sector — on a Massive Scale](https://medium.com/@social_72385/blockchain-adoption-in-the-energy-sector-on-a-massive-scale-a71c490be377)
- [Blockchain Adoption and Digital Privacy](https://medium.com/mit-cryptoeconomics-lab/blockchain-adoption-and-digital-privacy-b94210122021)
- [Blockchain Adoption: How Close Are We Really?](https://www.forbes.com/sites/luuloi/2018/01/26/blockchain-adoption-how-close-are-we-really/#6cf637fad9dc)
- [Blockchain's adoption in IoT: The challenges, and a way forward](https://www.sciencedirect.com/science/article/pii/S1084804518303473)
- [Europe Is a Leader in Blockchain Adoption](https://www.entrepreneur.com/article/322313)
- [the bumpy ride to blockchain adoption](https://medium.com/altcoin-magazine/9-big-obstacles-to-mass-adoption-of-blockchain-technology-5b9b82558644)
- [9 Big Obstacles to Mass Adoption of Blockchain Technology](https://medium.com/altcoin-magazine/9-big-obstacles-to-mass-adoption-of-blockchain-technology-5b9b82558644)


Adoption

- [Maker Dai - stable coin](https://makerdao.com/dai/)
- [0x Project - decentralized exchange](https://blog.0xproject.com/)



## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)




