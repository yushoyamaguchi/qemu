# To Build
sudo ./configure --prefix=/path/to/qemu
sudo make
sudo make install

# to install
- libpixman-1-dev  ninja-build  libglib2.0-dev libleveldb-dev flex
- python3-venv  python3-pip  python3-setuptools
## install with pip
tomli

# binary path
./build/


# build memo 202407
export CFLAGS="$(pkg-config --cflags glib-2.0)"
export LDFLAGS="$(pkg-config --libs glib-2.0)"


bashrcに
export PKG_CONFIG_PATH=/usr/local/lib/pkgconfig:$PKG_CONFIG_PATH
export LD_LIBRARY_PATH=/usr/local/lib:$LD_LIBRARY_PATH


sudo ./configure