
# Binary Toolbox

Various binary tools for Linux/UNIX

# Filename map

|   Binary      |   Shortcut    |Static |
| ------------- |:-------------:| -----:|
| `BusyBox`       | `bb` | <ul><li>[x] </li>  |
| `DarkHttpd`      | `dh`      | <ul><li>[x] </li>  |
| `Rsync` | `rs`      | <ul><li>[x] </li>  |

# Shortened URL

to easily download these binaries, use the following command:

`wget n0p.me/bin/XX`

XX is the name of the binary you want to download. For example, if you want to download a statically linked `darkhttpd`, the command would be:

`wget n0p.me/bin/dh`

# Custom Architectures

by default, the URL mapper will point to `x64` folder. If a new folder gets added (`arm` for example), the URL will work like this:

`wget n0p.me/bin/arm/XX`

I'll add the mapping table for each architectures as soon as I added them into this repository.

# What is it for

It's mainly developed to use in "tight" environments. For example, if you want to set up a simple HTTP Server to download something inside a docker container, or you just want to use a vi editor using `busybox`, you can easily download, use and then `rm` the whole thing in no time.
