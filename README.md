# ETW20 Protocol
ETW20 Protocol base on ETHW blockchain writing the string into the memo field of the transaction to achieve this.

## Token Economic
 - Token: ETWS
 - Supply: 21000000000(Non-autobiography and contract invalid)
 - limit: 1000

## Method
 - deploy: `data:,{"p":"etw-20","op":"deploy","tick":"etws","max":"21000000000","lim":"1000"}`
 - mint: `data:,{"p":"etw-20","op":"mint","tick":"etws","amt":"1000"}`
 - transfer: `data:,{"p":"etw-20","op":"transfer","tick":"etws","detail":[{"to":"ETHW Address","amt":"1000"}]}`

## Deploy txid
https://www.oklink.com/cn/ethw/tx/0xa90bd37363bd982d43b858db9cbdeee6fed34362d99bf12e3cdaa69a0e961842

## Deploy block
18448609

## Mint ETWS with TokenPocket Wallet
 - Receiver address: Your address. 
 - Transfer amount 0 ETHW
 - Click on Advanced Settings and fill in text `data:,{"p":"etw-20","op":"mint","tick":"etws","amt":"1000"}`
 - or Click on Advanced Settings and fill in hexadecimal `0x646174613a2c7b2270223a226574772d3230222c226f70223a226d696e74222c227469636b223a2265747773222c22616d74223a2231303030227d`
![image](https://github.com/ETW20-ETWS/ETW20/assets/152284226/a5ae35a1-6279-4bbb-95f1-9415ed463424)


