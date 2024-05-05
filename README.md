## Fund Me

A simple smart contract named FundMe that facilitates crowdfunding by allowing users to contribute funds in Ether to a project.

The contract verifies that the amount contributed meets a minimum threshold in USD value, which is determined by querying a Chainlink Price Feed for the current Eth to USD conversion rate.

Only the owner of the contract can trigger withdrawal of the funds. Additionally, the contract includes functions for retrieving information such as the amount funded by each address.

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

NOTE: make sure you have filled out your .env file

```shell
$ make deploy
```

OR

```shell
$ make deploy-sepolia
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
