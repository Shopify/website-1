---
title: Materialize show
series: vtctldclient
commit: d3012c188ea0cfc6837917fc6642ea23be9bb1ff
---
## vtctldclient Materialize show

Show the details for a Materialize VReplication workflow.

```
vtctldclient Materialize show
```

### Examples

```
vtctldclient --server localhost:15999 Materialize --workflow product_sales --target-keyspace customer show
```

### Options

```
  -h, --help           help for show
      --include-logs   Include recent logs for the workflow. (default true)
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --format string             The format of the output; supported formats are: text,json. (default "text")
      --server string             server to use for the connection (required)
      --target-keyspace string    Target keyspace for this workflow.
  -w, --workflow string           The workflow you want to perform the command on.
```

### SEE ALSO

* [vtctldclient Materialize](./vtctldclient_materialize/)	 - Perform commands related to materializing query results from the source keyspace into tables in the target keyspace.

