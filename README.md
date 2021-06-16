# aiya000 bug.n config
## Configure

```shell-session
# Please see the section 'Keymappings by aiya000'
$ vim src/Config.ahk
```

## Build & Run

1. Close running bug.n if bug.n already is running
1. Open ./tools dir with explorer.exe
1. Run build.ahk by double clicking
1. Run ./bugn.exe

Or

```shell-session
# This way is too heavy. Why?
$ /mnt/c/Program\ Files/AutoHotkey/Compiler/Ahk2Exe.exe /in src/Main.ahk /out Main.exe \
    && ./Main.exe
```
