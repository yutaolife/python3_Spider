# python3_Spider
学习python3也有一段时间了，最近通过学习用python3来写爬虫代码来练手，日后也会持续不断上传自己写的爬虫代码，希望大家可以相互学习
-----------------------

Learn Python3 also have a period of time, recently by learning to write Python3 code to practiced, the future will continue to upload their own code to write the crawler, I hope you can learn from each other



--------------
2018.1.26
上传了三个文件:spiderTest.py  /qsbkSpider.py(爬取嗅事百科热门) /bdtbSpider.py(爬取百度贴吧帖子内容)


-------------------
2018.1.29
上传新的项目iaskSpider.py(爬取爱问知识人)
解决：传入中文参数进url出现乱码问题；（url中是不允许出现中文字符的，这时候就改用urllib.parse.quote方法对中文字符进行转换。）
      优化正则表达式对内容的筛选

-------------------------
2018.1.30
上传新项目 movie250Spider.py(爬取豆瓣top250电影信息)
使用方法：requests,BeautifuSoap,codecs
注意：使用codecs 换行符'\n'会失效，需要用'\r\n'

上传项目：爬取豆瓣top250电影信息进阶，把数据保存到excel文件中
需要用到的模块 xlwt

--------------------------------
2018.1.31
上传新项目： 百度贴吧进阶版爬虫(bdtbSpider2.py) 爬取某个关键词贴吧首页所有帖子和内容

---------------------------------
2018.2.1
上传新项目：使用Scrapy爬取豆瓣新电影排行(douban_new_movie)
遇到的问题：豆瓣有反爬措施，需要伪装成浏览器，在settings.py中设置User_Agent

-----------------------------------
2018.2.2
上传新项目：使用urllib,urllib.request爬取豆瓣人物影集中的图片(douban_imageSpider.py)(单页)

-----------------------------------
2018.2.3
上传新项目:使用词云，结巴分词，BeautifulSoup,requests爬取豆瓣电影影评220条并形成词云wordCloudText.py(暂时无法突破豆瓣11页以后内容的封锁，后续会继续研究) 

--------------------------------------
2018.2.5
上传新项目：使用BeautifulSoup简单爬取知乎某问题下回答图片zhihuImageSimple.py(无法爬取JS加载的图片)

-------------------------------------------
2018.2.6
上传新项目：使用selenium+Firefox+python3 爬取知乎某问题下回答的图片zhihuImage.py(可以爬取JS动态加载出来的图片)

----------------------------------------------
2018.2.8
更新项目：zhihuImage.py  实现自动判断是否已经到达底部

-----------------------------------------------
2018.2.26
上传新项目：wangyiSpider.py 实现爬取网易云音乐某音乐下的评论

------------------------------------------------
2018.2.28
上传新项目：ipPool.py 实现构建简单自用IP池
更新项目：wangyiSpider.py 实现代理IP池爬取，爬取评论突破万条记录