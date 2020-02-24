#分布式第一次作业
*Wireshark是非常流行的网络封包分析软件，可以截取各种网络数据包，并显示数据包详细信息。*
## `ping`一个服务器
> 在wireshark中打开wlan选项，开始抓包
> 
> 打开cmd，输入`ping 122.112.200.214` 发送数据
> 
> 输入过滤格式`ip.dest eq` 即可查看详细信息
> ![ping](ping.png?raw=true)
***
## `tracert`一个服务器
> 在cmd中键入`tracert 122.112.200.214`
> 
> 查看到达目标IP地址所经过的路径
> 
> ![tracert](tracert.png?raw=true)
