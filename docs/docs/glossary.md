---
title: Glossary

slug: /glossary
---

### Deposit

Deposit takes tokens from user wallet and adds them to user's account as a [collateral](#collateral)

### Dept

Minting tokens adds debt to account as a share of the debt pool. As total debt can change, the debt of a user can as well.

### Max debt

After user debt exceeds max debt user can be [liquidated](#liquidation)

### Mint

Synthetic assets can be created by Stakers of the platform and then exchanged on Synthetify exchange. Exchange of two different synthetic assets is direct, even for pairs that do not exist on centralized exchanges e.g. xFTT -> xSRM instead of FTT -> USD -> SRM which results in lower exchange fees and no slippage.

### Mint limit

The maximum amount you can mint is calculated from [collateral](#collateral). To ensure the safety of the platform each asset has a predefined but adjustable limit of the amount of tokens that can be created.

### Withdraw

Deposited collateral can be transferred to the user's wallet by withdrawal.

### Burn

Synthetic tokens can be burned by Stakers to reduce their debt and free collateral tokens.

### Rewards

For participating in the debt pool you get some SNY tokens. Details of getting it are [here](/docs/staking#rewards).

### Collateral

Deposited tokens become collateral. It is stored inside the account and allows a user to [mint](#mint) tokens and to have debt. You can find more about collateral [here](/docs/technical/collateral)

### Collateral Ratio

Locked collateral to the value of minted tokens is called a collateral ratio.

### Liquidation

Liquidation means a collateral decrease by asset burn. To ensure platform stability Stakers can be liquidated and part of their collateral will be transferred to Liquidators in exchange for paying back part of a Staker debt. It takes place every time overrunning the collateral ratio occurs.

### Risk

The user can remove provided liquidity at any time. However, there are a few risks that can affect locked assets.

#### Market risk

Market risk is a possibility to experience losses due to price change. The cryptocurrency market is very volatile. Even 15% APY could not cover sharp market movement price change.

#### Liquidity Risk

Liquidity risk is a potential issue, especially on micro-cap assets. It could happen that exchanging earned assets will be obstructed because of liquidity on the market.

#### Rewards Loss Risk

There are three stages of providing liquidity:

1. Subscription
2. Staking
3. Claiming.

In phases 1 and 3 there is no possibility to lose staked assets. Earning rewards takes place during stage 2. The staking phase takes two weeks. During this stage, the user can freely withdraw its deposit. However, burning is bounded with losing earned rewards.

### Listing new assets

Adding new assets to Synthetify exchange requires the existence of a reliable price oracle for this asset. Currently, the Synthetify team controls what assets are listed on the exchange but in the future, this decision will be moved to the governance instance.

![Assets Exchange Symbolic Representation](https://i.imgur.com/yT9BdQe.png)
