## TUNMAN

 🚇👨‍🚒

> SSH Tunnel Manager bash script

## INSTALLATION

```bash
$ wget -O tunman https://raw.githubusercontent.com/khanhicetea/tunman/master/tunman
$ sudo mv tunman /usr/local/bin/tunman && sudo chmod +x /usr/local/bin/tunman
```

## USAGE

This script only supports local port forwarding tunnel, which you have an alias host in SSH config file `~/.ssh/config`

### Add an alias connection

```bash
$ tunman a [alias] [local-port] [remote-port]
```

### Remove an alias connection

```bash
$ tunman r [alias]
```

### Connect an alias connection

```bash
$ tunman c [alias]
```

### Disconnect an alias connection

```bash
$ tunman d [alias]
```

## LICENSE

MIT LICENSE
