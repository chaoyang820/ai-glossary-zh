# AI 行业中英词典

为英语基础较弱的 AI 从业者整理的中文速查手册，重点覆盖 2025–2026 年高频概念。每个词条均包含英文、中文和实际作用；中文译法以易懂为先，工作交流建议保留英文原词。

> 更新日期：2026-10-26。当前收录 215 个词条，并持续更新。

## 分类目录

| 分类 | 内容 | 文件 |
|---|---|---|
| 01 基础概念 | token、inference、模态、训练等 | [基础概念](docs/01-AI基础概念.md) |
| 02 模型与推理 | reasoning、MoE、蒸馏、量化等 | [模型与推理](docs/02-模型与推理.md) |
| 03 上下文、记忆与知识 | memory、RAG、context engineering 等 | [上下文与知识](docs/03-上下文记忆与知识.md) |
| 04 Agent 与协议 | agent、MCP、A2A、skills、tools 等 | [Agent 与协议](docs/04-Agent与协议.md) |
| 05 AI 开发工程 | API、structured outputs、workflow 等 | [AI 开发](docs/05-AI开发工程.md) |
| 06 AI 编程与工具 | vibe coding、coding agent、IDE/CLI 工具等 | [AI 编程与工具](docs/06-AI编程与工具.md) |
| 07 评测与可观测性 | evals、grader、trace、benchmark 等 | [评测与可观测性](docs/07-评测与可观测性.md) |
| 08 安全与治理 | prompt injection、guardrails、HITL 等 | [安全与治理](docs/08-安全与治理.md) |
| 09 部署、性能与成本 | serving、latency、caching、GPU 等 | [部署与性能](docs/09-部署性能与成本.md) |
| 10 生成式媒体 | 图像、视频、语音相关概念 | [生成式媒体](docs/10-生成式媒体.md) |

## 推荐学习路线

1. 新手先读 01、02，理解模型如何处理输入和产生输出。
2. 做知识库或企业应用，重点读 03、05。
3. 做智能体，重点读 04，再补 07、08。
4. 使用 AI 写代码，直接读 06，再回头学习 03、04。
5. 上生产环境前，务必掌握 07、08、09。

## 快速理解几个容易混淆的词

- **Prompt engineering** 关注“怎么写指令”；**context engineering** 关注“模型此刻能看到的全部信息如何组织”。
- **MCP** 解决智能体如何连接工具和数据；**A2A** 解决不同智能体如何彼此通信。
- **RAG** 在回答前检索资料；**memory** 保存跨轮次或跨会话仍有价值的状态。
- **Copilot** 通常是人主导、AI 辅助；**agent** 能在授权范围内自主执行多步任务。
- **Vibe coding** 重速度和自然语言驱动；**spec-driven development** 重规格、验证和可维护性。

## 主要参考

- [Model Context Protocol 官方规范](https://github.com/modelcontextprotocol/modelcontextprotocol)
- [Agent2Agent 官方项目](https://github.com/a2aproject)
- [Agent Skills 规范](https://github.com/agentskills/agentskills/blob/main/docs/specification.mdx)
- [GitHub：Spec-driven development with AI](https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/)
- [Anthropic：Context engineering for AI agents](https://www.anthropic.com/research/effective-context-engineering-for-ai-agents)
- [OpenAI：New tools for building agents](https://openai.com/index/new-tools-for-building-agents/)

## 贡献与许可

欢迎通过 Issue 或 Pull Request 补充新词、修正解释。本项目采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可。
