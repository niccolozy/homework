# 作业介绍

## 文件组成

主目录下包含四项：
- Source文件夹 - 作业程序源代码
- Car_maintenance.exe - 使用VS2015编译完成的作业程序
- test_case_1.txt - 官方测试用例1
- test_case_2.txt - 官方测试用例2

## 运行方法

将文本文档格式的测试用例与作业程序存放于相同路径，在命令行中以 Car_maintenance.exe + 测试txt文件名的形式运行。如：
```
Car_maintenance.exe test_case_1.txt
```

##源代码文件

###Car类

- 存储一辆车的基本信息：车牌号、购买日期、品牌、里程数、有无大修、保养状态。

###Maintenance_Checker类

- 存储读取的若干车辆信息
- 存储保养条件
- 从文本文件中读取车辆信息
- 检查车辆保养状态
- 向命令行按规定格式输出保养提醒信息
