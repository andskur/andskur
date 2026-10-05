# Andrew Skurlatov

Founders hire me as fractional CTO, from one day a week, before a raise, a launch or a listing. Funds and acquirers hire me, under my own name, to run technical due diligence before they sign.

For ten months I was fractional CTO to DeepNode, designing its decentralised AI infrastructure through its January 2026 token launch and exchange listing. Before that I co-founded Uddug, built it to 15 people, and it was acquired by Gateway.fm in 2024. I advised GoldenGate, a stablecoin issuer, as fractional CTO.

A fund or an acquirer gets the diligence in ten business days: a two-page decision brief first, then the full memo, every finding with its evidence, confidence, consequence and the cost to fix. When a team faces one hard decision, I run a two-week architecture or launch review that ends in a recommendation.

## Systems I led

Wirex Pay is a live L2 chain for a non-custodial debit card. I led its delivery end to end, from the indexer and oracles to account abstraction, with KYC wired in for MiCA alignment. It is a new product on live card rails that did not disrupt the one already running: self-custody card payments with no gas fees. Earlier at Gateway.fm I designed the RPC proxy, a smart proxy system with a cache layer and rate limiting, that served 140k+ requests per second at peak in production for Opera and 1inch, at 50 ms average latency on the heavy requests. Gnosis and the Ethereum Foundation ran on the same proxy, and it had no outages at peak.

Later I led the department that ran Gateway Yield, the infrastructure behind $1B+ locked in staking; it covered Lido, Gnosis, Stellar and Canton, and funds, custodians and protocol foundations staked through it. In the same period I led the build of a shared prover used across several ZK protocols and L2 ecosystems (Polygon zkEVM, cdk-erigon, Miden, Iden3, EY Nightfall), with GPU and CPU autoscaling on spot capacity that can be taken back at any time. Each new ecosystem was onboarded without new infrastructure, at a lower proving cost per chain. I also designed and led an app-kit framework for fintech products and took the RWA, stablecoin and payments kits into client delivery on Polygon, Canton, Miden and Ethereum: one month to market for a regulated fintech product, for less than a custom build.

Two pieces of the work have a public record. I led the build of the event infrastructure and backend for Infinex, the Synthetix front-end, under governance proposal XIP-9, and I presented [CIP-0084](https://lists.sync.global/g/cip-discuss/topic/cip_tbd_canton_evm/116639522) on EVM compatibility to the Canton network's super-validators.

I have 15+ years in software and 10+ in blockchain, and I have launched 20+ projects. At Gateway.fm I was VP of DLT and then VP of Platform and Yield, running about 25 people across two departments; the departments closed in June 2026 and I left. In July 2026 I co-founded Felag, an engineering studio I co-own with Mikhail Manko, my business partner since 2015, and I am its CTO. Felag is the restart of Uddug.

## Code here

[argon2-hashing](https://github.com/andskur/argon2-hashing) is a small Go package for Argon2 password hashes, and [go-microservice-template](https://github.com/andskur/go-microservice-template) is the Go service layout I start from. [gitsec-backend](https://github.com/uddugteam/gitsec-backend), under the Uddug organisation, is the backend of a git repository system on blockchain and IPFS that Uddug built in 2023. [OldNorseDictionary](https://github.com/andskur/OldNorseDictionary) and [Runatal](https://github.com/andskur/Runatal) are two Swift apps I ship outside work, an Old Norse dictionary and an Elder Futhark reference. Most of my work since 2021 sits in private repositories.

## Contact

If the code matters to a deal ahead, write to a.skurlatov@gmail.com, message me on [LinkedIn](https://www.linkedin.com/in/andrew-skurlatov/), or [book 30 minutes](https://calendly.com/and-skur/30min).
