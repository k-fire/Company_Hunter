根据IP/Domain批量提取资产归属单位及位置
数据来源：Hunter
```
批量提取资产归属单位及位置

Usage: company_hunter -f <FILENAME> -a <API_KEY>

Options:
  -f <FILENAME>      导入的资产清单
  -a <API_KEY>       Hunter API-KEY
  -h, --help         Print help information
  -V, --version      Print version information
```

获取奇安信Hunter API-Key：https://hunter.qianxin.com/home/userInfo

传入文件格式（IP/Domain一行一个）：
```
60.220.246.29
223.240.85.45
220.168.55.212
175.6.7.16
218.56.105.173
124.251.118.35
58.58.48.75
175.173.176.15
119.48.74.243
```
运行截图：
![运行截图](https://raw.githubusercontent.com/k-fire/Company_Hunter/main/main.png)

