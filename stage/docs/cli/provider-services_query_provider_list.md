## provider-services query provider list

Query for all providers

```
provider-services query provider list [flags]
```

### Options

```
      --count-total       count total number of records in providers to query for
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for list
      --limit uint        pagination limit of providers to query for (default 100)
      --offset uint       pagination offset of providers to query for
  -o, --output string     Output format (text|json) (default "text")
      --page uint         pagination page of providers to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of providers to query for
      --reverse           results are sorted in descending order
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query provider](provider-services_query_provider.md)	 - Provider query commands

###### Auto generated by spf13/cobra on 5-Dec-2022