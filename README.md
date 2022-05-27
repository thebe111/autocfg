# Autocfg - Autotools Usage Example

Basic example how to use the autotools build system

```shell
$ autoscan
$ mv configure.scan configure.ac
$ nvim configure.ac  # add projects config like `CMakeLists.txt`
$ autoconf
$ touch Makefile.am
$ aclocal
$ automake --add-missing
$ autoreconf
$ autoconf
```

