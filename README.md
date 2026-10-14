# AI 应用学习与实验 | AI Application Learning & Experiments

这里集中整理 AI 应用开发的学习路径、技术笔记和小型实验，覆盖 Agent、RAG、图检索、法律文档问答与 AI 图像生成。内容来自多个学习与实验仓库，按主题重新编排，适合作为技术参考与实践起点。

This repository brings together learning paths, technical notes, and small experiments in AI application development, covering agents, RAG, graph retrieval, legal-document question answering, and AI image generation. Materials from several study and experiment repositories have been reorganized by topic as a practical reference.

## 内容导航 | Contents

| 模块 | 说明 |
|---|---|
| [`notes/learning-roadmap`](notes/learning-roadmap/) | 大模型基础、微调、推理、多模态与项目路线学习笔记。 / LLM fundamentals, fine-tuning, inference, multimodal learning, and project roadmap. |
| [`notes/agents`](notes/agents/) | Agent 框架与核心设计笔记。 / Notes on agent frameworks and core design. |
| [`notes/openclaw`](notes/openclaw/) | OpenClaw 学习资料。 / OpenClaw learning materials. |
| [`notes/rag`](notes/rag/) | RAG、混合检索、GraphRAG 与烹饪问答方案笔记。 / RAG, hybrid retrieval, GraphRAG, and a cooking QA design note. |
| [`examples/legal-rag`](examples/legal-rag/) | Ollama、Chroma 与 Streamlit 的本地 PDF 问答实验代码。 / Local PDF QA experiment using Ollama, Chroma, and Streamlit. |
| [`examples/image-generation`](examples/image-generation/) | Ark 图片生成页面与轻量服务实验。 / An Ark image-generation page and lightweight service experiment. |
| [`case-notes/wdf101`](case-notes/wdf101/) | Azure DevOps Story 审计流程案例笔记。 / Case notes for an Azure DevOps Story audit workflow. |
| [`ARCHIVE_SOURCES.md`](ARCHIVE_SOURCES.md) | 来源仓库、保留的 Git 历史与整理说明。 / Source repositories, preserved Git history, and curation notes. |

## 使用说明 | How to use

这是学习与实验资料集合，包含设计笔记、方案描述和未统一验证的原型代码。文档中的架构与运行步骤反映原始资料；在实际部署前，请先核对依赖版本、服务配置、模型可用性及数据来源。此仓库不构成法律建议。

This is a collection of learning materials and experiments, including design notes, proposed approaches, and prototype code that has not been uniformly validated. Architecture descriptions and run instructions reflect the original materials; verify dependencies, service configuration, model availability, and data provenance before deployment. Nothing here constitutes legal advice.

## 安全与数据说明 | Security & data

- 不要提交真实 API Key、访问令牌、生产配置或私人数据；使用环境变量和本地 `.env` 文件，并确保 `.env` 不进入 Git。
- 图片生成示例保留为学习原型。浏览器端代码无法保护嵌入其中的服务密钥；真实应用应由服务端代理持有密钥。
- 法律 PDF 样本未纳入公开整理版。原实验使用者应自行确认文档授权、适用范围和更新状态。
- 数据集文件未纳入本次公开整理版；请在确认来源与许可后再单独加入。

- Do not commit real API keys, access tokens, production configuration, or private data. Use environment variables and local `.env` files, and keep `.env` out of Git.
- The image-generation example remains a learning prototype. Browser code cannot protect a service key embedded in it; a real application should keep the key behind a server-side proxy.
- Legal PDF samples are omitted from this public edition. Users of the original experiment must verify document rights, applicability, and currency.
- Dataset files are omitted from this public edition; add them only after confirming provenance and license.

## 语言 | Language

部分原始笔记只有中文，部分材料提供中英文版本。目录说明与本首页提供中英文对照；翻译或补充时请保留技术含义，并明确标记实验结论与未验证内容。

Some source notes are Chinese-only, while others are bilingual. This index and the landing page are provided in Chinese and English. Preserve technical meaning when translating or extending materials, and label experimental conclusions and unverified claims clearly.
