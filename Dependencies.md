# Dependencies

Follows some dependencies required to build this project.

## Linux / Ubuntu dependencies

_Note: Needs validation._

Ref. https://github.com/asb2m10/dexed/wiki/Linux-build-dependencies

```shell
sudo apt install libx11-dev \
libcurl4-gnutls-dev \
libfreetype6-dev \
libasound2-dev \
libxinerama-dev \
libjack-jackd2-dev \
libxcursor-dev \
libxrandr-dev
```

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
