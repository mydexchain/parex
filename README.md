## :PAREX: 

##### 1. API Reference (POST):

```
"https://apiv1.parex.exchange/echo"
```

```
"https://apiv1.parex.exchange/ping"
```


```
"https://apiv1.parex.exchange/getToken"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
```
- `assets : Parex Token`


```
"https://apiv1.parex.exchange/getAssets"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : Asset ID` 
- `shortname : Asset Short Name`
- `assets : Asset Name`


```
"https://apiv1.parex.exchange/getMarkets"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : Market ID` 
- `marketname : Market Name`
- `paircoin : PairCoin ID`
- `maincoin : MainCoin ID`
- `pairinfo : PairCoin Name`
- `maininfo : MainCoin Name`


```
"https://apiv1.parex.exchange/getWalletBalances"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : line number` 
- `address : Wallet Address`
- `shortname : Asset Short Name`
- `balance : Balance`


```
"https://apiv1.parex.exchange/getMyHistory"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `marketid : Parex Market ID`
- `X-TOKEN : Parex Token (getToken)`
```
- `type : Buy/Sell `
- `date : Datetime `
- `amount : Amount`
- `price : Price`
- `total : Total`
- `marketid : Parex MarketID`
- `pairinfo : PairCoin Name`
- `maininfo : MainCoin Name`


```
"https://apiv1.parex.exchange/getBuyOrders"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `marketid : Parex Market ID`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : line number `
- `type : Buy/Sell `
- `price : Price`
- `remaining : Remaining`


```
"https://apiv1.parex.exchange/getSellOrders"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `marketid : Parex Market ID`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : line number `
- `type : Buy/Sell `
- `price : Price`
- `remaining : Remaining`


```
"https://apiv1.parex.exchange/setSellOrder"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `marketid : Parex Market ID`
- `X-TOKEN : Parex Token (getToken)`
- `X-PRICE : Price`
- `X-AMOUNT : Amount`
```


```
"https://apiv1.parex.exchange/setBuyOrder"
- `apikey : Parex API Key`
- `secretkey : Parex Secret Key`
- `marketid : Parex Market ID`
- `X-TOKEN : Parex Token (getToken)`
- `X-PRICE : Price`
- `X-AMOUNT : Amount`
```

