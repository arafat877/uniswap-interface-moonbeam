# Classic DEX Example forked from Sushiswap-Classic-Exchange (Uniswap)

Forked from [sushiswap/sushiswap-classic-exchange](https://github.com/sushiswap/sushiswap-classic-exchange), and updated for both a Moonbase Standalone Node and Moonbase Alpha.

## Moonbase Standalone Addresses

If you use the [following repository](https://github.com/albertov19/uniswap-contracts-moonbeam): your contracts should have the following addresses:

```
      "WETH": "0xc9AaC2857B56CC8a274C360Fec231241d815Ca63",
      "Factory": "0x78A75A02c07a123a9EF05edB35Fc361f9fbd8B8a",
      "Router": "0x9618848B265b937992F5Eaa004F0ff30dF118FAA",
      "multicall": "0xbF910631692fd925fD094ee09A3783E8B6E87879",
      "init_code_hash": "0x01429e880a7972ebfbba904a5bbe32a816e78273e4b38ffa6bdeaebce8adba7c",
      "tok1": "0xe573BCA813c741229ffB2488F7856C6cAa841041",
      "tok2": "0xBb0CC0fb3e0c06725c67167501f850B4900D6DB5"
```

## Moonbase Alpha Addresses

To make the interface work with your Moonbase Alpha deployment, you need to modify the `./src/moonbase_address.json`. Also make sure that you modify the addresses in the SDK repo.

On Moonbase Alpha, these are the following addresses:

```
      "WETH": "0xc9AaC2857B56CC8a274C360Fec231241d815Ca63",
      "Factory": "0x78A75A02c07a123a9EF05edB35Fc361f9fbd8B8a",
      "Router": "0x9618848B265b937992F5Eaa004F0ff30dF118FAA",
      "multicall": "0xbF910631692fd925fD094ee09A3783E8B6E87879",
      "init_code_hash": "0x01429e880a7972ebfbba904a5bbe32a816e78273e4b38ffa6bdeaebce8adba7c",
      "tok1": "0x825458b871FC6582d94c6d2BCe887897DFD9EDA2",
      "tok2": "0xF8f525327D199F340D60d4b3ee847B5d49a28E3C"
```

## Build

Install packages:

```
npm i
```

Run:

```
npm start
```
