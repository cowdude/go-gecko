# CoinGecko API Client for GoLang

[![Build Status](https://travis-ci.com/superoo7/go-gecko.svg?branch=master)](https://travis-ci.com/superoo7/go-gecko)

Simple API Client for CoinGecko written in Golang

## Available endpoint

[Refer to CoinGecko official API](https://www.coingecko.com/api)

|            Endpoint             | Status  |          Function           |
| :-----------------------------: | :-----: | :-------------------------: |
|              /ping              |   [/]   |            Ping             |
|          /simple/price          | partial |      SimpleSinglePrice      |
| /simple/supported_vs_currencies |   [/]   | SimpleSupportedVSCurrencies |
|           /coins/list           |   [/]   |          CoinsList          |
|         /exchange_rates         |   [/]   |        ExchangeRate         |
|             /global             |   [/]   |           Global            |

## Usage

Installation with go get.

```
go get -u github.com/superoo7/go-gecko
```

For usage, checkout [Example folder for v3](/_example/v3)
