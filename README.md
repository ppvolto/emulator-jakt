# emulator-jakt [WIP]

The target of this Repository is to learn [Jakt](https://github.com/SerenityOS/jakt)
and posible create a simple Framework to write different Emulators
for [SerenityOS](https://github.com/SerenityOS/serenity)?

## Building
Required is a Jakt installation with ```JAKT_INSTALL``` pointing to the installation path

```
cmake -G Ninja -B build -DCMAKE_PREFIX_PATH=$JAKT_INSTALL
ninja -C build
```

## TODO

Test Implementations for the following Instruction sets
* [ ] rv32i
* [ ] rv64i