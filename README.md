<div align="center">

<h1>Hi, I'm leeoisaboy 👋</h1>

<p>
  <strong>AI 产品经理 · AI Product Builder（多模态与语音方向）</strong><br />
  <sub>AI Product Manager & Builder (Multimodal & Speech) · White-Box Evaluation · Post-Training · AI Agent Workflows</sub>
</p>

<p>
  <a href="https://leeoisaboy.github.io/wu-speech-synthbench/"><img alt="SynthBench Studio" src="https://img.shields.io/badge/Live_Demo_1-SynthBench_Studio-0ea5e9?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/disentangle-acoustic-print/"><img alt="Acoustic Print Studio" src="https://img.shields.io/badge/Live_Demo_2-Acoustic_Print_Studio-2b9c94?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/dialect-crossmodal-align/"><img alt="CrossModal Align Lab" src="https://img.shields.io/badge/Live_Demo_3-CrossModal_Align_Lab-0071e3?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/audiollm-latent-kws/"><img alt="Latent-KWS Audit Studio" src="https://img.shields.io/badge/Live_Demo_4-Latent--KWS_Audit_Studio-7b6bb0?style=flat-square" /></a>
</p>

<p>
  <a href="https://github.com/leeoisaboy/cosyvoice-lora-finetune-framework"><img alt="CosyVoice LoRA Framework Stars" src="https://img.shields.io/github/stars/leeoisaboy/cosyvoice-lora-finetune-framework?style=flat-square&logo=github&label=CosyVoice%20LoRA%20Framework&color=f59e0b" /></a>
  <a href="https://github.com/leeoisaboy/lora-cosyvoice123-chanting"><img alt="CosyVoice 1/2/3 Chanting Stars" src="https://img.shields.io/github/stars/leeoisaboy/lora-cosyvoice123-chanting?style=flat-square&logo=github&label=CosyVoice%201%2F2%2F3%20Chanting&color=f59e0b" /></a>
  <a href="https://github.com/leeoisaboy/paleomindocr-evahan2026"><img alt="EvaHan 2026 Ancient OCR Stars" src="https://img.shields.io/github/stars/leeoisaboy/paleomindocr-evahan2026?style=flat-square&logo=github&label=EvaHan%202026%20Ancient%20OCR&color=f59e0b" /></a>
</p>

<p>
  <a href="https://github.com/leeoisaboy?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/leeoisaboy?style=flat-square&label=Followers&color=1f2937" /></a>
  <a href="https://www.bilibili.com/video/BV1Sti7B9ENN/"><img alt="Bilibili Documentary" src="https://img.shields.io/badge/Bilibili-CosyVoice%20%E8%B0%83%E8%AF%95%E7%BA%AA%E5%AE%9E-fb7299?style=flat-square&logo=bilibili&logoColor=white" /></a>
  <img alt="WeChat Official Account" src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E4%B8%80%E4%B8%AAAI%E4%BA%A7%E5%93%81%E7%BB%8F%E7%90%86%E7%9A%84%E5%91%A8%E8%AE%B0-07c160?style=flat-square&logo=wechat&logoColor=white" />
</p>

</div>

---

### 💡 核心优势 · What Sets My Work Apart

- **🔬 源自真实场景的可视化算法原型（CBB 预研沉淀）**：低资源方言语音「白盒四部曲」并非纸面论文复现，而是我在 **AI 产品经理（语音方向）实习**中，围绕**技术预研与公共基础模块（CBB）搭建**的算法试错里沉淀出的工程产物——全部封装为**零后端、可实验、可视化的浏览器白盒工作台**（支持 60 FPS 实时麦克风、拖入 WAV、手拖超参现场验算），让每个算子与指标肉眼可见。
- **📊 评测先行与诚实消融**：拒绝黑盒玄学调参——公开五折交叉验证淘汰的阴性实验、80ms/40ms 双网格防泄漏审计、跨域路由陷阱（AUROC `0.999` → 命中率 `4%`）以及 CosyVoice 四关断路排障全记录。
- **🚀 从模型微调到产品闭环**：既能深入 PyTorch / LoRA / DoRA / DPO / Flow Matching / DiT 底层架构调优，也能交付 Codex Skill、多模态图文/视频自动化管线等真实落地的 AI 产品工具。

---

## 🧭 全景作品看板 · Featured Portfolio (8 Flagship Projects)

> GitHub 首页置顶栏仅支持 6 个仓库，以下看板完整呈现我的 **8 个核心公开项目**，涵盖 **白盒方言语音四部曲**、**CosyVoice 语音合成微调**、**古籍多模态 OCR** 与 **AI Agent 工作流**。

### 🎙️ 方向一：白盒低资源方言语音四部曲（White-Box Dialect Speech Quartet）

```mermaid
flowchart LR
    A["01 语料规划与校准<br/>wu-speech-synthbench"] --> B["02 音色与语速解耦<br/>disentangle-acoustic-print"]
    B --> C["03 跨模态零样本对齐<br/>dialect-crossmodal-align"]
    C --> D["04 Audio-LLM 重排与审计<br/>audiollm-latent-kws"]
```

| 阶段 | 项目仓库 | 在线交互台 | 核心亮点与技术指标 |
| :--- | :--- | :---: | :--- |
| **01 合成与评测** | **[wu-speech-synthbench](https://github.com/leeoisaboy/wu-speech-synthbench)**<br />![](https://img.shields.io/github/stars/leeoisaboy/wu-speech-synthbench?style=flat-square&color=f59e0b) | [▶ SynthBench Studio](https://leeoisaboy.github.io/wu-speech-synthbench/) | 零资源方言合成语料规划、能量谷信号级自动切字、Robust MAD 概率校准与防刷分评测；**全仓纯 NumPy**，零后端实时试算。 |
| **02 声学解耦** | **[disentangle-acoustic-print](https://github.com/leeoisaboy/disentangle-acoustic-print)**<br />![](https://img.shields.io/github/stars/leeoisaboy/disentangle-acoustic-print?style=flat-square&color=f59e0b) | [▶ Acoustic Print Studio](https://leeoisaboy.github.io/disentangle-acoustic-print/) | 免训练跨音色声学指纹：正交投影剥离说话人音色 + 等弧长重采样消除语速变化；内置 **60 FPS 浏览器实时麦克风**四轨示波器。 |
| **03 跨模态对齐** | **[dialect-crossmodal-align](https://github.com/leeoisaboy/dialect-crossmodal-align)**<br />![](https://img.shields.io/github/stars/leeoisaboy/dialect-crossmodal-align?style=flat-square&color=f59e0b) | [▶ CrossModal Align Lab](https://leeoisaboy.github.io/dialect-crossmodal-align/) | 开放词表零样本 OOV 组合式检索、语速不变跨模态注意力、FSQ 离散晶格与**路由陷阱模拟器**（直击 AUROC `0.999` 跨域崩塌至 `4%`）。 |
| **04 重排与审计** | **[audiollm-latent-kws](https://github.com/leeoisaboy/audiollm-latent-kws)**<br />![](https://img.shields.io/github/stars/leeoisaboy/audiollm-latent-kws?style=flat-square&color=f59e0b) | [▶ Audit Studio](https://leeoisaboy.github.io/audiollm-latent-kws/) | 冻结 Audio-LLM 免训练方言检索：80ms/40ms 双网格防泄漏审计、Top-20 语境重排、**Prefix KV-Cache `2.14×` 加速**与五折阴性实验公开。 |

---

### 🎵 方向二：语音合成微调与跨代架构评测（CosyVoice TTS & Chanting）

| 项目仓库 | 关注度 | 演示 / 资料 | 核心亮点与技术指标 |
| :--- | :---: | :---: | :--- |
| **[cosyvoice-lora-finetune-framework](https://github.com/leeoisaboy/cosyvoice-lora-finetune-framework)** | ![](https://img.shields.io/github/stars/leeoisaboy/cosyvoice-lora-finetune-framework?style=flat-square&color=f59e0b) | [▶ Bilibili 调试纪实](https://www.bilibili.com/video/BV1Sti7B9ENN/) | 从 Loss 卡死 `28+` 到成功突破：通过**四关断路测试**定位「语义泄漏」根因，设计 **LLM + Flow 联合 LoRA 训练**，实现**无 Prompt 推理**与极少样本音色定制。 |
| **[lora-cosyvoice123-chanting](https://github.com/leeoisaboy/lora-cosyvoice123-chanting)** | ![](https://img.shields.io/github/stars/leeoisaboy/lora-cosyvoice123-chanting?style=flat-square&color=f59e0b) | [🎧 试听与架构海报](https://github.com/leeoisaboy/lora-cosyvoice123-chanting#试听演示) | 面向中文古诗词吟诵的 **CosyVoice 1 / 2 / 3 三代跨架构 LoRA 实验框架**：同一数据集横向对比 LLM / FSQ / Flow / DiT 骨干差异与 prompt 边界，提出吟诵专用客观评估公式。 |

---

### 📜 方向三：多模态古籍 OCR 与 AI Agent 工作流（Multimodal VLM & Agent Skills）

| 项目仓库 | 关注度 | 场景定位 | 核心亮点与技术指标 |
| :--- | :---: | :---: | :--- |
| **[paleomindocr-evahan2026](https://github.com/leeoisaboy/paleomindocr-evahan2026)** | ![](https://img.shields.io/github/stars/leeoisaboy/paleomindocr-evahan2026?style=flat-square&color=f59e0b) | 古籍多模态 OCR | **EvaHan 2026 闭模态赛道完整解决方案**：YOLO 古籍版面检测 + `Xunzi-Qwen2-VL-7B` **DoRA 微调** + **DPO 强化学习**专项攻克生僻字与复杂版面识别。 |
| **[WeMD-SKILLS](https://github.com/leeoisaboy/WeMD-SKILLS)** | ![](https://img.shields.io/github/stars/leeoisaboy/WeMD-SKILLS?style=flat-square&color=f59e0b) | AI Agent Skill | 面向微信公众号 / WeMD 的**多模态配图与 15s 片头视频自动化 Codex Skill**：`Qwen Image 3.0` 主用、`Seedream 5.0` 备用、`wan3.0-video` 电影感片头 + 自动图床上传，真实落地于公众号「一个AI产品经理的周记」。 |

---

## ✍️ 最新周记 · Weekly Notes

> 公众号 **「一个AI产品经理的周记」** 同步更新，由 [WeMD-SKILLS](https://github.com/leeoisaboy/WeMD-SKILLS) 在发文后自动归档全部周记（首屏展示最新 5 期，往期自动折叠收纳）。

<!-- WEEKLY_NOTES_START -->
- `2026-11-22` | [AI产品经理实习周记｜管好政府资金项目，技术只是底牌，财务、主体和证据链才是大头](https://mp.weixin.qq.com/s/4xb8gpw7jaB6x6H20U0tfw) — 政府专项资金项目从申报起就按验收倒推，决定结项成败的往往是财务合规、多方主体协调与全流程证据链管理。
- `2026-11-18` | [AI产品经理实习周记｜先在局部打穿闭环，再顺着利益链条推开全局](https://mp.weixin.qq.com/s/aTnQgaOekvqOIn9bHt2y-A)
- `2026-11-14` | [AI产品经理实习周记｜怎么思考下一代解决方案和产品形态](https://mp.weixin.qq.com/s/wH5EdQVfIrtgUE7hZz00JA) — 先画完整服务链，再把存量资产放回去，用真实断点倒推下一代硬件形态。
- `2026-11-10` | [AI产品经理实习周记 | 硬件开发是层层递归而环环相扣的导演艺术——以《盗梦空间》为例](https://mp.weixin.qq.com/s/SO-x652iHHrA0Ma3c7Q00g) — 把半年硬件开发拆成五幕，用三次全员同步的决策制定点控制多层协作。
- `2026-11-06` | [AI产品经理实习周记｜一枚语音徽章背后的供应商尽调](https://mp.weixin.qq.com/s/xomx82ugsJNUr1fV9lTP8A) — 在签约付款前核验供应商资质、能力和交付风险，判断对方能否持续交付。

<details>
<summary>📚 展开查看全部往期周记（共 31 篇）</summary>

- `2026-11-05` | [AI产品经理实习周记｜一台智能音箱的硬件开发流程](https://mp.weixin.qq.com/s/gSKo73XbClmJJdAE68nRoQ) — 从一台智能音箱的制造流程看硬件开发的关键环节、角色分工与协作边界。
- `2026-11-01` | [AI产品经理实习周记｜我的技术预研过程产物介绍（一）——开源项目AudioLLM-Latent-KWS](https://mp.weixin.qq.com/s/gjHPlGDkiORYaCE6Q-6HxQ)
- `2026-10-24` | [AI产品经理实习周记：市场洞察给出理由，商业闭环给出结构，产品形态给出界面](https://mp.weixin.qq.com/s/9Az9F-mmFFuJWpOwkzb9EA)
- `2026-10-23` | [AI产品经理实习周记｜技术变强了，用户没有多一个购买理由](https://mp.weixin.qq.com/s/4pu0YXsNnzFrC__4hJxKfA)
- `2026-10-18` | [AI产品经理实习周记：产品不能停在从零到一，增长和爆款都藏在后面的跟进里](https://mp.weixin.qq.com/s/tWWoS8UkzgQGa0r-Ng554A)
- `2026-10-11` | [AI产品经理实习周记：IPD的第一课，为什么IBM和华为都要先把流程定死，再谈灵活](https://mp.weixin.qq.com/s/atfQtf47E-PLzlERu0wsjw) — 这周我开始读IPD的教材，想把这套被IBM和华为先后验证过的产品研发体系理清楚。
- `2026-10-02` | [AI产品经理实习周记：记录我用多模态插件完成3D建模交付的过程](https://mp.weixin.qq.com/s/uLz3UF_nKi8fQN4N8euNfA)
- `2026-09-27` | [AI产品经理实习周记：从云栖回来，我重新想了想 Agent 与人的边界](https://mp.weixin.qq.com/s/uc2CRWe2rMfqATT6RX8YUg)
- `2026-09-20` | [AI产品经理实习周记：外因是条件，内因是根据](https://mp.weixin.qq.com/s/cNd-xDaSeyJBhmVr_PCm3A)
- `2026-09-19` | [AI产品经理实习周记：战略上的一个判断，胜过战役上的一百个补丁](https://mp.weixin.qq.com/s/TAE-7L7M7aJf8qHygm_mtQ)
- `2026-09-13` | [AI产品经理实习周记：一次研究思路的掉头之三，抽车，将军，战略撤退换来战略主动](https://mp.weixin.qq.com/s/rtsNhfxIM-ap-0Eitd3JGQ)
- `2026-09-12` | [AI产品经理实习周记：一次研究思路的掉头之二，借别人的鲁棒性解自己的数据荒](https://mp.weixin.qq.com/s/wxDITBoqfnpIO6hjvZ9y1Q)
- `2026-09-11` | [AI产品经理实习周记：一次研究思路的掉头，让我明白战略决策远比战术选型更重要](https://mp.weixin.qq.com/s/uAhShCnavAb6BhFySU6ptQ)
- `2026-09-04` | [AI产品经理实习周记：五条路都走不通，我换了个更省事的目标](https://mp.weixin.qq.com/s/_YS-rFJUGybKpqJP2armRw)
- `2026-09-03` | [AI产品经理实习周记：AI为什么在合成音频里很准，一到真实世界就失灵](https://mp.weixin.qq.com/s/OHRqdAeXZRNFTdi0U03itA)
- `2026-09-02` | [AI产品经理实习周记：训练进程无声倒下，先找外因，再怀疑自己](https://mp.weixin.qq.com/s/hmte17kVR6XbSBXJFhXyfw)
- `2026-08-30` | [AI产品经理实习周记：一次语音微调工程的排雷复盘](https://mp.weixin.qq.com/s/o0XdilU7HaD44ybEQvxIbg)
- `2026-08-29` | [AI产品经理实习周记：商务洽谈，谈的是共同利益，也是利益博弈](https://mp.weixin.qq.com/s/ERtKV2xd9O9j0nWa_Zf1Zg)
- `2026-08-28` | [AI产品经理实习周记：语音微调有两个上限，一个决定听得清，一个决定写得对](https://mp.weixin.qq.com/s/ZVxRw_2Cz0ShNRA1gSRJ4A)
- `2026-08-21` | [AI产品经理实习周记：模型微调没有万能配方——聊聊语音模型微调的特殊性和普遍性](https://mp.weixin.qq.com/s/1uBymTDPv-Aex52F2IWg7A)
- `2026-08-20` | [AI产品经理实习周记：Coding Agent跑得飞快，谁来发现错误？——聊聊产品经理为什么要读源码](https://mp.weixin.qq.com/s/jb2O45FOadfddLPMkQNvOg)
- `2026-08-19` | [AI产品经理实习周记：产品经理不写一行代码，那靠什么吃饭？——聊聊PM的三种核心思维](https://mp.weixin.qq.com/s/I2LlhIZ8aBhJBVt_Emj-IA)
- `2026-08-16` | [AI产品经理实习周记：开源不一定是"做慈善"——从一个小智音箱看AI时代的生态战](https://mp.weixin.qq.com/s/PPkDL1C8G5lmU8jImrnrcA)
- `2026-08-15` | [AI产品经理实习周记：Agent再强，也替代不了专家的“技术直觉”](https://mp.weixin.qq.com/s/TlJQjzfKIxockwcNnjbuyg)
- `2026-08-12` | [AI产品经理实习周记：定义产品边界，从"手术刀级别"的评测理解开始](https://mp.weixin.qq.com/s/RsJdlKDxJcaf2ocxh65DaA)
- `2026-08-09` | [AI产品经理实习周记：996之后，我如何"偷"出时间经营自己？](https://mp.weixin.qq.com/s/8L7rfG-CEk0s7C4yqNpVJg)
- `2026-08-08` | [AI产品经理实习周记：当Coding Agent能自动训练模型时，产品经理的价值在哪里？](https://mp.weixin.qq.com/s/3UfgYcl-X0jx90rXjwurGg)
- `2026-08-07` | [AI产品经理实习周记：从实验室到企业，产品经理的"稳扎稳打"之道](https://mp.weixin.qq.com/s/DNUbAUAFmijEHE7IrEkJ_Q)
- `2026-07-30` | [AI产品经理实习周记：调研、矛盾、系统观](https://mp.weixin.qq.com/s/rZTzxugVM_B6p5lHxfPb_w)
- `2026-07-28` | [AI产品经理实习周记：实习生如何听懂任务、看懂需求、并找到自己的价值锚点](https://mp.weixin.qq.com/s/NyLzIoWTzfLAaRlh52Lizw) — AI产品沉思录
- `2026-07-26` | [AI产品经理实习周记：在“经验为王”的时代，用Harness式工作法做AI产品](https://mp.weixin.qq.com/s/VSjNOeboMSaHsCw7THu0wQ) — AI产品实习沉思录

</details>
<!-- WEEKLY_NOTES_END -->

---

## 🛠️ 技术栈 · Tech Stack

| 领域 | 核心工具与技术 |
| :--- | :--- |
| **Speech & Audio AI** | `CosyVoice 1/2/3` · `Flow Matching` · `DiT` · `FSQ` · `Audio-LLM` · `Keyword Spotting` · `Signal Processing (FFT / CUSUM / Pure NumPy)` |
| **Multimodal & Fine-Tuning** | `PyTorch` · `Qwen2-VL` · `LoRA / DoRA` · `DPO / RLHF` · `YOLO` · `Zero-Shot Cross-Modal Alignment` |
| **Evaluation & White-Box Viz** | `Leakage-Aware CV` · `Probability Calibration` · `Ablation & Negative Experiments` · `Zero-Backend Interactive Web Studios (GitHub Pages)` |
| **AI Product & Agent** | `Codex Skills` · `Qwen Image 3.0 / Seedream 5.0 / Wan 3.0` · `FastAPI` · `Gradio` · `Python` · `Go` |

---

<div align="center">
  <sub>✍️ 微信搜索公众号 <strong>「一个AI产品经理的周记」</strong> 查看更多 AI 产品思考与多模态工程实践</sub>
</div>
