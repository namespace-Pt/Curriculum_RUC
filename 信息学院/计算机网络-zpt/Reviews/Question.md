### Data Link
- CRC怎么保证整除
- 滑动窗口的信道利用率那里, 为什么$W_{max} = 2BD \mathbf{+ 1}$

### Access Control
- 时隙 == 帧时？
- 交换机为什么就不会冲突
- 集线器到底是在第几层
- 集线器的链路上会有CSMA协议么
- 以太网是全双工的？
- 以太网: 谁向谁发送？

### 网络
- 什么叫“分组”
- ip的数据包中是否包含子网掩码(前缀)？如果只给一个目的地址, 是直接遵循最长匹配原则？

路由选择协议是网络之间通信？
自治系统和局域网的区别

对整个网络的宏观理解, 就是我一个数据包从主机A到主机B中间经过的所有操作
什么叫报文？
- 接受窗口和拥塞窗口有什么区别



- PCM体系？就是电话那个采样的
- 码片序列那些
- 格雷码
- 电路交换, 报文交换, 分组交换在哪个层？
- 什么是冗余编码？
- 好像有一个私货检错码#### 发送端
- 发送的数据分段, 以两字节为单位相加
- 得到的结果的进位和低位相加
- 结果取反得到校验和(2字节)
#### 接收端
- 收到的数据和**发送端的校验和**一起以两字节为单位相加
- 得到的结果的进位和低位相加
- 结果取反, 如果为$H0000$, 则正确, 否则出错

- CRC为什么可以检测所有$r$位内的错
- ARQ和停止等待, 后退n帧, 选择重传的关系
- 选择重传的确认帧到底是到x为止都收到还是只收到x
- TDM, FDM什么的到底是在哪个层？
- 令牌环协议, 还没细看
- 网卡工作在物理层？
- 全双工为什么没有争用？
- 以太网自己也可以收到自己发的数据？我记得不行呀
- 以太网性能, 什么平均等待时间
- 字符填充和位填充
- 冲突域和广播域是一个东西吧
- 二层交换机那个总带宽到底除二么
- 交换机能够连接局域网和广域网么
- 链路状态分组的ACK字段和发送标志是什么鬼 ppt57
- IP因为链路层的MTU要进行分段/分片到底叫啥？？？？
- 英特网和互联网有区别？
- 路由器在哪里记录和其直接相连的网络?
- 默认网关是干嘛的
- ICMP是传输层协议？
- 伪首部里为什么也有UDP长度
- TCP中每个数据段都会有确认？
- 传输层的禁止区域
- 超时后也是快速恢复？
- 权限域名服务器和本地域名服务器有啥区别