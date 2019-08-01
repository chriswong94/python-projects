# 各城市地铁信息爬虫与分析

### 项目概述及目的

此项目致力于查看中国各城市的地铁分布与地铁站名字特点的情况

数据来源：高德地图  http://map.amap.com/subway/index.html?&1100

在此项目中,包括了数据的获取,解析,保存,评估,清洗,以及可视化.  

我们利用pyquery,json,requests库从高德地图网站上爬取数据并存入本地csv文件,

之后用python加载文件,查看,评估,清洗数据,

最后通过pyecharts对数据进行探索性分析与可视化.


### 文件描述

- crawler.ipynb : 数据的爬虫解析保存过程
- analysis.ipynb : 数据的评估，清洗，可视化过程 
- raw_data.csv : 通过爬虫抓取的原始数据
- README.md
- 各城市地铁信息爬虫与分析.pdf 
