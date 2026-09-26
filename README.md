# bottom

[![bottom](https://snapcraft.io//bottom/badge.svg)](https://snapcraft.io/bottom)

A snap for [bottom](https://github.com/ClementTsang/bottom).

This is a fork of the original snap repo created by [kz6fittycent](https://github.com/kz6fittycent/bottom)
(huge thanks to them for creating it in the first place); this is now the definitive source of truth for the snap,
which I am maintaining as the main dev for bottom.

## Installation

`sudo snap install bottom`

**After installation, run the following commands so the program will run as intended:**

```shell
sudo snap connect bottom:mount-observe
sudo snap connect bottom:hardware-observe
sudo snap connect bottom:system-observe
sudo snap connect bottom:process-control
```

Note that the snap also has an alias for `btm`, so the normal usage docs should still apply.

## Updating

To deploy a build, use go to <https://snapcraft.io/bottom/builds> and trigger a build, then run the publish
action after it's done to promote it to stable.
