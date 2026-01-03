

Overview
TauCoin is a next-generation blockchain platform that combines decentralized communication with blockchain technology. Built on a robust C++ foundation, TauCoin introduces the innovative Proof of Transaction (PoT) consensus mechanism, enabling secure peer-to-peer communication while maintaining a scalable blockchain infrastructure for digital transactions and community governance.

Learn More: Official Website | Whitepaper

Key Features
🔗 Proof of Transaction (PoT): Revolutionary consensus mechanism that rewards transaction activity
💬 Decentralized Communication: Built-in peer-to-peer messaging system with friend management
🏘️ Community Governance: Create and manage decentralized communities with voting mechanisms
🔒 Security First: Advanced cryptographic protocols and secure key management
⚡ High Performance: Optimized C++ implementation for speed and efficiency
🌐 Cross-Platform: Support for Linux, macOS, and Windows
Proof of Transaction (PoT) Consensus
TauCoin introduces Proof of Transaction (PoT), a revolutionary consensus mechanism that rewards network participants based on their transaction activity rather than computational power or stake. This innovative approach:

Incentivizes Usage: Users are rewarded for actively using the network
Energy Efficient: No energy-intensive mining or large stake requirements
Fair Distribution: Rewards are distributed based on actual network contribution
Scalable: Transaction activity naturally scales with network growth
For detailed technical specifications, see our Whitepaper.

Architecture
TauCoin consists of two main components:

Blockchain Module
Proof of Transaction (PoT): Innovative consensus where transaction activity drives block production
Transaction Processing: Submit and validate transactions with dynamic fee management
Block Management: Create, validate, and synchronize blocks using PoT consensus
Account Management: Secure wallet functionality with balance tracking
Community Features: Create and manage blockchain-based communities with PoT governance
Communication Module
Friend Management: Add, remove, and manage trusted contacts
Secure Messaging: End-to-end encrypted peer-to-peer communication
Device Synchronization: Multi-device message synchronization
Presence System: Track online status and last seen information
Quick Start
Prerequisites
Operating System: Ubuntu 18.04+ (recommended), macOS, or Windows
Compiler: GCC 10+ or equivalent C++17 compatible compiler
Dependencies: Boost 1.76.0, OpenSSL 1.1.1k, LevelDB 1.23
Building from Source
Clone the repository

git clone https://github.com/taucoin/taucoin.git
cd taucoin
Install dependencies (Ubuntu example)

# Install GCC
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt update
sudo apt install gcc-10 g++-10

# Build dependencies (see docs/building.md for detailed instructions)
Build the project

b2
Run examples

cd examples
b2
For detailed build instructions, see Building Guide.

API Reference
TauCoin provides comprehensive APIs for both blockchain and communication functionality:

Blockchain APIs
create_new_community() - Create blockchain-based communities
submit_transaction() - Submit transactions to the network
get_account_info() - Retrieve account balance and information
get_block_by_hash() - Query blocks by hash or number
get_mining_time() - Get PoT consensus timing information
get_top_tip_block() - Get highest transaction activity blocks
Communication APIs
add_new_friend() - Add trusted contacts
add_new_message() - Send encrypted messages
get_friend_info() - Retrieve contact information
For complete API documentation, see libTAU APIs.

Use Cases
Decentralized Social Networks: Build social platforms where user activity is rewarded through PoT
Community Governance: Create DAOs with transaction-based voting and treasury management
Secure Messaging: Private communication with blockchain-verified identities and PoT incentives
Digital Asset Management: Issue and trade custom tokens with PoT-driven liquidity
Activity-Based Rewards: Applications that reward user engagement through transaction activity
Documentation
Building Guide - Compilation and setup instructions
API Reference - Complete API documentation
Contributing - How to contribute to the project
Examples - Code examples and tutorials
Community & Support
Issues: Report bugs and request features on GitHub Issues
Discussions: Join community discussions on GitHub Discussions
Website: Visit our official website
Whitepaper: Read the TauCoin Whitepaper
Contributing
We welcome contributions from the community! Please read our Contributing Guide to get started.

Development Process
Fork the repository
Create a feature branch
Make your changes with tests
Submit a pull request
License
TauCoin is released under the BSD 3-Clause License. See the LICENSE file for details.

Acknowledgments
TauCoin builds upon the excellent work of the libtorrent project and incorporates various open-source cryptographic libraries. We thank all contributors and the open-source community.

Built with ❤️ by the TauCoin Community
