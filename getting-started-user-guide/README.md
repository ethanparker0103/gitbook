# Getting Started: User Guide

Antex is designed to be user-friendly, allowing both novice and experienced traders to start trading quickly with minimal barriers. This guide provides step-by-step instructions to join the platform, set up your wallet, deposit assets, execute trades, and withdraw funds securely. Whether you're using a standard EVM wallet or social login for convenience, Antex emphasizes self-custody and security, ensuring you retain full control over your assets at all times. The platform's testnet (available at [https://testnet.antex.ai/en/future](https://testnet.antex.ai/en/future)) is ideal for practice, supporting assets like USDT on networks such as Ethereum, BNB Chain, Solana, and TRON. With features like on-chain verifiability and low-latency execution (<200ms via parallel processing), getting started is seamless, but always prioritize best practices to protect your funds. This guide covers key processes, with tips to avoid common pitfalls like sharing private keys or ignoring network confirmations. For mainnet, the process is similar, but ensure you're using supported wallets and verified contracts.

#### How to Join Antex and Start Trading

Joining Antex requires connecting a wallet or using social login, followed by basic setup. This non-custodial approach means Antex never holds your assets—you do.

**Wallet Setup (EVM-Compatible Wallets like MetaMask)**

For traditional access, use an EVM-compatible wallet like MetaMask (download at [https://metamask.io/](https://metamask.io/)). Install the browser extension or mobile app, create a new wallet, and securely back up your 12-24 word recovery phrase—never share it, as anyone with it can access your funds. Store it offline (e.g., on paper in a safe). Add the Antex testnet to MetaMask (RPC URL: provided on the site, chain ID: custom for Antex). This setup ensures compatibility with Antex's EVM layer, allowing seamless interactions. Common mistake: Using an unsupported wallet; stick to MetaMask for reliability.

**Social Login Options**

For quicker access, Antex supports social login via providers like Google or Twitter, linking to a generated EVM address without manual setup. This abstracts private key management while maintaining self-custody (assets still in your control via the linked wallet). It's ideal for beginners, with 2FA for added security. Note: Social logins are convenient but use them with strong account security to avoid breaches.

Once connected, navigate to [https://testnet.antex.ai/en/future](https://testnet.antex.ai/en/future), click "Connect," select your method, and confirm in the popup. You're now ready to trade!

#### Depositing Assets (USDT on Mainnet/Testnet Networks)

Depositing is straightforward: From the dashboard, click "Deposit," select USDT (testnet address: e.g., 0x3253a335E7bFfB4790Aa4C25C4250d206E9b9773 on Arbitrum; check site for others like BNB Chain, Solana, TRON). Enter the amount (min $10 for testnet), confirm in your wallet (gas fees apply on source chain), and assets appear in <1 minute via cross-chain protocols. This leverages Antex's native bridges for security, avoiding third-party risks (e.g., $2 billion+ lost in bridge hacks). Tip: Start with small test deposits to verify; use testnet USDT for practice.

#### Trading Perpetual Contracts

Perpetual contracts let you long/short tokens with leverage using USDT collateral, without owning the asset.

**Token Selection, Position Sizing, and Order Placement**

Select a token (e.g., BTCUSDT) from the dashboard selector. Choose long (if expecting rise) or short (if fall). Use the slider or input for size (e.g., leverage \* collateral = position; $100 at 10x = $1,000). Click "Open Position," review (e.g., funding rate 0.01%), and confirm in wallet. Execution is instant via matching engine, with oracle prices for accuracy. Use case: Short ETH at 50x during a dip for 20% gains in hours. Tip: Monitor margins to avoid liquidations (auto-triggered at 0.5% for high leverage).

#### Spot Trading and Order Management

For spot, select pairs (e.g., ETH/USDT), choose order type (limit/market/stop-loss), enter details, and submit—matched on-chain with <0.1% slippage via ALP. Manage open orders via dashboard (cancel/edit), with real-time tracking. Use case: Buy SOL with limit order at $140, auto-executing on dip. Tip: Use trailing stops for dynamic management.

#### Withdrawing USDT and Other Assets

To withdraw, go to [https://testnet.antex.ai/en/future/BTCUSDT](https://testnet.antex.ai/en/future/BTCUSDT) (or similar), enter amount, click "Withdraw"—it's gas-free and completes in <1 minute to your wallet or another chain. Use case: Extract profits post-trade to Solana. Tip: Verify address to avoid losses.

#### Best Practices for Security (Mnemonic Phrases, Private Keys)

Prioritize security: Never share your mnemonic phrase or private keys (store offline); enable 2FA; use hardware wallets for large holdings; verify URLs to avoid phishing (official: antex.ai); monitor transactions on explorers. Common mistake: Sharing phrases—leads to total loss. Antex's self-custody ensures your security is in your hands.

This guide gets you trading on Antex—explore the testnet and join the community for support!
