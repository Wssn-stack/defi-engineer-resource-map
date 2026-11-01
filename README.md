## Credits & Source

This repository is a curated, filtered, and AI-assisted reorganization of the original resource list from the OffcierCia DeFi Developer Road Map. It is not a copy or replica of the original repository; rather, it separates, compresses, and prioritizes the most relevant material for a specific learning path.

Original source:
- Repository: https://github.com/OffcierCia/DeFi-Developer-Road-Map
- Main resource section: https://github.com/OffcierCia/DeFi-Developer-Road-Map#basics

This project narrows the broader ecosystem into a more practical and structured path for:
- blockchain security
- smart contract auditing
- DeFi protocol research
- DeFi engineering

All credit for the original research, links, and resource collection belongs to the authors and contributors of the original roadmap. This repository is intended to make the material easier to navigate and more relevant to a chosen specialization.

# defi-engineer-resource-map
Curated learning resources and roadmap for becoming a DeFi engineer, filtered from the OffcierCia DeFi Developer Road Map.

# DeFi Engineer Resource Map

Curated and filtered resources for becoming a DeFi Engineer, with a strong focus on:
- Solidity / smart contract engineering
- EVM and Ethereum fundamentals
- DeFi protocol understanding
- DeFi frontend integration
- security mindset
- real-world project building

This repository is intentionally curated from the broader OffcierCia DeFi Developer Road Map and narrowed to the most practical and high-signal resources for a DeFi Engineer path.

---

## Why this repo exists

The original DeFi Developer Road Map is very rich, but it also includes many resources across:
- blockchain basics
- security research
- ZK
- NFTs
- general Web3
- advanced academic papers

For someone who wants to become a DeFi Engineer, the best approach is not to study everything equally. The right path is:

1. Learn Ethereum + EVM fundamentals
2. Learn Solidity and smart contract development
3. Learn real DeFi protocol mechanics
4. Build DeFi products with frontend + wallet integration
5. Learn security and operational risk
6. Build portfolio projects

This repo filters the material to that path.

---

## Learning Path

### 1) Foundations
Focus on understanding blockchain, Ethereum, EVM, wallets, gas, transactions, and accounts.

#### Core resources
- Ethereum Docs: https://ethereum.org/en/developers/docs/
- Solidity Docs: https://docs.soliditylang.org/
- Mastering Ethereum: https://github.com/ethereumbook/ethereumbook
- EVM Docs: https://www.evm.codes/
- Learn Git: https://git-scm.com/doc
- HTTP / APIs: https://developer.mozilla.org/en-US/docs/Web/HTTP
- Linux + terminal basics: https://ubuntu.com/tutorials/command-line-for-beginners

#### Wallets, transactions, and RPC
- MetaMask docs: https://docs.metamask.io/
- WalletConnect docs: https://docs.walletconnect.com/
- Ethereum transaction lifecycle: https://ethereum.org/en/developers/docs/transactions/
- RPC providers: Alchemy, Infura, QuickNode
- Gas and fee concepts: https://ethereum.org/en/developers/docs/gas/

#### Important deep dives
- NOXX: https://noxx.substack.com/
- EVM Chad: https://github.com/mektigboy/evm-chad
- EVM article series by Zaryab: https://www.zaryabs.com/ethereum-virtual-machine-article-series/
- Understanding Trie databases in Ethereum: https://medium.com/shyft-network/understanding-trie-databases-in-ethereum-9f03d2c3325d

#### Practical learning
- Teach Yourself Crypto: https://teachyourselfcrypto.com
- Capture The Ether: https://capturetheether.com/
- OpenZeppelin docs: https://docs.openzeppelin.com/contracts/

---

### 2) Smart Contract Development
This is the core track for DeFi engineering.

#### Solidity resources
- Solidity by Example: https://solidity-by-example.org/
- Cryptozombies: https://cryptozombies.io/
- WTF Solidity: https://github.com/AmazingAng/WTF-Solidity
- Smart Contract Engineer: https://www.smartcontract.engineer
- smartcontract.engineer courses: https://www.smartcontract.engineer

#### Solidity patterns and best practices
- OpenZeppelin Contracts: https://github.com/OpenZeppelin/openzeppelin-contracts
- ConsenSys best practices: https://consensys.github.io/smart-contract-best-practices/
- Solidity security teaching resources: https://github.com/jcr-security/solidity-security-teaching-resources
- Useful Solidity Patterns: https://github.com/dragonfly-xyz/useful-solidity-patterns
- Proxy patterns and upgradeability: https://blog.openzeppelin.com/proxy-patterns/

#### Tooling
- Foundry: https://book.getfoundry.sh/
- Hardhat: https://hardhat.org/
- Remix: https://remix.ethereum.org/
- Solhint: https://github.com/protofire/solhint
- Slither: https://github.com/crytic/slither
- Mythril: https://github.com/ConsenSys/mythril
- Echidna: https://github.com/crytic/echidna
- TypeChain: https://github.com/dethcrypto/TypeChain

#### Testing and invariants
- Foundry test / fuzzing workflow: https://book.getfoundry.sh/forge/tests
- EVM invariant testing mindset: https://book.getfoundry.sh/forge/invariant-testing
- Test patterns and exploit reproduction: Damn Vulnerable DeFi, Ethernaut, Foundry examples

---

### 3) Ethereum & DeFi Protocol Fundamentals
A DeFi Engineer is not only building contracts; they must understand how real protocols work.

#### DeFi foundations
- SoK: Decentralized Finance (DeFi): https://arxiv.org/pdf/2101.08778.pdf
- DeFi-ning DeFi: Challenges & Pathway: https://arxiv.org/pdf/2101.05589.pdf
- Finematics YouTube: https://www.youtube.com/c/Finematics/featured
- DeFi research and protocols: https://arxiv.org/search/?query=defi+blockchain

#### AMM / DEX
- A theory of Automated Market Makers in DeFi: https://arxiv.org/pdf/2102.11350.pdf
- An analysis of Uniswap markets: https://arxiv.org/pdf/1911.03380.pdf
- Composing Networks of Automated Market Makers: https://arxiv.org/pdf/2106.00083.pdf
- Uniswap docs: https://docs.uniswap.org/
- Curve docs: https://resources.curve.fi/
- Balancer docs: https://docs.balancer.fi/

#### Lending / borrowing / liquidations
- Liquidations: DeFi on a Knife-edge: https://arxiv.org/pdf/2009.13235v4.pdf
- From banks to DeFi: the evolution of the lending market: https://arxiv.org/pdf/2104.00970.pdf
- Aave docs: https://docs.aave.com/
- Compound docs: https://docs.compound.finance/
- Health factor and liquidation threshold modeling: https://docs.aave.com/

#### Stablecoins
- Stablecoins 2.0: https://arxiv.org/pdf/2006.12388.pdf
- Stablecoin and peg stability analysis
- MakerDAO docs: https://docs.makerdao.com/
- DAI and CDP mechanics: https://makerdao.com/en/whitepaper/

#### Oracles
- SoK: Oracles from the Ground Truth to Market Manipulation: https://arxiv.org/pdf/2106.00667.pdf
- Chainlink docs: https://docs.chain.link/
- TWAP / Oracle risk in AMMs: https://docs.uniswap.org/

#### MEV
- Flash Boys 2.0: https://arxiv.org/pdf/1904.05234.pdf
- Quantifying Blockchain Extractable Value: https://arxiv.org/pdf/2101.05511v2.pdf
- Flashbots docs: https://docs.flashbots.net/
- Ethereum mempool and ordering dynamics: https://www.flashbots.net/

#### Governance and token dynamics
- Governance and voting power in DeFi: https://arxiv.org/pdf/2102.10096.pdf
- Timelock and governance safety patterns: https://docs.openzeppelin.com/contracts/4.x/governance

---

### 4) DeFi Frontend / Full Stack Integration
A strong DeFi Engineer also needs to understand how to connect smart contracts to a user-facing app.

#### Frontend stack
- React: https://react.dev/
- Next.js: https://nextjs.org/
- TypeScript: https://www.typescriptlang.org/
- Ethers.js: https://docs.ethers.org/
- viem: https://viem.sh/
- wagmi: https://wagmi.sh/
- RainbowKit: https://www.rainbowkit.com/
- Web3Modal: https://docs.walletconnect.com/web3modal/about

#### Wallet / chain integration
- MetaMask: https://metamask.io/
- WalletConnect: https://walletconnect.com/
- Etherscan APIs: https://docs.etherscan.io/
- RPC providers:
  - Alchemy: https://www.alchemy.com/
  - Infura: https://www.infura.io/
  - QuickNode: https://www.quicknode.com/
- Layer 2 / EVM networks: Base, Arbitrum, Optimism, Polygon

#### Data / indexing / backend
- The Graph: https://thegraph.com/
- Envio: https://envio.dev/
- HyperIndex / Envio event indexing pattern: https://envio.dev/
- Dune Analytics: https://dune.com/
- Formo: https://formo.so/

#### Frontend & DeFi patterns
- Connect wallet
- Display balances
- Handle approvals
- Detect chain changes
- Estimate gas
- Read/write contract state
- Handle transactions and errors
- Build dashboard UIs for AMM, lending, staking, and governance

---

### 5) DeFi Security and Risk Mindset
DeFi engineering must always include security thinking. This is one of the most important differences between “Web3 dev” and “DeFi engineer”.

#### Security resources
- Ethernaut: https://ethernaut.openzeppelin.com/
- Damn Vulnerable DeFi: https://www.damnvulnerabledefi.xyz/
- SCSVS: https://github.com/ComposableSecurity/SCSVS
- Smart Contract Attack Vectors: https://github.com/KadenZipfel/smart-contract-attack-vectors
- Not So Smart Contracts: https://github.com/crytic/not-so-smart-contracts
- DeFi security resources: https://github.com/freight-chain/defi-sec
- Secureum Bootcamp: https://hackmd.io/@secureum/bootcamp-epoch0-announcement

#### Common issues to learn
- reentrancy
- access control
- oracle manipulation
- price attack vectors
- governance risk
- flashloan abuse
- liquidation failures
- upgradeability risks
- approval / token transfer problems
- composability risks
- front-running / sandwich attacks

---

### 6) Practical DeFi Projects
The fastest way to become a real DeFi Engineer is by building.

#### Beginner projects
- ERC20 token with mint/burn and transfer logic
- basic staking contract
- simple vesting contract
- lending vault prototype
- governance contract with timelock
- flashloan demo
- simple AMM pool

#### Intermediate projects
- DEX frontend + smart contract
- lending dashboard with borrow/repay
- yield strategy dashboard
- token swap interface
- portfolio tracker with wallet integration
- governance voting dashboard

#### Advanced projects
- risk calculator
- liquidation monitor
- DeFi analytics dashboard
- strategy optimizer
- protocol comparison dashboard
- cross-chain bridge / routing interface

---

### 7) Core Reading Order (Recommended)
If you want a practical order, use this:

1. Ethereum basics
2. EVM fundamentals
3. Solidity basics
4. ERC20 and token logic
5. Foundry / Hardhat
6. AMM and DEX mechanics
7. Lending and liquidation
8. Stablecoin logic
9. Oracles and risk
10. MEV and front-running issues
11. DeFi frontend + wallet integration
12. Security auditing mindset
13. Deploy and build real portfolio projects

---

## Best resources to prioritize first
These are the most useful and high-signal resources for a real DeFi Engineer path:

- Ethereum Docs
- Solidity Docs
- Mastering Ethereum
- OpenZeppelin docs
- EVM docs
- Solidity by Example
- Foundry book
- Hardhat docs
- A theory of Automated Market Makers in DeFi
- SoK: Decentralized Finance (DeFi)
- Flash Boys 2.0
- SoK: Oracles from the Ground Truth to Market Manipulation
- Ethernaut
- Damn Vulnerable DeFi
- Slither
- Uniswap docs
- Aave docs
- Chainlink docs
- The Graph
- Envio
- Dune Analytics

---

## Recommended Stack
For a modern DeFi Engineer path, the practical stack is:

- Solidity
- Foundry or Hardhat
- OpenZeppelin
- Ethers.js / viem / wagmi
- React / Next.js
- WalletConnect / RainbowKit
- Alchemy / Infura / QuickNode
- The Graph / subgraphs / indexers
- Slither / Mythril / static analysis
- GitHub + Docker + terminal workflow

---

## Final advice
Do not try to consume every DeFi resource in the ecosystem. Instead:

- learn the fundamentals well
- build small protocol primitives
- understand real DeFi systems
- connect frontend to on-chain logic
- focus on security and risk
- ship projects and iterate

The real DeFi Engineer path is:
Smart contract engineering + protocol understanding + frontend integration + security mindset.

That is the discipline to aim for.

---

## Repository goal
This repository exists to be a practical resource map, not a giant dump of links. It is designed to help you move from:
- beginner Web3 learner
to
- DeFi engineer capable of building and reasoning about real protocols.

---

## License
Educational resource only. Not financial advice.
