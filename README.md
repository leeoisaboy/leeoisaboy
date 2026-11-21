<div align="center">

<h1>Hi, I'm leeoisaboy 👋</h1>

<p>
  <strong>AI 产品经理 & 多模态语音算法工程师</strong><br />
  <sub>AI Product Manager & Multimodal Speech Engineer · White-Box Evaluation · Speech & VLM Fine-Tuning · AI Agent Skills</sub>
</p>

<p>
  <a href="https://leeoisaboy.github.io/wu-speech-synthbench/"><img alt="SynthBench Studio" src="https://img.shields.io/badge/Live_Demo_1-SynthBench_Studio-0ea5e9?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/disentangle-acoustic-print/"><img alt="Acoustic Print Studio" src="https://img.shields.io/badge/Live_Demo_2-Acoustic_Print_Studio-2b9c94?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/dialect-crossmodal-align/"><img alt="CrossModal Align Lab" src="https://img.shields.io/badge/Live_Demo_3-CrossModal_Align_Lab-0071e3?style=flat-square" /></a>
  <a href="https://leeoisaboy.github.io/audiollm-latent-kws/"><img alt="Latent-KWS Audit Studio" src="https://img.shields.io/badge/Live_Demo_4-Latent--KWS_Audit_Studio-7b6bb0?style=flat-square" /></a>
</p>

<p>
  <a href="https://github.com/leeoisaboy?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/leeoisaboy?style=flat-square&label=Followers&color=1f2937" /></a>
  <a href="https://www.bilibili.com/video/BV1Sti7B9ENN/"><img alt="Bilibili Documentary" src="https://img.shields.io/badge/Bilibili-CosyVoice%20%E8%B0%83%E8%AF%95%E7%BA%AA%E5%AE%9E-fb7299?style=flat-square&logo=bilibili&logoColor=white" /></a>
  <img alt="WeChat Official Account" src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E4%B8%80%E4%B8%AAAI%E4%BA%A7%E5%93%81%E7%BB%8F%E7%90%86%E7%9A%84%E5%91%A8%E8%AE%B0-07c160?style=flat-square&logo=wechat&logoColor=white" />
</p>

</div>

---

### 💡 核心优势 · What Sets My Work Apart

- **🔬 把黑盒论文做成浏览器白盒交互台**：围绕低资源方言语音打造的「白盒四部曲」全部内置**零后端、纯本地运行的交互 Studio**（支持 60 FPS 实时麦克风、拖入 WAV、手拖超参现场验算），让每个算子与指标肉眼可见。
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
