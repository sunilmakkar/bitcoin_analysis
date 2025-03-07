# Crypto Market Analysis: Strategic Insights from Market Data

By Sunil Makkar
March 2025 

## Executive Summary

This project transforms raw cryptocurrency data into a strategic asset for financial decision-makers. By tapping into Kraken’s market feeds, I’ve analyzed Bitcoin’s price trends, trading activity, and liquidity as of March 2025. The result is a clear picture of market dynamics—equipping businesses to manage risk, seize opportunities, and execute with confidence. Full details are in crypto_EDA.ipynb.

## Objective

The goal was to assess cryptocurrency market behavior from a business perspective—beyond technical exploration. I aimed to uncover patterns in Bitcoin’s performance that inform investment timing, risk exposure, and trade execution, delivering value to portfolio managers, traders, and financial strategists.

## Approach

- **Data Acquisition:** Secured real-time ticker prices, order book depth, and historical daily OHLC data (Jan–Mar 2025) for Bitcoin and select USD-paired coins via Kraken’s API.  

- **Processing:** Structured raw data into clean, actionable tables, converting timestamps to readable dates and ensuring numeric precision for analysis.  

- **Visualization:** Produced a candlestick chart with volume and moving averages, designed for intuitive interpretation by non-technical stakeholders.  

- **Tools:** Utilized Python with Pandas for data handling, mplfinance for visualization, and the Kraken SDK for seamless market access.

## Key Conclusions

**1. Volatility Shapes Strategy**
Bitcoin’s price oscillated by over 20% in two months, with sharp drops (e.g., $106K to $84K). This volatility demands agile business tactics—locking in gains or hedging during turbulence.  

**2. Volume Signals Action**
Trading volume ranged from 311 BTC on quiet days to 6,144 BTC during peaks, highlighting moments of market intensity. Businesses can use these cues to time entries, exits, or risk adjustments.  

**3. Liquidity Enables Scale**
Order book analysis showed over $1.2M in bids and asks within 1% of Bitcoin’s $88,629 price (March 7). This depth assures firms they can move large volumes without destabilizing costs.

## Next Steps

- **Contextual Analysis:** Blend market data with external factors (e.g., news, regulations) to explain shifts.  

- **Real-Time Tools:** Develop alerts for price or volume thresholds to enable instant responses.  

- **Risk Quantification:** Add metrics like volatility or maximum drawdown to refine risk management.
