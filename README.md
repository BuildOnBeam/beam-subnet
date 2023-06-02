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

| Symbol |                                    Address | Decimals |                                                  Logo                                                   |            Description |
| -----: | -----------------------------------------: | -------: | :-----------------------------------------------------------------------------------------------------: | ---------------------: |
|     MC |                                            |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              | Beam mock native token |
|    WMC | 0x9bEacCFD08D12281D8Bd07b8B7899C54d6964700 |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              |        Mock Wrapped MC |
|   AVAX |                                        tbd |       18 | ![AVAX logo](https://assets.coingecko.com/coins/images/12559/small/Avalanche_Circle_RedWhite_Trans.png) |      Mock Bridged AVAX |
|    ETH |                                        tbd |       18 |           ![Ethereum logo](https://assets.coingecko.com/coins/images/279/small/ethereum.png)            |     Mock Bridged Ether |
|   USDC |                                        tbd |        6 |          ![USDC logo](https://assets.coingecko.com/coins/images/6319/small/USD_Coin_icon.png)           |      Mock Bridged USDC |

### Fuji Subnet Contracts

|           Contract |                                    Address | Description |
| -----------------: | -----------------------------------------: | ----------: |
|        Multicall 1 | 0x4661e0d785b2eE35B9a101B684303F1a0daf4cc5 |             |
|        Multicall 2 | 0x680638eB73F5d8a1207f38CC3eF7BAE9281d3F32 |             |
|        Multicall 3 | 0x9BF49b704EE2A095b95c1f2D4EB9010510c41C9E |             |
| Uniswap v2 factory | 0xfABa62a3B12f7c29F21881F5ed4c56cb6d45E4fb |             |
|  Uniswap v2 router | 0x91FE6E298Ee000cAb57c6b71fbBC5D834Bc81ef1 |             |

## Run your own node

- Run an [Avalanche node](https://docs.avax.network/nodes/build/set-up-node-with-installer)
- Install [Avalanche CLI](https://docs.avax.network/subnets/install-avalanche-cli) on it
- [Import the subnet](https://docs.avax.network/subnets/how-to-import-subnet) into Avalanche CLI
  - Fuji: `avalanche subnet import ./subnets/beam-test/export.json`
- [Join the subnet](https://docs.avax.network/subnets/deploying-subnets-on-prod#joining-a-subnet) with your node using Avalanche CLI
  - Fuji: `avalanche subnet join beam-test`
