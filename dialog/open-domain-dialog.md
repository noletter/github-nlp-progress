## 闲聊类对话技术

### 1. DuConv
- <strong>数据集简介：</strong>

    DuConv是百度发布的基于知识图谱的主动聊天任务数据集，让机器根据构建的知识图谱进行主动聊天，使机器具备模拟人类用语言进行信息传递的能力。数据集的创新性是：强调了bot的主动性，并且在闲聊对话中引入了明确的对话目标，即将对话引导到特定实体上。数据中的知识信息来源于电影和娱乐人物领域有聊天价值的知识信息，如票房、导演、评价等，以三元组SPO的形式组织，对话目标中的话题为电影或娱乐人物实体。数据集中共有3万session，约12万轮对话，其中10万训练集，1万开发集，1万测试集。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | DuConv | 3万session <br> 约12万轮对话 | 2019年 | Wu et al. | 百度 | [链接](https://www.aclweb.org/anthology/P19-1369/) | [链接](https://ai.baidu.com/broad/download)| [2019 Language and Intelligence Challenge on Dialog](http://lic2019.ccf.org.cn/) |

- <strong>基于该数据集发表的相关论文：</strong>
    - Wenquan Wu, Zhen Guo, Xiangyang Zhou, Hua Wu, Xiyuan Zhang, Rongzhong Lian, and Haifeng Wang. 2019. Proactive human-machine conversation with explicit conversation goal. In ACL.


### 2. DuRecDial
- <strong>数据集简介：</strong>

    面向推荐的对话(Conversational Recommendation)是指集成对话系统和推荐系统的人机交互系统，该系统先通过问答或闲聊收集用户兴趣和偏好，然后主动给用户推荐其感兴趣的内容，比如餐厅、美食、电影、新闻等。真实世界的人机交互同时涉及到多种类型的对话，比如问答、闲聊、任务型对话等。当前业界一般把多种类型的对话分开研究，这其实不符合真实的人机交互。如何自然的融合多类型对话是一个重要的挑战，为了应对这个挑战，我们提出了一个新的任务—多类型对话中的面向推荐的对话，期望系统能够主动且自然地将对话从非推荐对话（比如『问答』）引导到推荐对话，然后基于收集到的用户兴趣及用户实时反馈通过多次交互完成最终的推荐目标。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | DuRecDial | 1万session <br> 16万句 | 2020年 | Liu et al. | 百度 | (待公开) | (待公开) | [2020 Language and Intelligence Challenge on Dialog](http://lic2020.cipsc.org.cn/) |

- <strong>基于该数据集发表的相关论文：</strong>
    - Zeming Liu, Haifeng Wang, Zheng-Yu Niu, Hua Wu, Wanxiang Che, Ting Liu. 2020. Towards Conversational Recommendation over Multi-Type Dialogs. In ACL.
    
    
### 3. 豆瓣多轮对话
- <strong>数据集简介：</strong>

    豆瓣多轮对话数据集是北航／微软联合发布的用于评估闲聊对话技术的标准数据集。数据主要来源是豆瓣社交网站上的聊天数据。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | 豆瓣多轮对话 | 100万session | 2017年 | Wu et al. | 北航／微软 | [链接](https://www.aclweb.org/anthology/P17-1046/) | [链接](https://github.com/MarkWuNLP/MultiTurnResponseSelection) | 无 |

- <strong>基于该数据集发表的相关论文：</strong>
    - Yu Wu, Wei Wu, Chen Xing, Ming Zhou, Zhoujun Li. 2017. Sequential Matching Network: A New Archtechture for Multi-turn Response Selection in Retrieval-based Chatbots. In ACL. 

### 4. 豆瓣知识对话
- <strong>数据集简介：</strong>

    豆瓣知识对话数据集是计算所／京东联合发布的用于评估知识对话技术的标准数据集。数据主要来源是豆瓣社交网站上的问答以及知识相关的聊天数据。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | 豆瓣知识对话 | 2万session | 2018年 | Liu et al.  | 计算所／京东 | [链接](https://www.aclweb.org/anthology/P17-1046/) | [链接](https://github.com/liushuman/neural-knowledge-diffusion) | 无 |

- <strong>基于该数据集发表的相关论文：</strong>
    - Shuman Liu, Hongshen Chen, Zhaochun Ren, Yang Feng, Qun Liu, Dawei Yin. 2018. Knowledge Diffusion for Neural Dialogue Generation. In ACL.
