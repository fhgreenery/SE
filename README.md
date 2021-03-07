# SE


搜索引擎工作原理主要包括爬取网页、建立索引、搜索词处理、搜索结果排序四部分。

1. 爬行和抓取网页：搜索引擎从已知的数据库出发，就像正常用户的浏览器一样访问这些网页并抓取文件。搜索引擎通过这些爬虫去爬互联网上的外链，从这个网站爬到另一个网站，去跟踪网页中的链接，访问更多的网页，这些新的网址会被存入数据库等待搜索。


2.建立索引：将爬虫抓取的页面文件分解、分析，并以巨大表格的形式存入数据库，这个过程即是索引。搜索引擎的核心数据结构为倒排文件（也称倒排索引）。


3.搜索词处理：用户在搜索引擎界面输入关键词，单击“搜索”按钮后，搜索引擎程序即对搜索词进行处理，如中文特有的分词处理，去除停止词，判断是否需要启动整合搜索，判断是否有拼写错误或错别字等情况。


4.排序：对搜索词处理后，搜索引擎程序便开始工作，从索引数据库中找出所有包含搜索词的网页，并且根据排名算法计算出哪些网页应该排在前面，然后按照一定格式返回到“搜索”页面并对搜索引擎加以优化。
