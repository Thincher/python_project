①显示地图方法
-
>cmd cd 进入到index和csv文件夹
>利用Python给该文件夹开一个服务器 python -m http.server 8000 
>服务器开启之后在浏览器中输入 localhost:8000，打开html，再导入rent.csv

②命名规则
-
>crawl_xx.py：某网站的爬虫代码
>map.html: 地图网页，记事本打开可编辑
>rent_xx.csv：爬虫得到某网站的数据，rent为合并后的数据
>rent.ipynb：数据处理文件，jupyter打开
>bak：备份文件
