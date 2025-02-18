## akash query staking validator

Query a validator

### Synopsis

Query details about an individual validator.

Example:
$ akash query staking validator akashvaloper1gghjut3ccd8ay0zduzj64hwre2fxs9ldmqhffj

```
akash query staking validator [validator-addr] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for validator
      --node string     <host>:<port> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
```

### SEE ALSO

* [akash query staking](akash_query_staking.md)	 - Querying commands for the staking module

###### Auto generated by spf13/cobra on 28-Apr-2022
