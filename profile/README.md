# XRSec

Open-source tools maintained by [@Ran-Xing](https://github.com/Ran-Xing). Most of these started as small fixes for my own workflow: managing Android test phones without a laptop, wrapping Apple DFU commands in a UI, and keeping local coding agents from burning through tokens or leaving stray processes behind.

If you're looking for something specific, here is what lives here:

### Device & Network Utilities

- [**Screen-Remote**](https://github.com/XRSec/Screen-Remote): `scrcpy` ported to Android so you can control one Android phone from another over USB, TCP, or wireless ADB without a PC.
- [**wifi-adb**](https://github.com/XRSec/wifi-adb): Standalone wireless ADB app for Android 4.4+ (`minSdk 19`) with Wi-Fi state checks and optional accessibility auto-approval.
- [**adbd-auth-gateway**](https://github.com/XRSec/adbd-auth-gateway): Small Rust TCP gateway in front of ADB when you need authenticated shell access or multi-device routing for `scrcpy`.
- [**DFU-Tools**](https://github.com/XRSec/DFU-Tools): macOS Swift wrapper around Apple Configurator to reboot, revive, or restore Apple Silicon Macs, T2 Macs, and iOS devices without typing CLI flags.
- [**TunnelFlow**](https://github.com/XRSec/TunnelFlow): Desktop SSH tunnel manager (`-L`, `-R`, `-D`) built with Tauri v2 for macOS, Windows, and Linux, with tray controls and auto-reconnect.

### Local AI & Coding Agent Tooling

- [**Aura**](https://github.com/XRSec/Aura): Lightweight (~4 MB) Tauri + Rust desktop MCP bridge that exposes local files, shell access, and Skills to MCP clients with per-tool permission boundaries and built-in tunneling.
- [**AI-Agent-Launcher**](https://github.com/XRSec/AI-Agent-Launcher): Tauri v2 + Vue 3 process manager for local coding agents and dev services, built to stop orphaned background processes and `PATH` mismatches outside a terminal.
- [**antigravity-gemini-gateway**](https://github.com/XRSec/antigravity-gemini-gateway): Go proxy exposing standard Gemini `v1beta` endpoints over Antigravity OAuth accounts, with sticky sessions for prompt caching, 429/503 failover, and per-account proxies.
- [**pi-prompt-diet**](https://github.com/XRSec/pi-prompt-diet): Extension for Pi Coding Agent that trims baseline system prompt bloat, protects KV prompt cache, and stops the model from editing files when you only asked a question.
- [**pi-session-distill**](https://github.com/XRSec/pi-session-distill) & [**paseo-session-ids**](https://github.com/XRSec/paseo-session-ids): Small utilities for compacting Pi session handoffs and copying session IDs across `agy`, `claude`, `pi`, and `codex`.
- [**Yance**](https://github.com/XRSec/Yance) *(prototype)*: Local-first MCP project for keeping context across messaging accounts and drafting replies for human review before anything gets sent.

### System & Security Odds and Ends

- [**SAFE_DELETE**](https://github.com/XRSec/SAFE_DELETE): Rust `rmf` CLI that moves files to the OS Trash / Recycle Bin instead of deleting them permanently.
- [**Glimpse**](https://github.com/XRSec/Glimpse): macOS desktop UI automation script runner built with Tauri 2 and Vue 3.
- [**AWVS-Update**](https://github.com/XRSec/AWVS-Update) & [**AWVS-Docker**](https://github.com/XRSec/AWVS-Docker): Docker setups and rule-update scripts for running AWVS in containers.
- [**SKIP-MDM**](https://github.com/XRSec/SKIP-MDM): Helper scripts for skipping MDM / DEP enrollment on personal macOS machines.
- [**AUDCH**](https://github.com/XRSec/AUDCH) & [**cloudflare-email-manager**](https://github.com/XRSec/cloudflare-email-manager): Go Docker container auto-updater and a small Cloudflare Workers manager for temporary domain emails.

---

Questions, bug reports, and PRs are welcome in the individual repos. You can also reach me at [Jalapeno1868@outlook.com](mailto:Jalapeno1868@outlook.com) or check out occasional notes at [blog.xrsec.fun](https://blog.xrsec.fun).
