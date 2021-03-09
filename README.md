## MWget
MWget is a "MultiLine" wget for all POSTX System! The original package can be downloaded from [here](http://jaist.dl.sourceforge.net/project/kmphpfm/mwget/0.1/mwget_0.1.0.orig.tar.bz2).

It seems that the original package had some problems of missing "#include<...>" code when compiling on relatively new POSTX System. I fix those problems that I encounter and make this repository.

## Install
- Download the .zip package and decompress it or directly clone the repository:
```
git clone https://github.com/BlueHeart0621/MWget.git
cd MWget
```

- Configure compile environment:
```bash
./configure
```
If you want to install `mwget` at specific path, just add `--prefix=<path>` option.

- Make and install:
```
make -j4
make install
```