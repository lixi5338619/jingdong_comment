# jingdong_comment
jingdong_store -meidi- comment

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190414193323105.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)

 - 针对京东商城20W条美的热水器评论数据进行统计清洗分析。
 -  分析出所有正面评论和负面评论。 
 - 分词统计热词出现频率。 
 - 分析出销售问题所在。
 
 本项目的文本情感分析使用的是基于情感字典的文本情感分析。
为了能够正确标注一段中文文本的情感。需要如下几个情感字典：
①停用词字典：用于过滤掉一段文本中的噪声词组。
②情感词字典：用于得到一段文本中带有情感色彩的词组及其评分。
③程度副词字典：代表情感词的强烈程度，相当于情感词的权重。
④否定词字典：用于判断其后情感词的意思究竟是好（正极性）还是坏（负极性），若情感词前有否定词，则情感得分-1。
情感字典以及评分通常由手工标注完成，而标注是一项费时又费力的活，因此这四个字典都是由网络搜集而来。
![在这里插入图片描述](https://img-blog.csdnimg.cn/2019041419335078.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190414193549260.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190414193704457.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)
