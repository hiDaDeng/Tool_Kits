# Tool_Kits_Of_Python
Python工具箱大全

涵盖：

1. 网络爬虫
2. 数据库
3. 数据分析
4. 机器学习
5. 可视化
6. 文本分析
7. GUI
8. 自动化办公


<br>

## 网络爬虫

- [requests](https://github.com/psf/requests)  最好用、最简单的网络爬虫访问库
- [weibo_crawler](https://github.com/thunderhit/weibo_crawler) 最简单的微博爬虫
- [TikTok-Api](https://github.com/davidteather/TikTok-Api) 抖音国际站爬虫库
- [celery](https://github.com/celery/celery/) 可以用于制作爬虫访问队列
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) 最简单的网页解析库
- [pyquery](https://github.com/gawel/pyquery)  最简洁网页解析库
- [scrapy](https://github.com/scrapy/scrapy) 最流行的爬虫框架
- [pyspider](https://github.com/binux/pyspider) 国人开发的爬虫框架
- [selenium](https://github.com/SeleniumHQ/selenium/) 浏览器自动化测试框架，可以用于爬虫反爬
- [playwright](https://github.com/microsoft/playwright) 微软开源的浏览器自动化测试框架
- [scylla](https://github.com/imWildCat/scylla) 智能IP代理池，用于反爬
- [shreport](https://github.com/thunderhit/shreport) 上海证券交易所上市公司定期报告下载
- [newspaper](https://github.com/codelucas/newspaper) 新闻爬虫库，根据提供的url可以抽取出新闻标题、作者、关键词、总结，部分功能支持中文

<br>

# Web

- [flask](https://github.com/pallets/flask) 可以开发网站、分享rest-api接口;流行度top2的web框架
- [streamlit](https://github.com/streamlit/streamlit)、[PyWebIO](https://github.com/wang0618/PyWebIO)对Python小白最友好的的web库
- [fastapi](https://github.com/tiangolo/fastapi)  web框架，高性能，易于学习，快速编写代码；
- [PyWebIO](https://github.com/wang0618/PyWebIO)  不需要编写HTML和JS代码，就可以构建简单的基于浏览器的GUI应用。 

<br>

## 数据库

- [PyMySQL](https://github.com/PyMySQL/PyMySQL)  
- [Sqlite3](https://docs.python.org/3/library/sqlite3.html)  轻量级sql数据库(python内置库)
- [pymongo](https://github.com/mongodb/mongo-python-driver) 非关系型MongoDB库
- [redis](https://github.com/redis/redis)  Redis数据库
- 
<br>


## 数据分析

- [pandas](https://github.com/pandas-dev/pandas) 必须Python数据分析库，读取文件、预处理数据、分析、存储
- [statsmodels](https://github.com/statsmodels/statsmodels) Python的统计计量统计库
- [linearmodels](https://github.com/bashtage/linearmodels) 添加线性模型，包括statsmodels中缺少的工具变量和面板数据模型。
- [streamlit](https://github.com/streamlit/streamlit) 快速搭建本地数据分析类Web应用
- [modin](https://github.com/modin-project/modin) pandas加速库，接口语法与pandas高度一致
- [dask](https://github.com/dask/dask)  pandas加速库，接口语法与pandas高度一致
- [plydata](https://github.com/has2k1/plydata])  pandas管道语法库
- [networkx](https://github.com/networkx/networkx) 社交网络分析库

    
<br>


      

## 机器学习

- [scikit-learn](https://github.com/scikit-learn/scikit-learn) 机器学习必学库，支持有监督、无监督多种算法，含文本分析功能
- [Orange3](https://github.com/biolab/orange3) 点击操作的机器学习分析**软件**， 可文本分析
- [doccano](https://github.com/doccano/doccano) 文本数据标注工具
- [label-studio](https://github.com/heartexlabs/label-studio)  最牛掰的文本数据标注工具





## 可视化

- [streamlit](https://github.com/streamlit/streamlit) 快速搭建本地数据分析类Web应用
- [matplotlib](https://github.com/matplotlib/matplotlib)  Python中最万能绘图库，很少有ta画不出来的图；但语法较难、静态图
- [seaborn](https://github.com/mwaskom/seaborn) 基于matplotlib开发的简化版可视化库， 一般的图可以用ta绘制； 高度定制仍需要结合matplotlib进行样式定制；静态图
- [plotnine](https://github.com/has2k1/plotnine)  ggplot2语法的Python可视化库， 可与[plydata](https://github.com/has2k1/plydata]) 库结合使用
- [pyecharts](https://github.com/pyecharts/pyecharts) 国人开发并封装的动态可视化图绘制库; 中文文档
- [plotly](https://github.com/plotly/plotly.py) 动态可视化图绘制库
- [bokeh](https://github.com/bokeh/bokeh) 动态可视化图绘制库
- [SciencePlots](https://github.com/garrettj403/SciencePlots)  科研论文绘图，基于matplotlib
- [datapane](https://github.com/datapane/datapane)  数据分析报告生成
- [superset](https://github.com/apache/superset) 开源商务智能分析可视化库

<br> 



## 文本分析

- [nltk](https://github.com/nltk/nltk) 自然语言分析套件，对中文不友好
- [spacy](https://github.com/explosion/spaCy) 工业级自然语言模型库，支持中文
- [jieba](https://github.com/fxsjy/jieba)  中文文本分词库
- [snownlp](https://github.com/isnowfy/snownlp) 中文情感分析库
- [gensim](https://github.com/RaRe-Technologies/gensim)  最好用、最全的话题模型
- [cnsenti](https://github.com/thunderhit/cnsenti) 中文情感分析库(Chinese Sentiment))可对文本进行**情绪分析**、**情感分析**。
- [multistop](https://github.com/thunderhit/multistop) 多语言文本停用词库
- [label-studio](https://github.com/heartexlabs/label-studio)  最牛掰的文本数据标注工具
- [doccano](https://github.com/doccano/doccano) 文本数据标注工具
- [textstat](https://github.com/shivam5992/textstat)  文本可读性计算包(算法全，但仅支持英文)
- [texthero](https://github.com/jbesomi/texthero) 文本预处理、展示、可视化库，仅支持英文
- [textpipe](https://github.com/textpipe/textpipe) 文本分析流水线
- [textplot](https://github.com/davidmcclure/textplot) 词语网络图
- [shifterator](https://github.com/ryanjgallagher/shifterator) 通过让您查看单词使用方式的变化，单词移位可以帮助您进行从根本上更可解释的情感，熵和散度分析。量化不同单词对两个文本差异做出的贡献，以及它们如何发挥作用。 
<br>





## GUI窗体软件开发

- [tkinter](https://wiki.python.org/moin/TkInter) Python内置的gui库
- [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) 最简单的gui开发库
- [pyqt5、pyside](https://doc.qt.io/qt.html#qtforpython) 最牛掰的gui软件开发库

 <br>



## 自动化办公

- [zmail](https://github.com/zhangyunhao116/zmail) 自动化收发邮件管理库
- [pywinauto](https://github.com/pywinauto/pywinauto) Windows电脑自动化Python库
- [WeasyPrint](https://github.com/Kozea/WeasyPrint)  自动化生产pdf报告
- [](https://github.com/jorisschellekens/ptext-release) 对PDF文件读取、更改、添加信息
- [selenium](https://github.com/SeleniumHQ/selenium/) 浏览器自动化框架，可以自动化点击浏览器，完成某些工作
- [mkdocx](https://github.com/mkdocs/mkdocs/) 
- [python-docx](https://github.com/python-openxml/python-docx)  创建、修改docx文件库
- [python-ppt](https://github.com/scanny/python-pptx)  创建、修改ppt文件库
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) xlsx文件库
- [PyWebIO](https://github.com/wang0618/PyWebIO)  不需要编写HTML和JS代码，就可以构建简单的基于浏览器的GUI应用。 
- 
<br>


## 其他
- [hiresearch](https://github.com/hiresearch/hiresearch.github.io) 丢弃繁杂收藏夹，定义简洁办公的浏览器首页
- [reveal.js](https://github.com/hakimel/reveal.js) 最流行的幻灯片
- [slidev](https://github.com/slidevjs/slidev) 编程人员使用的幻灯片
- [mkdocs](https://github.com/mkdocs/mkdocs) 制作文档网站


# 如果

如果您是经管人文社科专业背景，编程小白，面临海量文本数据采集和处理分析艰巨任务，个人建议学习[《python网络爬虫与文本数据分析》](https://ke.qq.com/course/482241?tuin=163164df)视频课。作为文科生，一样也是从两眼一抹黑开始，这门课程是用五年时间凝缩出来的。自认为讲的很通俗易懂o(*￣︶￣*)o，

- python入门
- 网络爬虫
- 数据读取
- 文本分析入门
- 机器学习与文本分析
- 文本分析在经管研究中的应用

感兴趣的童鞋不妨 戳一下[《python网络爬虫与文本数据分析》](https://ke.qq.com/course/482241?tuin=163164df)进来看看~
[![](img/课程.png)](https://ke.qq.com/course/482241?tuin=163164df)


# 更多

- [B站:大邓和他的python](https://space.bilibili.com/122592901/channel/detail?cid=66008)
- **公众号：大邓和他的python**
- [知乎专栏：数据科学家](https://zhuanlan.zhihu.com/dadeng)


<br>

![](img/大邓和他的Python.png)

    

      
