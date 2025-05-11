# **Raydium Volume Bot**  

**Automated bot for distributing SOL and executing simultaneous buy/sell transactions on Raydium and Meteora platforms**  

The **Raydium Volume Bot V3** is a highly efficient trading bot designed to automate the distribution of SOL across multiple wallets and perform endless buy and sell swap transactions on both **Raydium** and **Meteora** platforms. Leveraging **Solana's blockchain**, this bot enhances trading operations while boosting volume on decentralized exchanges (DEXs) and increasing token holders in the marketplace.

---

## **📈 What’s New in Raydium Volume Bot V3?**  

### **🔧 Last Version's Demerits**  

- ❌ **Repetitive Buy and Sell with One Wallet**: The previous version of the bot used fixed wallets, which were easily identifiable on platforms like DexScreener due to repetitive buy/sell actions.
- ❌ **No Increase in Number of Holders**: It only boosted volume without increasing the number of token holders.
- ❌ **Gathering Token Instead of SOL**: If there were leftover tokens after a transaction, it didn’t sell them before gathering. Instead, it simply gathered tokens to the main wallet.
- ❌ **Equal Number of Buys and Sells**: The operation consisted of one buy and one sell, causing **sell pressure** due to the balance of buys and sells.

---

### **🚀 Improvements in Raydium Volume Bot V3**  

- ✅ **Transfer SOL to New Wallet**: After each buy and sell operation, SOL is transferred to a newly created wallet to continue the process without repetition.
- ✅ **Holder Increase**: New wallets are generated with each round of buying and selling, **increasing the number of holders**.
- ✅ **Sell Before Gather**: Tokens are **sold before gathering** them, optimizing the process and ensuring only SOL is gathered, reclaiming the token account rent (0.00203 SOL).
- ✅ **More Buys than Sells**: The bot now buys twice for every sell action, creating **more buy pressure** and better market movement.

---

## **🌟 Features**  

- ⚙️ **Automated SOL Distribution**: Automatically distributes SOL to new wallets for continued trading.
- 🔄 **Endless Buy and Sell Swaps**: Executes simultaneous buy and sell transactions in real-time.
- 🚀 **Swap with Jupiter V6**: Leverages the **Jupiter V6 swap aggregator** for optimal token swaps.
- 🚀 **Swap with Meteora SDK**: Integrates with **Meteora SDK** for DLMM and Dynamic liquidity pools.
- 🛠️ **Configurable Parameters**: Customize buy amounts, intervals, wallet distribution, and more to match your strategy.

---

## **🔗 Example**  

Check out the bot’s activity through the following links:

- **Solscan Account**:  
  [View Account](https://solscan.io/account/EqCgCTBSSqdzaZDr6r1LPsysXdJwc2jn3CBqD5dNQS6Q)

- **Asset Example**:  
  ![Example](https://github.com/user-attachments/assets/df532c73-3c68-42e7-828a-4e1927c42047)

---

## **🚀 Usage Guide**

### **1. Clone the Repository**  

Clone the repository to your local machine:

```bash
git clone https://github.com/toptrendev/solana-volume-bot.git
cd solana-volume-bot
```

### **2. Install Dependencies**  

Install the necessary dependencies:

```bash
npm install
```

### **3. Configure Environment Variables**  

Rename the `.env.copy` file to `.env` and configure the following:

- RPC and WSS
- Main keypair's secret key
- Other relevant environment variables

### **4. Run the Bot**  

Start the bot using the following command:

```bash
npm start
```

### **5. Gather Funds from Distributed Wallets**  

To gather funds from distributed wallets, run:

```bash
npm run gather
```

---

## **📬 Contact & Community**  

📢 **Telegram:** [@toptrendev](https://t.me/toptrendev)  
📢 **Discord:** [toptrendev](https://discordapp.com/users/334173411402317846)  
