# ChargingBull
Created by tawtis#9000

## Charting Division

### Stocks, Indices, and Equities - $
- Example:
`$tsla rsi mfi`
![TSLA Daily with RSI and MFI](https://cdn.discordapp.com/attachments/563558685608116254/589570549412397083/chart.ashxttslatyctast_csch_200psma_50sma_200sma_20mfi_b_14rsi_b_14pdslrev1560172643487.png)
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
`$/es m`
![ES Monthly Chart](https://cdn.discordapp.com/attachments/563558685608116254/589569415339704330/espm1rev1560172643487.png)
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
![Bitcoin Weekly Chart](https://cdn.discordapp.com/attachments/563558685608116254/589571839848611840/fx_image.ashxbtcusd_w1_l.png)
- Available Parameters
    - Time Intervals
        - `5` -> 5min
        - `h` -> Hourly
        - `d` -> Daily
        - `w` -> Weekly 

### Forex - /
- Currently supports [10 Currency Pairs](https://elite.finviz.com/forex_charts.ashx)
- Example:
`$usd/jpy w`
![Weekly USD/JPY Chart](https://cdn.discordapp.com/attachments/563558685608116254/589574723760029707/fx_image.ashxusdjpy_w1_l.png)
- Available Parameters
    - Time Intervals
        - `5` -> 5 minute (Default)
        - `h` -> Hourly
        - `d` -> Daily
        - `m` -> Monthly
