# T3rn Executor Script

## ✨ Preparation

### 💸 Purchase Sepolia ETH
- Easily purchase **ETH Sepolia** here:  
  [🔗 Testnet Bridge](https://testnetbridge.com/sepolia)  
  *With just **$10**, you'll receive plenty of ETH for testing across various networks.*

### 🌉 Bridging ETH Sepolia
To bridge your ETH Sepolia to other networks, use these links:

1. **Sepolia to ARB Sepolia**  
   [🔗 Arbitrum Bridge](https://bridge.arbitrum.io/)

2. **Sepolia to BASE Sepolia**  
   [🔗 Superbridge Base](https://superbridge.app/base-sepolia)

3. **Sepolia to Sepolia Optimism**  
   [🔗 Superbridge Optimism](https://superbridge.app/op-sepolia)

4. **Sepolia to Sepolia BLAST**  
   Send Sepolia ETH directly to:
   0xc644cc19d2a9388b71dd1dede07cffc73237dca8

**Tip:** Transfer **10 ETH** to each network for ample testing!

### 🧪 Setup

1. **Create an Alchemy or Infura Account**
- Sign up at [Alchemy](https://www.alchemy.com/) or [Infura](https://www.infura.io/).
- Get the **RPC URL** for the networks you're working with.

2. **Prepare Your Wallet**
- Ensure your wallet has a balance on:
  - **ETH OP Sepolia**
  - **ETH Arb Sepolia**
  - **ETH Base Sepolia**
  - **ETH Sepolia Blast**
  - **Token BRN**

3. **Get BRN Token**
- Claim BRN tokens for testing by connecting your MetaMask wallet here:  
  [🔗 BRN Faucet](https://faucet.brn.t3rn.io/)

4. **Check Your BRN Balance**
- Use the explorer: [🔗 BRN Explorer](https://brn.explorer.caldera.xyz/)
- Enter your address to check your balance.

### 🗂️ Script Execution

**Ensure the script is in the root directory.**

To auto-install and run the script, execute:
```bash
wget https://raw.githubusercontent.com/HarbhagwanDhaliwal/t3rn_guide/main/t3rn_executor.sh && chmod +x t3rn_executor.sh && ./t3rn_executor.sh

📊 Check Service Logs and Dashboard
After running the script, monitor the service logs with:
bash
sudo journalctl -u t3rn-executor.service -f --no-hostname -o cat

Check your node reward dashboard by visiting:
https://bridge.t1rn.io/executor/Your_Wallet_Address - Replace Your_Wallet_Address with your actual wallet address.

This version includes emojis for visual appeal, clearer instructions, and uses a more engaging format to make the document more user-friendly on GitHub.
