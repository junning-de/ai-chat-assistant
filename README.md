# AI Chat Assistant 🤖

一个基于 Node.js + 前端页面的 AI 聊天助手项目，支持调用大模型 API 实现基础对话功能。

## 🚀 功能特点

* 简单聊天界面
* 前后端分离结构
* 支持调用 AI 模型接口
* 可扩展为流式输出、Markdown 渲染等高级功能

## 🛠 技术栈

* 前端：HTML + CSS + JavaScript
* 后端：Node.js + Express
* API：OpenRouter / Gemini / OpenAI（可替换）

## 📁 项目结构

```
├─ public/
│  ├─ index.html
│  ├─ style.css
│  └─ app.js
├─ server.js
├─ package.json
```

## ⚙️ 本地运行

### 1. 克隆项目

```
git clone https://github.com/你的用户名/ai-chat-assistant.git
cd ai-chat-assistant
```

### 2. 安装依赖

```
npm install
```

### 3. 配置环境变量

新建 `.env` 文件：

```
OPENROUTER_API_KEY=你的key
PORT=3000
```

### 4. 启动项目

```
npm start
```

打开浏览器访问：

```
http://localhost:3000
```

## 📌 后续优化方向

* ✅ 流式输出（Streaming）
* ✅ Markdown 渲染
* ✅ 代码高亮
* ✅ 会话历史记录
* ✅ 文件上传（文档问答）

## 👨‍💻 作者

* Your Name
