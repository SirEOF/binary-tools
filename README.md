
# Binary Toolbox

Various binary tools for Linux/UNIX

# Filename map (x64)

|   Software                                                | Filename              | Binary link   |
| ----------------------------------------------------------|:---------------------:| -------------:|
| [3proxy](https://github.com/z3APA3A/3proxy)               | `3proxy`              |      Static   |
| [Brook](https://github.com/txthinking/brook)              | `brook`               |      Static   |
| [BusyBox](https://busybox.net)                            | `busybox`             |      Static   |
| [curl](https://github.com/curl/curl)                      | `curl`                |      Static   |
| [Darkhttpd](https://github.com/ryanmjacobs/darkhttpd)     | `dh`                  |      Static   |
| [DnsMonster](https://github.com/mosajjal/dnsmonster)      | `dnsmonster`          |      Dynamic  |
| [Dropbear](https://github.com/mkj/dropbear)               | `dropbear`            |      Static   |
| [Dead Simple VPN](https://github.com/jedisct1/dsvpn)      | `dsvpn`               |      Static   |
| [Gost](https://github.com/ginuerzh/gost)                  | `gost`                |      Static   |
| [Gotop](https://github.com/cjbassi/gotop)                 | `gotop`               |      Static   |
| [ICMP Tunnel](https://github.com/DhavalKapil/icmptunnel)  | `icmptunnel`          |      Static   |
| [iodine](https://github.com/yarrick/iodine)               | `iodine`/`iodined`    |      Static   |
| [IOPing](https://github.com/koct9i/ioping)                | `ioping`              |      Static   |
| [Miniserve](https://github.com/svenstaro/miniserve)       | `miniserve`           |      Static   |
| [Nano](https://www.nano-editor.org/)                      | `nano`                |      Static   |
| [PassiveDNS](https://github.com/gamelinux/passivedns)     | `pdns`                |      Static   |
| [Socat](http://www.dest-unreach.org/socat/)               | `socat`               |      Static   |
| [Suricata](https://suricata-ids.org/)                     | `miniserve`           |      AppImage |
| [WG Tools](https://github.com/WireGuard/wireguard-tools)  | `wg-user`             |      Static   |
| [Zgrab/2](https://github.com/zmap/zgrab2)                 | `zgrab` `zgrab2`      |      Static   |
| [Zmap](https://github.com/zmap/zmap)                      | `ztee` `zmap` `zmapbl`|      static   |



# Filename map (ARM)

|   Binary      |   Shortcut    |Static |
| ------------- |:-------------:| -----:|
| `BusyBox`       | `bb` |<ul><li>[x] </li>  |
| `PV`      | `pv`      |<ul><li>[x] </li>  |
| `Strace` | `st`      |<ul><li>[x] </li>  |
| `TcpDump`      | `td`      |<ul><li>[x] </li>  |

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
