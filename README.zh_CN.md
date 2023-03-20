[English](./README.md)

# my-vcpkg-triplet
一些vcpkg triplet的收集

## How to use?
将参数 `--overlay-triplets=<relative-or-absolute-path-to-checkout>` 转递给 `vcpkg install` 或者在使用vcpkg工具链时通过在CMake中设定`VCPKG_OVERLAY_TRIPLETS`为`<relative-or-absolute-path-to-checkout>`。

## Triplets:

`x64-linux-clang`: 一个使用clang的 `x64-linux`版.

`x64-linux-clang-libc++`: 一个使用clang和libc++的 `x64-linux`版.

## Thanks
从 [Neumann-A's repo](https://github.com/Neumann-A/my-vcpkg-triplets) 修改。