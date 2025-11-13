# Beam common ABIs

Common ABIs to use with tools like Beam's [Safe](https://app.safe.onbeam.com/) fork or foundry.

## Ownership and permission

For changing contract ownership or access control roles, and special permissions that come with those:

### Ownable

Single owner with special permissions.

- ABI: `access/Ownable`
- Methods:
  - `transferOwnership(address)`
  - `renounceOwnership(address)`

#### Ownable 2-Step

additionally to the above:

- ABI: `access/Ownable2Step`
- Method: `acceptOwnership(address)`

### Access Control

// TODO

## Proxies (upgradeable contracts)

Used with upgradeable contracts. Usually either a `ProxyAdmin` paired with a `TransparentUpgradeableProxy`, _or_ a `UUPSUpgradeable` contract.

### ProxyAdmin

// TODO

### TransparentUpgradeableProxy

// TODO

### UUPSUpgradeable

// TODO

## [Precompiles](https://build.avax.network/docs/virtual-machines/default-precompiles)

Precompiles provide control functionality in Avalanche L1s.

### [AllowList](https://build.avax.network/docs/virtual-machines/default-precompiles/allowlist)

General interface shared by all precompiles, also used for Avalanche's _Deployer Allow List_ and _Transaction Allow List_ ([read more](https://build.avax.network/docs/virtual-machines/default-precompiles)).

- ABI: `precompiles/AllowList`
- Methods:
  - `setAdmin(address)`
  - `setManager(address)`
  - `setEnabled(address)` (can call the precompile)
  - `setNone(address)` (revoke permissions)

### Native Minter

Mint native coins

- ABI: `precompiles/NativeMinter`
- Contract: `0x0200000000000000000000000000000000000001`
- Method: `mintNativeCoin(address, uint256)`

## Uniswap

Set the protocol fee recipient and -setter

- ABI: `uniswap/v2.Factory`
- Contracts:
  - Testnet: `0x`
  - Mainnet: `0x`
- Methods:
  - `setFeeTo(address)` (recipient)
  - `setFeeToSetter(address)` ("admin")

Remove Liquidity
