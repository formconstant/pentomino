# pentomino

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
