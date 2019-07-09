# Python调用高德地图,玩转北京

### 项目概述及目的

为了查看并大致了解北京地区休闲娱乐项目的分布,本项目调用了高德地图的API来获取数据.  

在此项目中,包括了数据的获取,解析,保存,利用pyecharts与folium库所实现的数据可视化.  


### 软件的安装

- pandas
- requests
- json
- pyecharts
- folium
- csv

### 文件描述

- POI获取.ipynb : 数据的下载解析保存过程
- POI解析.ipynb : 数据的可视化过程 
- data/crawler_output.csv : 通过高德地图API加载获得并保存的数据文件	
- visualization/outputs.html : 通过pyechart进行的数据可视化，北京地区休闲活动类别排行结果
- README.md

