# bitfinexAPI

I used "BITFINEX API v2"
<br><br>

01. HOW TO USED ?<br>
[ "https://api.bitfinex.com/v2/tickers?symbols=" ]<br>
Select the desired coin from the list below and enter it after this address with a t in front of it.<br>
Example, i choose btcusd. This word not with a "t" in fron of it. put a "t" on it to make a "tBTCUSD".<br><br>

 btcusd	xmrusd	zrxusd	yywusd rcnusd<br>
 ethusd	omgusd	qtumusd	tnbusd<br>
 eosusd	dashusd	batusd	funusd<br>
 ltcusd	zecusd	sntusd	spkusd<br>
 xrpusd	trxusd	repusd	elfusd<br>
 bchusd	btgusd	qashusd	sngusd<br>
 iotausd	sanusd	gntusd	mnausd<br>
 neousd	edousd	aidusd	rlcusd<br>
 etcusd	etpusd	datausd	avtusd<br><br>

02. json parse<br>
import json and urllib.<br>
save url in apiUrl variable.<br><br>

json data are saved in the dict variable.<br>
 HOW? - line no.7 ~ line no.13<br><br>

json data view is in the this link.<br>
" https://api.bitfinex.com/v2/tickers?symbols=tBTCUSD,tLTCUSD "<br><br>

03. timer<br>
import threading.<br><br>

added function in last line this code.<br>
threading.Timer( [second],[func name] ).start ]<br><br>

func name is not with "()".
