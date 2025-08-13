---
hidden: true
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Trading

## 1. **Deposit Funds or Claim Faucet (For Testnet only）**

Perpetual DEX requires collateral in your trading account before you can open positions.

* Navigate to **“Deposit”**
* Select the chain and asset you want to deposit (e.g., Arbitrum-USDC).
* Enter the deposit amount.
* Approve the transaction in your wallet (if needed).
* Wait for the confirmation on-chain.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=NDNiNzY2N2RlZWUzM2VmYmU1MTlmMWUyMjcyYTQxZmNfdTBtZUlZc05Gd2FhWnBXdDl2Z0hSbENqY3FSVjFRTzhfVG9rZW46RnZYUmJZUDZrb1dXcmh4RFVUamx6Y3diZzFnXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **2. Select a Trading Pair**

* Go to the **Trading** page.
* In the **Market Selector**, choose the pair you want to trade (e.g., BTC-USDT, ETH-USDT).
* Review the current price chart, order book, and recent trades.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=ZTZiMTdkNGJiNTc0MTE0MTFjNWRmOGQ3ODlhMGU4MjBfRHN6aGp6ajRSMWZmNnJQN09tRUltR3FIazNMd25PYUNfVG9rZW46TVlkNmJQazdFb0VVcEN4RlZvMWx3dlJwZzBkXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **3. Choosing Your Position Margin Mode: Cross or Isolated**

* **Cross Margin Mode(Default):**

All your positions that use the same margin asset share a common margin balance. This means your available margin across those positions can be used to prevent liquidation. While this maximizes margin efficiency, it also means that if one position incurs significant losses, it may affect all your positions under that asset.

* **Isolated Margin Mode:**

Each position has its own dedicated margin. The margin allocated to a position is independent, limiting your risk to that specific position only. If the position’s margin is exhausted, only that position will be liquidated, without affecting your other positions.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=MTNmMjYyOGNkMzdlZGE1MjMzZjQxNjBiMmI3OGY2YjBfMmg2WWY4dTRvdFpiNmplcFpNS004VUxJRUhKM2gyNG9fVG9rZW46QzVKc2JhZXdPb29VSkF4bVRpSmx5QWtYZ2xoXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **4. Set Leverage**

* Use the leverage slider or input box to choose your leverage (e.g., 5×, 10×, 20×), default to 10x.
* Remember: Higher leverage = higher risk of liquidation.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=MmRlZGIwNGRjZGU0NzhmZTAyNmM2MjlkNTZiZTkwMDFfRnc5UkhUbXE3WlUxVFA3bUxUZkgzWlV3eFZNS1lOM2tfVG9rZW46WjBvQ2JsUG9ZbzJnamt4UWRMaWxOMWlyZ21oXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **5. Choose Order Type**

AnteX supports multiple order types:

* **Market Order** – Executes immediately at the best available price.
* **Limit Order** – Executes only at your chosen price or better.
* **Stop Orders** – Triggered automatically at a specified price.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=OTQ1YTA5YWM0MzY0NzQwZGRiYTA1YmE2NmNiMmY2MjVfNnZ5N0tkbWFlRUM1VkZqNUxqUkdnR0xGdmMyaFBPRnJfVG9rZW46TUFlTWJPTVJqbzJpZVJ4Y1RybGx1OTdJZ2JiXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **6. Place Your Order**

* Enter:
  * **Order Size** (in base or quote token)
  * **Price** (if limit order)
* Double-check:
  * **Price**
  * **Position Value**
  * **Initial Margin**
* Click **“Buy / Long”** or **“Sell / Short”**.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=NTFiN2IzNGJmM2M4OWEwZTcwMjhiYjMzYzkwMDgxNTJfUkVRSGVoSENxaUljSXFzZjVJT1Q1N0FoSGx0UkRpTUtfVG9rZW46SzAzQWJMWXp0b1F6UFF4enJHQ2w5OWU2Z0dnXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **7. Monitor Your Position**

* View open positions in the **Positions Panel**:
  * Entry Price
  * Size
  * PnL (Profit & Loss)
  * Margin
  * Liquidation Price
* Adjust stop-loss or take-profit orders as needed.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=ZjJmZTQyNGZmMjdjYWQzZWZkZGJlNWE4M2IxMjhlZGVfcGhsMmdrelRtU0tqTjJ2b1pSRUZUMFQwRVBoSG55VVFfVG9rZW46UWoxNWJxVk1Ub0lvMjJ4RFRlOWxSVmtuZ2loXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>

## **8. Close Your Position**

* From the Positions Panel, click **“Close”**.
* Choose:
  * **Market Close** – Instantly closes at market price.
  * **Limit Close** – Closes only at your chosen price.

<figure><img src="https://g436fuyahxw.sg.larksuite.com/space/api/box/stream/download/asynccode/?code=MjdiNDc5ZWVmZWQyMjM2OTM5ZjYwNzFiZmEzODZmYjFfYm5JN3U1UVFkOEJPMTBPU3VZZjFCOUFhUnM1TWtRaEFfVG9rZW46WEJ5TmJjaEM2bzk4TWJ4dURBRmxKaUs1ZzNmXzE3NTUwNzE1MzI6MTc1NTA3NTEzMl9WNA" alt=""><figcaption></figcaption></figure>
