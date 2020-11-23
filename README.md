# HEU_Timetable_in_Xiaoai
Last Update :2020.10.4.17:30
## 更新日志
2020-11-23 修复了issue3对应的问题，现在导入无课程地点的项目不会再卡死了。

2020-10-04 上传第一代版本，同步在小米审核。

2020-10-03 在本地编辑、调试代码。（此部分代码没有上传）

## bug & TODO

**BUG**

请在issue中反馈，我会尽快阅读（我可能无法修复，还望大佬指正）。

-----

**TODO**

精简代码，用注释的方式说明每一行的作用，方便以后修改和bug修复。

~~不使用id寻找、判定数据。~~(已处理 #1)

不使用非数字判断课程名，而是直接获取。

## 概述
此脚本作为*小爱同学课程表*适配教务系统的一部分，用于*小爱课程表*截取哈尔滨工程大学教务系统数据后的拆分、转换工作，产生的数据用于小爱课程表导入课表数据。

由于上传的代码只是一个（组）用于解析课表的函数，此脚本不能直接运行。如果需要，请待审核通过后于**小爱课程表导入课表**。

因为本人的技术不高、完全是小白，这里展示的代码有较多的冗余，但也希望这能作为适配其他学校教务系统的参考。

## 导入说明
0. 审核和内测期间你可能无法导入课表；
1. iOS下载小爱课程表，非小米手机需要下载小爱课程表（app），小米手机叫出小爱同学，说“打开课程表”;
2. 请在右下角->设置->选择学校为“哈尔滨工程大学-强智教务学期理论课表”，然后点击“教务网站导入-[导入]”;
3. 在校园网环境下输入账号、密码，点击“课表查询”，点击右下角“一键导入”；
4. 如果未能打开教务系统，显示“正在跳转统一身份验证平台”或英文，请退出（按下返回键），然后重新导入；
5. 如果仍然不能导入，请在issue中提供反馈，建议你的反馈包括问题发生截图（或截图链接）、问题发生之前的操作。



## 参考资料&感谢
> 以下资料对这个脚本的诞生至关重要，在此表示感谢

SZTU深圳技术大学教务系统小爱课程表导入——强智科技13369 （作者：源心锁  ）
https://blog.csdn.net/qq_38331169/article/details/108500577?utm_source=app

官方说明文档
https://ldtu0m3md0.feishu.cn/docs/doccnhZPl8KnswEthRXUz8ivnhb#line-41

cheerio说明文档（官方）
https://cheerio.js.org/

cheerio说明文档（中文翻译）
https://www.jianshu.com/p/629a81b4e013


