# QBridge - Qubic to Ethereum Cross-Chain Bridge

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-Proposal-orange.svg)]()

## 📖 Overview

**QBridge** is a next-generation, non-custodial cross-chain bridge that enables seamless token transfers between the **Qubic blockchain** and **Ethereum network**. Built with security and decentralization as core principles, QBridge provides friction-free interoperability for users and developers across both ecosystems.

## 🚀 Key Features

- **🔒 Non-Custodial**: Users maintain full control of their assets
- **⚡ Fast Transfers**: Cross-chain transactions completed in seconds
- **🛡️ Secure**: Advanced security protocols and validator network
- **🌉 Seamless UX**: Intuitive interface inspired by top bridging protocols
- **💰 Fee Sharing**: Transparent fee distribution model
- **🔧 Maintainable**: Comprehensive SLA and support structure

## 🏗️ Architecture

### Core Components

- **Validator Services**: Distributed network ensuring bridge security
- **API Layer**: RESTful APIs for integration and monitoring
- **Middleware**: Smart contract interaction layer
- **Liquidity Pools**: Uniswap integration for wQubic/ETH trading

## 💰 Economic Model

### Annual Maintenance Fee
- **Amount**: 30,000 USDT equivalent
- **Payment Options**: USDT, USDC, or QUBIC (+5% adjustment for QUBIC)
- **Coverage**: Technical maintenance, updates, security patches

### Initial Liquidity Requirements
- **Pool**: wQubic/ETH on Uniswap
- **Amount**: $25,000 in QUBIC + equivalent ETH
- **Ownership**: Incubation Program/Market Maker
- **Benefits**: Fee capture and withdrawal flexibility

## 🔧 Technical Specifications

### Supported Networks
- **Source**: Qubic Blockchain
- **Destination**: Ethereum Network
- **Token**: QUBIC ↔ wQUBIC

### Service Level Agreement (SLA)

| Severity | Definition | Response Time | Resolution Target |
|----------|------------|---------------|-------------------|
| **S1 - Critical** | Bridge down, funds at risk | ≤ 30 min | ≤ 24 hours |
| **S2 - High** | Degraded performance | ≤ 2 hours | ≤ 3 days |
| **S3 - Normal** | Minor issues | ≤ 1 day | Next release |

**Uptime Target**: ≥ 99.5% monthly uptime

### Support Hours
- **Schedule**: Monday - Friday, 09:00 - 18:00 CET (UTC+1)
- **Coverage**: Spanish national holidays excluded
- **Emergency**: 24/7 on-call for S1 incidents

## 📋 Requirements

### For Users
- Web3 wallet (MetaMask, etc.)
- QUBIC tokens for transfers
- ETH for gas fees (Ethereum side)

### For Developers
- Node.js 16+
- Web3.js or Ethers.js
- Access to Qubic network

## 🚀 Getting Started

### Prerequisites
```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
```

### Configuration
```bash
# Required environment variables
QUBIC_NETWORK_URL=your_qubic_node_url
ETHEREUM_NETWORK_URL=your_ethereum_node_url
PRIVATE_KEY=your_operator_private_key
BRIDGE_CONTRACT_ADDRESS=deployed_bridge_address
```

### Running the Bridge
```bash
# Start validator services
npm run start:validators

# Start API server
npm run start:api

# Start monitoring
npm run start:monitor
```

## 📊 Monitoring & Analytics

### Key Metrics
- Transaction volume
- Bridge utilization
- Fee generation
- Uptime statistics
- Security events

### Dashboard Access
- **URL**: [Bridge Dashboard](https://dashboard.qbridge.io)
- **API**: RESTful endpoints for integration
- **Alerts**: Real-time notifications for incidents

## 🔒 Security

### Security Features
- Multi-signature validator network
- Time-locked transactions
- Rate limiting
- Automated security monitoring
- Regular security audits

### Audit Reports
- [Security Audit Report 2024](docs/audit-report-2024.pdf)
- [Penetration Testing Results](docs/pen-test-results.pdf)

## 📈 Roadmap

### Phase 1: Launch (Q1 2024)
- [x] Core bridge development
- [x] Security audits
- [x] Initial liquidity seeding
- [ ] Public launch

### Phase 2: Growth (Q2-Q3 2024)
- [ ] Additional token support
- [ ] Mobile app development
- [ ] Advanced analytics
- [ ] Community governance

### Phase 3: Expansion (Q4 2024)
- [ ] Multi-chain support
- [ ] DeFi integrations
- [ ] Advanced trading features

## 🤝 Contributing

We welcome contributions from the community! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup
```bash
# Fork and clone the repository
git clone https://github.com/your-username/qbridge.git
cd qbridge

# Install dependencies
npm install

# Run tests
npm test

# Start development server
npm run dev
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

### Documentation
- [Technical Documentation](docs/)
- [API Reference](docs/api.md)
- [Integration Guide](docs/integration.md)

### Community
- **Discord**: [Qubic Community](https://discord.gg/qubic)
- **Telegram**: [QBridge Updates](https://t.me/qbridge)
- **Twitter**: [@QBridge](https://twitter.com/qbridge)

### Support Channels
- **Technical Issues**: [GitHub Issues](https://github.com/qubic/qbridge/issues)
- **Business Inquiries**: [Contact Form](https://qbridge.io/contact)
- **Emergency**: On-call support for S1 incidents

## 📞 Contact

- **Operator**: Vottun
- **Email**: support@qbridge.io
- **Website**: [https://qbridge.io](https://qbridge.io)

---

**Disclaimer**: This bridge is operated by Vottun under agreement with the Qubic Incubation Program. Users should always verify transaction details and understand the risks associated with cross-chain transfers.
