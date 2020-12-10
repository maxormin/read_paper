## 论文阅读笔记
-----------
### 1.基于LightGBM算法的P2P项目信用评级模型的设计及应用
---------------
* 摘要：
> 研究目标-在xx背景下，通过xx以达到xx目的<br>
> 研究方法-基于xx数据，采用xx方法对xx进行预测并对不同方法的结果进行比较<br>
> 研究发现-我的方法最好，相较于xx提升了xx个百分点<br>
> 研究价值-在我的方法的基础上，可以帮助xx得到发展（改善）<br>

关键词: P2P，信用评级，违约率控制，数据清洗，LightGBM算法

* 问题的提出<br>
(时代背景及xx方向对于发展的意义)：伴随着互联网技术的发展。。。。做好信用评级相关工作，则是保证互联网金融健康发展的关键一环<br>
(方向的含义)：P2P是以“普惠”为核心思想的互联金融的典型代表, 它利用网络实现了投资者和借款人的直接对接, 并使双方都获得收益。<br>
(过去的人在该方向上的操作)：Robert和Benjamin (2010) 发现利用综合的信用系统根据借款人的个人名誉、信用评分等个人信息, 可以筛选出高质量的借款人。Iyer等 (2016) 研究发现, P2P借贷市场中的出借人具有很强的信用甄别能力。<br>
(~~过去的操作不再适用~~，大人，时代变了:smirk:	)：但P2P行业的快速发展, 也伴随着层出不穷的问题严重阻碍其发展。<br>
(存在问题的原因)：P2P网络平台存在本地偏好 (Lin和Viswanathan, 2016) 和羊群效应 (Herzenstein等, 2011) 。徐硕正 (2016) 称P2P行业虽已声名鹊起, 却是毁誉参半, 誉者赞其曰“金融创新”“普惠金融”, 毁者斥之“非法集资”“庞氏骗局”。<br>
(导致的后果)：发展至今, 我国P2P网贷行业出现了大规模平台跑路、倒闭潮的情况, 为投资者带来了巨大的损失, 违约率远高于国外P2P平台的违约率, <br>
(xx方向对于问题的意义)：而风险管理控制是降低违约率的关键所在, 也是P2P行业发展的核心。<br>
