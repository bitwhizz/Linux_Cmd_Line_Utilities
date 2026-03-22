# ch2/part-1

Introduces _"Hello, ~~world~~ CMake!"_ application.

## Visual Studio Code Debugging

Open Visual Studio Code from `ch2/part-1`.

```bash
cd ch2/part-1
code .

# or

code ch2/part-1
```

##Resolve setup issues:

sudo apt install libssl-dev

https://cmake.org/download/
cmake-3.31.11.tar.gz

tar -xzvf cmake-3.22.1.tar.gz
cd cmake-3.22.1
./bootstrap
make -j$(nproc)
sudo make install


 sudo apt-get install ninja-build



## Commands

```bash
# start
cd ch2/part-1
# configure
cmake -B build -G "Ninja Multi-Config"
# build
cmake --build build
# run
./build/Debug/minimal-cmake
```





