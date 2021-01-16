# ChargingBull
Created by tawtis#9000

## General Division
- Available Commands
    - ban
    - brokers
    - cc
    - clear
    - clearchat
    - help
    - kick
    - ping
    - report
    - whois

## Charting Division

### Stocks, Indices, and Equities - $
- Example:
`$tsla rsi mfi`
- Available Parameters
    - Indicators
        - `rsi` 
        - `macd` 
        - `adx`
        - `atr` 
        - `cci`
        - `fi` 
        - `mfi` 
        - `ppi` 
        - `rwi` 
        - `roc` 
        - `rmi` 
        - `stofu` 
        - `stofsl` 
        - `stofa` 
        - `trix`
        - `ult` 
        - `wr` 
        - `ema` 
        - `bb_20` 
        - `bb_50` 
        - `hilo`
 
When specifying numbers for an indicator, do not leave a space. For example. "ema 20" would become "ema20"
        
    - Chart Types
        - `candle`
        - `line` 
    - Time Intervals
        - `3` -> 3min
        - `5` -> 5min
        - `15` -> 15min
        - `d` -> Daily
        - `w` -> Weekly
        - `m` -> Monthly

### Futures - f$
- [48 Futures / Commodities](https://elite.finviz.com/futures_charts.ashx)
- Example:
`f$es m`
- Available Parameters
    - Time Intervals
        - `5` -> 5min
        - `h` -> Hourly
        - `d` -> Daily
        - `w` -> Weekly 

### Crypto - c$
- Supports
    - `btc` -> Bitcoin
    - `ltc` -> LiteCoin
    - `eth` -> Ethereum
    - `xrp` -> Ripple
    - `bch` -> Bitcoin Cash
- Example:
`c$btc w`
- Available Parameters
    - Time Intervals
        - `5` -> 5min
        - `h` -> Hourly
        - `d` -> Daily
        - `w` -> Weekly 

### Forex - $
- Currently supports [10 Currency Pairs](https://elite.finviz.com/forex_charts.ashx)
- Example:
`$usd/jpy w`
- Available Parameters
    - Time Intervals
        - `5` -> 5 minute (Default)
        - `h` -> Hourly
        - `d` -> Daily
        - `m` -> Monthly
