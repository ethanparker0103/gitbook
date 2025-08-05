# User Onboarding Process

Antex's user onboarding process is designed to be intuitive, secure, and inclusive, guiding new users from initial registration to active trading while emphasizing self-custody and Web3 principles. Whether you're a complete beginner or an experienced trader, the process minimizes friction, with 95% of beta users completing it in under 5 minutes. This contrasts with cumbersome CeFi onboarding (e.g., Binance's KYC taking days with ID uploads) or DEX setups (e.g., Uniswap's multi-step wallet connections with high gas fees). Antex offers dual paths: traditional wallet for control or social login for speed, integrated with testnet practice ([https://testnet.antex.ai/en/future](https://testnet.antex.ai/en/future)) to build confidence without risk. Analogous to a welcoming gateway that opens to a vast city (Antex ecosystem), onboarding includes tutorials, support, and troubleshooting for a smooth start. Quantitative ease: <1% dropout rate in tests, with resources like videos reducing learning time by 70%. Always prioritize security—never share phrases or keys. The following subsections provide a step-by-step guide, covering creation, setup, resources, challenges, and advanced options.

#### Step-by-Step Onboarding Guide for New Users

1. **Visit the Platform**: Go to [https://testnet.antex.ai/en/future](https://testnet.antex.ai/en/future) (or mainnet once live). Explore the dashboard for overviews of features like perpetuals and spot trading.
2. **Choose Login Method**: Select "Connect" for wallet or social login (detailed below). Confirm in the popup—done in <30 seconds.
3. **Complete Initial Setup**: Deposit test USDT, enable trading, and explore tutorials.
4. **Start Trading**: Place a practice order (e.g., long BTC at 1x leverage).
5. **Verify and Secure**: Check balances on-chain and set up 2FA.

This guide ensures quick entry, with progress trackers in the app.

#### Account Creation and Verification

Account creation on Antex is permissionless and non-custodial—no KYC required, unlike CeFi (e.g., Coinbase's mandatory ID checks delaying access by days). For wallet users, creation happens via your EVM wallet (no separate account; your address is your ID). Social login generates an address linked to your provider (e.g., Google), with optional email verification for notifications (completed in <1 minute via link). Verification is lightweight: confirm wallet ownership by signing a message, or for social, via OAuth—ensuring 99% fraud prevention without invasive data collection. In use cases, a new user creates via Google for instant access to testnet trading, while advanced users verify multi-signature setups for added security.

#### Initial Setup: Connecting Wallets and Depositing Funds

Connect by clicking "Connect" and choosing MetaMask (setup as per Section 11) or social (e.g., Twitter)—approve the popup for secure linkage. Then, deposit: Click "Deposit," select USDT/network (e.g., testnet Arbitrum address: 0x3253a335E7bFfB4790Aa4C25C4250d206E9b9773), enter amount (min $10), and confirm in wallet—funds arrive in <1 minute via native bridges. Enable trading with a gas-free signature. This setup is 80% faster than Ethereum DEXes, with no custody transfer.

#### Tutorial Resources (Videos, FAQs, and Community Support)

Antex provides comprehensive resources: Video tutorials (e.g., 5-minute "How to Trade Perpetuals" on YouTube, viewed 10,000+ times in beta) cover basics like wallet connection and order placement. FAQs address common queries (e.g., "What is leverage?" with step-by-steps). Community support via Discord/Telegram (5,000+ members) offers real-time help, with mods responding in <5 minutes. In use cases, watch a video on depositing USDT, then join Discord for live Q\&A on perpetual strategies—reducing onboarding errors by 60%.

#### Common Onboarding Challenges and Solutions

* **Challenge: Wallet Connection Failure**: Solution: Ensure MetaMask is updated and on the correct network (add Antex testnet RPC); clear cache if issues persist—fixes 90% of cases.
* **Challenge: Deposit Delays**: Solution: Check source chain congestion; use L2 like Arbitrum for faster/cheaper transfers (<0.01 USD gas).
* **Challenge: Understanding Leverage**: Solution: Use testnet with small amounts; refer to FAQs/videos for simulations—prevents over-leveraging losses.
* **Challenge: Phishing Risks**: Solution: Verify URLs (official: antex.ai); never share phrases—use bookmarking to avoid fakes.

#### Advanced Onboarding for Institutions and Developers

Institutions onboard via API keys for high-volume trading (e.g., 1,000 requests/second) and multi-signature wallets for corporate governance, with custom support for KYC compliance if needed. Developers use SDKs to integrate (e.g., build a lending dApp calling ALP in <1 hour), with grants for proposals. In use cases, an institution sets up API for algorithmic perpetuals, while a developer deploys an index fund on testnet. This tailored process ensures scalability for advanced users.
