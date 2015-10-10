# 高可用

技术方案： heartbeat + drbd  + netcontrold <br>
heartbeat , drbd两者为标准服务 <br>
heartbeat 做双机的HA 实现心跳和切换功能 <br>
drbd 做双机之间块数据等级的数据同步 <br>
netcontrold为自己编写的服务器,为了控制切换.