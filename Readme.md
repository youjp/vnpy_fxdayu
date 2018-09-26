# VNPY_FXDAYU

## 简介

    基于官方版VNPY修改的适用于Python 3 开发环境的开源量化交易程序开发框架，当前用于数字货币的策略研究和实盘交易。
    已经可以使用的数字货币交易所有 OKEX， 火币HUOBI，币安BINANCE，其他交易所功能陆续开通中。
    项目增加了多策略和多品种持仓、订单的存储和查询，优化回撤引擎，帮助用户更好地制定策略。
详细说明请查阅：[VNPY_FXDAYU说明文档](https://github.com/xingetouzi/vnpy_fxdayu/wiki)
## 项目安装（WINDOWS）：

    1、此版本VNPY基于python3.6开发，建议安装ANACONDA3_5.2.0以上版本
    2、安装MONGODB 4.0
    3、在下载项目的文件夹内找到install.bat，双击即可进入自动安装

## 项目使用方法：

    实盘：

    在下载的文件中，打开example文件夹，按照设置的说明填写配置文件，双击打开 “VNPY - 交易界面.bat” 这个文件，即可进行实盘。同时，我们为数字货币准备了专用的交易界面Crypto_Trader，同样在example文件夹内，双击打开 “VNPY - 数字货币.bat”这个文件，即可进行实盘。

    回测：

    1、在MongoDB存入历史数据，范例可在下载的文件内找到loadData文件夹，配置好数据库连接，即可导入提供的数据样本，时间跨度2018年1月1日到1月31日； 
    
    2、在example文件夹内，有两个和回测有关的配置文件，runBacktesting 是回测，runOptimization 是对回测进行优化。同样的，提供了运行的快捷方式，双击 “VNPY-回测” 可以进行回测，双击 “VNPY-并行优化” 可以得到优化结果

## 最新功能：

    2018/7/15
    增加多账户管理

    2018/7/9
    修复同时下多个订单只能撤掉一单的Bug
    发布 VNPY_FXDAYU 1.0 正式版

    2018/7/8
    增加订单信息保存到数据库功能

    2018/7/5
    增加分批加载数据和数据缓存功能

    2018/7/3
    策略模块新增基于策略的持仓信息计算和查询

    2018/7/1 发布
    发布基于数字货币期货功能开发的内测版本

    2018/6/30
    新增火币报价和账户查询

    2018/6/25
    新增VNPY多品种下单功能, 新增策略历史数据加载模块

    2018/6/20
    新增OKEX的期货查询和CTA策略 TICK / BAR下单功能

    2018/6/16
    实现CTP查询，CTA下单；新增OKEXgateway，实现OKEX现货的查询和CTA下单

    2018/6/13
    基于官方版VNPY，修改为Python 3 适用版本