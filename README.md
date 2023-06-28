# Beam Subnet

## Fuji Testnet

[Subnet Overview](https://subnets-test.avax.network/subnets/ie1wUBR2bQDPkGCRf2CBVzmP55eSiyJsFYqeGXnTYt2r33aKW)
[Block Explorer](https://subnets-test.avax.network/beam/)

### Fuji Subnet Info

| Beam Fuji Subnet |                                                                |
| :--------------- | -------------------------------------------------------------: |
| Subnet Name      |                                                           Beam |
| Subnet Logo      |         ![Beam Logo](https://www.onbeam.com/favicon-64x64.png) |
| Subnet ID        |            `ie1wUBR2bQDPkGCRf2CBVzmP55eSiyJsFYqeGXnTYt2r33aKW` |
| VM ID            |            `kLPs8zGsTVZ28DhP1VefPCFbCgS7o5bDNez8JUxPVw9E6Ubbz` |
| Chain Name       |                                                   Beam Testnet |
| Chain Logo       | [Beam Logo](https://www.onbeam.com/android-chrome-512x512.png) |
| Blockchain ID    |            `y97omoP2cSyEVfdSztQHXD9EnfnVP9YKjZwAxhUfGbLAPYT9t` |
| Eth Chain ID     |                                                          13337 |
| RPC URL          |                `https://subnets.avax.network/beam/testnet/rpc` |
| Explorer URL     |                        https://subnets-test.avax.network/beam/ |
| Description      |                                               Beam Fuji Subnet |
| Site             |                                         https://www.onbeam.com |

### Fuji Subnet ERC-20 Tokens

| Symbol |                                    Address | Decimals |                                                  Logo                                                   |            Description |
| -----: | -----------------------------------------: | -------: | :-----------------------------------------------------------------------------------------------------: | ---------------------: |
|     MC |                                            |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              | Beam mock native token |
|    WMC | 0x9bEacCFD08D12281D8Bd07b8B7899C54d6964700 |       18 |              ![MC logo](https://assets.coingecko.com/coins/images/19304/small/Db4XqML.png)              |        Mock Wrapped MC |
|   AVAX | 0x008518e76FAD03f592Bbb7E394C762d5FD54cb97 |       18 | ![AVAX logo](https://assets.coingecko.com/coins/images/12559/small/Avalanche_Circle_RedWhite_Trans.png) |      Mock Bridged AVAX |
|    ETH | 0xA2a41769a58cFf5dF4304CFdd4894f881C0f32E8 |       18 |           ![Ethereum logo](https://assets.coingecko.com/coins/images/279/small/ethereum.png)            |     Mock Bridged Ether |
|   USDC | 0xa0023A23bE994CcD8400476790915e6128b3D474 |        6 |          ![USDC logo](https://assets.coingecko.com/coins/images/6319/small/USD_Coin_icon.png)           |      Mock Bridged USDC |

### Fuji Subnet Contracts

|           Contract |                                    Address | Description |
| -----------------: | -----------------------------------------: | ----------: |
|        Multicall 1 | 0x4661e0d785b2eE35B9a101B684303F1a0daf4cc5 |             |
|        Multicall 2 | 0x680638eB73F5d8a1207f38CC3eF7BAE9281d3F32 |             |
|        Multicall 3 | 0x9BF49b704EE2A095b95c1f2D4EB9010510c41C9E |             |
| Uniswap v2 factory | 0xfABa62a3B12f7c29F21881F5ed4c56cb6d45E4fb |             |
|  Uniswap v2 router | 0x91FE6E298Ee000cAb57c6b71fbBC5D834Bc81ef1 |             |

### Fuji Subnet Thirdweb Contracts

|                Contract |                                    Address |                       Description |
| ----------------------: | -----------------------------------------: | --------------------------------: |
|       Trusted Forwarder | 0xe518da278288337FdE7B9b8cCb1217c40B759580 |                               GSN |
|              TWRegistry | 0x238fC67A71DE52832Ed38cdef6aaD8Cea57cd4b6 |          Register implementations |
|               TWFactory | 0xa9eA7C2af311b361f86d435BFC0e8FE2EB310b56 |                    Deploy proxies |
| Multiwrap Impelentation | 0x5F46D40231c0FfAFf3DB63265C2ea3e6Ec4f19B8 |                        Wrap logic |
|      Pack Impelentation | 0x42A186E3f1012350FB7C829374CC2FAc384189e7 |                     Lootbox logic |
|         Multiwrap Proxy | 0xa8dDAb412cE207b65440A12aF8B4d7C0dB2eeE5e |    Wrap ERC20, ERC721 and ERC1155 |
|              Pack Proxy | 0xE5ccfEFA45601D08B1708500416fa93628A111C3 | Lootbox ERC20, ERC721 and ERC1155 |

## Run your own node

- Run an [Avalanche node](https://docs.avax.network/nodes/build/set-up-node-with-installer)
- Install [Avalanche CLI](https://docs.avax.network/subnets/install-avalanche-cli) on it
- [Import the subnet](https://docs.avax.network/subnets/how-to-import-subnet) into Avalanche CLI
  - Fuji: `avalanche subnet import ./subnets/beam-test/export.json`
- [Join the subnet](https://docs.avax.network/subnets/deploying-subnets-on-prod#joining-a-subnet) with your node using Avalanche CLI
  - Fuji: `avalanche subnet join beam-test`
