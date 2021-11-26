

## :PAREX: 

##### 1. API Reference (POST):

```
"https://apiv1.parex.market/getToken”
- `X-APIKEY : Parex API Key`
- `X-SECRET : Parex Secret Key`
```
- `assets : Parex Token`


```
"https://apiv1.parex.market/getAssets”
- `X-APIKEY : Parex API Key`
- `X-SECRET : Parex Secret Key`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : Asset ID` 
- `shortname : Asset Short Name`
- `assets : Asset Name`

```
"https://apiv1.parex.market/getMarkets”
- `X-APIKEY : Parex API Key`
- `X-SECRET : Parex Secret Key`
- `X-TOKEN : Parex Token (getToken)`
```
- `id : Market ID` 
- `marketname : Market Name`
- `paircoin : PairCoin ID`
- `maincoin : MainCoin ID`
- `pairinfo : PairCoin Name`
- `maininfo : MainCoin Name`

