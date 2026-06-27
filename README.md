SentinelX — AI-Powered Offensive Security Framework for Blockchain

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![Blockchain](https://img.shields.io/badge/Domain-Blockchain%20Security-orange)
![ML](https://img.shields.io/badge/ML-Smart%20Contract%20Vuln%20Detection-green)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> Final Year Project (BISF 3500) — BSc Information Security & Digital Forensics 
> KCA University | Researcher: Paul Omboko | 2026

 Overview

SentinelX is an AI-powered offensive security framework designed to detect, 
classify, and report vulnerabilities in blockchain smart contracts in real time. 
It combines machine learning-based vulnerability detection with Forta Network 
protocol integration to deliver automated threat intelligence for decentralized 
ecosystems.

The problem it solves: Smart contract vulnerabilities cost the blockchain 
industry over $3.8 billion in 2022 alone. Existing tools are reactive. 
SentinelX is proactive — detecting attack patterns before exploitation occurs.


Core Features

| Feature | Description |
|---|---|
|  ML Vulnerability Detection | Classifies smart contract code for known vulnerability patterns (reentrancy, integer overflow, access control flaws) |
|  Forta Integration | Real-time alert streaming via Forta Network's decentralized threat intelligence protocol |
|  SentinelX Deep Recon | Automated reconnaissance module for on-chain forensic analysis |
|  Threat Intelligence Dashboard | Visualizes active threat patterns across target blockchain networks |
|  Real-Time Alerting | Configurable alert thresholds with webhook/API output |

 Architecture

 SentinelX/
├── ml_engine/  ML model for smart contract vulnerability classification
├── forta_integration/  Forta Network bot configuration and alert handlers
├── recon_module/  On-chain reconnaissance and forensic tooling
├── threat_intel/  Real-time threat pattern aggregation
├── dashboard/  Visualization layer
└── docs/  Technical documentation and research paper

Technologies

- Python 3.11+ — Core framework
- Solidity — Smart contract analysis target language
- Forta Network — Decentralized threat intelligence protocol
- Scikit-learn / TensorFlow — ML vulnerability classification models
- Web3.py — Blockchain interaction layer
- Slither — Static analysis integration
- Mythril — Symbolic execution engine

Vulnerability Classes Targeted

- Reentrancy attacks
- Integer overflow/underflow
- Access control vulnerabilities  
- Front-running exploits
- Flash loan attack patterns
- Oracle manipulation

Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/sentinelx-blockchain-security.git

# Navigate to directory
cd sentinelx-blockchain-security

# Install dependencies
pip install -r requirements.txt

# Run initial vulnerability scan (demo mode)
python sentinelx.py --target demo_contract.sol --mode scan
```

(Full setup guide in `/docs/SETUP.md` — coming soon)

Research Context

This framework is part of academic research into the application of artificial 
intelligence in offensive blockchain security. Research domains include:

- Machine learning for smart contract static analysis
- Decentralized threat intelligence via Forta Network
- Real-time anomaly detection in DeFi protocols
- On-chain forensic investigation methodologies

Target Platforms Post-Research: Immunefi Bug Bounty | Code4rena Audit Contests

Why This Matters for Africa

Africa's blockchain adoption is accelerating — from M-Pesa integrations to 
national CBDCs. Yet the security infrastructure protecting these ecosystems 
lags critically behind. SentinelX is built with African blockchain ecosystems 
in mind, targeting the specific threat landscape facing emerging market DeFi.

Researcher

Paul Omboko 
BSc Information Security & Digital Forensics — KCA University (2022–2026)  
Specialization: Offensive Security | Blockchain Forensics | AI/ML Security  
Nairobi, Kenya  

Connect: [LinkedIn](linkedin.com/in/paul-omboko-7a2238266) | 

[Email](mailto:paulomboko504@gmail.com)

License

MIT License — See [LICENSE](LICENSE) for details.

Built during the 2026 Mercury pre-retrograde sprint window. 
The temple is under construction.
