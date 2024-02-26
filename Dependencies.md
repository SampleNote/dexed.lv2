# Dependencies

Follows some dependencies required to build this project.

## lvtk library

### lvtk v1

```shell
apt install python2 python-pip libboost-system-dev
```

### lvtk v2

_Note: dot tool = graphviz_

```shell
apt install meson doxygen graphviz libcppunit-dev
```

### lvtk v3

```shell
apt install glslang-tools reuse
```

# Build the project

After install the dependencies, you should execute the following:

```shell
export PKG_CONFIG_PATH=/usr/local/lib/pkgconfi

# Download source code and build it.
git clone git@github.com:SampleNote/dexed.lv2.git
cd dexed/src
make install
```
