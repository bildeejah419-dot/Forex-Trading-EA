PROJECT
Project: Conversion of a Forex indicator into an Expert Advisor (EA)
Aim: To convert an existing Forex Trading Indicator (Fractal-scalper) into an Expert Advisor, with additional custom features.
EXPERT ADVISOR NAME: Fractal-Times

â€¢	It should trade the following currencies
â€¢	GBP/JPY, GBP/USD, EUR/USD, XAU/USD
â€¢	It should trade only during the London and NewYork sessions
â€¢	It should trade 5 days a week
â€¢	Important addition
----------------------------------------------------------------------------------------------------------------------
Avoid:
â€¢	Late Friday (after 5PM GMT)
â€¢	Market open (First 1-2 hours Monday)
Continuation
â€¢	It should run on VPS â€“ VPS requirements are stated below:
â€¢	Low latency (< 10ms to broker)
â€¢	24/7 uptime
â€¢	Stable internet
---------------------------------------------------------------------------------------------------
â€¢	It should avoid NFP news
â€¢	It should trade on Live and Demo account
â€¢	It should trade minimum account of $20
â€¢	It should trade with minimum lot size of 0.01
â€¢	It should trade on H1 and H4 time frames (create multi-timeframe confluence)
â€¢	It should be one trade per signal
â€¢	It should be simple (controlled simplicity)
â€¢	Keep: Clear entry logic (fractal breakout)


KEY NOTES
â€¢	Blue arrow = confirmed bullish breakout
â€¢	Blue arrow =  buy signal
â€¢	Red arrow =  confirmed bearish breakout
â€¢	Red arrow =  sell signal 
â€¢	ENTRY CONDITION:
*	Fractal breakout signal
*	Confirm with candle close

â€¢	EXIT CONDITION: 
â€¢	Close and reverse trade immediately

â€¢	STOPLOSS CONDITION
â€¢	Buy trade SL below last fractal low
â€¢	Sell trade SL above last fractal high
â€¢	SL = fractal-base

         VERY IMPORTANT NOTES:
â€¢	This indicator is classified into:
â€¢	Breakout scalping system
â€¢	Momentum confirmation strategy
â€¢	Micro-structure Trend following Tool



EXPLANATION ON TIMEFRAMES
How to use them properly
H4  ===> Trend Filter
-	Determines direction
-	Above structure ===> Buy
-	Below structure ===> Sell
H1 ===> Entry execution
â€¢	Fractal breakout signal trigger here

â€¢	Note: Use it as it is in the indicator 

     
