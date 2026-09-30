# Hunt

Builder at **[Halldon](https://halldon.com)**. I ship products end to end: smart contracts, backends, apps, and the launch.

**Author of [ERC-8426: Wallet Pass Extension](https://github.com/ethereum/ERCs/pull/2036)**, an Ethereum standard for turning any token into a live Apple Wallet / Google Wallet pass.

~2,000 commits in the last year, almost all in private company repos. Here is what they built.


## Live products

| | What it is | Built with |
|---|---|---|
| **[Walletchi](https://www.playwalletchi.com)** · [code](https://github.com/huntclubhero/walletchi) | A pixel pet NFT that lives in your Apple/Google Wallet. Mint with an email, feed it from the pass, last pet alive wins the pot. | Solidity (ERC-721, ERC-6551, EIP-7702, sponsored gas), pass signing + APNs push, anti-Sybil wall |
| **Clawcity** · [code](https://github.com/huntclubhero/clawcity) | A city where AI agents build, play and sell games to humans. Any agent can create a game through the MCP server; humans play, buy items and wager in USDC. | 365 game templates, 31 renderers, 62-tool MCP server, USDC marketplace + wagering contracts live on Base mainnet ([Marketplace](https://basescan.org/address/0x07533A314E8c0A8EEA2c648C447be91B6e5f79D0), [Betting](https://basescan.org/address/0x11b938DfDf9Fa228D7BEAA9070a424a0af1B211C)), Express + Redis + WebSockets |
| **[Compliable](https://compliable.org)** · [code](https://github.com/huntclubhero/compliable) | Web accessibility (WCAG) scanner: crawls a whole site, runs real axe-core checks, writes the report. | Next.js, full-site crawler, axe-core |
| **[Blueprint estimator](https://shamrock-estimator.vercel.app)** | Upload a construction PDF, get a priced quantity takeoff. Built for Shamrock Hardscapes. | 8-pass vision + OCR extraction pipeline with cross-verification |
| **Procurement platform** | Order management portal in production for school and government buyers in New York. | Next.js, Prisma, role-based workflows, 2,000+ check smoke suite |

## Rare Friends ecosystem (public)

- **[Rare Friends Cards](https://rare-friends-cards.vercel.app)**: shareable stat cards for every holder. [code](https://github.com/Halldon-Inc/rare-friends-cards-public)
- **[Friends Publishing House](https://friends-publishing-house.vercel.app)**: holder-gated manga studio. [code](https://github.com/Halldon-Inc/friends-publishing-house)
- **[The First Bank of Friends](https://github.com/Halldon-Inc/bank-of-friends)**: a market-making desk funded by idle holder capital.
- **[Pirate Friends](https://github.com/Halldon-Inc/pirate-friends)**: fire your Generations, sink their ship.

## Also built

- **AI phone agent** for a contractor: books and reschedules jobs over the phone in under a second of latency.
- **AI photo studio** for car dealerships: inventory photo editing and video generation, iOS/Android.
- **[The Great Migration](https://not-fkn-bearish.vercel.app)**: NFT lending game design, borrow ETH against your bear and get tranquilized if you get liquidated (site live, contracts in progress). [code](https://github.com/huntclubhero/great-migration)
- **[Farmers](https://github.com/huntclubhero/farmers-nft)**: 200 fully on-chain animated pet NFTs, claimed by tapping an NFC hat. UUPS contract, 39 tests, front-run-resistant claim site.
- **[Tap2](https://github.com/huntclubhero/tap2)**: customer accounts without the app. Loyalty, memberships and access as Apple/Google Wallet passes backed by smart accounts.
- **[THE PIT](https://github.com/huntclubhero/the-pit)**: peer-to-peer memecoin perps (750+ Foundry tests, fuzz + invariants), in development.
- **[Hero Chat](https://hero-chat-peach.vercel.app)**, **[wormping](https://github.com/huntclubhero/wormping)** (Worms voice alerts for AI coding agents), **[Tennis line calling](https://github.com/Halldon-Inc/Tennis)** (computer vision MVP).

## Stack

Solidity · Foundry · Solana / Anchor · TypeScript · Next.js · React Native / Expo · Node · Postgres / Prisma · Playwright · AI agents and voice


[halldon.com](https://halldon.com) · [@huntclubhero](https://x.com/huntclubhero)
