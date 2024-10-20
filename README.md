# Liquid Bitcoin Workshop

Notes for my workshop on using Liquid Bitcoin

![Screenshot from 2024-10-19 22-16-23](https://github.com/user-attachments/assets/9b811ebf-089f-49af-a3b4-7d40eb0a7f31)


# I. What

> As a sidechain of Bitcoin, Liquid allows you to move bitcoin (BTC) between the Bitcoin mainchain and the Liquid sidechain through a verifiable 1-to-1 peg.
>
> Bitcoin sidechains such as Liquid are blockchains that facilitate the transfer of assets to and from the Bitcoin mainchain via a two-way peg. The amount of BTC circulating on a sidechain is always verifiably equal to the amount of BTC “locked” on the Bitcoin mainchain.
>
> While sidechains are interoperable with the Bitcoin mainchain, they operate independently of the Bitcoin network itself. Sidechains depend on Bitcoin; Bitcoin does not depend on sidechains.

## Liquid Sidechain

> Liquid is run by the Liquid Federation, which comprises leading exchanges, trading desks, wallet providers, payment processing services, financial institutions, and other Bitcoin-focused companies. No single member has control over the network.
>
> Unlike on Bitcoin, blocks on the Liquid sidechain aren’t mined using proof-of-work. Instead, blocks are signed by 15 Liquid functionaries in a round-robin. The Liquid functionaries are specialist hardware units operated by a subsection of the Liquid Federation, geographically dispersed around the world.
>
> While anyone can run a Liquid node and verify the state of the network, the Liquid functionaries are the “beating heart” of the network, signing transactions, generating blocks, and securing the BTC held by the network.

## Liquid Members

- [liquid.net](https://liquid.net)
![Screenshot from 2024-10-19 22-10-57](https://github.com/user-attachments/assets/fd5ed1ce-6500-4ab2-a986-d37f51803621)
![Screenshot from 2024-10-19 22-11-45](https://github.com/user-attachments/assets/b27f5dd9-2be3-4690-b20e-991ac0f39076)



---

# II. Why

## 1. Privacy

- Confidential amounts
- View key is in your control
- [liquid.network](https://liquid.network)

![Screenshot from 2024-10-19 22-24-21](https://github.com/user-attachments/assets/93036a55-4cf5-4ac7-b757-311bf4e511e6)


## 2. Reduce transaction costs

- UTXO management
  - Accumulate sats and swap into Liquid. When your balance is large enough, peg out into your cold storage wallet and you'll have a nice big UTXO, good preparation for a future high-fee environment.

## 3. Balance Lightning channels

- Swap from Lightning to Liquid to give your Lightning channel inbound liquidity. Conversely, swap from Liquid to Lightning to give your Lightning channel outbound liquidity.

---

# III. How

## Demo time

Two tools needed: Boltz Exchange and Blockstream Green Wallet.

- [Boltz Exchange](https://boltz.exchange)

![3-way-swap](https://github.com/user-attachments/assets/1c050d69-59db-4563-a0e2-ee4269924049)

- [Blockstream Green wallet](https://blockstream.com/green)

Alternative service for moving between Bitcoin and Liquid Bitcoin:

- [SideSwap](https://sideswap.io)

# IV. Tradeoffs & Mitigations

- Not actually Bitcoin
- Counterparty risk
- Don't use for life saving, but reasonable amounts are probably okay
