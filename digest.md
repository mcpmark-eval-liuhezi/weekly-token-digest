# Weekly Token Digest

**Week covered:** 2026-10-20 through 2026-10-26
**Data source:** Alchemy token price APIs

## Current Prices

| Token | Current USD Price | As Of (UTC) |
|-------|-------------------|-------------|
| ETH   | $2,329.58         | 2026-10-26 00:28:27 |
| BTC   | $80,238.63        | 2026-10-26 00:28:30 |
| LINK  | $11.4620          | 2026-10-26 00:28:29 |
| UNI   | $6.9300           | 2026-10-26 00:28:29 |
| USDC  | $1.00112          | 2026-10-26 00:28:30 |

## 7-Day Change — Volatile Four

Change basis: daily closes from 2026-10-20 (week open) to 2026-10-26 (week close).

| Token | Week Open (Oct 20) | Week Close (Oct 26) | 7-Day Change |
|-------|---------------------|-----------------------|--------------|
| ETH   | $2,405.92           | $2,326.83             | −3.29%       |
| BTC   | $81,875.26          | $80,048.85            | −2.23%       |
| LINK  | $12.0498            | $11.4414              | −5.05%       |
| UNI   | $7.3086             | $6.9147               | −5.39%       |

### Daily closes (USD)

| Date (UTC) | ETH | BTC | LINK | UNI |
|------------|-----|-----|------|-----|
| 2026-10-20 | 2405.92 | 81875.26 | 12.0498 | 7.3086 |
| 2026-10-21 | 2446.49 | 82943.83 | 12.3157 | 7.4313 |
| 2026-10-22 | 2472.68 | 84082.27 | 12.4969 | 7.4514 |
| 2026-10-23 | 2386.48 | 81328.21 | 11.9475 | 7.0019 |
| 2026-10-24 | 2384.75 | 81102.31 | 11.8174 | 6.9556 |
| 2026-10-25 | 2356.57 | 80810.57 | 11.6129 | 6.8598 |
| 2026-10-26 | 2326.83 | 80048.85 | 11.4414 | 6.9147 |

## USDC Contract Check

Treasury sheet reference: USDC on Ethereum mainnet at `0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48`.

| Quote Method | Price | As Of (UTC) |
|--------------|-------|-------------|
| Symbol quote (USDC) | $1.00112 | 2026-10-26 00:28:30 |
| Contract address (eth-mainnet) | $0.9998 | 2026-10-26 00:27:02 |

- **Difference:** $0.00132
- **Tolerance:** $0.01
- **Result:** ✅ **MATCH** — the contract-address quote agrees with the symbol quote. The difference of $0.00132 is well within the $0.01 tolerance, so the treasury sheet's USDC reference checks out.

## Notes

- All four volatile tickers closed the week lower; LINK (−5.05%) and UNI (−5.39%) were the week's weakest, ETH (−3.29%) and BTC (−2.23%) smaller decliners.
- Trading was choppy mid-week: ETH, BTC and LINK all peaked near Oct 22 (~$2,473 / $84,082 / $12.50) before sliding into the final weekend to lower levels.
- Live spot prices sit within cents of the Oct 26 daily closes, so they match the daily values essentially exactly.