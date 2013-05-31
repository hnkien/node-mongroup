
# node-mongroup

  A nodejs port of [mongroup](https://github.com/jgallen23/mongroup), a group-based
  process monitor backed by [mon](https://github.com/visionmedia/mon).

## Installation

```
$ npm install -g mongroup
```

## mongroup(1)

  The `mongroup` executable is also aliased as `mg`.

```

  Usage: mongroup [options]

  Options:

    -h, --help           output usage information
    -V, --version        output the version number
    -c, --config <path>  load configuration [./mongroup.conf]

  commands:

    status           output process status
    stop [names]     stop all or specified processes
    start [names]    start all or specified processes
    restart [names]  restart all or specified processes

```

## Configuration

  Example configuration.

```bash
# settings

logs = /tmp/logs
pids = /tmp/pids

# web app

web-1 = node server 9001
web-2 = node server 9002
web-3 = node server 9003
web-4 = node server 9004
```

# License

  MIT
