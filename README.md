# NFT-Domain-Leasing-in-a-Blockchain-Based-Secure-DNS-Framework
A decentralized DNS solution leveraging blockchain and NFTs to securely register, lease, and resolve domain names - ensuring tamper-proof, transparent, and Web3-ready domain management.

This project introduces a decentralized, tamper-resistant alternative to traditional DNS using blockchain and NFTs. Each domain is represented as a unique NFT, enabling verifiable ownership, leasing, and decentralized DNS resolution. It addresses major vulnerabilities in conventional DNS by removing centralized control and adding programmable trust.

🌐 Key Features
🏷️ NFT-based domain ownership on Ethereum.

⏳ Domain leasing with automatic expiration.

📦 On-chain DNS records, including support for IPFS CIDs.

🔐 Tamper-proof, censorship-resistant infrastructure.

👛 Wallet-based domain interactions using smart contracts.

🧠 Designed for Web3 apps, enterprises, and privacy-first platforms.

🛠 Architecture Overview
Smart contracts manage domain registration, leasing, and resolution.
Domains are stored as ERC-721 tokens (NFTs).

IP addresses are stored in a mapping that supports dynamic updates by owners or lessees.

Python scripts (web3.py) enable local node interaction and domain operations.

💡 Project Novelty
Unlike existing blockchain DNS models, this system supports:

NFT-based domain leasing (temporarily delegate DNS control).

Fine-grained access control with automatic lease expiration.

Fast, IPFS-compatible resolution for decentralized web hosting.

Real-time updates from both owners and lessees (within valid lease duration).

🧪 Tools & Technologies
Ethereum (Solidity smart contracts)

Ganache (Local blockchain for testing)

Web3.py (Python-based blockchain interaction)

IPFS (for decentralized content addressing)

Jupyter Notebook (for experimentation and integration testing)

🚀 Use Cases
Hosting fully decentralized websites

Leasing premium Web3 domain names

Launching censorship-resistant platforms

Secure enterprise-level DNS services
