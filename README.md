# vix-variance-risk-premium
Does the VIX overestimate realised S&amp;P 500 volatility? 32 years of daily data, 1994–2026.

# VIX vs realised volatility (1994–2026)

Compares the VIX with the S&P 500 volatility that actually followed over the next 21 trading days.

**Data:** daily ^VIX and SPY closes from yfinance.

**Findings**
- The VIX exceeded realised vol by 3.7 points on average, on 83% of days
- Skew of -3.2: steady small gains, rare large losses
- Worst case was 19 Feb 2020 (VIX 14.4, realised vol 80.9 the following month)
- The premium grows with the VIX level, but worst-case losses don't shrink

**Caveats:** overlapping windows, so observations aren't independent. Measures the premium, not a tradable strategy.

**Files:** `Do options overprice volatility.ipynb` (code), `Do options overprice volatility.pdf` (write-up)
