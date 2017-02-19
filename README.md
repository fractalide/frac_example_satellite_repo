# Template

## Project Description:

## Problem:

## Solution:

## Stability Status:

- [x] Raw
- [ ] Draft
- [ ] Stable
- [ ] Deprecated
- [ ] Legacy

## Build Instructions
Ensure you've installed [nix](https://nixos.org/nix).
```
$ export NIX_PATH+=:fractalide=https://github.com/fractalide/fractalide/archive/v20170218.tar.gz
$ git clone git://github.com/fractalide/workbench.git
$ cd workbench
$ nix-build --argstr rs test
```
