---
# Display name
title: 杨坤

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: Kun
last_name: Yang

# Status emoji
status:
  icon: 

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: PhD Student

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: 北航可靠飞行控制研究组
    url: https://rfly.buaa.edu.cn/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: custom/mail
    url: 'mailto:yangkun_buaa@buaa.edu.cn'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/KennethYangle
  - icon: brands/weixin
    url: uploads/weixin.jpg
    label: 13263120776
  - icon: custom/bilibili
    url: https://space.bilibili.com/60684260

education:
  - area: 博士，导航、制导与控制
    institution: 北京航空航天大学
    date_start: 2021-09-01
    date_end: 2025-06-20
    summary: |
      博士论文题目: **视线角约束下的多旋翼无人机拦截控制研究**。
      俄乌、巴以冲突在实战中表明，无人机深刻影响战争形态。无人机“黑飞”威胁航空、石油、电力等公共安全事件频发。现有防御系统难以反制灵活自主的无人机，应用无人机拦截提供了一个解决方案。我们提出的捷联单目无人机方案具有精度高、价格低、小型化等优势。应对部署中遇到的挑战，<strong><font color=#fe7a03>本课题探讨如何设计拦截器构型，如何解决拦截中相机运动与多旋翼运动耦合，如何持续拦截目标，如何有效组织一群无人机应对多目标这几个关键问题。</font></strong>

    button:
      text: '查看研究内容PPT'
      url: uploads/PPT.pdf
  - area: 硕士，导航、制导与控制
    institution: 北京航空航天大学
    date_start: 2018-09-01
    date_end: 2021-06-20
    summary: |
      排名: 17/61

      - 毕业设计: 面向空中多目标的多旋翼自主拦截控制
      - 熟练掌握C/C++、Python、MATLAB、Linux和ROS机器人操作系统开发和使用
      - 获得国家奖学金、“无微不智2019”全国微型智能无人机挑战赛精准穿越项目智能策略奖、创新工场DEECAMP2019冬令营最佳技术奖、“如影随行”无人机空中精确对接技术挑战赛模拟对接比赛第二名
  - area: 本科，自动化
    institution: 华北电力大学
    date_start: 2014-09-01
    date_end: 2018-06-20
    summary: |
      排名: 10/120
      
      获得ACM/ICPC国际大学生程序设计大赛亚洲赛区青岛站铜牌、全国大学生数学建模竞赛北京赛区一等奖、美国大学生数学建模竞赛M奖（一等奖）、大学生创新创业训练计划项目国家级优秀、北京市大学生电子设计竞赛三等奖

work:
  - position: 基于图像视觉伺服的多旋翼无人机高速拦截
    company_name: 研究课题
    company_url: ''
    company_logo: ''
    date_start: 2021-06-01
    date_end: 2023-06-01
    summary: |
      无人机威胁公共安全事件频发。对于完全自主的无人机的入侵，传统的方法如射频干扰和GPS屏蔽可能会失效。本研究提出一种方案，使用捷联单目相机的自主多旋翼无人机来拦截入侵目标。创新点包括：
      - 提出基于图像的视觉伺服（IBVS）高速拦截方案，解决了相机固定安装在机身上时飞机运动与特征点成像之间的耦合难题。确保了在高速和大机动拦截控制过程中，目标始终在摄像机的视野范围内。
      - 提出一种延迟滤波（DKF）方案，解决相机成像过程中的延迟、帧率低的问题。
      - 实验验证了算法的有效性。我们的自主多旋翼在机载处理下，以超过 20m/s 的速度高速飞行拦截目标，最大俯仰角达到 50°。

      {{< bilibili BV1gh4y187xK >}}
  - position: 多旋翼无人机持续拦截控制
    company_name: 研究课题
    company_url: ''
    company_logo: ''
    date_start: 2023-07-01
    date_end: 2023-10-01
    summary: |
      如何让自主无人机像人类飞手一样，在拦截失败后还能主动发起后续拦截，对目标紧追不舍？本研究提出了一种增强型自主无人机拦截方法，利用球面成像模型和基于图像的视觉伺服（IBVS）技术，提高拦截综合成功率。创新点包括：
      -	在蒙特卡洛定位（MCL）框架内引入持续拦截策略，根据观测信息与估计状态的一致性生成目标概率分布，从而有效解决测量数据缺失的问题；
      -	开发适用于首次和持续拦截阶段的基于视觉伺服的统一控制方法；
      -	实验验证了算法的有效性。显著提高拦截成功率。

      {{< bilibili BV1Bc411t7NY >}}
  - position: 多旋翼飞行器集群拦截/对抗
    company_name: 研究课题
    company_url: ''
    company_logo: ''
    date_start: 2023-11-01
    date_end: ''
    summary: |
      将单机拦截扩展至集群对抗领域。涉及到多视角目标估计、弱通信条件下集群任务分配问题。创新点包括：
      -	提出基于图博弈的集群任务分配方法，弱通信条件下通过主动观测完成自主决策；
      -	提出群视角多目标估计方法，利用多旋翼集群的对极几何和动力学特性提高目标定位精度；
      -	实验验证了算法的有效性。仅使用主动视觉和机载计算实现了蜂群合作拦截。

      {{< bilibili BV1gE421w722 >}}
  - position: JZ环境下无人机集群协同技术
    company_name: JKW
    company_url: ''
    company_logo: ''
    date_start: 2022-10-01
    date_end: 2023-10-01
    summary: |
      负责固定翼无人机红外制导打击算法研究及仿真验证，用于**巡飞弹图像末制导**阶段控制。建立固定翼无人机微分平坦模型，适用于大机动敏捷飞行制导控制。
  - position: 室内集群协同打击控制技术
    company_name: JKW
    company_url: ''
    company_logo: ''
    date_start: 2020-12-01
    date_end: 2022-09-01
    summary: |
      负责室内自主无人机集群软件架构开发，无人机集群控制算法和基于图像伺服的无人机自主打击技术研究。
      - 构建全套软件系统框架，北航团队负责集群飞行控制，联合上海交大和南开团队完成感知和决策形成闭环；
      - 应用[虚拟管道](https://journals.sagepub.com/doi/abs/10.1177/02783649231210012?journalCode=ijra)理论构建集群打击走廊，实现在室内环境集群快速搜索打击；
      - sim2real快速迭代，应用机载处理器和飞控进行硬件在环仿真，相同代码快速部署飞行实验；
      - **实现国内领先的室内10机自主无人机协同搜索打击任务**。
  - position: RflySim基于模型设计半物理仿真平台开发（教育类产品）
    company_name: JKW & 北京卓翼智能科技有限公司
    company_url: 'https://rflysim.com/doc/zh/'
    date_start: 2019-03-01
    date_end: ''
    summary: |
      基于模型—软件在环仿真—硬件在环仿真—实飞实验顺序，构建高逼真的无人机全流程开发平台[RflySim (https://rflysim.com/)](https://rflysim.com/doc/zh/)。
      - 从UE4引擎获取渲染图像；设计Python和C++接口，实现环境交互和控制指令与飞机通信；
      - 服务于实验室项目开发，已推广至全国多所高校和科研院所。
  - position: 交通违章检测研发（实习）
    company_name: 北京旷视科技有限公司
    company_url: 'https://www.megvii.com/'
    date_start: 2019-10-01
    date_end: 2019-12-01
    summary: |
      重构交通违章检测pipeline为并行模块化结构，包括行人、车辆、环境检测，3D框，reID，质量评价，目标跟踪，违章判断等模块。模块间数据以batch流动，业务速度提升一倍，可扩展性强；端到端的确定系统准确率和召回率，同时细化到每一模块效果，可视化评价结果，完善违章检测逻辑。


# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: “智能争锋-2023”无人机集群反制技术挑战赛定点打击中获得第一名，协同围捕和针锋相对中获得第二名，队长
    date: '2023-06-18'
    awarder: 中国电科智能院

  - title: “智在飞翔-2021”无人飞行器智能感知技术竞赛仿真赛废墟赛道一等奖和公园赛道三等奖，线下实飞赛第二名，队长
    url: https://www.robomaster.com/zh-CN/robo/drone?djifrom=nav_drone
    date: '2021-10-30'
    awarder: DJI RoboMaster
    summary: |
      {{< bilibili BV1NV411X7ym >}}
  - title: “如影随行”无人机空中精确对接技术挑战赛模拟对接比赛第二名，队长
    url: https://news.buaa.edu.cn/info/1005/52970.htm
    date: '2020-10-15'
    awarder: 中国航天科工集团
    summary: |
      {{< bilibili BV1B4421Z7Ax >}}
  - title: 国家奖学金
    date: '2020-12-31'
    awarder: 中华人民共和国教育部
  - title: ACM/ICPC国际大学生程序设计大赛亚洲赛区青岛站铜牌
    url: https://icpc.global/
    date: '2016-11-30'
    awarder: ACM

  
---

本人目前在北航全权老师课题组攻读博士研究生，导师为全权、白成刚教授。研究方向：<strong><font color=#fe7a03>无人机自主拦截/打击，集群对抗，自主无人系统，视觉导航</font></strong>。目前已发表SCI论文3篇，其中一作2篇，已发表EI论文2篇，其中一作1篇，另有3篇一作SCI论文审稿中，已授权专利6项。获2020年“如影随行”无人机空中精确对接技术挑战赛模拟对接比赛第二名, “智在飞翔”2021 • 无人飞行器智能感知技术竞赛线上仿真赛废墟赛道一等奖和公园赛道三等奖，线下实飞赛第二名，“智能争锋-2023”无人机集群反制技术挑战赛定点打击中获得第一名（皆为队长）。本人在实验室深入参与多项重点项目，多次经历从项目论证、设计、实施、验收的完整过程，对科研项目有较深刻的理解，有技术攻关和带领团队的丰富经验。