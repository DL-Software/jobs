# DL Software UI Challenge

Are you a good UI developer? 

There is a STOMP websocket: `wss://v3.godelnum.com/events/topic/watchlist/c96d5122-6d4f-4780-9779-925019051565`

This will push Last Sale (Trade) and Quote deltas for ~a dozen securities. It is only on during market hours 9:30AM -> 4:00PM.

It is key alue pairs. The key is a composite key of `ASSET_CLASS:SYMBOL-KEY`: `value`. For example, for Apple's stock price, you might see `EQ:AAPL-lastPrice`: `188.33` 

1. Using React, build a UI to display these events. 
2. Bencmark the framerate of the UI during peak market hours. 

