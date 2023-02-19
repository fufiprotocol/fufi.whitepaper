
`fufi.whitepaper.dex-spot`

# FuFi - Order-book based Spot Trading DEX Protocol

## Table of Content
  - [Why Order-book based Spot Trading?](#why-spot-trading)
  - [Key Characteristics](#key-characteristics)
    - [limit and market order](#limit-and-market-order)
    - [price-time-priority-basis](#price-time-priority-basis)
    - [realtime onchain settlement](#realtime-onchain-settlement)
    - [self-custody](#self-custody)
  - [Liquidity and Market Maker](#liquidity-and-market-maker)
  - [Trading Pairs](#trading-pairs)
    - [ERC-20 Tokens](#erc-20-tokens) 
    - [NFT-1155 Tokens](#nft-1155-tokens)
  - [List/Delist Tokens](#listdelist-tokens)
  - [Trading Fees](#trading-fees)
  - [Resource Model](#resource-model)
  - [Armonia Blockchain](#armonia-blockchain)
  
## Why Order-book based Spot Trading?

There are many decentralized exchanges (DEXs) protocols existing in DeFi world nowadays and majority of them fall into the category of automated market maker (AMM) which incentivizes average users to become liquidity providers. However, AMM has been regarded as a passive market making mechanism. Tranditional traders are primarily more interested in active market making, meaning placing orders with a limit or market price.

This will give traders the full control over their orders, unlike automated market making. Orderbook and matching is fully automated on-chain and orders are coming directly from FuFi end users.

## Key Characteristics

### limit and market order
FuFi on-chain limit orderbooks allow users to submit orders with directions, prices and sizes, giving them control over their trading. Orders are recorded, matched and settled fully onchain. Users can also cancel unmatched orders from onchain.

### price-time-priority-basis
In short, the highest bid and the lowest ask converge to represent the current market price, and users have the option to cross this bid-ask spread to immediately execute the order. Given the transparency of this system, users can see market depth in real-time.
 
### Realtime onchain settlement
Unlike centralized exchanges (CEXs) that keep settled assets in their centralized custodian environment, FuFi Spot-trading DEX transfers the settled assets to the traders immediately upon settlement.

## Liquidity and Market Maker
Liquidity is key for attracting traders/investors to trade on FuFi DEX. It can be especially hard for the initial stage to have enough traders and liquidity in the market. However, through market making activities, all top well-known exchanges will be good sources for borrowing liquidity from.

In a long run, average users can also leverage a cloud-based trading bot service to do quantitive trading including meeting market making needs.

## Trading Pairs

First, crypto assets in ERC-20 form will be supported and then NFT-1155 tokens will be also supported.

### ERC-20 Tokens

Initially supported trading pairs are as following upon launch:

- BTC-USDT
- ETH-USDT
- BTC-USDC
- ETH-USDC
  
Once FuFi decentralized stablecoin is ready, it will be introduced as a new option for the quote symbol.

### NFT-1155 Tokens

Technically these kind of assets can be also traded in FuFi DEX and when the great needs arise for certain NFT-1155 or even other type of NFT tokens to be traded in DEX, FuFi will certainly open up the trading functions to them.

## List/Delist Tokens

Main coins like BTC/ETH/USDT/USDC will be supported on the launch of FuFi spot DEX. For new tokens, they will be only listed after going through a governance process via onchain voting. It can be also possible to delist a token from FuFi spot after a governance process.

## Trading Fees

There is a fee charged on each trade. All of those net fees go into a buy/burn of FuFi governance token.

## Resource Model

FuFi doesnot prefer a gas model which is deemed not friendly to end users and DEX operation. Hence resource model as adopted in FuFi protocols usually requires end users to stake in blockchain main coins in order to particpate in trading activities. However, to achieve the best user experience, FuFi DEX will cover the resource cost for each trade instead of requiring end users to pay for the resource usage. 

Howerver, some malicious attackers could create a denial of serice (DOS) attack by placing a large amount of miniature-sized trades to occupy the execution queue and estentially block all other trades from other legitimate users. This kind of attacks will be countered by a risk control engine running offchain to monitor all onchain activites and blacklist such trades and penalize them by removing their funds into a common pool for other users to share.

## Armonia Blockchain

[Armonia](https://amax.network) is a blockchain with significantly higher speed and lower costs than most contemporary blockchains. It has hunderds of settlement cycles per second and costs zero fee to place orders. The Armonia-based FuFi DEX will have the speed, cost and UX that users expect from a centralized exchange–all while being trustless and noncustodial.

And because of FuFi’s full cross-chain integration, users will be able to trade BTC, ETH, ERC20s, ARC20 tokens (the token standard on the Armonia blockchain), and more on it. This will finally give DeFi users a fully decentralized exchange that has the experience they’ve come to expect from CeFi (e.g. centralized exchanges).
