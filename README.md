全国行政区划代码
================
项目代号：Crius
提供全国行政区化代码的CSV文件
开源文档，欢迎修订、贡献和资助
项目介绍包括以下几个内容：
+ 内容介绍
+ 使用方式
+ 如何贡献
+ 项目周期
+ 一元资助 


内容介绍
--------
最新一次更新：2017-03-29 18:38:26
共收入：64,5308 条记录
CSV文本放置在:./resource/~
31个文件，命名看起来像这样：
```
	11-北京市-行政区划代码.csv
	12-天津市-行政区划代码.csv
	13-河北省-行政区划代码.csv
	14-山西省-行政区划代码.csv
	15-内蒙古自治区-行政区划代码.csv
	...
```

文件数据，看起来像这样：
```
	"province_id","city_id","country_id","town_id","village_id","province","city","country","town","village"
	"11","01","01","001","001","北京市","市辖区","东城区","东华门街道办事处","多福巷社区"
	"11","01","01","001","002","北京市","市辖区","东城区","东华门街道办事处","银闸社区"
	"11","01","01","001","005","北京市","市辖区","东城区","东华门街道办事处","东厂社区"
	...
```
或像这样：

```
	...
	"35","01","11","202","201","福建省","福州市","晋安区","日溪乡","日溪村"
	"35","01","11","202","202","福建省","福州市","晋安区","日溪乡","梓山村"
	"35","01","11","202","203","福建省","福州市","晋安区","日溪乡","山秀园村"
	"35","01","11","202","204","福建省","福州市","晋安区","日溪乡","东坪村"
	"35","01","11","202","205","福建省","福州市","晋安区","日溪乡","南峰村"
	"35","01","11","202","206","福建省","福州市","晋安区","日溪乡","党洋村"
	...
	
```
新疆地区还未更新


使用方式
--------
建议使用Windows的Office excel打开编辑、修改和筛选,并保存。
要程序读取，原数据编码为ANSI，可根据需要转码。

如何贡献
--------
如果您发现数据错误，请先创建一个分支，然后修改提交并申请合并

项目周期
--------
长期项目，数据来源于国家统计局：http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/
使用程序固定抓取数据，然后比对本库进行后更新
每年三月份刷新一次

一元资助
--------
数据是完全免费！
如果这数据能帮助您，您可以帮忙修改、维护；
如果您很忙，也可以提供一元资助，链接如下：

