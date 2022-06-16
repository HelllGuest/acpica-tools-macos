# acpica-tools-macos


## How to build

_On linux install dependencies first, like: gcc, m4, bison, flex_

Download this repo using git clone or download as zip

```
$ cd acpica-unix-VERSION
$ make clean
$ make
```
To generate an individual tool (examples):
```
$ cd acpica-unix-VERSION
$ make iasl
$ make acpixtract
$ make acpiexec
$ make acpihelp
$ make acpisrc
$ make acpibin
```

To install the generated tools in /usr/bin:
```
$ cd acpica-unix-VERSION
$ make install
```
[Reference](https://acpica.org/downloads)
