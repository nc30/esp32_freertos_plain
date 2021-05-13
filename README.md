# esp32_freertos_plain

~~~
$ cmake -S . -B build -DCMAKE_TOOLCHAIN_FILE=amazon-freertos/tools/cmake/toolchains/xtensa-esp32.cmake -GNinja
$ cmake --build build
$ amazon-freertos/vendors/espressif/esp-idf/tools/idf.py -p /dev/ttyUSB0 -b 1500000 flash monitor
~~~
