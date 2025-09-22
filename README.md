# Aztec Sequencer Guide

## 📋 Prerequisites

- **OS Ubuntu**
- **4 Core**
- **8GB RAM**
- **100GB Disk**
- Stable internet connection

## 🛠️ Quick Start

### 1. One Command Instlation
```bash
git clone https://github.com/brillianxbt/aztec.git
cd aztec
chmod +x autoinstall-aztec-docker.sh
sudo ./autoinstall-aztec-docker.sh
```

### The script will ask for the following information:

- **ETHEREUM_RPC_URL**: Ethereum mainnet RPC URL (dari Infura, Alchemy, dll.)
- **CONSENSUS_BEACON_URL**: URL layer konsensus Ethereum (Beacon chain)
- **VALIDATOR_PRIVATE_KEYS**: Kunci pribadi validator - dipisahkan koma jika lebih dari satu
- **COINBASE**: Alamat dompet untuk menerima hadiah
- **P2P_IP**: IP publik VPS Anda (akan terdeteksi secara otomatis)
