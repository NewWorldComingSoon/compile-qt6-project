# UnknownKit


## Building.

```
cmake -Bbuild -TLLVM-MSVC_v143 -DCMAKE_PREFIX_PATH=c:\Qt\6.30\msvc2019_64static -DCMAKE_INSTALL_PREFIX=install
cmake --build build --config Release
cmake --install build
```
