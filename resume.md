---
layout: page
title: 简历
permalink: /resume/
---

# 钱玉磊
1990年，Email：qianyulei@126.com

---

## 个人简介

大模型方向：负责美团基座大模型推理（文本+多模态）加速，通过投机推理（Medusa/Eagle/MTP/PLD）、PrefixCache、计算通信并行（EPS-MoE）、量化压缩、分布式EP等技术提高模型在英伟达H20/H800和华为910B/C卡上的推理性能，降低成本；主导美团第一个支持千亿规模模型的强化学习框架落地。

搜推机器学习方向：有比较深的软硬件协同设计以及算法工程化方面的工作经验。主导百度凤巢软硬一体的大规模稀疏CTR训练框架AIBOX，完成基于HBM-DDR层次化参数服务器的训练、推理引擎在美团首页搜索、推荐场景落地。参与百度凤巢图腾项目，使用深度学习算法为广告实时配图，获2018年百度技术最高奖。

---

## 教育背景
- **2021年——2023年**，北京大学，工商管理，硕士
- **2012年——2015年**，中国科学院大学，软件工程，硕士
- **2008年——2012年**，郑州大学，计算机科学与技术，学士

---

## 工作背景
### 一、2020年5月—至今，美团，Staff Engineer，团队Lead
**主要方向**：大模型Infra、搜推机器学习、分布式架构、搜推架构。

**工作总结**：
1. **大模型方向**：大模型推理引擎、合成数据、强化学习训练、多模态训练和推理、模型应用架构等方面的工作；推理框架上，通过投机推理、PrefixCache、EPS-MoE、通信量化等方法提升吞吐数倍，在DeepseekV2时，beat DeepSeek论文中吞吐，相关成果见论文发表。
2. **搜推机器学习方向**：美团首页推荐、搜索机器学习引擎全面GPU化，在离线一体的层次化参数服务器，业内首次完成特征抽取的GPU框架，训练效率提升4倍，推理算力空间提升一个数量级。端到端机器学习平台建设，月均迭代+35倍。
3. **搜推架构方向**：全图化在线执行引擎设计，解决搜推场景的算子化调度问题。
4. **管理方面**：从0到1搭建美团机器学习引擎团队，培养多个核心技术人员。承担部门TC工作，参与部门整体技术水平提升和系统架构的设计。

#### 2023年2月-至今，美团，大模型加速方向
1. **文本大模型推理**： 2023-至今，负责内部自研大模型推理框架的总体设计；MoE推理优化；投机推理的算法和工程；算法-工程协同设计模型结构，通过结构设计和工程实现，在500B总参规模模型上达成100 TPS的生成速度。
2. **多模态大模型推理**：2023-至今，负责语音（TTS+ASR）、融合多模（图文理解、图文生成、语音融合多模）等多模态大模型的推理架构。
3. **多模态大模型RL**：2025-至今，负责多模态RL的rollout优化过程。
4. **模型量化压缩**：2025-至今，模型压缩方向，模型量化、模型稀疏化、高效Attention结构设计。
5. **国产芯片推理**：2025-至今，负责昇腾卡（910B/C）的推理优化，通过superkernel、通算并行等方法，优化延时和吞吐对标H20。
6. **端侧推理引擎**：2025-至今，负责公司级的端侧推理引擎和IoT场景的支持。
7. **多模态大模型训练**：2023-2024，融合多模训练。

#### 2020年5月-2024年1月，美团，搜索推荐方向
1. **搜推机器学习引擎**：美团首页推荐、大搜机器学习引擎全面GPU化（公司内首次），在离线一体的层次化GPU参数服务器。
2. **搜推机器学习平台**：公司级搜推机器学习平台。
3. **搜推在线架构**：负责搜推在线检索架构的总体设计和推广落地。

### 二、2015年7月—2020年5月，百度凤巢-CTR团队，资深研发工程师（T7）
**工作总结**：
1. **2018 年-2020 年**，完成千亿级稀疏模型GPU训练框架AIBOX/PaddleBOX，行业首次采用GPU加速大规模稀疏模型的训练，成本下降90%，业内首次技术突破，相关成果发表在SYSML、CIKM、GTC2019等会议。
2. **2018 年-2018 年**，从0到1设计和研发PaddlePaddle大规模稀疏参数服务器PSLIB，在手百FEED全面推广，是PaddlePaddle首次得以具备千亿级稀疏模型的训练能力。
3. **2017 年-2018 年**，自研分布式向量检索算法LOPQ，大幅提升索引效果，并通过搜索广告图片素材库搭建，线上实时化广告配图，提升广告配图率，实现广告输入增加2亿+/年，团队获2018年百度技术最高奖。
4. **2016 年-2017 年**，流式计算与模型推理：从0到1自研基于Lambda架构的数据处理框架，实现百度素材库秒级传输；深度参与百度内部流批一体的计算框架Dstream3的设计与开发。
5. **2015 年-2016 年**，凤巢推理服务云化部署，首次通过凤巢专有云来完成LR模型训练、推理部署、测试、实验、效果回收等全流程的平台化迭代支持。凤巢个性化与非个性化模型的拆分。

---

## 论文
1. **Team, Meituan LongCat et al.** “LongCat-Flash-Omni Technical Report.” (2025).
2. **Team, Meituan LongCat et al.** “LongCat-Flash-Thinking Technical Report.” (2025).
3. **Team, Meituan LongCat et al.** “LongCat-Flash Technical Report.” ArXiv abs/2509.01322 (2025): n. pag.
4. **Li, Q., Zhang, B., Kang, H., Xu, T., Qian, Y., Xie, Y., & Ma, L. (2025).** FlashCommunication V2: Bit Splitting and Spike Reserving for Any Bit Communication. ArXiv, abs/2508.03760.
5. **Su, Z., Li, Q., Zhang, H., Qian, Y., Xie, Y., & Yuan, K. (2025).** Unveiling Super Experts in Mixture-of-Experts Large Language Models. ArXiv, abs/2507.23279.
6. **Qian, Y., Li, F., Ji, X., Zhao, X., Tan, J., Zhang, K., & Cai, X. (2024).** EPS-MoE: Expert Pipeline Scheduler for Cost-Efficient MoE Inference. ArXiv, abs/2410.12247.
7. **Zhao, W., Zhang, J., Xie, D., Qian, Y., Jia, R., & Li, P. (2019, November).** AIBox: CTR prediction model training on a single node. In Proceedings of the 28th ACM International Conference on Information and Knowledge Management (pp. 319-328).
8. **Zhao, Weijie, Deping Xie, Ronglai Jia, Yulei Qian, Ruiquan Ding, Mingming Sun, and Ping Li. (2020).** Distributed hierarchical gpu parameter server for massive scale deep learning ads systems. Proceedings of Machine Learning and Systems 2 (2020): 412-428.
