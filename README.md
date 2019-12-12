#### 文件字段说明

每一行的数据代表一条用户连接Wi-Fi的记录，字段（按次序从左到右用制表符`\t`隔开）分别是：

| asso_id            | user_name    | client_mac      | ap_id                | bytes                        | RSSI                                                   | conn_time    | disconn_time |
| ------------------ | ------------ | --------------- | -------------------- | ---------------------------- | ------------------------------------------------------ | ------------ | ------------ |
| 连接记录的id，唯一 | 用户名，唯一 | 用户设备MAC地址 | AP的id(8-id or 7-id) | 本次连接产生的流量，单位字节 | radio signal strength , 如果值为-1代表本条记录无此字段 | 开始连接时间 | 断开连接时间 |

