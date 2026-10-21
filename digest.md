# Weekly Token Digest

**Week covered:** 2026-10-15 through 2026-10-21
**Data source:** Alchemy token price APIs

## Current Prices

| Token | Current USD Price | As Of (UTC) |
|-------|-------------------|-------------|
| ETH   | $2,490.03         | 2026-10-21 20:19:04 |
| BTC   | $84,469.44        | 2026-10-21 20:19:05 |
| LINK  | $12.648           | 2026-10-21 20:19:06 |
| UNI   | $7.5519           | 2026-10-21 20:19:07 |
| USDC  | $1.0006           | 2026-10-21 20:15:48 |

## 7-Day Change — Volatile Four

Change basis: daily closes from 2026-10-15 (week open) to 2026-10-21 (week close).

| Token | Week Open (Oct 15) | Week Close (Oct 21) | 7-Day Change |
|-------|-------------------|---------------------|--------------|
| ETH   | $2,419.69         | $2,446.49           | **+1.11%**   |
| BTC   | $81,603.65        | $82,943.83          | **+1.64%**   |
| LINK  | $12.4256          | $12.3157            | **−0.88%**   |
| UNI   | $7.1872           | $7.4313             | **+3.40%**   |

### Daily closes (USD)

| Date (UTC) | ETH | BTC | LINK | UNI |
|------------|-----|-----|------|-----|
| 2026-10-15 | 2419.69 | 81603.65 | 12.4256 | 7.1872 |
| 2026-10-16 | 2439.96 | 82155.54 | 12.4482 | 7.4238 |
| 2026-10-17 | 2420.56 | 81523.66 | 12.3344 | 7.3266 |
| 2026-10-18 | 2400.31 | 81408.35 | 11.9773 | 7.1452 |
| 2026-10-19 | 2407.84 | 82019.58 | 12.0256 | 7.1892 |
| 2026-10-20 | 2405.92 | 81875.26 | 12.0498 | 7.3086 |
| 2026-10-21 | 2446.49 | 82943.83 | 12.3157 | 7.4313 |

## USDC Contract Check

Treasury sheet reference: USDC on Ethereum mainnet at `0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48`.

| Quote Method | Price | As Of (UTC) |
|--------------|-------|-------------|
| Symbol quote (USDC) | $1.0006 | 2026-10-21 20:15:48 |
| Contract address (eth-mainnet) | $1.0007 | 2026-10-21 20:18:55 |

- **Difference:** $0.0001
- **Tolerance:** $0.01
- **Result:** ✅ **MATCH** — the contract-address quote agrees with the symbol quote. The difference of $0.0001 is well within the $0.01 tolerance, so the treasury sheet's USDC reference checks out.

## Notes

- Live spot prices (above) are slightly ahead of the Oct 21 daily closes, e.g. ETH at $2,490.03 live vs $2,446.49 daily close.
- LINK dipped mid-week to $11.98 (Oct 18) before recovering most of the loss; UNI's +3.40% was the strongest weekly move of the volatile four.
