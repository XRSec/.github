<div align="center">

# XRSec · 星冉安全与智能体实验室

**低调求发展，潜心习安全 · Local-First AI Agents · Cross-Platform Infrastructure · Device & Security Engineering**

[![Owner](https://img.shields.io/badge/Maintainer-Ran--Xing-da282a?style=flat-square&logo=github)](https://github.com/Ran-Xing)
![Focus](https://img.shields.io/badge/Focus-AI%20Agents%20%26%20Security-0f172a?style=flat-square)
[![Email](https://img.shields.io/badge/Email-Jalapeno1868%40outlook.com-da282a?style=flat-square&logo=minutemailer&logoColor=white)](mailto:Jalapeno1868@outlook.com)
[![Blog](https://img.shields.io/badge/Blog-xrsec.vercel.app-da282a?style=flat-square&logo=vercel)](https://xrsec.vercel.app)

</div>

---

### 🧭 关于 XRSec (Overview)

**XRSec** 是由 [@Ran-Xing (星冉)](https://github.com/Ran-Xing) 主导的开源研发组织。从早期的**网络空间安全、攻防研究与苹果/安卓底层设备运维**起步，现已全面演进为聚焦 **AI Coding Agent 基础设施、MCP (Model Context Protocol) 桥接、LLM 高性能网关与跨平台原生桌面/移动控制** 的工程实验室。

---

### 🚀 核心开源矩阵 (Featured Projects)

#### 🤖 AI Agent 基础设施与上下文工程 (AI Agents & Context Engineering)
| 项目 | 技术栈 | 核心能力 |
| :--- | :--- | :--- |
| [**Yance**](https://github.com/XRSec/Yance) `★12` | `Swift` `MCP` | **Local-First 个人关系与通信 AI 大脑** — 多平台身份图谱、关系记忆、回复策略与受控自动回复 |
| [**AI-Agent-Launcher**](https://github.com/XRSec/AI-Agent-Launcher) | `Tauri v2` `Vue 3` `Rust` | **跨平台 AI Agent 与本地服务进程管理器** — 支持守护进程常驻、重启策略编排与状态监控 (macOS · Windows · Linux) |
| [**Aura**](https://github.com/XRSec/Aura) | `Rust` `MCP` | **安全桌面 MCP 桥接器** — 将 AI 助手安全连接至本机文件、Shell、Skills、Pi Tools、OAuth 与多隧道穿透 |
| [**antigravity-gemini-gateway**](https://github.com/XRSec/antigravity-gemini-gateway) | `Go` | **高性能 Gemini REST 网关** — 面向 Antigravity OAuth，支持 Session Sticky 粘性调度保障 Prompt Caching、代理池隔离与 Web UI |
| [**pi-prompt-diet**](https://github.com/XRSec/pi-prompt-diet) `★5` | `TypeScript` | **Pi Coding Agent 系统提示词瘦身器** — 在保持全量工具完好可用的前提下，削减 60%+ 基线 Token 开销 |
| [**pi-session-distill**](https://github.com/XRSec/pi-session-distill) | `TypeScript` | **Pi 会话状态交接与蒸馏工具** — 支持 Agent State Handoff 清理、合并、校验与可重复压缩 |
| [**paseo-session-ids**](https://github.com/XRSec/paseo-session-ids) | `TypeScript` | **跨 CLI 会话标识透视插件** — 一键查看并复制 Paseo ID 与底层 CLI Session ID（兼容 `agy`、`claude`、`pi`、`codex`） |

#### 📱 跨端远控、网络隧道与底层硬件 (Device Control & Network Infra)
| 项目 | 技术栈 | 核心能力 |
| :--- | :--- | :--- |
| [**Screen-Remote**](https://github.com/XRSec/Screen-Remote) `★206` | `JavaScript` | **移动端 Scrcpy 跨设备远控** — 将 scrcpy 移植至移动平台，实现在 Android 手机上远程低延迟控制其他 Android 设备 |
| [**DFU-Tools**](https://github.com/XRSec/DFU-Tools) `★53` | `Swift` | **Apple 设备底层维护桌面工具** — 辅助 Apple Silicon、T2 芯片 Mac 及 iPhone/iPad 进行 DFU 引导、重启、恢复与修复 |
| [**TunnelFlow**](https://github.com/XRSec/TunnelFlow) `★8` | `TypeScript` | **下一代跨平台 SSH 隧道与端口转发管理器** — 面向 macOS、Windows 与 Linux 的可视化链路编排工具 |
| [**wifi-adb**](https://github.com/XRSec/wifi-adb) `★3` | `Kotlin` | **独立无线 ADB 调试工具** — 兼容 Android 4.4+ (`minSdk 19`)，支持无线调试、Wi-Fi 状态监控、双语 UI 与无障碍自动授权 |
| [**adbd-auth-gateway**](https://github.com/XRSec/adbd-auth-gateway) | `Rust` | **Rust ADB TCP 认证网关** — 提供带鉴权的设备 Shell 接入、密码自动注入与兼容 scrcpy 的多设备路由转发 |

#### 🛡️ 安全工程与系统效能工具 (Security & System Utilities)
| 项目 | 技术栈 | 核心能力 |
| :--- | :--- | :--- |
| [**AWVS-Update**](https://github.com/XRSec/AWVS-Update) `★226` / [**AWVS-Docker**](https://github.com/XRSec/AWVS-Docker) | `Docker` | **安全扫描器容器化维护与规则更新套件** — 自动化镜像构建与引擎维护 |
| [**SAFE_DELETE**](https://github.com/XRSec/SAFE_DELETE) `★3` | `Rust` | **防误删安全回收工具** — 替代高危直接删除操作，保障Agent与终端环境下的文件安全 |
| [**SKIP-MDM**](https://github.com/XRSec/SKIP-MDM) `★3` | `HTML` `Shell` | **macOS 设备管理与激活绕过辅助方案** — 面向个人设备维护的 MDM / DEP 辅助脚本 |
| [**AUDCH**](https://github.com/XRSec/AUDCH) `★4` / [**cloudflare-email-manager**](https://github.com/XRSec/cloudflare-email-manager) | `Go` `TS` | **容器自动更新编排与 Cloudflare 域名临时邮箱管理** — 轻量级自托管运维套件 |

---

### 🛠️ 技术栈图谱 (Tech Stack)

- **Systems & Native**: `Rust` · `Go` · `Swift (macOS)` · `Kotlin (Android)` · `Tauri v2`
- **AI & Agent Stack**: `MCP (Model Context Protocol)` · `Claude Code` · `Pi Coding Agent` · `Antigravity (agy)` · `Codex` · `Prompt Caching & Gateway`
- **Web & Serverless**: `TypeScript` · `Vue 3` · `Node.js` · `Cloudflare Workers` · `Docker`

---

<div align="center">
  <sub>Built with rigor by <a href="https://github.com/Ran-Xing">@Ran-Xing</a> · Security-Minded, Agent-Native.</sub>
</div>
