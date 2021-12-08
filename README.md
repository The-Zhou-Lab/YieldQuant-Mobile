# 结合轻量级麦穗检测模型和离线Android软件开发的田间小麦测产

陈佳伟<sup>1,2</sup>, 谭巧行<sup>1</sup>, 桂世全<sup>1</sup>, 周济<sup>1,3※</sup>

<sup>1</sup>南京农业大学前沿交叉研究院/植物表型组学研究中心/江苏省现代作物生产省部共建协同创新中心，南京 210095;

<sup>2</sup> 南京农业大学工学院，南京 210095;

<sup>3</sup>英国剑桥作物研究中心/英国国立农业植物研究所，剑桥 CB3 0LE，英国

## 概述
在本次发布中，我们上传了最新版本的“YieldQuant-Mobile" (YQ-M)，这是一个基于MobileNet-YOLOV4、迁移学习、Android SDK和SQLite的安卓分析软件，可以离线识别手机拍摄的麦穗数量。YQ-M中预先嵌入了小麦产量构成要素的历史数据库，在离线识别出手机拍摄的麦穗数量后，可结合历史数据库在田间实现产量预测和结果输出等功能。YQ-M在田间试验中测试了80个代表性小麦品种（共240个1平方米小区），完成了这些品种的麦穗检测和小区测产，结果显示YQ-M的精确率、召回率、平均精确度和F1分数分别为84.33%，91.05%，91.96%和0.88。单位面积测产结果和实际产量的决定系数为0.839，案例研究表明YQ-M对麦穗识别精度高，在田间环境下测产结果和算法鲁棒性良好。此外，YQ-M开放了部署多种轻量级模型的端口，为实现多种作物产量预测、作物品类扩充和系统功能提升提供了开放式平台。因此，我们相信随着智能手机配置的不断提高，YQ-M可扩展至大部分小麦品种，为广大农业从业人员和科研人员提供在田间开展经济、便捷和可靠的产量量化分析的技术手段。


## 安装"YieldQuant-Mobile" (YQ-M)
如果您希望使用YQ-M，您需要下载YieldQuant-Mobile_v1.0.apk。

下载链接：https://github.com/The-Zhou-Lab/YieldQuant-Mobile/releases/latest
   
## 运行"YieldQuant-Mobile" (YQ-M)

在使用YQ-M之前，请参阅此存储库中的YieldQuant-Mobile用户指南.pdf文件。

## 知识产权声明
<b>YQ-M</b>软件由周济实验室（中）研发，该软件所有知识产权归南京农业大学周济实验室所有，中华人民共和国国家版权局已授予计算机软件著作权登记证书，登记号：2021SR1296887。<b>YQ-M</b>软件的任何副本可自由供科研使用，软件相关的一切所有权和知识产权均归周济实验室拥有，不得用于任何商业途径。商业用户不得对<b>YQ-M</b>软件进行反向工程，反向编译或反汇编，违者属于侵权行为，并自行承担有此引起的不利后果。科研工作者如需修改<b>YQ-M</b>软件，可联系周济实验室（中）对软件功能、性能、界面等进行必要的修改，但不得去除周济实验室（中）或南京农业大学的版本标示; 未经周济实验室（中）授权许可，不得向任何第三方提供修改后的软件。 　　

<b>凡有上述侵权行为的个人、法人或其它组织，必须立即停止侵权、并对侵权造成的一切不良后果承担全部责任。周济实验室（中）将依据《著作权法》、《计算机软件保护条例》等相关法律、法规追究其经济责任和法律责任。</b>

有意合作者可通过Email: chenjiawei@njau.edu.cn 与实验室取得联系。如选择使用本软件，即接受本协议所有条款。
