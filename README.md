# Random Raffle Contract

## About

This code is to create a random smart contract lottery.

## What does it do?

1. Users can enter by paying for a ticket
    1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner.
    1. And this will be done programatically.
3. Using Chainlink VRF and Chainlink Automation
    1. Chainlink VRF => randomness
    2. Chainlink Automation -> Time based trigger

## Build
```shell
#To build the project

$ forge build
```

## Tests
```shell
#To run tests

$ forge test
```

## Deploy
```shell
#To deploy the project

$ make deploy
```