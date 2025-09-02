
<img width="1096" height="614" alt="image" src="https://github.com/user-attachments/assets/843bcd3a-7daa-4d56-aee4-ed02abf790a6" />
<img width="1088" height="614" alt="image" src="https://github.com/user-attachments/assets/eb4e88c8-0521-4911-8926-6ee1228562ac" />
<img width="1050" height="623" alt="image" src="https://github.com/user-attachments/assets/dc60f10c-2f02-46f9-9de4-1434ceb8df8c" />
<img width="709" height="579" alt="image" src="https://github.com/user-attachments/assets/5c328ba9-6a60-42bb-916d-f4e3a6ec1820" />


## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
