# 大创项目

## 中医药知识图谱的构建

**目前进度**：

~~1.利用Python的scrapy框架对网络上的公开药材网进行药材爬取~~

2.通过利用pandas库对数据清洗等初步处理后以实现基本实体及实体关系的确认，可实现将现有数据导入neo4j数据库形成基本的图谱

**接下来目标：**

1.利用TensorFlow建立训练模型对【来源】，【用法用量】，【主治功能】，【性味】等存在大段文字的实体进行进一步的抽取，争取做到抽出准确词语。

2.利用远程监督的方式（或者是其他的方式），对实体关系进行抽取，目前要使用的技术工具还未知。

