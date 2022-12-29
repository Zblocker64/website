## provider-services query evidence

Query for evidence by hash or for all (paginated) submitted evidence

### Synopsis

Query for specific submitted evidence by hash or query for all (paginated) evidence:

Example:
$ <appd> query evidence DF0C23E8634E480F84B9D5674A7CDC9816466DEC28A3358F73260F68D28D7660
$ <appd> query evidence --page=2 --limit=50

```
provider-services query evidence [flags]
```

### Options

```
      --count-total       count total number of records in evidence to query for
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for evidence
      --limit uint        pagination limit of evidence to query for (default 100)
      --offset uint       pagination offset of evidence to query for
  -o, --output string     Output format (text|json) (default "text")
      --page uint         pagination page of evidence to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of evidence to query for
      --reverse           results are sorted in descending order
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query](provider-services_query.md)	 - Querying subcommands

###### Auto generated by spf13/cobra on 5-Dec-2022