hassin@P51:~/projects2/stm32-cmake-bare2$ cmake -Bbuild -DCMAKE_TOOLCHAIN_FILE=gcc-arm-none-eabi.cmake -DCMAKE_BUILD_TYPE=Debug -DCMAKE_EXPORT_COMPILE_COMMANDS=true

hassin@P51:~/projects2/stm32-cmake-bare2/build$ make clean && make -j8
