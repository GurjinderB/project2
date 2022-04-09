# Project 2

## Contents

* [Introduction](#Introduction)
* [Design](#Design)
* [Risk Assessment](#Risk-Assessment)
* [Agile Development](#Agile-Development)
* [Testing](#Testing)

## Introduction
This project aims to demonstrate my understanding of python, implement CI development practices and knowlegde fo cloud fundamentals.

## Design
There are four services to the project:
1. ### Service 1 ###
Responsible for rendering a Jinja2 template for users to interact with the application. Users will be able to see realtime data of trades executed.

2. ### Service 2 ###
Connecting to an external API, recieving live trade data from the Binance exchange. The first implementation will focus on one currency pair: **BTC/USDT**.
  * Future revisions can allow for retrevial of other currency pairs.
  
3. ### Service 3 ###
Contain a database of names and balances of traders and choose two random names from the database, representing the buyer and seller. Each trader will have an initial balance of **1 BTC** and **10000 USDT**.

4. ### Service 4 ###
Asign the random names generated by service 3 to the trade recieved from service 1, and update the balances according to the trader data.
 * A future revision can update the balances stored in the database for each trader.



## Risk Assessment

| Risk | Impact | Mitigation |
|------|--------|--------------------|
| Broken vesion gets deployed | High | Use a version control system such as github |
|Cross site request forgery | Low | Set a secret key |





## Agile Development
![Kanban board](https://github.com/GurjinderB/exchange-app/blob/main/figures/Kanbanbord.png)
## Testing

## App
![Application Home](https://github.com/GurjinderB/exchange-app/blob/main/figures/home.png)
![Create Account](https://github.com/GurjinderB/exchange-app/blob/main/figures/create-account.png)
![Trade](https://github.com/GurjinderB/exchange-app/blob/main/figures/trade.png)
