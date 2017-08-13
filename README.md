# Warning
This project works, but is very much a work in progress, and documentation will be lacking.

# Building Static Libraries
Run `chmod +x ./build && ./build` to generate the static library (`.a`) files in `./out`. This will generate `.a` files for the following architectures, as well as a "universal" file that targets all of the architectures:

* arm64-v8a
* armeabi
* armeabi-v7a
* mips
* mips64
* x86
* x86_64

