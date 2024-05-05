Needs webkit2 and gtk header

```
$ meson build
$ cd build
$ ninja
$ ./browse ../1900.mp3 
```
If whitescreen
```
WEBKIT_DISABLE_COMPOSITING_MODE=1 ./browse ../1900.mp3 
```
