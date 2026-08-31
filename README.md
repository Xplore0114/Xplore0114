<p align="center">
  <a href="https://github.com/Xplore-LAB">
    <img src="https://readme-typing-svg.demolab.com?font=Georgia&size=20&duration=2500&pause=80&multiline=true&width=640&height=100&lines=Hey%2C+I'm+Kevin+%F0%9F%91%8B;ZJU+Control+Engineering+Master;LLM+Engineering+%7C+Industrial+AI+%7C+NL2SQL" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:zju_hzq@163.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://Xplore-LAB.github.io"><img src="https://img.shields.io/badge/-Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white" /></a>
  <a href="https://xplore-lab.github.io/llm-tracker/"><img src="https://img.shields.io/badge/-LLM%20Tracker-6E4B9E?style=for-the-badge&logo=readthedocs&logoColor=white" /></a>
  <a href="https://github.com/Xplore-LAB?tab=repositories"><img src="https://img.shields.io/badge/-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<br />

<!-- ====== About Me ====== -->
<a href="https://github.com/Xplore-LAB">
  <img align="right" src="https://github-stats-alpha.vercel.app/api?username=Xplore-LAB&cc=22272e&tc=37BCF6&ic=fff&bc=0000&show_icons=true&icon_color=37BCF6&hide_border=true" width="48%" />
</a>

### 🚀 About Me

🎓 控制工程硕士 @ **浙江大学**，本科 @ 北京科技大学自动化
🔬 研究方向：**大模型微调与知识注入 · 工业数据智能 · Agent 工程化**
💼 算法实习 @ **腾讯**（游戏 LLM 应用方向）
🏭 产学研合作：杭氧集团（深冷空分行业龙头）
🎯 **2026 秋招求职中**，目标算法岗（LLM / Agent 应用）
💡 信念：让工业数据"听得懂人话"，用 AI 降低专业分析门槛

<br clear="left" />

---

### 📄 Research

#### OKC-SFT：面向工业异常工况诊断的知识注入微调方法

> 一作论文，**投稿 CAC 2026，审稿中**

针对通用大模型在工业诊断场景下凭空编造机理与数据的问题，提出以运行知识卡片（Operational Knowledge Card）为中介的监督微调范式，把非结构化的专家经验蒸馏成可校验的结构化训练信号。

| 指标 | 基线 QA-SFT | OKC-SFT |
|---|---|---|
| 幻觉率 | 34.4% | **15.6%** |
| 结构完整率 | 未约束 | **99.8%** |
| 关键点覆盖率 | 低 | **0.7378** |

实验设置：Qwen2.5-7B + LoRA，611 条 OKC-SFT 训练样本对照 858 条 QA-SFT 基线，61 条测试集，场景为空分装置粗氩塔氮塞。

📦 配套数据集已开源 → [**OKC-SFT-Dataset**](https://github.com/Xplore-LAB/OKC-SFT-Dataset)

---

### 🔬 Projects

<table>
<tr>
<td width="50%">

#### 🤖 [LLM Tracker](https://github.com/Xplore-LAB/llm-tracker) · 大模型情报局

> 每日自动追踪大模型前沿的知识站点

- **13k+ 论文** 自动化管线，覆盖 34 家 AI Lab
- 16 个专题页：编年史 / 技术档案 / 模型排行榜 / 硬件志 / 可交互实验室
- 模型排行榜采用**双榜并列**设计，拒绝把能力与人类偏好合成单一总分
- GitHub Actions 每日无人值守更新

🔗 [在线访问](https://xplore-lab.github.io/llm-tracker/)

</td>
<td width="50%">

#### 🗣️ NL2SQL Query Engine

> 工业数据库自然语言查询引擎

- 多阶段推理链：意图识别 → 查询分解 → Schema Linking → SQL 生成 → 反馈修正
- 工业场景复杂查询准确率 **>90%**
- 浙大与杭氧联合项目，已在生产环境验证

</td>
</tr>
<tr>
<td width="50%">

#### 🏭 Air Separation Diagnosis Agent

> 空分装置智能诊断 Agent

- LangGraph 多层推理架构
- 数据质量门控 → 特征提取 → 异常检测 → 证据链推理 → 优化建议
- 算法层输出结构化证据，语言层只做转述，从架构上抑制编造

</td>
<td width="50%">

#### 📊 [DataLens](https://github.com/Xplore-LAB/DataLens)

> 工业控制性能分析工具

- **单文件 · 离线运行 · 零依赖**
- CSV 导入即分析，支持脱硝优化、空分节能等场景
- 面向现场工程师快速定位控制回路问题

</td>
</tr>
<tr>
<td width="50%">

#### 🧰 [Xplore-LAB-skills](https://github.com/Xplore-LAB/Xplore-LAB-skills)

> 个人 Agent Skills 工具箱

- 可复用技能集，适配 WorkBuddy / Claude Code
- 覆盖论文精读、写作流水线、仓库运维等工作流
- 每个技能自带触发词与可执行步骤

</td>
<td width="50%">

#### 🔌 [openai-compatible-proxy](https://github.com/Xplore-LAB/openai-compatible-proxy)

> 任意 LLM API 转 OpenAI 兼容端点

- 几分钟接入，屏蔽各家协议差异
- 配套 [llm-gateway-lite](https://github.com/Xplore-LAB/llm-gateway-lite) 做多模型统一路由
- 支持 OpenAI / DeepSeek / Qwen 等

</td>
</tr>
</table>

<details>
<summary><b>🧪 更多实验性项目</b></summary>

<br />

| 项目 | 说明 |
|---|---|
| [minimax-h3-dgx-spark](https://github.com/Xplore-LAB/minimax-h3-dgx-spark) | 在 NVIDIA DGX Spark / GB10 上跑通 MiniMax H3 视频生成，全容器化 ComfyUI + NGC PyTorch，torchaudio 源码编译 |
| [dsh-plugin-asmemory](https://github.com/Xplore-LAB/dsh-plugin-asmemory) | 动作状态记忆引擎，带趋势 / 异常 / 因果分析的时序记忆插件 |
| [tech-news](https://github.com/Xplore-LAB/tech-news) | 每日科技新闻自动聚合，多源抓取 + 自动摘要 + 定时更新 |
| [pc-doctor](https://github.com/Xplore-LAB/pc-doctor) | 中英双语电脑健康检查技能，只读、保守阈值、轻量与深度双模式 |
| [openclaw-scholar-pack](https://github.com/Xplore-LAB/openclaw-scholar-pack) | 学术助手技能包 |
| [word-mail-merge-batch-sender](https://github.com/Xplore-LAB/word-mail-merge-batch-sender) | Word + Outlook VBA 批量邮件工具，支持按行附件 |

</details>

---

### 🛠 Tech Stack

<p>
<b>Languages:</b><br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
</p>
<p>
<b>LLM / Training:</b><br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/LoRA%20%2F%20SFT-8E44AD?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/LLaMA--Factory-FF6F00?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/vLLM-1C7ED6?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Qwen-4FC08D?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/DeepSeek-0066FF?style=flat-square&logoColor=white" />
</p>
<p>
<b>Agent / RAG:</b><br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Agent%20Skills-6E4B9E?style=flat-square&logoColor=white" />
</p>
<p>
<b>Backend / Infra:</b><br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
</p>
<p>
<b>Frontend:</b><br/>
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Xplore-LAB&theme=radical&hide_border=true" width="60%" />
</p>

---

<p align="center">
  <i>"The best way to predict the future is to create it."</i><br/>
  <b>Open to 2026 campus recruitment · LLM Engineering, Agent Applications & Industrial AI 🤝</b>
</p>
