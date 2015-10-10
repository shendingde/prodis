# 高可用

技术方案： heartbeat + drbd  + netcontrold <br>
heartbeat , drbd两者为标准服务 <br>
heartbeat 做双机的HA 实现心跳和切换功能
drbd