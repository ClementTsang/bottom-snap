# bottom

[![bottom](https://snapcraft.io//bottom/badge.svg)](https://snapcraft.io/bottom) [![🧪 Snap Builds](https://github.com/kz6fittycent/bottom/workflows/%F0%9F%A7%AA%20Snap%20Builds/badge.svg)](https://github.com/kz6fittycent/bottom/actions?query=workflow:"🧪+Snap+Builds")

A snap for [bottom](https://github.com/ClementTsang/bottom).

Original snap repo created by [kz6fittycent](https://github.com/kz6fittycent/bottom), this is a fork that I'm managing now as the maintainer of bottom.

## Install the snap:

`sudo snap install bottom`

**After installation, run the following commands so the program will run as intended:**

```shell
- sudo snap connect bottom:mount-observe
- sudo snap connect bottom:hardware-observe
- sudo snap connect bottom:system-observe
- sudo snap connect bottom:process-control
```
