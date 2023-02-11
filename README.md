# Deathloop. A kittypaws plugin

A plugin to restart certain docker containers with the use of [kittypaws](https://github.com/subatiq/kittypaws).

## Installation

Put the `run.sh` into `~/.kittypaws/plugins/deathloop` folder.

## Example config

```yaml
plugins:
- deathloop:
    target: container-name
    frequency: random
    min_interval: PT4H
    max_interval: PT6H
```

`target` - which container to restart.

The rest is described in [kittypaws](https://github.com/subatiq/kittypaws) README.
