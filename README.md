## Orion Protocol — Intro

## Features
- You can add ETH or ORN address
- For added addresses tracks balance and usdt/eur exchange rate
- Charts

## Running
- Copy `.env.front.example` to `.env.front`
- Copy `.env.back.example`  and `.env.back`
- In `.env.back` you **MUST** specify WEB3_HTTP_PROVIDER_API param at least. Current app developed with Ropsten Infura API where API looks like https://ropsten.infura.io/v3/YOUR_TOKEN
- Run `docker-compose up -d`

## Sources

- [Frontend repository](https://github.com/lobotomoe/rates_front)
- [Backend repository](https://github.com/lobotomoe/rates)
