---
hidden: true
---

# Token Selection, Position Sizing, and Order Placement

1. **Select the Token**: From the dashboard ([https://testnet.antex.ai/en/future](https://testnet.antex.ai/en/future)), use the token selector to choose your pair (e.g., BTCUSDT, ETHUSDT). AnteX supports mainstream tokens with real-time charts and oracle-fed data for informed decisions—e.g., select BTC if expecting volatility.
2. **Decide on Long or Short**: Choose long if you anticipate a price rise (profit from increases) or short if expecting a fall (profit from decreases). This is based on market analysis; for example, go long on SOL during a bull run or short ETH in a bear market.
3. **Set Position Size and Leverage**: Use the intuitive slider or input field to set your collateral (e.g., $500 USDT) and leverage (1x-100x). Position size calculates automatically as leverage \* collateral (e.g., 10x on $500 = $5,000 exposure). Adjust based on risk tolerance—higher leverage amplifies gains/losses (e.g., 1% price move yields $50 profit/loss at 10x).
4. **Place and Confirm the Order**: Review details (e.g., estimated funding rate, margin requirements), then click "Open Position" or "Confirm." Sign the gas-free transaction in your wallet popup—execution is instant via the matching engine, with confirmations in <200ms thanks to AntBFT.

In use cases, a trader deposits $1,000 USDT, selects BTCUSDT, goes long at 50x for $50,000 exposure during a rally, profiting $500 from a 1% rise, with funding rates auto-adjusted via oracle. Another shorts ETH at 20x to hedge a spot position, earning fees if shorts are underrepresented. Tip: Use stop-loss orders to automate exits (e.g., close at 5% loss to cap risks), monitor via app notifications, and start with low leverage (5-10x) on testnet to practice—avoid over-leveraging, as liquidations occur if maintenance margin drops below thresholds (e.g., 0.5% for 100x). Common mistake: Ignoring funding rates—check them to avoid unexpected costs. With AnteX's verifiability, audit positions on-chain for peace of mind. This process integrates with multi-chain deposits, making perpetual trading accessible and efficient.
