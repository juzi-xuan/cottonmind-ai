# 🌱 CottonMind

> AI Product Team for Baby & Maternity Cotton Products

CottonMind 是一个面向母婴棉品行业的 AI 数字产品团队，由多个 AI Agent 协作完成新品孵化流程。

## ✨ 功能特性

- 🔍 **消费者洞察** - 分析用户评论，发现痛点，总结消费趋势
- 🎯 **产品设计** - 根据洞察设计新品方案
- 📝 **营销内容** - 生成小红书、抖音、电商等多平台内容
- 📈 **增长分析** - 分析数据，提出优化建议和增长策略

## 🚀 快速开始

### 环境要求

- Python 3.10+
- OpenAI API Key / 其他LLM API
- Dify Account

### 安装步骤

```bash
git clone https://github.com/xxx/cottonmind-ai.git
cd cottonmind-ai
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
# 编辑 .env 文件
```

## 🏗️ 技术栈

- Python 3.10+
- Dify Workflow
- LangChain (RAG)
- Streamlit (Web Demo)
- Chroma (向量数据库)

## 📁 项目结构

```
cottonmind-ai/
├── .github/workflows/   # CI/CD配置
├── data/                # 知识库数据
│   ├── brand/           # 品牌资料
│   ├── industry/        # 行业报告
│   ├── reviews/         # 用户评论
│   └── competitors/     # 竞品分析
├── dify/                # Dify Workflow配置
│   └── agent_prompts/   # Agent Prompt模板
├── docs/                # 项目文档
├── src/
│   ├── cottonmind/      # 核心代码
│   └── demo/            # Streamlit Demo
└── tests/               # 测试模块
```

## 📄 License

MIT License
