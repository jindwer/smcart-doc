# 数据库设计 集合说明

## 汽车信息说明

### carinfo

| 中文名称 | 英文 | 类型 | 说明 | 备注 |
|---------|------|------|------|-----|
| 工单号   | id |  String |  |  |
| 车牌号 | carnum | String |  |  |
| 车主姓名 | name | String |   |   |
| 车主电话 | phone| String  | |  | 
| 车主公司 | company | String |  |  |
| 车主地址 | address | String |  |  |
| 保险公司 | baoxian | String |  |  |
| 车名     | carname | String |  |  |
| 车类型   | cartype | String |  |  |
| 车着色   | carcolor | String|  |  |
| sa姓名   | saname | String |   |  |
| 输入时间 | nowtime | String | 登记时间 |  |
| 交车时间 | ftime  |  Date | 预计交车时间 |  |
| 实交车时间 | realtime | date | 实际的交车时间 |  |
| 钣金工序 | bjgx | string | 钣金工序 | 是否完成工序 |
| 钣金工序时间 | bjgx-start | string | 钣金工序开始时间 |  |
| 钣金工序时间 | bjgx-end | string | 钣金工序结束时间 |  |
| 钣金工序时间 | bjgx-about | string | 钣金工序预计花费的时间 | 这个工序大约需要2小时间 |
| 钣金工序时间 | bjgx-will | string | 钣金工序预计时间 |  |
| 钣金工序时间 | bjgx-about | string | 钣金工序预计花费的时间 | 这个工序大约需要2小时间 |





## 工人信息

### userinfo

| 中文名称 | 英文 | 类型 | 说明 | 备注 |
|---------|------|------|------|-----|
| 姓名    | name  | string |  |   |
| 密码    | passwd | string | MD5加密 |  |
| 工种    | worktype | string | 一个人可以全多个工序 |   |
