---
permalink: /
title: "Yingying Zhu"
author_profile: true
show_page_title: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .lang-btn {
    background-color: transparent;
    color: #666;
    border: 2px solid #ddd;
    padding: 4px 16px;
    border-radius: 20px;
    cursor: pointer;
    font-family: inherit;
    font-size: 14px;
    font-weight: 600;
    transition: all 0.3s ease;
  }
  .lang-btn:hover {
    border-color: #24292e;
    color: #24292e;
  }
</style>

<div style="text-align: right; margin-bottom: 20px;">
  <button id="lang-toggle" class="lang-btn" onclick="toggleLanguage()">
    中
  </button>
</div>



<div id="en-content" style="display: block;" markdown="1">


💫About me
======
Welcome to **Yingying Zhu's Homepage**! 👋

I am a **First-Year Master's Student** at the School of Computer Science, **Beijing Institute of Technology (BIT)**, currently supervised by Dr. [Ren Qi](http://lab.malab.cn/~qiren/).

I completed my Bachelor's degree at the School of Information and Safety Engineering, **Zhongnan University of Economics and Law (ZUEL)**.

My primary research interests span:

* **Large Language Models (LLMs) & AI Agents**
* **Drug-Drug Synergism** (**DDS**)
* **Natural Language Processing** (**NLP**)
* **Computer Vision** (**CV**)

I am passionately focused on pushing the frontiers of Artificial Intelligence. I am always enthusiastic about exploring novel concepts and actively seeking opportunities for collaboration.

**Contact Me:**

📧 Feel free to reach out via email: [Julianne_M@163.com](mailto:Julianne_M@163.com)


 🗎  My resume can be found [here](/files/cv.pdf).


## 🎓 Education


- 09.2025~06.2028, M.Eng. in Computer Technology, Beijing Institute of Technology, Beijing
- 09.2021~06.2025, B.Eng. in Computer Science and Technology, Zhongnan University of Economics and Law, Wuhan





## 💼 Work Experience

### AI Conversation System Data Construction and Optimization
**Period:** May 2025 – Aug 2025 | **Role:** AI Training Data Engineer (Internship)

* **Key Achievement:** Led the design of training data incorporating **nested business loops** and **multi-turn dialogue state awareness**. Ranked **first** among an 11-person team with 9 high-quality data outputs, setting the team's benchmark.
* **Data Construction:** Independently built a **large-scale dataset with 958 dialogue nodes**, applying **Turn/FAQ/Step-aware labeling** and **Loop A-B metadata tags** to enhance the model's comprehension of complex logic.
* **Optimization:** Improved model generation quality and tool-calling accuracy by controlling data construction via **response ranking** and **Function-call methods**.
* **Migration & Prompt Engineering:** Spearheaded the data task migration and **Prompt Engineering** from Indonesian to English, ensuring accurate intent recognition in cross-lingual scenarios.



## 📝 Research Experience

### KanSynLM: Overcoming Spectral Bias in Drug Synergy Prediction via Wavelet KANs and Large Language Models
**Period:** Dec 2025 – Present | **Role:** Core Researcher

* **Core Challenge:** Addressed the "Spectral Bias" in traditional MLP-based drug synergy models and the severe prediction collapse caused by extreme class imbalance (<0.1% positive rate in a 700k dataset).
* **Algorithmic Innovation:** * **MultWaveletKAN:** Pioneered the use of multiplicative Mexican Hat wavelets to replace traditional MLPs. Leveraging the compact support property of wavelets to accurately capture high-order non-linear chemogenomic features.
    * **LLM Semantic Enhancement:** Shifted from traditional structural fingerprints (e.g., ECFP) to LLM-extracted deep functional semantics of drugs and cell lines, fusing them via Transformer cross-attention to enable true "Scaffold Hopping."
    * **Residual Bias Injection:** Reframed synergy prediction as a residual learning problem using Confounding Adjustment Bias (CAB), mathematically preventing minority-class collapse without complex loss weighting.
* **Results:** Achieved state-of-the-art performance on 6 major benchmark datasets (678,302 pairs). In extremely imbalanced tasks, F1-Score reached 0.43 and AUC-PR 0.40, outperforming current SOTA baselines (DeepDDS, MARSY) by up to 39%. Maintained a <5% performance drop in harsh zero-shot cold-start scenarios.

---


### MFVim: Enhanced Privacy-Preserving VIM-Based Medical Image Classifier
**Period:** Mar 2024 – Jul 2025 | **Role:** Co-First Author

* **Project Overview:** Developed a Vision Mamba variant model that integrates Federated Learning (FL) and Circular Knowledge Distillation (CKD), significantly enhancing privacy protection and improving the accuracy and efficiency of disease marker recognition for medical image classification.
* **Key Contributions:** Introduced a knowledge distillation execution threshold. Led dataset adjustments and standardization, simulating real institutional data distribution. Responsible for model fine-tuning, defining the comparative experiment framework, and developing evaluation metric algorithms. Wrote the methodology section of the research paper.
* **Results:** The MFVim model achieved superior performance compared to ViT and DeiT, demonstrating enhanced privacy protection and maintaining high original accuracy (96.4% on the PneumoniaMNIST dataset) while reducing computational complexity.

---

### Evolution of Literature Themes in Graduate Education Promoting Intergenerational Mobility (Weighted Heterogeneous Academic Network)
**Period:** Oct 2023 – May 2025 | **Role:** Core Member

* **Research Background:** Developed a more precise model to address the accuracy bottleneck in assessing the impact of graduate education on intergenerational mobility, overcoming the traditional analysis methods' neglect of literature attributes and time-series factors.
* **Research Task:** Constructed a theme evolution model based on a Weighted Heterogeneous Academic Network to quantitatively analyze global and local theme changes across at least five time windows, and accurately calculate the influence of academic entities (literature, authors, journals).
* **Implementation:** Collected 37,453 documents from WoS and CNKI. Used the GLDA model for global and local theme distribution analysis, the HR-PageRank algorithm for calculating academic influence, and Skip-Gram to map themes across different periods into the same semantic space for evolution path mining.
* **Results:** Constructed a heterogeneous academic network with hundreds of nodes and thousands of edges. Mined 15 global themes and over 40 local themes across 5 time periods, successfully revealing the thematic evolution trajectory.

---

### ICM: EcoGuardians: A Five-Year Comprehensive Plan to Combat Illegal Wildlife Trade
**Period:** Feb 2024

* **Task Overview:** Formulated effective solutions for key stakeholders through data analysis and model prediction, aiming for the long-term containment of illegal wildlife trade and the maintenance of global biodiversity.
* **Key Contributions:** Responsible for drafting the project overview and memorandum. Designed and drew the project workflow diagram. Used MICE and PCA for data cleaning and Delphi method to screen key indicators, constructing a new indicator system. Coordinated the final report revision.
* **Outcome:** The team's proposal received recognition from the judging panel, providing strategic recommendations for the United Nations Environment Programme.

---

### GitHub Real-Time Data Analysis and Visualization Bootcamp (Alibaba Cloud)
**Period:** Jul 2023 – Aug 2023

* **Project Background:** Utilized the GitHub Archive public dataset for data collection, analysis, and visualization to demonstrate real-time data trends and relevant metrics on GitHub.
* **Data Analysis:** Used DataWorks to ingest 160 million GitHub data records into Hologres for real-time synchronization and analysis. Wrote SQL queries to extract necessary metrics, such as Top 10 programming languages, starred project rankings, and active user/project counts.
* **Technical Implementation:** Used DataV built-in templates to set up a real-time visualization data dashboard, configuring data sources and charts to display multiple GitHub metrics.
* **Outcome:** Successfully deployed a multi-metric data dashboard and completed the skill certification for "Hot Topic Analysis based on MaxCompute."

---

### Housing Listing Profile Analysis (Alibaba Cloud)
**Period:** Jul 2023

* **Project Background:** Built a comprehensive profile analysis and provided statistical reports for a second-hand housing brokerage firm, integrating housing and listing data to support high-level decision-making, business operations, and data mining.
* **Data Integration:** Used DataWorks to load housing, listing, and dictionary data, generating 11 initial tables and performing data statistics. Achieved data synchronization using MaxCompute.
* **Report Display:** Generated statistical data and visual reports using Quick BI based on dimensions such as maintainer, entry person, urban district, and ring road information.
* **Outcome:** Output multi-dimensional statistical reports, demonstrated familiarity with the profiling construction methodology and process, and completed the skill certification for "Housing Listing Profile Analysis."

---

### Three-Dimensional Model Simplification Technology Based on Visual Saliency
**Period:** May 2023 – Jul 2023 | **Role:** Data Analysis and Model Prediction

* **Research Background:** Developed a method to determine the optimal observation viewpoint in a 6 Degrees of Freedom (6DoF) environment by integrating eye movement data classification, visual analysis, and saliency detection techniques.
* **Data Processing:** Collected eye movement data and read 6DoF data using an HMD device. Employed the I-VT algorithm for eye movement data classification.
* **Model Construction:** Selected the FPFH feature descriptor for point cloud description. Achieved point cloud dataset saliency detection and optimal observation viewpoint prediction by calculating the Euclidean distance between features and weighted saliency.
* **Outcome:** Successfully collected and analyzed eye movement data for 17 different types of 3D models. The project secured the first-place priority internal funding at the college level and was successfully concluded.






## 💻 Development Projects

### KanSynLM Agent Server: LLM & Wavelet KANs Driven Intelligent DDS System
**Period:** Early 2026 | **Role:** Full-Stack & AI Algorithm Developer

* **Project Overview:** Independently developed and deployed a vertical-domain AI Agent web service integrating high-concurrency prediction, intent recognition, and automated literature RAG to tackle the "combinatorial explosion" in anti-cancer drug screening.
* **Core Tech Stack:** PyTorch, LangGraph, LangChain, GLM-4 API, FastAPI, Uvicorn, Tavily.
* **Agentic Workflow:** Built a state machine utilizing **LangGraph**. The Agent autonomously extracts drug/cell-line features from natural language, calls the underlying KanSynLM model, and triggers dynamic **RAG** when high synergy scores (>0.8) are detected, translating mathematical outputs into biologically interpretable reports.
* **Engineering Optimization:** Implemented a `ModelBundle` global singleton pattern to keep massive PyTorch weights in memory/VRAM, avoiding Python asynchronous deadlocks and achieving millisecond-level inference response.
* **Dual-Modal Architecture:** Supports both traditional structured data processing (high-throughput CSV batch inference) and unstructured natural language interactions (Agent Chat).

---




### Online Education Platform
**Period:** Feb 2023 – Apr 2023 | **Role:** Personal Full-Stack Developer

* **Project Description:** Designed and developed a B2C commercial module using a microservices architecture and separate front-end/back-end development. The platform features course listing display on the homepage, detailed course viewing, payment processing, video playback, and utilizes WeChat for login and payment operations.
* **Back-end Features:** Implemented comprehensive back-end management including authority/permission control, course management, statistical analysis, and course categorization.
* **Technical Stack:** Vue, Nuxt, SpringBoot, SpringCloud, EasyExcel, JWT, OAuth2, Alibaba Cloud OSS (Object Storage Service), Video-on-Demand Service, and SMS Service.
* **Key Contributions:**
    * Designed the database schema and performed SQL query optimization.
    * Responsible for platform deployment and testing; deployed eight back-end JAR modules via Nacos and used Nginx for reverse proxy deployment of the Vue front-end project.

---

### Online Appointment System (Hospital)
**Period:** Nov 2022 – Jan 2023 | **Role:** Personal Full-Stack Developer

* **Project Description:** Designed and implemented an online registration and appointment system based on the MVC pattern, supporting three user roles: patient, doctor, and administrator.
* **Core Features:** Covers user registration/login, appointment management, department maintenance, email notifications, report export, and integration with Alipay Sandbox for online payment.
* **Technical Stack:** Servlet, JSP, JDBC, MyBatis, MySQL, JavaMail, Apache POI, and Alipay Sandbox Payment.
* **Project Highlights:**
    * Implemented identity verification using Session mechanisms.
    * Utilized MyBatis to optimize data operation and interaction efficiency.
    * Developed the front-end interface with CSS/JS to achieve dynamic interaction.


## 🎖 Honors and Awards

- **2024**
    * National Excellent Award, The 17th National College Students Information Security Competition Security Works
    * Provincial Silver Award, China College Students Innovation Competition
    * National Project Approval, College Students Innovation and Entrepreneurship Training Program Venture Group
    * Provincial Project Approval, College Students Innovation and Entrepreneurship Training Program Innovation Group
    * Provincial Silver Award, China College Students Computer Design Competition AI Practice
    * Software Copyright LawgiCian - Intelligent Contract Review Service Platform
    * Meritorious Winner Second Prize, Mathematical Contest In Modeling MCM

- **2023**
    * Top 100 in the Finals, SODA Open Data Innovation Application Competition
    * Successful Project Completion, The 36th "Bowen Cup" College Students Innovation Fund Project
    * Excellent Award, Baidu Songguo Qingying Class Internal Training Competition and Baidu Star Selection
    * Outstanding Student Cadre College Level, First-Class Scholarship, Outstanding Student

- **2022**
    * Outstanding Communist Youth League Member School Level

- **2021**
    * Excellent Trainee Military Training

## 🧩 Miscellaneous

### Skills

- **Programming/Tools:** Python, SQL, Tableau, Java, VScode, Jupyter, AutoDL, Xmind, etc.

### Certificates

- CET-6
- Alibaba Cloud ECS Certificate
- Certificate of Skills in House Listing-Based Profile Analysis
- UNICEF Aid Certificate

### Relevant Self-Study

- *Lean Analytics*
- *Python Machine Learning* (In-Depth and Simplified)
- *Sense of Participation*
- *Theory U: Leading from the Future as It Emerges*
- ...

</div>

<div id="zh-content" style="display: none;" markdown="1">

💫关于我
======
欢迎访问 **竺盈莹的个人主页**！👋

我是 **北京理工大学 (BIT)** 计算机学院的一名 **研一硕士生**，目前师从 [齐忍](http://lab.malab.cn/~qiren/) 博士。

我本科毕业于 **中南财经政法大学 (ZUEL)** 信息与安全工程学院。

我的主要研究兴趣包括：

* **大语言模型与智能体** (**LLMs & AI Agents**)
* **药物协同作用** (**DDS**)
* **自然语言处理** (**NLP**)
* **计算机视觉** (**CV**)

我热衷于推动人工智能的前沿发展。我总是充满热情地探索新概念，并积极寻找合作机会。

**联系我：**

📧 欢迎通过邮件联系我：[Julianne_M@163.com](mailto:Julianne_M@163.com)


 🗎  我的简历可以在[这里](/files/cv.pdf)查看。


## 🎓 教育背景


- 2025.09~2028.06，北京理工大学，计算机技术，工程硕士，北京
- 2021.09~2025.06，中南财经政法大学，计算机科学与技术，工学学士，武汉





## 💼 实习/工作经历

### AI对话系统数据构建与优化
**时间：** 2025年5月 – 2025年8月 | **角色：** AI训练数据工程师（实习）

* **关键成就：** 主导设计包含**嵌套业务循环**与**多轮对话状态感知**的训练数据。在11人团队中，以9条高质量数据产出排名**第一**，设定了团队基准。
* **数据构建：** 独立构建含**958个对话节点的大规模数据集**，应用**Turn/FAQ/Step感知标注**及**循环A-B元数据标记**，以增强模型对复杂逻辑的理解。
* **优化：** 通过**回复排序**与**Function-call控制**数据构建方法，提升了模型生成质量与工具调用准确率。
* **迁移与Prompt工程：** 主导数据任务从印尼语至英语的迁移与 **Prompt 工程**，确保在跨语言场景下的准确意图识别。



## 📝 科研经历

### KanSynLM: 基于小波 KANs 与大语言模型克服药物协同预测中的频谱偏置
**时间：** 2025年12月 – 至今 | **角色：** 核心研究员

* **核心痛点与挑战：** 现有的深度学习药物协同预测模型普遍采用 MLP 作为回归头，其固有的“频谱偏置（Spectral Bias）”导致模型无法拟合高频非线性特征。同时，在近 70 万样本的真实数据集中极端的类别不平衡（阳性<0.1%）导致传统模型发生预测坍塌。
* **算法创新：**
    * **MultWaveletKAN 预测头：** 首次在药物协同领域引入乘法墨西哥帽小波基函数替换传统 MLP。利用小波紧支撑特性，精准捕捉高阶化学基因组非线性特征，解决频谱偏置问题。
    * **LLM 语义增强：** 摒弃单一分子结构指纹，利用大语言模型提取药物和细胞系深层语义，通过 Transformer 交叉注意力机制进行特征融合，实现真正的“骨架跃迁（Scaffold Hopping）”。
    * **残差偏置注入：** 引入混杂因子调整偏置（CAB），将协同预测重构为残差学习问题，从数学底层避免少数类预测坍塌。
* **实验性能：** 在整合自 DrugComb 的 6 大基准数据集（超67万对样本）上进行验证。在极度不平衡分类任务中，KanSynLM 的 F1-Score 达 0.43，AUC-PR 达 0.40，较最强基准（DeepDDS等）提升高达 39%。在完全未见过的药物冷启动（Cold-Start）场景下，AUC-ROC 性能下降不足 5%，展现极强泛化能力。

---



### MFVim: 基于VIM的增强隐私保护医学图像分类器
**时间：** 2024年3月 – 2025年7月 | **角色：** 共一作者

* **项目概述：** 研发融合联邦学习（FL）和环形知识蒸馏（CKD）的 Vision Mamba 变体模型，显著增强隐私保护措施，提升医学图像分类任务中疾病标志识别的准确性和效率。
* **关键贡献：** 引入知识蒸馏执行阈值。主导数据集调整与标准化，模拟真实机构数据分布。负责模型微调，定义对比实验框架，并开发评价指标算法。撰写了研究论文的方法论章节。
* **结果：** 与 ViT 和 DeiT 相比，MFVim 模型表现出卓越性能，证明了其增强的隐私保护能力，并在降低计算复杂度的同时保持了高原始精度（在 PneumoniaMNIST 数据集上达到 96.4%）。

---

### 基于加权异构学术网络的研究生教育促进代际流动文献主题演化研究
**时间：** 2023年10月 – 2025年5月 | **角色：** 核心成员

* **研究背景：** 为解决评估研究生教育对代际流动影响时的准确性瓶颈，克服传统分析方法对文献属性和时间序列因素的忽视，开发了更精确的模型。
* **研究任务：** 构建基于加权异构学术网络的主题演化模型，定量分析至少五个时间窗口内的全局及局部主题变化，并准确计算学术实体（文献、作者、期刊）的影响力。
* **项目实施：** 收集了来自 WOS 和知网的 37,453 篇文献。采用 GLDA 模型分析全局及局部主题分布，使用 HR-PageRank 算法计算学术影响力，运用 Skip-Gram 将不同时期主题映射至同一语义空间以挖掘演化路径。
* **结果：** 构建了包含数百节点及数千边的异构学术网络。挖掘出5个时间段的15个全局主题和40多个局部主题，成功揭示了主题演化轨迹。

---

### ICM: EcoGuardians: 打击非法野生动物贸易的五年综合计划
**时间：** 2024年2月

* **任务概述：** 通过数据分析和模型预测为关键利益相关者制定有效解决方案，旨在长期遏制非法野生动物贸易并维护全球生物多样性。
* **关键贡献：** 负责撰写项目概述和备忘录。设计并绘制了项目工作流程图。使用 MICE 和 PCA 进行数据清洗，通过 Delphi 方法筛选关键指标，构建了新的指标体系。协调了最终报告的修订。
* **成果：** 团队的提案获得了评审团的认可，为联合国环境规划署提供了战略建议。

---

### 阿里云 Github 实时数据分析与可视化训练营
**时间：** 2023年7月 – 2023年8月

* **项目背景：** 利用 GitHub Archive 公开数据集进行数据采集、分析和可视化，以展示 GitHub 上的实时数据趋势和相关指标。
* **数据分析：** 使用 DataWorks 将 1.6 亿条 GitHub 数据导入 Hologres 进行实时同步和分析。编写 SQL 查询提取所需指标，如 Top 10 编程语言、高星项目排名以及活跃用户/项目数。
* **技术实现：** 使用 DataV 内置模板搭建实时可视化数据大屏，配置数据源和图表以显示多项 GitHub 指标。
* **成果：** 成功部署了多指标数据大屏，并完成了“基于 MaxCompute 的热门话题分析”技能认证。

---

### 阿里云 · 基于房源的画像分析
**时间：** 2023年7月

* **项目背景：** 为二手房经纪公司构建全面的画像分析并提供统计报表，整合房屋和房源数据以支持高层决策、业务运营和数据挖掘。
* **数据整合：** 使用 DataWorks 加载房屋、房源和字典数据，生成 11 张初始表并进行数据统计。使用 MaxCompute 实现数据同步。
* **报表展示：** 使用 Quick BI 基于维护人、录入人、城区和环线信息等维度生成统计数据和可视化报表。
* **成果：** 输出多维度的统计报表，展示了对画像构建方法和流程的熟练程度，并完成了“基于房源的画像分析”技能认证。

---

### 基于视觉显著性的三维模型简化技术
**时间：** 2023年5月 – 2023年7月 | **角色：** 数据分析与模型预测

* **研究背景：** 结合眼动数据分类、视觉分析和显著性检测技术，开发了一种在 6 自由度（6DoF）环境下确定最佳观察视角的方法。
* **数据处理：** 使用 HMD 设备收集眼动数据并读取 6DoF 数据。采用 I-VT 算法进行眼动数据分类。
* **模型构建：** 选择 FPFH 特征描述符进行点云描述。通过计算特征间的欧氏距离和加权显著性，实现了点云数据集的显著性检测和最佳观察视角预测。
* **成果：** 成功收集并分析了 17 种不同类型 3D 模型的眼动数据。该项目获得学院级第一顺位优先内部立项并成功结项。






## 💻 开发项目

### KanSynLM Agent Server: 基于大模型与 Wavelet KANs 的智能药物协同预测系统
**时间：** 2026年初 | **角色：** AI算法与全栈开发

* **项目定位：** 旨在解决抗癌药物联合疗法筛选中“组合爆炸”痛点。独立开发并部署集“高并发预测、智能意图识别、自动文献检索与分析”于一体的垂直领域 AI Agent Web 服务。
* **核心技术栈：** PyTorch, LangGraph, LangChain, 智谱 GLM-4 API, FastAPI, Tavily。
* **Agent 编排与 RAG：** 使用 **LangGraph** 状态机摒弃传统硬编码。Agent 具备自主“意图识别”能力，从自然语言提取特征并调用底层算法。当预测到高协同得分（>0.8）时，自主触发网络搜索工具（Tavily）进行动态 RAG，将冰冷的数学预测转化为具备生物学可解释性的专业分析报告。
* **系统架构与性能：** 实现双模态架构，支持高吞吐量 CSV 批量预测与非结构化自然语言 Agent 对话。通过 `ModelBundle` 全局单例模式将庞大的 PyTorch 权重驻留显存/内存，打破 Python 异步死锁陷阱，实现毫秒级推理响应。

---




### 在线教育平台
**时间：** 2023年2月 – 2023年4月 | **角色：** 个人全栈开发

* **项目描述：** 采用微服务架构和前后端分离开发，设计并开发了一个 B2C 商业模块。平台功能包括首页课程列表展示、详细课程查看、支付处理、视频播放，并利用微信进行登录和支付操作。
* **后端功能：** 实现了全面的后端管理，包括权限控制、课程管理、统计分析和课程分类。
* **技术栈：** Vue, Nuxt, SpringBoot, SpringCloud, EasyExcel, JWT, OAuth2, 阿里云 OSS（对象存储服务）, 视频点播, 短信服务。
* **关键贡献：**
    * 设计了数据库模式并进行了 SQL 查询优化。
    * 负责平台部署和测试；通过 Nacos 部署了八个后端 JAR 模块，并使用 Nginx 对 Vue 前端项目进行反向代理部署。

---

### 在线预约挂号系统（医院）
**时间：** 2022年11月 – 2023年1月 | **角色：** 个人全栈开发

* **项目描述：** 设计并实现了一个基于 MVC 模式的在线注册和预约系统，支持三类用户角色：患者、医生和管理员。
* **核心功能：** 涵盖用户注册/登录、预约管理、科室维护、邮件通知、报表导出，以及集成支付宝沙箱进行在线支付。
* **技术栈：** Servlet, JSP, JDBC, MyBatis, MySQL, JavaMail, Apache POI, 和支付宝沙箱支付。
* **项目亮点：**
    * 使用 Session 机制实现身份验证。
    * 利用 MyBatis 优化数据操作和交互效率。
    * 使用 CSS/JS 开发前端界面以实现动态交互。


## 🎖 荣誉与奖项

- **2024年**
    * 国家级优秀奖，第十七届全国大学生信息安全竞赛信息安全作品赛
    * 省级银奖，中国国际大学生创新大赛
    * 国家级立项，大学生创新创业训练计划创业组
    * 省级立项，大学生创新创业训练计划创新组
    * 省级银奖，中国大学生计算机设计大赛人工智能实践赛
    * 软件著作权：LawgiCian - 智能合同审查服务平台
    * 二等奖 (Meritorious Winner)，美国大学生数学建模竞赛 (MCM)

- **2023年**
    * 决赛全国百强，SODA 开放数据创新应用大赛
    * 成功结项，第36届“博文杯”大学生百项实证创新基金项目
    * 优秀奖，百度松果菁英班内训赛及百度之星选拔赛
    * 校级优秀学生干部，一等奖学金，优秀学生

- **2022年**
    * 校级优秀共青团员

- **2021年**
    * 军训优秀学员

## 🧩 其他

### 技能

- **编程/工具:** Python, SQL, Tableau, Java, VScode, Jupyter, AutoDL, Xmind 等。

### 证书

- 大学英语六级 (CET-6)
- 阿里云 ECS 证书
- 基于房源的画像分析技能证书
- 联合国儿童基金会援助证书

### 相关自学

- 《精益数据分析》
- 《深入浅出Python机器学习》
- 《参与感》
- 《U型理论》
- ...

</div>

<script>
  function toggleLanguage() {
    var en = document.getElementById("en-content");
    var zh = document.getElementById("zh-content");
    var btn = document.getElementById("lang-toggle");
    
    // 使用更稳健的逻辑：只要英文区没被隐藏，点击就切换到中文
    if (en.style.display !== "none") {
      en.style.display = "none";
      zh.style.display = "block";
      btn.innerHTML = "EN";  // 此时显示中文，按钮提示切换到 EN
    } else {
      en.style.display = "block";
      zh.style.display = "none";
      btn.innerHTML = "中";   // 此时显示英文，按钮提示切换到 中文
    }
  }
</script>
