# Aztec Sequencer Guid

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

Follow the Prompts
The script will ask for the following information:

ETHEREUM_RPC_URL: Ethereum mainnet RPC URL (from Infura, Alchemy, etc.)
CONSENSUS_BEACON_URL: Ethereum consensus layer URL (Beacon chain)
VALIDATOR_PRIVATE_KEYS: Validator private key(s) - comma separated if multiple
COINBASE: Wallet address to receive rewards
P2P_IP: Public IP of your VPS (will auto-detect)
