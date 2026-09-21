# bottom

[![bottom](https://snapcraft.io//bottom/badge.svg)](https://snapcraft.io/bottom)

A snap for [bottom](https://github.com/ClementTsang/bottom).

Shoutout to the original snap repo created by [kz6fittycent](https://github.com/kz6fittycent/bottom); this is a fork that I'm managing now as the maintainer of bottom.

## Installation

`sudo snap install bottom`

**After installation, run the following commands so the program will run as intended:**

```shell
sudo snap connect bottom:mount-observe
sudo snap connect bottom:hardware-observe
sudo snap connect bottom:system-observe
sudo snap connect bottom:process-control
```

## Updating

To deploy a build, use go to <https://snapcraft.io/bottom/builds> and trigger a build, then run the publish action after it's done to promote it to stable.
