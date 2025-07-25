---
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

# Proposal: Staking referral program

_At this time, there is no definitive implementation for the staking referral program ready for mainnet. Based on extensive user and builder feedback, it is being re-evaluated to ensure fairness for all builders and a healthy builder ecosystem._

Details for the original proposal for a staking referral program are below:

Builders and referrers who stake HYPE will be able to keep a percentage of their referred users’ trading fees, up to a maximum of 40% for builders and referrers at the highest staking tier. All builders and referrers with staked HYPE will automatically enjoy these benefits once the feature is enabled on mainnet.

Furthermore, builders and referrers will be able to share up to 50% of the staking referral revenue back to the referred user. This allows referrers to offer better than the default rates to new users.

## What are builder codes and referral codes?

Builder codes allow interfaces routing through Hyperliquid to charge a custom fee on a per-order basis. This additional fee is called a builder fee and goes 100% to the builder. The new staking referral program is strictly more revenue for builders.

Referral codes are applied when a user joins via a referral link. Unlike builder codes, referral codes are tied to users and apply regardless of how the user trades in perpetuity. Note that builder codes override referral codes for that order, and referral codes are disabled after the user trades $1B cumulative volume.

## How it works

The staking referral program interacts with staking tier fee discounts and the VIP tier fee schedule. If a builder or referrer has a higher staking tier than their referred user on a trade, they keep up to 100% of the difference. The percentage kept by the builder or referrer decreases as the volume tier of the referred user increases, starting at 100% for VIP 0 and ending at 40% for VIP 6.

As an example: Alice has 100k staked HYPE, which gives a trading fee discount of 30%. Bob has 100 staked HYPE, which gives a trading fee discount of 10%, and Bob is at VIP 1. If Bob uses Alice’s builder or referral code, Alice can keep (30% - 10%) \* 90% = 18% of the fees that Bob pays. Alice could share with Bob up to 9% of his fees. In other words, Bob could receive up to a 9% trading fee discount using Alice’s builder or referral code.

<table><thead><tr><th width="140.3671875">VIP tier</th><th width="208.53515625">14d weighted volume ($)</th><th width="265.47265625">Amount kept by builder or referrer</th></tr></thead><tbody><tr><td>0</td><td></td><td>100%</td></tr><tr><td>1</td><td>>5M</td><td>90%</td></tr><tr><td>2</td><td>>25M</td><td>80%</td></tr><tr><td>3</td><td>>100M</td><td>70%</td></tr><tr><td>4</td><td>>500M</td><td>60%</td></tr><tr><td>5</td><td>>2B</td><td>50%</td></tr><tr><td>6</td><td>>7B</td><td>40%</td></tr></tbody></table>

_Note these tiers correspond to the fee schedules in_ fees
