
# Binary Toolbox

Various binary tools for Linux/UNIX

# Filename map (x64)

|   Software                                                | Version        |Filename               | Binary link   |
| ----------------------------------------------------------|----------------|:---------------------:| -------------:|
| [3proxy](https://github.com/z3APA3A/3proxy)               |0.9-devel       | `3proxy`              |  Static       |
| [Bandwhich](https://github.com/imsnif/bandwhich)          |0.12.0          | `bandwhich`           |  Static       |
| [Brook](https://github.com/txthinking/brook)              |20181212        | `brook`               |  Static       |
| [BusyBox](https://busybox.net)                            |1.29.2          | `busybox`             |  Static       |
| [Corkscrew](https://github.com/bryanpkc/corkscrew)        |2.0             | `corkscrew`           |  Static       |
| [curl](https://github.com/curl/curl)                      |7.63.0          | `curl`                |  Static       |
| [Darkhttpd](https://github.com/ryanmjacobs/darkhttpd)     |1.12.from.git   | `dh`                  |  Static       |
| [DnsMonster](https://github.com/mosajjal/dnsmonster)      |0.1             | `dnsmonster`          |  Dynamic      |
| [Dropbear](https://github.com/mkj/dropbear)               |2018.76         | `dropbear`            |  Static       |
| [Dead Simple VPN](https://github.com/jedisct1/dsvpn)      |0.1.3           | `dsvpn`               |  Static       |
| [Fish](https://github.com/fish-shell/fish-shell)          |3.1.0           | `fish`                |  Static       |
| [Gost](https://github.com/ginuerzh/gost)                  |2.7.1           | `gost`                |  Static       |
| [Gotop](https://github.com/cjbassi/gotop)                 |2.0.1           | `gotop`               |  Static       |
| [Htop](https://hisham.hm/htop/)                           |1.0.3           | `htop`                |  Static       |
| [httptunnel](https://www.gnu.org/software/httptunnel/)    |3.3.git         | `httptunnel-*`        |  Static       |
| [ICMP Tunnel](https://github.com/DhavalKapil/icmptunnel)  |1.0.0-alpha     | `icmptunnel`          |  Static       |
| [iodine](https://github.com/yarrick/iodine)               |0.7.0           | `iodine`/`iodined`    |  Static       |
| [IOPing](https://github.com/koct9i/ioping)                |0.9             | `ioping`              |  Static       |
| [NetCat](https://www.freebsd.org/cgi/man.cgi?query=netcat)|1.68            | `nc`                  |  Static       |
| [Kibi](https://github.com/ilai-deutel/kibi)               |0.1.2           | `kibi`                |  Static       |
| [Miniserve](https://github.com/svenstaro/miniserve)       |0.5.0           | `miniserve`           |  Static       |
| [Nano](https://www.nano-editor.org/)                      |2.7.0           | `nano`                |  Static       |
| [PassiveDNS](https://github.com/gamelinux/passivedns)     |1.2.1           | `pdns`                |  Static       |
| [Socat](http://www.dest-unreach.org/socat/)               |1.7.3.0         | `socat`               |  Static       |
| [TCPDump](https://www.tcpdump.org/)                       |4.7.4           | `tcpdump`             |  Static       |
| [WG Tools](https://github.com/WireGuard/wireguard-tools)  |0.3.0           | `wg-user`             |  Static       |
| [Zgrab/2](https://github.com/zmap/zgrab2)                 |0.1.3           | `zgrab` `zgrab2`      |  Static       |
| [Zmap](https://github.com/zmap/zmap)                      |2.1.1           | `ztee` `zmap` `zmapbl`|  Static       |



# Filename map (ARM)

|   Binary      |   Shortcut    |Static     |
| ------------- |:-------------:| -----:|
|                | `BusyBox`       |                | `bb` |<ul><li>[x] </li>  |
|                | `PV`      |                | `pv`      |<ul><li>[x] </li>  |
|                | `Strace` |                | `st`      |<ul><li>[x] </li>  |
|                | `TcpDump`      |                | `td`      |<ul><li>[x] </li>  |

# Shortened URL

to easily download these binaries, use the following command:

`wget n0p.me/bin/XX`

XX is the name of the binary you want to download. For example, if you want to download a  Statically linked `darkhttpd`, the command would be:

`wget n0p.me/bin/dh`

# Custom Architectures

by default, the URL mapper will point to `x64` folder. If a new folder gets added (`arm` for example), the URL will work like this:

`wget n0p.me/bin/arm/XX`

I'll add the mapping table for each architectures as soon as I added them into this repository.

# What is it for

It's mainly developed to use in "tight" environments. For example, if you want to set up a simple HTTP Server to download something inside a docker container, or you just want to use a vi editor using `busybox`, you can easily download, use and then `rm` the whole thing in no time.
