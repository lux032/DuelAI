# DuelAI

## 中文说明

一个简单的 AI 辩论小工具：接入 API 后，让 AI-A 与 AI-B 围绕同一议题进行观点生成、矛盾判定与多回合辩论，最后由裁判模型给出总结。

### 功能

- 支持 AI-A / AI-B / 裁判 三角色独立配置
- 支持 OpenAI 兼容接口与 Claude 接口
- 支持在线拉取模型列表
- 自动判定双方观点是否存在矛盾
- 多回合攻防辩论
- 裁判最终总结
- 一键导出辩论文本

### 使用

1. 打开 `index.html`
2. 分别填写 AI-A、AI-B、裁判的 API Key
3. 选择模型并输入议题
4. 点击“开始”

### 页面预览

![DuelAI Preview](./index.png)

---

## English

A lightweight AI debate playground: connect APIs, let AI-A and AI-B generate initial views, have a judge model detect conflicts, run multi-round rebuttals, and produce a final summary.

### Features

- Independent configuration for AI-A / AI-B / Judge
- Supports OpenAI-compatible APIs and Claude APIs
- Fetch model lists online
- Automatic conflict detection between initial views
- Multi-round debate flow
- Final judge summary
- One-click export of debate transcript

### Usage

1. Open `index.html`
2. Fill API keys for AI-A, AI-B, and Judge
3. Select models and enter a topic
4. Click "Start"
