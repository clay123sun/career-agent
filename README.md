# 星策 · 职业生涯规划 AI Agent

一套开箱即用的职业生涯规划智能体，包含网页端、本地服务端、微信小程序与公众号 H5 四部分。

## 下载

点击右侧 **Releases → v1.0 → `career-agent.zip`** 下载完整打包（含字体、示例图等全部二进制资源，解压即用）。

或直接访问下载直链：
https://github.com/clay123sun/career-agent/releases/download/v1.0/career-agent.zip

## 目录内容

| 文件 / 目录 | 说明 |
|---|---|
| `index.html` | 网页端主程序（含 PDF 解析 pdf.js） |
| `server.js` | 本地服务端（Node.js） |
| `prompts.js` | 智能体提示词配置 |
| `assets/` | 静态资源 |
| `miniprogram/` | 微信小程序源码 |
| `部署指南_小程序与公众号H5.md` | 小程序与公众号 H5 部署说明 |
| `启动星策.command` | macOS 一键启动脚本 |

## 快速开始

1. 下载并解压 `career-agent.zip`。
2. 安装 Node.js 18+。
3. 进入解压目录执行：
   ```bash
   npm install
   node server.js
   ```
4. 浏览器打开提示地址（默认 `http://localhost:3000`）。macOS 也可直接双击 `启动星策.command`。

## 部署说明

- 微信小程序 / 公众号 H5 部署见 `部署指南_小程序与公众号H5.md`。
- 二次开发：提示词在 `prompts.js`、业务逻辑在 `server.js`。
