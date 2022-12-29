## provider-services query gov params

Query the parameters of the governance process

### Synopsis

Query the all the parameters for the governance process.

Example:
$ <appd> query gov params

```
provider-services query gov params [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for params
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query gov](provider-services_query_gov.md)	 - Querying commands for the governance module

###### Auto generated by spf13/cobra on 5-Dec-2022