
# binary-tools

Various binary tools for Linux/UNIX

# Filename map

|   Binary      |   Shortcut    |Static |
| ------------- |:-------------:| -----:|
| BusyBox       | bb | - [x]  |
| DarkHttpd      | dh      | - [x]  |
| Rsync | rs      | - [x]  |


# Shortened URL

to easily download these binaries, use the following command:

`wget n0p.me/bin/XX`

XX is the name of the binary you want to download. For example, if you want to download a statically linked `darkhttpd`, the command would be:

`wget n0p.me/bin/dh`


# What is it for

It's mainly developed to use in "tight" environments. For example, if you want to set up a simple HTTP Server to download something inside a docker container, or you just want to use a vi editor using busybox, you can easily download, use and then `rm` the whole thing in no time. 

