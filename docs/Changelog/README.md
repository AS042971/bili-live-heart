# 更新日志

## v1.2.0
2022-3-26  
- 修复了版本检测失败导致程序异常退出  
- 修复了老版本可能由于小心心分包导致死循环获取小心心的BUG   
- 修复了由于设置主播粉丝牌超过20级导致粉丝牌经验计算异常的BUG  
- 尽可能多的打卡更多的房间（房间打卡非常玄学，有的特殊房间打卡会异常）  
- 优化了小心心的赠送条件 不会给超过20级粉丝牌的主播赠送，以免造成浪费  
- 增加的脚本使用条件：**必须**关注A-SOUL**五人**B站账号，否则不允许使用

## v1.1.1  
2022-1-27
- 更新了文档，增加了Cookie获取工具

## v1.1.0  
2022-1-13
- 再次修复：无法打卡所有直播间问题 
- 将打卡时间间隔改为6秒
- 更新了文档  
- 获取完粉丝牌经验后改为原来的牌子  

## v1.0.1  
2022-1-13
- 修复：部分直播间跳过打卡的问题  
- 更新了文档，Cookie获取方式，更新云函数教程  
- 优化了Cookie的检验  

## v1.0.0
2022-1-11
- 全面更新，重构代码
- 新增：版本检测、Cookie检测
- 新增：友好的日志打印
- 新增：文档全面更新
- 新增：内置定时模块
- 新增：本地部署支持多用户
- 修复：概率一次获取不了全部24个小心心
- 修复：概率无法获取到粉丝牌信息

## v0.8.0
2022-1-2
- 新增：解除了云函数必须大于9个粉丝牌才能运行的限制
- 修复：B站接口更换导致小心心无法获取

## v0.1.0 -v0.7.0
2021-10-29 - 2021-12-7
- 摆~
