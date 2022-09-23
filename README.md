cmake -G Ninja -B build -DCMAKE_PREFIX_PATH=$JAKT_INSTALL -DCMAKE_CXX_COMPILER=clang++-14
ninja -C build