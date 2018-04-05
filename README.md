# pentomino

[![PyPI](https://img.shields.io/pypi/v/librosa.svg)](https://pypi.python.org/pypi/librosa)
[![Anaconda-Server Badge](https://anaconda.org/conda-forge/librosa/badges/version.svg)](https://anaconda.org/conda-forge/librosa)
[![License](https://img.shields.io/pypi/l/librosa.svg)](https://github.com/librosa/librosa/blob/master/LICENSE.md)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1174893.svg)](https://doi.org/10.5281/zenodo.1174893)

[![Build Status](https://travis-ci.org/librosa/librosa.png?branch=master)](http://travis-ci.org/librosa/librosa?branch=master)
[![Build status](https://ci.appveyor.com/api/projects/status/8i1hhr8yj78195xf?svg=true)](https://ci.appveyor.com/project/bmcfee/librosa)
[![Coverage Status](https://coveralls.io/repos/librosa/librosa/badge.svg?branch=master)](https://coveralls.io/r/librosa/librosa?branch=master)
[![Dependency Status](https://dependencyci.com/github/librosa/librosa/badge)](https://dependencyci.com/github/librosa/librosa)

### Requirements

- External Applications 

```
# dnf install cflow ctags cscope
```

- Libraries and Build System

```
# dnf install meson
# dnf install igraph-devel 
# dnf install glib2-devel
# dnf install gtk3-devel
```

### Configure and Build

```
$ meson --prefix=/usr/local build
$ ninja -C build/ -j 4
```

### Install 
```
$ ninja -C build/ install
```

## License

NULL™ Free as an AIR License

Free as an AIR License is a free of charge - unconditional grant; for any person to deal with the material without any restriction and/or limitation.
