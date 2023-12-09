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
 - Receiver address:0x521F460FA35F3231Ca176e2B3B8Db17896D4D66e.
 - Transfer amount 0 ETHW
 - Click on Advanced Settings and fill in text `data:,{"p":"etw-20","op":"mint","tick":"etws","amt":"1000"}`
 - or Click on Advanced Settings and fill in hexadecimal `646174613A2C7B2270223A226574772D3230222C226F70223A226D696E74222C227469636B223A2265747773222C22616D74223A2231303030227D`
![image](https://github.com/ETW20-ETWS/ETW20/assets/152284226/d93e90a2-c4c8-4efe-b74c-dd51e76814b6)
