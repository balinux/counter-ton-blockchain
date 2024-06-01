# simple-counter

## Project structure

- `contracts` - source code of all the smart contracts of the project and their dependencies.
- `wrappers` - wrapper classes (implementing `Contract` from ton-core) for the contracts, including any [de]serialization primitives and compilation functions.
- `tests` - tests for the contracts.
- `scripts` - scripts used by the project, mainly the deployment scripts.

## How to use

### Build

`npx blueprint build` or `yarn blueprint build`

### Test

`npx blueprint test` or `yarn blueprint test`

### Deploy or run another script

`npx blueprint run` or `yarn blueprint run`

### Add a new contract

`npx blueprint create ContractName` or `yarn blueprint create ContractName`

### my smart contract address

````languagContract deployed at address EQDy0hb-GMWLH8dVewk9i4wAFvviN94Wzl_rFVkz5m4rgmeT
You can view it at https://testnet.tonscan.org/address/EQDy0hb-GMWLH8dVewk9i4wAFvviN94Wzl_rFVkz5m4rgmeT
ID 3320n```
````

[ton explore](https://testnet.tonscan.org/address/EQDy0hb-GMWLH8dVewk9i4wAFvviN94Wzl_rFVkz5m4rgmeT)
[ton faucet](https://t.me/testgiver_ton_bot)

### Refernsi tutorial

[build your first Ton Dapp with tact](https://www.youtube.com/watch?v=J7ZF3KWxX_8)

[create ton tact app](https://docs.tact-lang.org/)
