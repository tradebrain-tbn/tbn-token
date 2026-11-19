# TradeBrain (TBN)

**Utility token of TradeBrain, an automated crypto trading platform — on Solana.**  
Fixed supply · no minting · no freezing · immutable metadata · team vested · liquidity locked.  
*Forged, not printed.*

| | |
|---|---|
| Mint address | `FxZSdHu6vLGSdo8qbG9K6UuBZxmAzY2dXEyrdc36u6UA` |
| Network | Solana mainnet-beta (SPL token, 9 decimals) |
| Total supply | 10,000,000,000 TBN — fixed, mint authority revoked |
| Freeze authority | none |
| Metadata | immutable (isMutable = 0), stored on Arweave: [tbn.json](https://gateway.irys.xyz/331uYhJyFikyrz9Lib9AGzBnngVrQt2RkyzpTZdR2LPK) |
| Logo | [tbn_logo.png (Arweave)](https://gateway.irys.xyz/Aw83Lx7AmSeWuT25Wr8uMAMKPQwKtxFPdQJyCkPjWn1R) |
| Liquidity | Raydium CPMM pool TBN/SOL, AMM `GXkJxqznGsNSCmeCSuHNLqkKrVY7ZT2Q2Yt8ArkWk2KH` — 100% LP permanently locked (Raydium Burn & Lock, 9 Nov 2026) |
| Team vesting | 24 months linear, daily, non-cancellable — [Streamflow contract](https://app.streamflow.finance/contract/solana/mainnet/CRgCmUGP6BZPGWjTp74Khf1UPTSjmxbp3mfhjmYJD7VJ) |
| Dashboard | https://tradebrain-tbn.github.io/tbn-token/ |
| Explorer | [Solscan](https://solscan.io/token/FxZSdHu6vLGSdo8qbG9K6UuBZxmAzY2dXEyrdc36u6UA) · [DexScreener](https://dexscreener.com/solana/GXkJxqznGsNSCmeCSuHNLqkKrVY7ZT2Q2Yt8ArkWk2KH) |

## Allocation

| Allocation | % | TBN | Wallet |
|---|---|---|---|
| Liquidity | 60% | 6,000,000,000 | `HVuSqwSDGCar3rUyu2uzaLADrrtvYK7xpudof5YqLs2j` |
| Community | 20% | 2,000,000,000 | `CYHZVkHJnjCCbs5wWwgjcPFt6XhFkvhEtXnd8k6WBWkz` |
| Team / Treasury | 10% | 1,000,000,000 (vested) | `DWa8ZrARzXD7XxxuWy5i3fcKtcyBRwAsv8oj3F5zQGy8` |
| Reserve | 10% | 1,000,000,000 | `CJxGK3Di4Y4TVUjqzgstboHtXKwR8wm7t9STAXLxLKvF` |

## Utility

TBN is the membership and discount token of TradeBrain. TBN carries no profit share, dividend or ownership right.

**First service — TradeBrain Lab Notes (live since 15 Nov 2026).** A members-only Telegram group for wallets holding **at least 5,000,000 TBN**. Every 14 days, in turns: a note on reading charts and indicators, and one finished measurement from TradeBrain's own data (the question, the method, what the data said — published at least 14 days after it was closed). No signals, positions or settings. Members above the threshold get priority and a discount on the first paid TradeBrain service, once it exists.

Join: [https://telegram.me/collablandbot?start=VFBDI1RFTCNDT01NIy0xMDAzOTc5MzMxMzcw](https://telegram.me/collablandbot?start=VFBDI1RFTCNDT01NIy0xMDAzOTc5MzMxMzcw) — the Collab.Land bot checks your balance; you sign a message to prove wallet ownership (read-only, no transaction, never share a seed phrase). Members who drop below the threshold are removed at the next balance check.

## Channels

[X — @TradeBrainTBN](https://x.com/TradeBrainTBN) · [Lab Notes (Telegram, holders ≥5M TBN)](https://telegram.me/collablandbot?start=VFBDI1RFTCNDT01NIy0xMDAzOTc5MzMxMzcw) · [GitHub](https://github.com/tradebrain-tbn/tbn-token)

YouTube (short explainers with the TBN mascot) follows in December 2026. Content is in English; channels for Vietnam, the Philippines and Indonesia come later.

## This repository

`index.html` — the public dashboard (single file, reads directly from the Solana blockchain and public APIs; no server, no keys).  
`tbn.json`, `tbn_logo.png` — devnet-era copies of the metadata; the mainnet metadata points to Arweave (links above).

*Not financial advice. Crypto assets are volatile.*
