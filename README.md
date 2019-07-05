## Related Repository

- https://github.com/nagadomi/cutorch
- https://github.com/nagadomi/cunn
- https://github.com/nagadomi/cudnn.torch

## Original README.md

[![Build Status](https://travis-ci.org/torch/distro.svg?branch=master)](https://travis-ci.org/torch/distro)

#### NOTE: Torch is not actively developed anymore and is in maintenance mode.

Self-contained Torch installation
============

#### Please refer to the [Torch installation guide](http://torch.ch/docs/getting-started.html#_) for details on how to make a fresh install of Torch on Linux or MacOS.
#### If on windows with msvc, please refer to this [guide](win-files/README.md) for details on installation and usage.


## Repo content

#### Clone

```bash
git clone https://github.com/mbayser/distro.git ~/torch --recursive
```

#### Lua and Torch
The self-contained Lua and Torch installations are performed via:
```bash
TORCH_LUA_VERSION=LUA52 ./install.sh
```
