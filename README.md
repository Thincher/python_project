①显示地图方法 
-

1.cmd cd 进入到index和csv文件夹

2.利用Python给该文件夹开一个服务器 python -m http.server 8000 

3.服务器开启之后在浏览器中输入 localhost:8000，打开html，再导入rent.csv

②命名规则 
-

1.crawl_xx.py：某网站的爬虫代码

2.map.html: 地图网页，记事本打开可编辑

3.rent_xx.csv：爬虫得到某网站的数据，rent为合并后的数据

4.rent.ipynb：数据处理文件，jupyter打开

5.bak：备份文件
