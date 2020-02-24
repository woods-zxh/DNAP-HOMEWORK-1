#分布式第一次作业
*Wireshark是非常流行的网络封包分析软件，可以截取各种网络数据包，并显示数据包详细信息。*
## ping一个服务器
> 在wireshark中打开Wlan选项，开始抓包
> 打开cmd，输入`ping 122.112.200.214` 开始发送数据
> 输入过滤格式ip.dest eq 即可查看详细信息
> ![ping](https://github.com/444knig/DNAP-HOMEWORK-1/blob/master/ping.png)
***
## [^tracert]一个服务器
> 在cmd中键入`tracert 122.112.200.214`
> 查看到达目标IP地址所经过的路径
> ![tracert](https://github.com/444knig/DNAP-HOMEWORK-1/blob/master/tracert.png)

[^tracert]: Tracert是路由跟踪程序，用于确定 IP 数据报访问目标所经过的路径