## cloudcli server snapshot

List/manage server snapshots

### Synopsis

List/manage server snapshots

```
cloudcli server snapshot [flags]
```

### Options

```
      --create string   Name of a new snapshot to create
      --delete string   Snapshot ID to delete
  -h, --help            help for snapshot
      --id string       Specific server UUID
      --name string     Server name or regular expression matching a single server
      --revert string   Snaptshot ID to revert to
      --wait            Wait for command execution to finish only then exit cli.
```

### Options inherited from parent commands

```
      --api-clientid string   API Client ID
      --api-secret string     API Secret
      --api-server string     API Server Hostname
      --config string         config file (default is $HOME/.cloudcli.yaml)
      --debug                 enable debug output to stderr
      --dryrun                enable dry run mode, does not perform actions
      --format string         output format, default format is a human readable summary
      --no-config             disable loading from config file
```

### SEE ALSO

* [cloudcli server](cloudcli_server.md)	 - Server management

###### Auto generated by spf13/cobra on 24-Sep-2019