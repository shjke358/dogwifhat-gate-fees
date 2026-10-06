# how to buy dogwifhat: a Gate walkthrough from account setup to Solana withdrawal, with the fees that actually apply

Most people searching this already know what they want. They want the dog in the pink hat, they want it today, and they'd rather not find out afterwards that they bought a copycat token or paid 5% to a card processor on a $150 order.

The clicking part is easy. The three things that trip people up are: confirming they're buying the real WIF, choosing a funding route that doesn't quietly cost more than the trade, and knowing what happens once the tokens land in an exchange account. This guide walks through all three using Gate, which has listed WIF since the early days of the meme and runs a WIF/USDT spot market alongside futures and leveraged tokens.

One caveat before anything else: crypto prices move fast, and so do fee schedules. Everything below reflects Gate's published information, but the number you should trust is the one on the order confirmation screen at the moment you click.

## Confirm which WIF you're buying before you buy anything

dogwifhat is an SPL token on Solana, launched in November 2023, built around a Shiba Inu wearing a pink knit cap. It has no staking, no protocol revenue, and no roadmap in the traditional sense. It's a meme coin, and it trades like one.

The detail that matters when you're buying: there is one correct token, and dozens of impostors using the same name and ticker.

> **dogwifhat contract address (Solana):** `EKpQGSJtjMFqKZ9KQanSqYXRcF8fBopzLHYxdM65zcjm`

This address is the one used by Coinbase, HTX, Bitget, Upbit and Gate's own WIF market, and it matches the on-chain token audited by Cyberscope in April 2024. That audit also confirms the supply is fixed at roughly 998.9 million WIF, the mint authority and freeze authority were both revoked, and the token uses 6 decimals. No new WIF can be created, and no one can freeze your balance.

Wallet interfaces routinely flag lookalike tokens — same name, same ticker, different mint address — as unverified. If the address in your wallet or on your order screen isn't the string above, you're not buying dogwifhat. You're buying somebody's exit liquidity.

For context on what you're getting into: WIF peaked around $4.85 in March 2024 and trades at a small fraction of that level today. That's not a reason to buy or avoid it. It's just the honest shape of the chart.

## Three ways to buy WIF, and who each one suits

Almost every "how to buy" guide lists the same options. What they usually skip is who each route is actually for.

**Centralized exchange (Gate, and the usual list of large platforms).** You register, verify identity, fund the account, and trade. You don't manage keys, which is convenient and also the trade-off: the exchange holds the assets until you withdraw. This is the default route for anyone buying a few hundred dollars' worth and who wants cards, bank transfers, or P2P as funding options.

**Non-custodial wallet swap.** You hold the keys and swap SOL or USDC for WIF inside a wallet app. No registration, no KYC. You need crypto to start with, you'll have to verify the token contract yourself, and you'll pay network fees.

**Decentralized exchange.** Similar to the wallet route, with a UI that looks like a trading terminal. Works well if you already live on-chain, and it's a poor first experience if you've never signed a transaction.

The rest of this piece focuses on the exchange route, because it's the one that handles fiat funding, has a support desk when something goes wrong, and gives you a limit order so you're not automatically the taker paying full spread.

## How to buy dogwifhat on Gate, step by step

Gate's own walkthrough for WIF is four steps. In practice there are a couple more decisions hiding inside them.

**1. Create the account.** Email or phone number. Set a strong password, and turn on two-factor authentication *before* your first trade rather than after. This is the step people skip, and it's the one that matters most.

**2. Complete identity verification (KYC).** Verification unlocks higher trading limits and more payment channels. What's required varies by region and by payment method, so expect the exact document list to depend on where you are. While you're in the security settings, set an anti-phishing code and a withdrawal address whitelist. Both take two minutes and both make a compromised login far less expensive.

**3. Fund the account.** Card, bank transfer, P2P/C2C, or an on-chain deposit from another exchange or wallet. Details on costs below.

**4. Buy WIF.** Three ways to do it, and they're not interchangeable:

- **Direct card purchase** — you buy WIF with a card, no pre-funding, and the fee is baked into the quote. Fastest, priciest.
- **Convert (flash swap)** — if you already hold USDT or ETH, swap straight into WIF. Instant, cheap, but you're crossing the spread rather than choosing a price.
- **Spot order on WIF/USDT** — place a limit order at your price and pay the maker fee, or a market order and pay the taker fee. Slightly more clicks, materially better pricing on anything but a tiny order.

You've done this before if you've used any exchange, and the layout is unremarkable: search WIF, pick the WIF/USDT pair, size the order, confirm.

**5. Check the total before you confirm.** The order screen shows price plus applicable fees. On a card purchase, the spread is embedded in the rate and not broken out, which is why card buys can look cheaper than they are.

**6. WIF lands in your spot wallet.** From there you can hold it, trade it against USDT, or withdraw it. If you withdraw, verify the network and the address, and send a small test amount first. On-chain transfers on Solana are irreversible, and "irreversible" here means exactly what it says.

If you'd rather open the account and follow along in a live interface than read another paragraph: 👉 [👉 Start on Gate and open the WIF/USDT market](https://bit.ly/GateVIP)

## Funding routes on Gate, compared

Fees and availability shift by country, and card fees in particular move with your bank and order size. Treat this as the shape of the pricing, not a quote.

| Funding route | What it accepts | Typical cost | Speed | Best for |
| --- | --- | --- | --- | --- |
| Card / Apple Pay | Visa, Mastercard, debit cards | Roughly 1–5%, embedded in the rate | Seconds to minutes | Small first buys, no pre-funding |
| Bank transfer | SEPA, SWIFT, FPS and similar rails | Low or zero, varies by bank | 1–3 business days (SEPA instant is faster) | Larger purchases |
| P2P / C2C | Bank transfer, PayPal, Wise and others | Platform fee 0; seller sets the price | Depends on the seller releasing funds | Users in regions with weak card support |
| Convert (flash swap) | USDT, ETH and other balances you already hold | Spread only | Instant | Adding to a position you're already funded for |
| On-chain deposit | Crypto sent from another wallet or exchange | Network fee only | Minutes, depends on chain | People moving funds from elsewhere |
| GateCode | Transfer between Gate users | Free | Immediate | Receiving funds from someone already on Gate |

Two practical notes. Card convenience is real, but on a $100 order a 3% embedded cost is $3, and a limit order at 0.1% plus spread would have run you well under a dollar — the difference between the card route and the spot route is often larger than the price move you're trying to catch. And in P2P, the platform fee being zero doesn't mean the trade is free; the advert price is set by the counterparty, so compare a couple of quotes before accepting.

## WIF on Gate: what the fees actually look like

Gate prices spot trading through 17 VIP tiers, from VIP 0 to VIP 16. A brand-new account sits at VIP 0 and pays 0.10% maker and 0.10% taker — note that maker and taker are identical through VIP 3, so resting an order on the book buys you nothing until VIP 4. Paying fees in GT gets a small discount at the lower tiers, and that discount disappears from VIP 10 up.

| VIP tier | Spot maker / taker | Same fees paid in GT | 24h withdrawal limit (USD) |
| --- | --- | --- | --- |
| VIP 0 | 0.10% / 0.10% | 0.09% / 0.09% | 3,000,000 |
| VIP 1 | 0.099% / 0.099% | 0.089% / 0.089% | 3,000,000 |
| VIP 2 | 0.098% / 0.098% | 0.088% / 0.088% | 3,000,000 |
| VIP 3 | 0.097% / 0.097% | 0.087% / 0.087% | 3,000,000 |
| VIP 4 | 0.095% / 0.096% | 0.086% / 0.086% | 3,000,000 |
| VIP 5 | 0.09% / 0.095% | 0.081% / 0.085% | 5,000,000 |
| VIP 6 | 0.085% / 0.09% | 0.076% / 0.081% | 5,000,000 |
| VIP 7 | 0.08% / 0.085% | 0.07% / 0.076% | 5,000,000 |
| VIP 8 | 0.075% / 0.08% | 0.06% / 0.072% | 5,000,000 |
| VIP 9 | 0.07% / 0.075% | 0.05% / 0.068% | 8,000,000 |
| VIP 10 | 0.04% / 0.058% | 0.04% / 0.058% | 8,000,000 |
| VIP 11 | 0.03% / 0.045% | 0.03% / 0.045% | 8,000,000 |
| VIP 12 | 0.02% / 0.037% | 0.02% / 0.037% | 10,000,000 |
| VIP 13 | 0.01% / 0.03% | 0.01% / 0.03% | 20,000,000 |
| VIP 14 | 0.008% / 0.023% | 0.008% / 0.023% | 30,000,000 |
| VIP 15 | 0% / 0.02% | 0% / 0.02% | 40,000,000 |
| VIP 16 | 0% / 0.0175% | 0% / 0.0175% | 50,000,000 |

Tier placement is calculated on whichever track benefits you more: your 30-day weighted trading volume or your 14-day average GT holding. Spot and stock volume count at 100%, USDT and BTC perpetuals at 40%, options at 20%, and CFD contracts at 10% — which means a futures trader needs roughly two and a half times the notional turnover of a spot trader to land on the same tier. VIP 1 starts at $60,000 of 30-day volume or 50 GT held; VIP 4 sits at $500,000; the top tier is $3 billion.

For anything beyond plain buying, two more numbers are worth knowing: USDT-margined futures start at 0.02% maker and 0.05% taker at VIP 0, and Alpha trading is charged a flat 0.8% at every tier, from VIP 0 to VIP 16. That 0.8% is eight times the VIP 0 spot rate and never comes down.

Ready to see which tier your first trade puts you on? 👉 [👉 Compare Gate's VIP tiers against your trading plan](https://bit.ly/GateVIP)

## What a WIF trade costs, in actual dollars

Abstract percentages are hard to feel. Take a hypothetical $500 limit buy of WIF/USDT as a VIP 0 account with GT deduction switched off:

- Trading amount: $500
- Maker fee at 0.10%: $0.50
- If you crossed the spread with a market order at 0.10% taker: $0.50

At these order sizes the trading fee is a rounding error next to the spread and the funding route. A 3% card purchase on the same $500 costs about $15 before you've made a single trade — thirty times the spot fee. That's the real cost story for small buyers, and it's the reason a two-step approach (fund with a bank transfer or P2P, then buy on the spot market with a limit order) beats one-click card checkout on anything above pocket change.

Then there's the exit. Withdrawals are priced per coin and per network, not as a percentage, and the same asset can cost very different amounts depending on which chain you pick. Gate's deposit-and-withdrawal table lists the fee, the minimum, and a network status field for each coin and chain. Read the status field before you send. Deposits to a chain flagged as disabled are the kind of mistake that turns a five-minute transfer into a support ticket.

## After you buy: holding WIF vs. moving it off Gate

Leaving WIF on an exchange is fine if you plan to trade it. It is not self-custody, and the phrase "not your keys, not your coins" exists because exchange failures have cost people real money.

If you do withdraw, the flow is straightforward and unforgiving:

1. Open Gate's withdrawal page and select WIF.
2. Confirm you're on the **Solana** network — WIF is an SPL token, and Solana is the only chain where the real contract lives.
3. Paste your receiving wallet address and double-check it character by character.
4. Send a small test amount first, confirm it arrives, then send the rest.
5. Keep your seed phrase offline. Losing it loses the coins, permanently, with no support desk to call.

One more Solana-specific detail: if you're moving WIF into a fresh wallet, that wallet needs a small amount of SOL to cover transaction fees. WIF alone in an empty wallet won't move.

## Risks that are specific to WIF

**Impostor tokens.** Covered above, worth repeating because it's the single most common way people buying WIF lose money on their first attempt. Verify the mint address.

**Liquidity and slippage.** WIF trades on dozens of venues, but depth varies enormously between them. On thinner markets, a large market order can fill several percent away from the quoted price. If you're buying a meaningful amount, use a limit order.

**Leverage products.** Gate lists WIF/USDT perpetual futures plus WIF leveraged tokens in both long and short directions, and similar products exist across the market. On a meme coin that can move double digits in a day, these amplify both directions of the outcome. If the plan is "buy WIF and see what happens," leverage isn't that plan.

**Regional restrictions.** Gate's own pages note that services are restricted or unavailable in certain jurisdictions, listing the United States and Canada among others. Availability of specific payment methods also varies by region — the card option visible to a user in one country may simply not render for another.

**Position sizing.** Meme coins are volatile by design and WIF has no cash flow, no staking yield, and no product roadmap. The honest framing: size it as a speculative position, not as a savings account.

## Quick answers

**Is WIF available on Gate?** Yes — a WIF/USDT spot pair, a USDT-margined WIF perpetual, and WIF leveraged tokens.

**What's the minimum I can buy?** It depends on the funding route. Card and Convert purchases typically start in the low single-digit dollar range, while spot orders are limited by the exchange's minimum order size on the pair.

**Do I need KYC to buy WIF on Gate?** Yes for trading and fiat funding. Verification levels also determine your limits and which payment channels appear.

**Can I buy WIF with a credit card?** Yes, through Gate's card channel, typically at a cost of roughly 1–5% embedded in the rate, arriving in minutes.

**Which network do I use to withdraw WIF?** Solana. The contract address is `EKpQGSJtjMFqKZ9KQanSqYXRcF8fBopzLHYxdM65zcjm`, and it only exists there.

**Is the maker/taker fee really 0.10% at the base tier?** On the published spot schedule, yes — 0.10% maker and 0.10% taker at VIP 0, dropping to 0.09% on both sides if you pay fees in GT. Fees on other platforms and older articles quote different numbers, so check the live fee page rather than a screenshot.

**How do I check the current WIF price?** Look at the live WIF/USDT order book on the exchange you plan to trade on, not at a cached article. The all-time high was around $4.85 in March 2024, and today's number is whatever the market says when you load the page.

Buying WIF is a fifteen-minute process once you know which of the three purchase routes you're taking and which costs are real. Verify the contract, fund the account the cheap way, use a limit order, and decide before you start whether the coins are staying on the exchange or going to a wallet you control. 👉 [👉 Set up your Gate account and make your first WIF buy](https://bit.ly/GateVIP)

*Crypto assets are volatile and you can lose your entire investment. Nothing here is financial advice.*
