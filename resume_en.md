---
layout: page
title: Resume
permalink: /resume/
---

# Yulei Qian
**Staff/Principal Engineer** | Born 1990 | Email: qianyulei@126.com

---

## 🚀 Professional Summary

**Staff/Principal Engineer** specializing in **Ultra-Scale AI Infrastructure** and **Hardware-Software Co-design**. Recognized for leading **Pioneering 0-to-1** initiatives at **Trillion-Parameter** scale, driving both fundamental research (8+ papers) and massive production efficiency across Meituan and Baidu.

* **🏆 Technical Breakthrough & Cross-Organizational Leadership:**
       * **Domestic Chip Parity:** Led a **cross-company technical taskforce (Meituan & Huawei)** to achieve industry-leading LLM inference performance on domestic Ascend NPUs, matching H20 performance.
    * **AIBOX Innovation:** Led the development of **AIBOX** (GPU-accelerated sparse CTR framework), **the industry's first sparse Parameter Server on a single machine GPU**. Successfully collaborated with **NVIDIA China R&D, Baidu Search/Feed/Hardware, and PaddlePaddle teams** to scale a 10TB-level model onto a single node via Hierarchical Parameter Server design. **Reduced training costs by 90%** (Winner of **Baidu's Top Technical Award**, 2018).

* **💡 LLM Infrastructure Depth:** Designed and deployed a proprietary LLM inference framework, achieving **100+ TPS** generation speed on **560B MoE** models, demonstrating industry-leading efficiency.
* **🤝 Organizational Impact:** Built and scaled high-impact ML/LLM infrastructure teams from scratch; responsible for setting **cross-organizational technology roadmaps** and mentoring senior engineers (L9).

---

## 📚 Publications and Patents

*(This section is placed early to highlight research and innovation impact)*

1.  **Qian, Y. et al.** EPS-MoE: Expert Pipeline Scheduler for Cost-Efficient MoE Inference. ArXiv, abs/2410.12247 (2024).
2.  **Zhao, W. et al.** AIBox: CTR prediction model training on a single node. In *Proceedings of the 28th ACM International Conference on Information and Knowledge Management* (CIKM 2019).
3.  **Zhao, W. et al.** Distributed hierarchical gpu parameter server for massive scale deep learning ads systems. *Proceedings of Machine Learning and Systems* (SysML 2020).
4.  *(... other papers demonstrating LLM/MoE expertise)*

1. ** Team, Meituan LongCat et al. **  “LongCat-Flash-Omni Technical Report.” (2025).
2. ** Team, Meituan LongCat et al. ** “LongCat-Flash-Thinking Technical Report.” (2025).
3. ** Team, Meituan LongCat et al. ** “LongCat-Flash Technical Report.” ArXiv abs/2509.01322 (2025): n. pag.
4. ** Li, Q., Zhang, B., Kang, H., Xu, T., Qian, Y., Xie, Y., & Ma, L. (2025). ** FlashCommunication V2: Bit Splitting and Spike Reserving for Any Bit Communication. ArXiv, abs/2508.03760.
5. ** Su, Z., Li, Q., Zhang, H., Qian, Y., Xie, Y., & Yuan, K. (2025). ** Unveiling Super Experts in Mixture-of-Experts Large Language Models. ArXiv, abs/2507.23279.
6. ** Qian, Y., Li, F., Ji, X., Zhao, X., Tan, J., Zhang, K., & Cai, X. (2024). ** EPS-MoE: Expert Pipeline Scheduler for Cost-Efficient MoE Inference. ArXiv, abs/2410.12247.
7. ** Zhao, W., Zhang, J., Xie, D., Qian, Y., Jia, R., & Li, P. (2019, November). ** AIBox: CTR prediction model training on a single node. In Proceedings of the 28th ACM International Conference on Information and Knowledge Management (pp. 319-328).
8. ** Zhao, Weijie, Deping Xie, Ronglai Jia, Yulei Qian, Ruiquan Ding, Mingming Sun, and Ping Li. (2020). ** Distributed hierarchical gpu parameter server for massive scale deep learning ads systems. Proceedings of Machine Learning and Systems 2 (2020): 412-428.

---

## 💼 Work Experience

### I. Meituan, Staff Engineer / Team Lead (May 2020 – Present)
**Focus Areas**: LLM Infra, Hardware-Software Co-design, Search & Recommendation ML Platforms.

#### **LLM Infrastructure & System Co-design (Feb 2023 – Present)**
* **Domestic Chip Optimization (Ascend NPUs):** **Led a joint technical taskforce** across Meituan and Huawei departments to optimize LLM inference on Ascend 910B/C. Achieved **H20 parity** on key performance metrics (latency/throughput) through low-level Superkernel and compute/communication overlap ($P_{comp} \cap P_{comm}$) strategies, resulting in **industry-leading NPU inference performance**.
* **Pioneering MoE & Efficient LLM Inference:** Architected and deployed a proprietary LLM inference engine, achieving **100 TPS** on the **560B LongCat-Flash MoE** model using self-developed MoE EP Communication Libraries and Speculative Decoding techniques.
* **Trillion-Scale RL Platform:** Designed and built the first-generation **Trillion-Parameter Reinforcement Learning (RL) Framework** for text and multimodal models, ensuring deterministic rollout inference and consistency.

#### **Search & Recommendation Machine Learning (May 2020 – Jan 2024)**
* **ML Platform GPU Transformation:** Led the *0-to-1* transition of the core Search/Rec ML engine to a **GPU-native architecture** (company-first). Designed the **Hierarchical GPU Parameter Server** and a GPU Feature Extraction Framework. **Result:** **4x** training speed increase and **10x** gain in serving capacity.
* **Organizational Impact:** Drove the end-to-end ML platform roadmap, accelerating the model iteration rate by **35x** monthly, significantly improving the feature iteration velocity.

### II. Baidu Phoenix Nest (Fengchao) - CTR Team, Senior R&D Engineer (T7) (Jul 2015 – May 2020)

* **AIBOX/PaddleBOX (Industry-First Sparse GPU Training):** **Spearheaded cross-functional collaboration** with **NVIDIA China R&D, Baidu Search/Feed/Hardware, and PaddlePaddle teams** to develop AIBOX.
    * **Technical Depth:** **Pioneered** the design of a hierarchical Parameter Server to compress a **10TB-level sparse model** for lossless training on a single machine GPU. This marked the industry's first sparse Parameter Server implementation on GPUs. **Result:** **90% reduction** in model training costs, winning the **Baidu's Top Technical Award (2018)**.
* **PSLIB (Trillion-Scale Parameter Server):** Designed and deployed **PaddlePaddle's Large-Scale Sparse Parameter Server (PSLIB)** from scratch, enabling the platform to support trillion-scale sparse model training, widely adopted by Baidu FEED.
* **LOPQ (Distributed Vector Retrieval):** Developed and commercialized the distributed vector retrieval algorithm **LOPQ** for real-time ad image matching. **Result:** Contributed to an annual revenue growth of **200M+ RMB**.

---

## 🎓 Education

* **2021 – 2023**, Peking University, Master of Business Administration (MBA)
* **2012 – 2015**, University of Chinese Academy of Sciences (UCAS), Master of Engineering in Software Engineering
* **2008 – 2012**, Zhengzhou University, Bachelor of Science in Computer Science and Technology
