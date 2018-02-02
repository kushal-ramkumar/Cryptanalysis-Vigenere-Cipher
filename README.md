# Cryptanalysis of the Vigenère Cipher

The Vigenère Cipher is a form of a polyalphabetic cipher that can be used for encrypting alphabetic text using a series of interwoven Caesar Ciphers based on the letters of a keyword. This project can be used to break a Vigenère Cipher using statistical analysis.

## Getting Started

### Prerequisites

Nothing, really. It's just one C++ file. Compile it and run in an environment of choice!

```
I've used Microsoft Visual Studio 12 as the IDE for development.
```

### Installing

The project uses CMake to create an MSVC solution file. It works just as well with MinGW or Unix Makefiles.

```
cmake . -Bbuild -G"Visual Studio 12"
```

The solution file is created in "build/", load it, compile and run!

## Built With

* [Miscrosoft Visual Studio 12](https://www.visualstudio.com/) - IDE


## Authors

* **Kushal Ramkumar** - [kushal-ramkumar](https://github.com/kushal-ramkumar)

## Acknowledgments

* The attack is based on concepts explained in An Introduction to Mathematical Cryptography by Jeffrey Hoffstein
