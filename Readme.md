# DuelAI

## 中文说明

一个简单的 AI 辩论小工具：接入 API 后，让 AI-A 与 AI-B 围绕同一议题进行观点生成、矛盾判定与多回合辩论，最后由裁判模型给出总结。

### 功能

- 支持 AI-A / AI-B / 裁判 三角色独立配置
- 支持 OpenAI 兼容接口与 Claude 接口
- 支持在线拉取模型列表，也支持手动填写模型名称
- 支持可选 Tavily 联网搜索（仅用于首次观点生成，且由 AI 自主决定是否搜索及搜索词）
- 自动注入当前系统时间上下文，减少“今天/今年/最近”时间理解偏差
- 自动判定双方观点是否存在矛盾
- 多回合攻防辩论
- 裁判最终总结
- 一键导出辩论文本

### 使用

1. 打开 `index.html`
2. 分别填写 AI-A、AI-B、裁判的 API Key
3. 选择或手动填写模型，并输入议题
4. （可选）填写 Tavily API Key，用于首次观点生成时联网参考
5. 点击“开始”

### 页面预览

![DuelAI Preview](./index.png)

---

## English

A lightweight AI debate playground: connect APIs, let AI-A and AI-B generate initial views, have a judge model detect conflicts, run multi-round rebuttals, and produce a final summary.

### Features

- Independent configuration for AI-A / AI-B / Judge
- Supports OpenAI-compatible APIs and Claude APIs
- Fetch model lists online, with manual model name input fallback
- Optional Tavily web search (used only for the initial view generation, with AI deciding whether and what to search)
- Injects current system-time context to reduce ambiguity for terms like "today/this year/recent"
- Automatic conflict detection between initial views
- Multi-round debate flow
- Final judge summary
- One-click export of debate transcript

### Usage

1. Open `index.html`
2. Fill API keys for AI-A, AI-B, and Judge
3. Select or manually enter models, then enter a topic
4. (Optional) Fill Tavily API Key for web references in initial views
5. Click "Start"
