---
title: "pgo show backup"
---
## pgo show backup

Show backup information

### Synopsis

Show backup information. For example:

	pgo show backup mycluser

```
pgo show backup [flags]
```

### Options

```
      --backup-type string   The backup type output to list. Valid choices are pgbackrest or pgdump. (default "pgbackrest")
  -h, --help                 help for backup
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver that will process the request from the pgo client. Note that the URL should **not** end in a '/'.
      --debug                    Enable additional output for debugging.
      --disable-tls              Disable TLS authentication to the Postgres Operator.
      --exclude-os-trust         Exclude CA certs from OS default trust store
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo show](/pgo-client/reference/pgo_show/)	 - Show the description of a cluster

###### Auto generated by spf13/cobra on 14-Jan-2021