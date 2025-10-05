# 💬 Vite-React-Socket.io-JWT 即时聊天 Demo

> 🥰一个极简却功能齐全的**单页即时聊天应用**，演示了如何用  
> **Vite + React + TypeScript + Tailwind CSS** 做前端，  
> **Node.js + Express + Socket.IO** 做后端，  
> 并通过 **JWT** 完成登录鉴权与双人在线单聊。

---

## ✨ 功能一览

| 功能 | 状态 |
|---|---|
| 🔐 用户名 + JWT 登录 | ☐


---

## 🏁 一键体验

### 1️⃣ 克隆 & 安装

```bash
git clone https://github.com/Jorryscat/chat-app.git
cd chat-app

# 同时装前端 + 后端依赖（monorepo 脚本）
npm i
```

### 2️⃣ 启动后端（WebSocket 服务）

```bash
npm run server
# 默认监听 http://localhost:3001
```

### 3️⃣ 启动前端（Vite 热更新）

```bash
npm run dev
# 默认打开 http://localhost:5173
```

### 4️⃣ 开两个浏览器窗口
- 都用 **user1 / password** 和 **user2 / password** 登录  
- 互相点击头像即可开始实时对话！

---

## 📁 项目结构速览

```
chat-app
├─ server/                 # Express + Socket.IO 后端
│  ├─ index.js             # 入口：JWT 校验、Socket 事件
│  └─ utils/jwt.js         # 生成 & 验证 Token
├─ src/
│  ├─ components/          # React 组件（登录、好友列表、聊天窗）
│  ├─ hooks/               # 自定义 hooks（useSocket、useAuth、useChat）
│  ├─ utils/               # localStorage 助手、JWT 前端工具
│  ├─ types/               # TypeScript 类型定义
│  └─ App.tsx              # 路由 & 全局状态
├─ package.json            # 前端脚本
└─ README.md               # 你正在看的文档
```

---

## 🔧 技术栈

| 分类 | 技术 |
|---|---|
| 前端构建 | Vite 5 |
| 前端框架 | React 18 + TypeScript |
| 样式 | Tailwind CSS 3 |
| 状态管理 | React Context + 自定义 Hooks |
| 实时通信 | Socket.IO Client |
| 后端 | Node.js 20 + Express 4 |
| 鉴权 | JWT（jsonwebtoken） |
| 存储 | 内存（演示用，可无缝替换为 MongoDB/PostgreSQL） |

---

## 🧪 测试账号



---


## 🚀 部署小贴士


---

## 📌 已知限制 / TODO

- 暂无

---

## 🤝 贡献

欢迎提 Issue / PR！  
如需添加「群组聊天」、「消息漫游」、「WebRTC 音视频」等功能，请留言交流。

---

## 📄 License

MIT © 2025 yourname  
随意拿去当面试作品、课程设计或二次开发！