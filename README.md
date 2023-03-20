[简体中文](./README.zh_CN.md)

# my-vcpkg-triplet
Small collection of vcpkg triplets

## How to use?
pass the parameter `--overlay-triplets=<relative-or-absolute-path-to-checkout>` to `vcpkg install` or  
set/append `<relative-or-absolute-path-to-checkout>` to `VCPKG_OVERLAY_TRIPLETS` in cmake when using the vcpkg toolchain. 

## Triplets:

`x64-linux-clang`: A release fork by `x64-linux` but use clang.

`x64-linux-clang-libc++`: A release fork by `x64-linux` but use clang and libc++.

## Thanks
Changed from [Neumann-A's repo](https://github.com/Neumann-A/my-vcpkg-triplets).
