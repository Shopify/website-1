---
title: Mount
series: vtctldclient
commit: b539ce927ee86b723a94a627cdec1403dd4020f0
---
## vtctldclient Mount

Mount is used to link an external Vitess cluster in order to migrate data from it.

### Options

```
  -h, --help   help for Mount
```

### Options inherited from parent commands

```
      --action_timeout duration              timeout to use for the command (default 1h0m0s)
      --compact                              use compact format for otherwise verbose outputs
      --server string                        server to use for the connection (required)
      --topo-global-root string              the path of the global topology data in the global topology server (default "/vitess/global")
      --topo-global-server-address strings   the address of the global topology server(s) (default [localhost:2379])
      --topo-implementation string           the topology implementation to use (default "etcd2")
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.
* [vtctldclient Mount list](./vtctldclient_mount_list/)	 - List all mounted external Vitess Clusters.
* [vtctldclient Mount register](./vtctldclient_mount_register/)	 - Register an external Vitess Cluster.
* [vtctldclient Mount show](./vtctldclient_mount_show/)	 - Show attributes of a previously mounted external Vitess Cluster.
* [vtctldclient Mount unregister](./vtctldclient_mount_unregister/)	 - Unregister a previously mounted external Vitess Cluster.

