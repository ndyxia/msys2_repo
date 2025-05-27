# msys2_repo

## just a backup of msys2 repos

### usage

> $ cat /etc/pacman.conf

...

``` conf
[mingw64]
Server = https://github.com/ndyxia/msys2_repo/releases/download/DATE_mingw64/

[ucrt64]
Server = https://github.com/ndyxia/msys2_repo/releases/download/DATE_ucrt64/

[clang64]
Server = https://github.com/ndyxia/msys2_repo/releases/download/DATE_clang64/

[msys]
Server = https://github.com/ndyxia/msys2_repo/releases/download/DATE_msys/
```
...

\* change DATE with available dates on releases
example: DATE_mingw64 -> 250521_mingw64
