# 猫眼电影爬虫与分析

### 项目概述及目的

此项目致力于查看猫眼电影TOP100榜单上的电影的分布.
https://maoyan.com/board/4

在此项目中,包括了数据的获取,解析,保存,评估,清洗,利用matplotlib库所实现数据可视化.  

我们利用pyquery与requests库从猫眼网站上爬取数据存入本地csv文件,

之后用python加载文件,查看,评估,清洗数据,

最后通过matplotlib对数据进行探索性分析与可视化.

### 软件的安装

- pandas
- requests
- matplotlib
- collections
- pyquery
- csv

### 文件描述

- crawler.ipynb : 数据的爬虫解析保存过程
- wrangling & visualization..ipynb : 数据的评估，清洗，可视化过程 
- raw_data.csv : 通过爬虫从猫眼网站上抓取的原始电影数据
- data.csv : 经过评估，清洗后的数据
- README.md

