### Show OS Version

使用其中一个方法即可，哪个可以用哪个。

1. `cat /etc/os-release`{{execute}}
2. `lsb_release -a`{{execute}}


### Show CPU Info

`cat /proc/cpuinfo`{{execute}}

说明：（下标从0开始）
processor：表示几个核数（包含虚拟核）；
其他的自行百度谷歌；

### Show Memory Info

内存信息：
`cat /proc/meminfo`{{execute}}

内存占用信息：
`free -g`{{execute}}

### Show Disk Info

`df -h`{{execute}}
