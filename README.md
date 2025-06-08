# mcd
English
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/Ordneri/mcd/blob/main/README-zh.md">中文</a>

## About

`mcd` is a linux user script, combined mkdir and cd.

## Installation

BASH:
```bash
curl -sSL -o mcd.temp https://raw.githubusercontent.com/Ordneri/mcd/main/mcd && mv mcd.temp $PREFIX/bin/mcd
```

## Usage


Use ". mcd NewDirName" to create and change to this directory.
**Note add dot and space at beginning.**
```
. mcd NewDirName
```

## Uninstall


BASH:
```bash
rm -f $PREFIX/bin/mcd
```


## Note


mcd only tested on Termux.
