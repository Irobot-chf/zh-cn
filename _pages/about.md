---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我目前在捷克布拉格的捷克理工大学（Czech Technical University in Prague）担任博士后研究员。我博士毕业于安徽合肥的中国科学技术大学科学岛研究生分院，导师是王晓杰研究员。本科毕业于陕西西安的西安电子科技大学机电工程学院。包括合著在内，我已经发表 10+ 篇学术论文
 <a href='https://scholar.google.com.hk/citations?user=IBlC5j4AAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。


我的研究领域包括：
- 生物医学图像与信号处理
- 电阻抗成像
- 触觉感知
- 人机交互
- 深度学习
- 逆问题
- 多模态传感器融合
- 3D 打印技术
  


<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2018.09 - 2024.06 (Expected)*, <a href="https://www.ustc.edu.cn/"><img class="svg" src="/images/ustc_logo.png" width="23pt"></a> 中国科学技术大学 合肥物质研究院, 安徽合肥, 硕博连读
- *2014.09 - 2018.06*, <a href="https://www.scu.edu.cn/"><img class="svg" src="/images/xidian_logo.png" width="20pt"></a> 西安电子科技大学 机电工程学院, 陕西西安, 本科
 
<span class='anchor' id='-lwzl'></span>


# 🔥 新闻
- 2026.04.07，受邀作为 Speaker 参加 RoboSoft 2026 Workshop —— "Electrical Impedance Tomography-Based Tactile Sensing: Bridging Soft Robotics and Artificial Touch"，日本金泽。[[Workshop主页]](https://sites.google.com/view/eit-robosoft-2026/home)
- 2026.01.22，拜访了代尔夫特理工大学（TU Delft）Robert Babuška 教授的实验室，重点围绕基于学习的控制与机器人研究进行交流学习。
- 2026.01.11-03.14，正在访问[埃因霍温理工大学](https://www.tue.nl/en/)，与 Hyosang Lee 合作开展基于电阻抗成像（EIT）的触觉传感研究。
- 2025.10.19–10.26，参加了 2025 年 IEEE/RSJ 智能机器人与系统国际会议（IROS 2025）。
- 2024.07.31，顺利抵达布拉格✈️。
- 2024.06.27，参加了第24届电阻抗断层扫描生物医学应用国际会议（EIT 2024）。
- 2024.06.11，参加了2024级研究生毕业典礼，并荣获安徽省优秀毕业生奖。[[报道1]](http://www.iim.cas.cn/xwzx_2021/jqyw/202406/t20240612_789131.html)
- 2024.05.24，通过了博士论文答辩🎉。
- 2024.05，陈皓枫参加2024年IEEE机器人与自动化国际会议，并做了线上口头报告。
- 2023.10，王晓杰、陈皓枫参加2023第十六届中国智能机器人大会(CCIR)。[[报道]](http://www.bihfcas.net/xw/23.10.27.html)[[相关报道1]](http://www.iamt.cas.cn/zxzx/gzdt/202311/t20231102_762488.html)[[相关报道2]](http://www.iim.cas.cn/xwzx_2021/dtjx/202311/t20231102_762496.html)
- 2022.12，陈皓枫、杨轩轩参加2022 IEEE ROBIO国际会议。[[报道]](http://www.bihfcas.net/xw/22.12.04.html)
- 2021.07，陈皓枫、马刚、杨轩轩获得"互联网+"创新创业大赛安徽省赛金奖、科学岛研究生创新创业大赛二等奖等荣誉。[[报道]](http://www.bihfcas.net/xw/21.07.13.html)
- 2019.12，陈皓枫、王鹏参加"中国科大校园算法邀请赛"并获得二等奖。[[报道]](http://www.bihfcas.net/xw/19.12.22.html)

  
# 📝 论文专利

### 英文
---
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2022</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Jian Tang`, Rongbiao Wang, Gongzhe Qiu, Yu Hu, Yihua Kang. Mechanism of magnetic flux leakage detection method based on the slotted ferromagnetic lift-off layer. *Sensors*, 2022, 22(9): 3587. (JCR:Q2; IF:3.847)  
[[网页]](https://dx.doi.org/10.3390/s22093587) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/TangJ-2022-Mechanism%20of%20Magnetic%20Flux%20Leakage%20Detection%20Method%20Based%20on%20the%20Slotted.pdf) [[下载]](/pdf/TangJ-2022-Mechanism%20of%20Magnetic%20Flux%20Leakage%20Detection%20Method%20Based%20on%20the%20Slotted.pdf)

</div>
</div>

- Bo Feng, Jianbo Wu, Hongming Tu, `Jian Tang`, Yihua Kang. A Review of Magnetic Flux Leakage Nondestructive Testing. *Materials*. 2022, 15 (20): 7362. (JCR:Q1; IF:3.748)  
[[网页]](https://dx.doi.org/10.3390/ma15207362) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/FengB-2022-A%20Review%20of%20Magnetic%20Flux%20Leakage%20Nondestructive%20Testing.pdf) [[下载]](/pdf/FengB-2022-A%20Review%20of%20Magnetic%20Flux%20Leakage%20Nondestructive%20Testing.pdf)
-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACS Appl. Electron. Mater. 2023</div><img src='images/TOC.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	H. Chen, X. Yang, J. Geng, G. Ma, and X. Wang, "A Skin-Like Hydrogel for Distributed Force Sensing Using an Electrical Impedance Tomography-Based Pseudo-Array Method," ACS Applied Electronic Materials, vol. 5, no. 3, pp. 1451-1460, 2023/03/28 2023. (JCR:Q2; IF:4.7)  
[[HTML]](https://pubs.acs.org/doi/10.1021/acsaelm.2c01394) [[Preview]](https://github.com/Irobot-chf/Irobot-chf.github.io/blob/main/pdf/2023-A%20Skin-Like%20Hydrogel%20for%20Distributed%20Forc.pdf) [[PDF]](/pdf/2023-A%20Skin-Like%20Hydrogel%20for%20Distributed%20Forc.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> IEEE ICRA 2024</div><img src='images/MMCNN.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	H. Chen, X. Yang, G. Ma, Y. Wang, and X. Wang, "Enhancing Tactile Sensing in Robotics: Dual-Modal Force and Shape Perception with EIT-based Sensors and MM-CNN," in 2024 IEEE International Conference on Robotics and Automation (ICRA), 2024: IEEE, pp. 3311-3317.   
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10610215)

</div>
</div>

- G. Ma, H. Chen, S. Dong, X. Wang, and S. Zhang, "PDCISTA-Net: Model-Driven Deep Learning Reconstruction Network for Electrical Impedance Tomography-Based Tactile Sensing," IEEE Transactions on Industrial Informatics, vol. 21, no. 1, pp. 633 - 642, 2024.
- X. Yang, Y. Zhang, H. Chen, G. Ma, and X. Wang, "A Physics-Embedded Dual-Learning Imaging Framework for Electrical Impedance Tomography," Neural Networks, vol. 197, no. 108464, p. 108464, 2025.
- H. Chen, Yang X, Ma G, et al. Correcting Non-Uniform Sensitivity in EIT Tactile Sensing via Jacobian Vector Approximation [J]. IEEE Robotics and Automation Letters, 2024, 9(3): 2335 - 2342.
- H. Chen, Yang X, Wang P, et al. A Large-Area Flexible Tactile Sensor for Multi-Touch and Force Detection Using Electrical Impedance Tomography [J]. IEEE Sensors Journal, 2022, 22(7): 7119-7129.
- H. Chen, Yang X, Geng J, et al. A Skin-Like Hydrogel for Distributed Force Sensing Using an Electrical Impedance Tomography-Based Pseudo-Array Method [J]. ACS Applied Electronic Materials, 2023, 5(3): 1451-1460.
- H. Chen, Ma G, Wang P, et al. A Bio-Impedance Analysis Method Based on Human Hand Anatomy for Hand Gesture Recognition [J]. IEEE Transactions on Instrumentation and Measurement, 2021, 70: 1-10.
- Ma G, H. Chen, Wang P, et al. Multi-Frame Constrained Block Sparse Bayesian Learning for Flexible Tactile Sensing Using Electrical Impedance Tomography [J]. IEEE Transactions on Computational Imaging, 2022, 8: 438-448.
- Ma G, H. Chen, Wang P, et al. A two-electrode frequency-scan system for gesture recognition [J]. Mechatronics, 2023, 94: 103039.
- Wang P, H. Chen, Ma G, et al. Deep learning scheme PSPNet for electrical impedance tomography [C]// Sensors and Smart Structures Technologies for Civil, Mechanical, and Aerospace Systems 2021. SPIE, 2021: 223-230.
- H. Chen, Yang X, Geng J, et al. A convolutional neural network-based electrical impedance tomography method for skin-like hydrogel sensing [C]// 2022 IEEE International Conference on Robotics and Biomimetics (ROBIO), 5-9 Dec. 2022. 2022: 178-183.
  
<!--
### 中文
---
-->


### 专利
---
*	王晓杰, 陈皓枫, 杨轩轩, 耿加露, 马刚. 一种基于电阻抗成像的一体化触觉传感器的检测方法 [P]. 专利号：ZL202210132777.8.（发明专利，已授权）
*	陈皓枫, 杨轩轩, 马刚, 王晓杰, 耿加露. 一种低成本且便携式的电阻抗成像电路 [P]. 专利号：ZL202222593360.X.（实用新型，已授权）
*	王晓杰, 王玉成, 马刚, 陈皓枫, 王鹏, 曹洪新, 赵娜娜. 一种融合生物电阻抗信息和肌电信息的手势识别系统 [P]. 专利号：ZL202010390176.8.（发明专利，已授权）
*	耿加露, 陈皓枫, 王晓杰, 杨轩轩. 一种高弹性水凝胶传感器及其制备方法 [P]. 专利号：ZL202111340087.3.（发明专利，已授权）
*	王晓杰, 陈皓枫, 杨轩轩, 马刚. 基于电阻抗成像的多模态柔性触觉传感器及触觉感知方法 [P]. 专利号：CN202311535146.1.（发明专利，实审）



<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- 2023年，中国科学院合肥物质院2023年度“悦群品学兼优奖学金”博士生一等奖[[报道]](https://www.hf.cas.cn/sbpy/yjsc/gsgk/pyxxgk/202312/t20231215_6943279.html) [名单](https://www.hf.cas.cn/sbpy/yjsc/gsgk/pyxxgk/202312/P020231215539828540094.pdf)
- 2023年，第十六届中国智能机器人大会[优秀论文](http://www.bihfcas.net/xw/23.10.27.html)
- 2021年，科学岛研究生双创中心首届研究生创新创业大赛二等奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/6科学岛创新奖.jpg)
- 2021年，第七届安徽省“互联网+”大学生创新创业大赛 安徽省高教主赛道金奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/2021互联网金.png)
- 2020年，第六届安徽省"互联网+"大学生创新创业大赛 安徽省高教主赛道银奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/4第六届互联网加安徽省银奖.jpg)
- 2019年，EMG-EIT 感知器结合 EIT 与肌电信号对手势进行识别，参加陆装举办的“超能勇士-2019” 单兵穿戴技术与外骨骼系统挑战赛（深圳赛区）获得优胜奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/3超能勇士1.jpg)
- 2019年，第七届“发现杯”全国大学生互联网软件设计大奖赛西部赛区二等奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/2发现杯二等奖.jpg)
- 2019年，中国科大校园算法邀请赛获得二等奖，第四名 [证书](https://irobot-chf.github.io/hfchen.github.io//images/1中科大算法大赛.jpg) [现场](https://irobot-chf.github.io/hfchen.github.io//images/微信图片_20240228191953.jpg)
- 2017年，第五届全国大学生工程训练综合能力竞赛（环形避障组）陕西赛，省级一等奖 [证明](https://irobot-chf.github.io/hfchen.github.io//images/工程训练获奖证明.pdf)
- _2015年_，陕西省第十次大学生高等数学（本科）竞赛，省级二等奖 [证书](https://irobot-chf.github.io/hfchen.github.io//images/高数竞赛.jpg)
- 2016年，TI杯陕西省西安五校联赛，校级二等奖




---
- 2022年，常州先进制造技术研究所2021年度秀研究生 [证书](https://irobot-chf.github.io/hfchen.github.io//images/2先进所优秀研究生.png)
- 2022年，安徽省研究生“创新创业之星”的荣誉称号 [证书](https://irobot-chf.github.io/hfchen.github.io//images/8 创新创业之星.jpg)
- 2018年，校优秀毕业生 [证书](https://irobot-chf.github.io/hfchen.github.io//images/优秀毕业生.jpg)
- 2016年，校优秀学生标兵 [证书](https://irobot-chf.github.io/hfchen.github.io//images/优秀学生标兵.jpg)



  
<!--
- *2015.11* 获得 第十四届“挑战杯”全国大学生课外学术科技作品竞赛 `一等奖`  
- *2015.06* 获得 第十三届“挑战杯”四川大学生课外学术科技作品竞赛 `一等奖` [[新闻]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
-->
<span class='anchor' id='-xshy'></span>

# 🏛️ 学术会议
- *2026.04*, RoboSoft 2026 Workshop — "Electrical Impedance Tomography-Based Tactile Sensing: Bridging Soft Robotics and Artificial Touch"，日本金泽，受邀报告。[[Workshop主页]](https://sites.google.com/view/eit-robosoft-2026/home)
- *2025.10*, 2025年IEEE/RSJ智能机器人与系统国际会议（IROS 2025），中国杭州。
- *2024.05*，2024年IEEE机器人与自动化国际会议，日本横滨 [报告截图]
- *2023.10*, 第十六届中国智能机器人大会, 上海, 口头报告 [参考](http://www.bihfcas.net/xw/23.10.27.html)
- *2022.12*, 2022年IEEE国际机器人与仿生学会议, 云南西双版纳, 口头报告 [参考](http://www.bihfcas.net/xw/22.12.04.html)


# 🏭 访问经历

- 访问研究员，荷兰埃因霍温，2026.01.11-03.14

在埃因霍温理工大学担任访问研究员，与 [Hyosang Lee](https://scholar.google.com/citations?user=_ZU4B9AAAAAJ&hl=zh-CN) 合作开展基于EIT的触觉传感研究，内容涵盖传感材料开发以及面向大面积柔性系统的触觉建模。

<!--
- *2021.10*, 全国电磁无损检测技术研讨会 暨 中国机械工程学会无损检测分会电磁专业技术大会第十一届第四次全体会议, 陕西西安, 受邀报告
- *2019.09*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 江苏南京, 海报
- *2017.10*, 第六届中国国际管道会议 (CIPC 2017), 河北廊坊
-->
<span class='anchor' id='-gzsx'></span>


<!--
# 💻 工作实习

- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉
-->

