PROJECT
Project: Conversion of a Forex indicator into an Expert Advisor (EA)
Aim: To convert an existing Forex Trading Indicator (Fractal-scalper) into an Expert Advisor, with additional custom features.
EXPERT ADVISOR NAME: Fractal-Times

- It should trade the following currencies
- GBP/JPY, GBP/USD, EUR/USD, XAU/USD
- It should trade only during the London and NewYork sessions
- It should trade 5 days a week
	
#Important addition
----------------------------------------------------------------------------------------------------------------------
Avoid:
-Late Friday (after 5PM GMT)
-Market open (First 1-2 hours Monday)

Continuation
- It should run on VPS â€“ VPS requirements are stated below:
- Low latency (< 10ms to broker)
- 24/7 uptime
- Stable internet
---------------------------------------------------------------------------------------------------
- It should avoid NFP news
- It should trade on Live and Demo account
- It should trade minimum account of $20
- It should trade with minimum lot size of 0.01
- It should trade on H1 and H4 time frames (create multi-timeframe confluence)
- It should be one trade per signal
- It should be simple (controlled simplicity)
- Keep: Clear entry logic (fractal breakout)


KEY NOTES
- Blue arrow = confirmed bullish breakout
- Blue arrow =  buy signal
- Red arrow =  confirmed bearish breakout
- Red arrow =  sell signal 
	
        ENTRY CONDITION:
*	Fractal breakout signal
*	Confirm with candle close

	EXIT CONDITION: 
	Close and reverse trade immediately

	STOPLOSS CONDITION
	Buy trade SL below last fractal low
	Sell trade SL above last fractal high
	SL = fractal-base

         VERY IMPORTANT NOTES:
	This indicator is classified into:
	Breakout scalping system
	Momentum confirmation strategy
	Micro-structure Trend following Tool



EXPLANATION ON TIMEFRAMES
How to use them properly
H4  ===> Trend Filter
-	Determines direction
-	Above structure ===> Buy
-	Below structure ===> Sell
H1 ===> Entry execution
â€¢	Fractal breakout signal trigger here

â€¢	Note: Use it as it is in the indicator 

     
