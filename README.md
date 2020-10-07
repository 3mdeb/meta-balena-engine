# meta-balena-engine

The goal of the layer is to allow for usage of the
[balenaEngine](https://www.balena.io/engine/) in the regular (not BalenaOS)
Yocto builds.

# Usage

* Add `meta-balena-engine` to your `bblayers.conf`

> layer depends on `meta-virtualization`

* Add `balena-engine` to your image
