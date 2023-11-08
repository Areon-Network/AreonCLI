# AreonCLI

#### AreonCLI is an all-in-one command-line interface (CLI). It enables users to run an Areon Chain node, manage wallets, and interact with the network through queries and transactions.

#### The CLI allows users to input commands to perform various operations and communicate with the network. With the features provided by AreonCLI, it becomes easier to perform different tasks on the Areon and manage the network effectively.

## Example commands

| Command                    | Description                                                                       |
| -------------------------- | --------------------------------------------------------------------------------- |
| -h / -help                 | `Help for CLI`                                                                    |
| version                    | `Print the application binary version information`                                |
| keys list                  | `Imported or created wallets`                                                     |
| keys add [name]            | `Create a new wallet`                                                             |
| keys unsafe-export-eth-key | `Exporting your Areon wallet as evm`                                              |
| start                      | `Run the full node`                                                               |
| debug addr [address]       | `Convert an address between hex encoding and bech32`                              |
| init [moniker]             | `Initialize private validator, p2p, genesis, and application configuration files`   |
| config [key]               | `Create or query an application CLI configuration file`                              |
| validate-genesis           | `Validates the genesis file at the default location`                               |
| tendermint reset-state     | `Remove all the data and WAL`                                                     |
| tendermint show-validator  | `Show this node's tendermint validator info`                                      |
| tendermint show-node-id    | `Show this node's ID`                                                             |