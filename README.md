# 弹性网络预测模型的数据与代码

**基于议题类型的临近预测：使用社交媒体预测新冠确诊人数**

卢功靖, 卢林艳, 李媛媛, 王成军 

摘要: 在新冠肺炎疫情中，预测感染人数对于疫情防控至关重要。不同于其他传统媒体平台，社交媒体数据为预测新冠肺炎的新增人数提供了一个新的角度。传统利用关键词预测的方法存在局限性，如何利用中国社交媒体数据、摆脱关键词的限制更好地预测重大突发公共卫生事件的确诊人数？本文基于临近预测的理论框架，人工编码9000条微博文本，构建机器学习模型将1.9亿条社交媒体数据自动化分为九类，创新使用议题类型预测确诊人数，通过格兰杰因果检验进行验证。研究发现议题类型中科普信息、公益捐赠、寻人求助等是新增确诊人数的格兰杰原因。此外，本文构建的弹性网络算法准确度达到83%，实现了较为精准的预测，有助于我们更好应对潜在的突发公共卫生事件。	

关键词：新冠肺炎 机器学习 格兰杰因果检验 临近预测 弹性网络

**Nowcasting Based on Issue Categories: Predicting the Number of Confirmed Cases of COVID-19 Using Social Media**

Abstract: In the case of COVID-19, predicting the number of infections is crucial to prevention and control. Different from other traditional media platforms, social media data provides a new Angle for predicting the growth of COVID-19.Traditional methods of keyword prediction have limitations. How to use Chinese social media data to better predict the number of people diagnosed with public health emergencies without the limitation of keywords? Based on the theoretical framework of nowcasting, this paper manually encodes 9000 micro-blog texts, and builds a machine learning model based on which 190 million social media data are automatically divided into nine categories. This study innovatively used issue type to predict the number of diagnosed patients.The study found that among the issue types,Popular Science, Charitable Donations, and Contact Tracing & Seeking Help are Granger reasons for  the number of confirmed cases. In addition, the accuracy of the Elastic-Net algorithm constructed in this article has reached 83%. it is helpful for responding to potential public health emergencies.

Key words: COVID-19; Machine learning; Granger causality; Nowcasting; Elastic-Net

## Python代码

https://nbviewer.jupyter.org/github/socrateslab/cbjs/blob/master/elastic_net.ipynb

## 时间序列数据

https://github.com/socrateslab/cbjs/blob/master/%E6%97%B6%E9%97%B4%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE.xlsx?raw=true
