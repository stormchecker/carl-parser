> [!IMPORTANT]
> ## carl-parser was replaced by a Python-based lark parser and is no longer maintained. Please use the native parsing support integrated in [stormpy](https://github.com/moves-rwth/stormpy) instead.


Parser for carl data structures
--------------------------------------

This is an [ANTLR](http://www.antlr.org)-based parser which is meant as an extension to [CArL](https://github.com/stormchecker/carl-storm).

### Requirements

The parser requires the following tools:
- [CArL](https://github.com/stormchecker/carl-storm)
- Java

### Building

Build carl-parser with

```bash
mkdir build
cd build
cmake ..
make
```

You can run tests with

```bash
make test
```

### Authors:

- Harold Bruintjes
- Sebastian Junges
- Gereon Kremer
- Matthias Volk
