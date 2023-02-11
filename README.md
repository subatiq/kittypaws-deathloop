# Deathloop. A kittypaws plugin

A plugin to restart certain docker containers with the use of [kittypaws](https://github.com/subatiq/kittypaws).

## Installation

Put the `run.sh` into `~/.kittypaws/plugins/deathloop` folder.

## Example config

```yaml
plugins:
- deathloop:
    target: mmcv_traffic-npd_1
    frequency: random
    min_interval: PT4H
    max_interval: PT6H
```
