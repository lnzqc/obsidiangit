# A novel echo state network and its application in temperature prediction of exhaust gas from hot blast stove
> [!info]+ <center>Metadata</center>
> 
> |<div style="width: 5em">Key</div>|Value|
> |--:|:--|
> |文献类型|journalArticle|
> |标题|A novel echo state network and its application in temperature prediction of exhaust gas from hot blast stove|
> |短标题||
> |作者|[[Yinghua Yang]]、 [[Xin Zhao]]、 [[Xiaozhi Liu]]|
> |期刊名称|[[IEEE Transactions on Instrumentation and Measurement]]|
> |DOI|[10.1109/TIM.2020.3003975](https://doi.org/10.1109/TIM.2020.3003975)|
> |存档位置|14 citation(s)|
> |文库编目|5.6|
> |索书号|2|
> |版权||
> |分类|[[文献]]|
> |条目链接|[My Library](zotero://select/library/items/7CRHQ283)|
> |PDF 附件|[2020_Yang 等_A Novel Echo State Network and Its Application in Temperature Prediction of Exhaust Gas From Hot Bla.pdf](zotero://open-pdf/library/items/5K5C23X9)|
> |关联文献||
> ^Metadata

> [!example]- <center>本文标签</center>
> 
> `$=dv.current().file.tags`

> [!quote]- <center>Abstract</center>
> 
> Hot blast stove (HBS) provides hot air for the blast furnace and temperature prediction for its exhaust gas is of vital importance to control the process. In this article, a novel deep memory echo state network (DMESN) is proposed for temperature prediction. First, data preprocessing is performed, including outlier rejecting, missing data handling and lag time calculating, so that better dynamic characteristics of data set can be obtained. Then, in order to improve the prediction accuracy, an improved hidden layer structure is proposed, which consists of two parts: echo state formation and hidden state formation. Echo state formation is used in network starting phase. Aiming at the problem that information cannot be effectively retained, three gates are designed in the cell to obtain a stable echo state which will be used to initialize the hidden state. In this way, the hidden state can operate continuously and stably. Finally, comparing experiments were carried out to demonstrate the efficiency of the proposed method. The simulation results show that DMESN achieves excellent performance in terms of accuracy, stability, and learning speed.

> [!tldr]- <center>隐藏信息</center>
> 
> itemType:: journalArticle
> title:: A novel echo state network and its application in temperature prediction of exhaust gas from hot blast stove
> shortTitle:: 
> creators:: [[Yinghua Yang]]、 [[Xin Zhao]]、 [[Xiaozhi Liu]]
> publicationTitle:: [[IEEE Transactions on Instrumentation and Measurement]]
> journalAbbreviation:: 
> volume:: 69
> issue:: 12
> pages:: 9465-9476
> series:: 
> language:: 
> DOI:: [10.1109/TIM.2020.3003975](https://doi.org/10.1109/TIM.2020.3003975)
> ISSN:: 1557-9662
> url:: [https://ieeexplore.ieee.org/document/9122050](https://ieeexplore.ieee.org/document/9122050)
> archive:: 
> archiveLocation:: 14 citation(s)
> libraryCatalog:: 5.6
> callNumber:: 2
> JCRQ:: Q1
> rights:: 
> extra:: Conference Name：IEEE Transactions on Instrumentation and Measurement
> collection:: [[文献]]
> tags:: #🤖️ #领域/热风炉
> related:: 
> itemLink:: [My Library](zotero://select/library/items/7CRHQ283)
> pdfLink:: [2020_Yang 等_A Novel Echo State Network and Its Application in Temperature Prediction of Exhaust Gas From Hot Bla.pdf](zotero://open-pdf/library/items/5K5C23X9)
> qnkey:: 2020_Yang_A novel echo state n_KEY-7CRHQ283
> date:: 2020-12
> dateY:: 2020
> dateAdded:: 2024-04-20
> datetimeAdded:: 2024-04-20 13:47:57
> dateModified:: 2025-03-05
> datetimeModified:: 2025-03-05 05:15:59
> 
> abstract:: Hot blast stove (HBS) provides hot air for the blast furnace and temperature prediction for its exhaust gas is of vital importance to control the process. In this article, a novel deep memory echo state network (DMESN) is proposed for temperature prediction. First, data preprocessing is performed, including outlier rejecting, missing data handling and lag time calculating, so that better dynamic characteristics of data set can be obtained. Then, in order to improve the prediction accuracy, an improved hidden layer structure is proposed, which consists of two parts：echo state formation and hidden state formation. Echo state formation is used in network starting phase. Aiming at the problem that information cannot be effectively retained, three gates are designed in the cell to obtain a stable echo state which will be used to initialize the hidden state. In this way, the hidden state can operate continuously and stably. Finally, comparing experiments were carried out to demonstrate the efficiency of the proposed method. The simulation results show that DMESN achieves excellent performance in terms of accuracy, stability, and learning speed.


%--------------ω--------------%

## ✏️ 笔记区

>[!inbox]- <center>📫 笔记简报</center>
>
>⏰ importDate:: 2025-06-06
>⏰ importDateTime:: 2025-06-06 06:30:04

> [!IMPORTANT]+ <center>🌱 研读印象</center>  
>
>📌 comment::  

> [!WARNING]+ <center>🐣 总结</center>  
>
>📌 comment:: 

%--------------ω--------------%



## 🤖️ AI 文献解读

> 🚀 [笔记回链](zotero://select/library/items/YU9GYSVP)

^KEYaiPapers

> <span class="AIReading">🤖 AI 解读，快人一步</span>
> 
> 🎯 研究问题:: 研究问题集中在如何提高热风炉废气温度的预测准确性，特别是在工业过程中对动态特性的准确反映。
> 
> 🔎 研究背景:: 随着人工智能的不断发展，深度学习作为其一个经典框架，特别是在时间序列数据分析中，被广泛讨论和应用。其中，循环神经网络（RNN）及其变种长短期记忆网络（LSTM）和回声状态网络（ESN）在系统建模、系统识别、时间序列预测等领域有广泛应用。然而，ESN在初始化回声状态时存在问题，这影响了网络的稳定性和结果的可靠性。
> 
> 🚀 研究方法:: 本文提出了一种新的深度记忆回声状态网络（DMESN），通过改进的隐藏层结构，包含回声状态形成和隐藏状态形成两部分，以提高预测准确性。此外，还包括数据预处理步骤，如异常值拒绝、缺失数据处理和滞后时间计算。
> 
> 🐔 研究思路:: 研究首先通过数据预处理来获得更好的数据集动态特性，然后利用提出的DMESN模型进行温度预测，并通过比较实验来展示所提方法的效率。
> 
> 📺 主要内容:: 文章主要内容涉及DMESN模型的理论基础、结构设计、超参数讨论、预测模型构建、数据预处理方法以及案例研究和结果分析。
> 
> 🎉 研究结论:: 研究结果表明，DMESN在准确性、稳定性和学习速度方面表现出色，相较于其他预测方法，如Leaky-ESN、CNN、RNN和LSTM，DMESN在不同预测时间下都能获得最佳的预测结果，并且具有更好的稳定性和更短的训练时间。
> 
> 🗝️ 创新点:: DMESN模型的创新之处在于其改进的隐藏层结构，通过引入遗忘门、输入门和输出门来优化网络的初始化过程，以及在ESN中融入LSTM的门控思想。
> 
> 💩 研究局限:: 研究局限可能包括DMESN模型在不同工业过程中的泛化能力尚未得到广泛验证，以及模型参数优化和选择可能依赖于特定的数据集。
> 
> 🐾 研究展望:: 未来的研究可以考虑将云计算和边缘计算技术应用于DMESN模型的在线更新，以适应不断变化的工业环境和提高模型的实时预测能力。
> 
> ✏️ 备注:: 本文的研究得到了中国国家重点研发计划的支持，编号为2017YFB0304202。
> 
> 🏷️ #🤖️/AI文献阅读

^KEYC97F113D