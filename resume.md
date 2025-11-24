---
layout: page
title: 简历
permalink: /resume/
---

# 钱玉磊
1990年，Email：qianyulei@126.com

---

## 个人简介

资深技术负责人 / Staff Engineer / Team Lead，大模型infra & 分布式机器学习系统。拥有 10+ 年互联网大厂(美团/百度)核心系统 0 到 1 建设及团队管理经验。具备模型—系统协同设计、软硬件协同优化、超大规模训练/推理系统落地、国产芯片优化、团队与组织建设的全栈经验。核心成绩：

- 大模型推理/训练 Infra (美团)：主导美团自研大模型推理框架，负责模型体系结构优化、MoE加速（首创EPS-MoE）、量化压缩、端侧推理等。成功在 LongCat-Flash（26B–560B MoE）上达成 100+ TPS 推理速度（H20/昇腾）。主导美团第一代千亿级大模型强化学习框架研发，覆盖文本与多模态模型 rollout、确定性推理保障。

- 搜推机器学习：具备丰富的 GPU 机器学习平台、大规模稀疏模型训练、分布式参数服务器、实时检索架构经验。在百度与美团多次主导核心系统从0到1搭建与规模化落地，2018年百度凤巢图腾项目获百度技术最高奖。2018-2019主导百度凤巢软硬一体的大规模稀疏CTR训练框架AIBOX，训练成本降低90%，成为行业主流选型。

- 团队管理 / 技术领导力：成功从 0 到 1 搭建美团机器学习引擎团队/大模型推理团队，指导多名成员晋升 L9；主导多项公司级技术规划和方向建设。

---

## 教育背景
- **2021年——2023年**，北京大学，工商管理，硕士
- **2012年——2015年**，中国科学院大学，软件工程，硕士
- **2008年——2012年**，郑州大学，计算机科学与技术，学士

---

## 工作背景
### 一、2020年5月—至今，美团，Staff Engineer，团队Lead
**主要方向**：大模型Infra、搜推机器学习、分布式架构、搜推架构。

#### 2023年2月-至今，美团，大模型方向
1. **文本大模型方向**：模型Efficient方向，通过算法-工程协同设计、Efficient Transformer、模型量化压缩、推理引擎、Speculative Decoding等方法加速模型推理速度，降低推理成本。负责自研大模型推理框架的总体设计；自研MoE EP通信库等。核心成果：EPS-MoE，Expert计算和传输overlap；在LongCat-Flash 560B总参规模模型上达成100 TPS的生成速度。
2. **多模态大模型方向**：先后负责过多模态训练、多模态推理等方向。负责语音（TTS+ASR）、融合多模（图文理解、图文生成、语音融合多模）等多模态大模型的推理。
3. **强化学习方向**：负责美团大模型方向第一代支持千亿参数的强化学习框架搭建；强化学习rollout推理一致性；多模态RL的rollout优化过程。
4. **国产芯片推理**：负责昇腾卡（910B/C）的推理优化，通过superkernel、通算并行控核、大EP等方法，优化延时和吞吐对标H20。
5. **端侧推理引擎**：负责公司级的端侧推理引擎和IoT场景的支持。

#### 2020年5月-2024年1月，美团，搜索推荐机器学习方向
1. **搜推机器学习引擎**：美团首页推荐、搜索场景的机器学习引擎全面GPU化（公司内首次），在离线一体的层次化GPU参数服务器，业内首次完成特征抽取的GPU框架，训练效率提升4倍，推理算力空间提升一个数量级。
2. **搜推机器学习平台**：公司级搜推机器学习平台，解决搜推场景的机器学习迭代效率和PS的AutoCapacity问题，端到端机器学习平台建设，月均迭代+35倍。
3. **搜推在线架构**：负责搜推在线检索架构的总体设计和推广落地，完成全图化执行引擎的总体设计和实现。

### 二、2015年7月—2020年5月，百度凤巢-CTR团队，资深研发工程师（T7）
**工作总结**：
1. **2018 年-2020 年**，负责千亿级稀疏模型GPU训练框架AIBOX/PaddleBOX，行业首次采用GPU加速大规模稀疏模型的训练，成本下降90%，业内首次技术突破，相关成果发表在SYSML、CIKM、GTC2019等会议。
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
