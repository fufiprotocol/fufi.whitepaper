
`fufi.whitepaper.dex-spot`

# FuFi - Order-book based Spot Trading DEX Protocol

## Table of Content
  - [Why Order-book based Spot Trading?](#why-spot-trading)
  - [Design Principles](#design-principles)
    - [Transparency](#transparency)
    - [No front-running](#no-front-running)
    - [No centralized custody](#no-centralized-custody)
    - [Realtime settlement](#realtime-settlement)
    - [Affordability](#affordablity)
  - [Architecture](#architecture)
  - [Contribute](#contribute)
  - [License](#license)
  
## Why Order-book based Spot Trading?

There are many decentralized exchanges (DEXs) protocols existing in DeFi world nowadays and majority of them fall into the category of automated market maker (AMM) which encentivizes average users to become liquidity providers. However, AMM has been regarded as a passive market making mechanism. Tranditional traders are primarily more interested in active market making, meaning placing orders with a limit or market price.

This will give traders full control over their orders, unlike automated market making. Orderbook and matching is fully automated on-chain and orders are
from FuFi end users.

## Key characteristics
### limit order and market order
FuFi on-chain limit orderbooks allow users to submit orders with directions, prices and sizes, giving them control over their trading. Orders are recorded, matched and settled fully onchain. Users can also cancel unmatched orders from onchain.

### price-time-priority-basis
In short, the highest bid and the lowest ask converge to represent the current market price, and users have the option to cross this bid-ask spread to immediately execute the order. Given the transparency of this system, users can see market depth in real-time.
 
### realtime settlement
### self-custody


## Market maker

## Trade to mine

## Trading pairs

First, crypto assets in ERC-20 form will be supported and then NFT-1155 tokens will be also supported.

### ERC-20 tokens
  - BTC-USDT
  - ETH-USDT
  - BTC-USDC
  - ETH-USDC
  
Once FuFi decentralized stablecoin is ready, it will be introduced as a new option for the quote symbol.

### NFT-1155 supported

## List/Delist tokens on FuFi Spot DEX

Main coins like BTC/ETH/USDT/USDC will be supported on the launch of FuFi spot DEX. For new tokens, they will be only listed after going through a governance process via onchain voting. It can be also possible to delist a token from FuFi spot after a governance process.

## Trading fees

There is a fee charged on each trade. All of those net fees go into a buy/burn of FuFi governance token.

## Resource model

FuFi doesnot prefer a gas model which is not friendly to end users and DEX operation. Hence resource model as adopted in FuFi protocols usually requires end users to stake in blockchain main coins in order to particpate in trading activities. However, to achieve the best user experience, FuFi DEX will cover the resource cost for each trade instead of requiring end users to pay for the resource usage. 
