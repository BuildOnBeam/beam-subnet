# Beam Subnet

## Fuji Testnet

### Fuji Subnet Info

| Beam Fuji Subnet |                                                   |
| :--------------- | ------------------------------------------------: |
| Subnet Name      |                                              Beam |
| Subnet Logo      |                                               tbd |
| Subnet ID        | ie1wUBR2bQDPkGCRf2CBVzmP55eSiyJsFYqeGXnTYt2r33aKW |
| VM ID            | kLPs8zGsTVZ28DhP1VefPCFbCgS7o5bDNez8JUxPVw9E6Ubbz |
| Chain Name       |                                      Beam Testnet |
| Chain Logo       |                                               tbd |
| Blockchain ID    | y97omoP2cSyEVfdSztQHXD9EnfnVP9YKjZwAxhUfGbLAPYT9t |
| Eth Chain ID     |                                             13337 |
| RPC URL          |                                               tbd |
| Explorer URL     |                                               tbd |
| Description      |                                  Beam Fuji Subnet |
| Site             |                                               tbd |

### Fuji Subnet ERC-20 Tokens

| Symbol | Address | Decimals |                                                  Logo                                                   |            Description |
| -----: | ------: | -------: | :-----------------------------------------------------------------------------------------------------: | ---------------------: |
|     MC |         |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              | Beam mock native token |
|    WMC |     tbd |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              |        Mock Wrapped MC |
|  WAVAX |     tbd |       18 | ![AVAX logo](https://assets.coingecko.com/coins/images/12559/small/Avalanche_Circle_RedWhite_Trans.png) |      Mock Wrapped AVAX |
|   WETH |     tbd |       18 |           ![Ethereum logo](https://assets.coingecko.com/coins/images/279/small/ethereum.png)            |     Mock Wrapped Ether |
|   USDC |     tbd |        6 |          ![USDC logo](https://assets.coingecko.com/coins/images/6319/small/USD_Coin_icon.png)           |              Mock USDC |

### Fuji Subnet Contracts

|           Contract | Address | Description |
| -----------------: | ------: | ----------: |
|        Multicall 1 |     tbd |             |
|        Multicall 2 |     tbd |             |
|        Multicall 3 |     tbd |             |
| Uniswap v2 factory |     tbd |             |
|  Uniswap v2 router |     tbd |             |

## Run your own node

- Run an [Avalanche node](https://docs.avax.network/nodes/build/set-up-node-with-installer)
- Install [Avalanche CLI](https://docs.avax.network/subnets/install-avalanche-cli) on it
- Import the subnet genesis file into Avalanche CLI
  - Fuji: `avalanche subnet import subnets/beam-test/export.json`
- Add the subnet setup to your node with Avalanche CLI
  - Fuji: `avalanche subnet join beam-test`
