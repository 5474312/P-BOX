<div align="center">

# 🚀 P-BOX

**Enterprise-Grade Proxy Management & Network Toolkit**

**企业级代理管理与网络工具箱**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Go](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go)](https://go.dev)
[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)](https://typescriptlang.org)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows-lightgrey)]()

<img src="frontend/public/p-box-logo.png" width="140" alt="P-BOX Logo">

<br/>

[English](#-features) | [中文](#-功能特性)

</div>

---

<div align="center">

## 💖 Support This Project / 支持本项目

**If P-BOX has been helpful to you, please consider supporting continued development!**

**如果 P-BOX 对您有帮助，请考虑支持持续开发！**

<br/>

### 🎁 Donate / 捐赠

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/XLayer-OKX_Layer_2-000000?style=for-the-badge&logo=okx" alt="XLayer"/>
<br/><br/>

```
0xf628bc88a210b436512349ca1b09bcb2d020f5e1
```

<sub>👆 Click to copy | 点击复制</sub>
</td>
</tr>
</table>

<br/>

> 🙏 **Thank you to all our generous supporters!** Your donations help cover server costs, development time, and keep P-BOX free and open source. Every contribution, big or small, makes a difference!
>
> 🙏 **感谢所有慷慨的支持者！** 您的捐赠帮助支付服务器成本、开发时间，并保持 P-BOX 免费开源。每一份贡献，无论大小，都意义非凡！

<br/>

---

</div>

## ✨ Features

<details open>
<summary><b>🔥 Proxy Core Management</b></summary>

- **Dual Core Support** - Sing-box (with 26 P-BOX exclusive mods) + Mihomo (Clash.Meta)
- **Dynamic Inbound** - Add/remove local services at runtime without restart
- **Node Management** - CRUD, latency test, speed test, health check, smart replacement
- **Subscription Manager** - Multi-source, auto-update, deduplication, UA config
- **Proxy Groups** - Load balance, failover, URL test, auto/manual select
- **Proxy Chain** - Multi-hop proxy chain configuration
- **Traffic Routing** - 13 rule types, process/UID filtering, smart GeoIP mode

</details>

<details>
<summary><b>🌐 DNS & Network</b></summary>

- **Advanced DNS** - DoH/DoT, FakeIP, DNS cache, leak detection
- **DNS Diagnostics** - Query test, flow visualization, cache management
- **DNS Enhancements** - Concurrent racing, fallback filter, singleflight, lazy cache, pipeline
- **DDNS** - Cloudflare, AliDNS, DNSPod support
- **Ping Tool** - ICMP ping with streaming output
- **Port Scanner** - TCP/UDP scan with WebSocket real-time output
- **IP Lookup** - GeoIP query with IP2Region
- **Website Checker** - HTTP/HTTPS connectivity test
- **Speed Test** - Multi-threaded node speed test

</details>

<details>
<summary><b>☁️ Cloudflare Integration</b></summary>

- **IP Optimizer** - IPv4/IPv6 scanning, DC mapping, segment collection
- **Worker Manager** - Deploy, update, env vars, KV storage, routing
- **WARP Manager** - WARP+ registration, config generation, Zero Trust
- **Account Manager** - Multi-account switching, API token management
- **ECH Deployment** - Encrypted Client Hello configuration

</details>

<details>
<summary><b>🖥️ Virtualization (VM)</b></summary>

- **VM Management** - libvirt/QEMU/KVM, full VM lifecycle, VNC/SPICE console
- **Storage** - Pool management (Dir/LVM/NFS/iSCSI), volume CRUD, ISO library
- **Network** - Virtual networks (NAT/Bridge/Isolated)
- **Templates** - 11 presets (Ubuntu, Debian, CentOS, Windows, OpenWrt...)
- **Enterprise** - Scheduled snapshots, Cloud-init, HA cluster, live migration
- **AI Optimization** - Resource prediction, optimization suggestions, anomaly detection

</details>

<details>
<summary><b>🐳 Docker Management</b></summary>

- **Container** - Full lifecycle, logs, terminal, resource monitoring
- **Image** - Pull, delete, build, list
- **Network & Volume** - Create/delete networks and volumes
- **Compose** - docker-compose file management
- **One-Click Install** - Multi-platform Docker installation

</details>

<details>
<summary><b>🔐 VPN & Security</b></summary>

- **WireGuard** - Config management, key generation, QR sharing
- **IKEv2** - Certificate management, connection handling
- **L2TP** - IPSec configuration, pre-shared key management
- **SSL Certificate** - ACME auto-apply, Let's Encrypt integration
- **Crypto Tools** - Base64, URL encode, MD5/SHA256, AES, JWT, UUID

</details>

<details>
<summary><b>⚙️ System Management</b></summary>

- **System Control** - Reboot, shutdown, update, version management
- **Nginx Manager** - Config, HTTPS, reverse proxy (Linux/macOS/Windows)
- **Network Optimization** - IP forwarding, BBR, system tuning
- **Scheduled Restart** - Cron-based scheduling
- **Monitoring** - CPU, memory, disk, network real-time stats
- **WebSSH** - Terminal, SFTP, batch operations, session recording
- **File Manager** - Browse, upload/download, edit
- **Disk Tools** - Partition, format, mount

</details>

<details>
<summary><b>📊 Dashboard & UI</b></summary>

- **Real-time Stats** - Traffic, DNS, routing, IP info, proxy groups
- **Connection Manager** - Active connections, details, disconnect
- **Log Viewer** - Core logs with filtering and export
- **Themes** - macOS/iOS style, dark/light mode
- **i18n** - Chinese, English, Russian, Urdu

</details>

---

## 🇨🇳 功能特性

<details open>
<summary><b>🔥 代理核心管理</b></summary>

- **双核心支持** - Sing-box（26 项 P-BOX 专属魔改）+ Mihomo (Clash.Meta)
- **动态入站** - 运行时添加/删除本地服务，无需重启核心
- **节点管理** - CRUD、延迟测试、速度测试、健康检查、智能替换
- **订阅管理** - 多源支持、自动更新、节点去重、UA 配置
- **代理组** - 负载均衡、故障转移、URL 测试、自动/手动选择
- **链式代理** - 多级代理链配置
- **流量分流** - 13 种规则类型、进程/UID 过滤、智能 GeoIP 模式

</details>

<details>
<summary><b>🌐 DNS 与网络</b></summary>

- **高级 DNS** - DoH/DoT、FakeIP、DNS 缓存、泄漏检测
- **DNS 诊断中心** - 查询测试、流向可视化、缓存管理
- **DNS 增强** - 并发竞速、Fallback 过滤、Singleflight、懒缓存、Pipeline
- **DDNS** - Cloudflare、阿里云、腾讯云支持
- **Ping 工具** - ICMP ping 流式输出
- **端口扫描** - TCP/UDP 扫描 WebSocket 实时输出
- **IP 查询** - GeoIP 查询 + IP2Region
- **网站检测** - HTTP/HTTPS 连通性测试
- **速度测试** - 多线程节点测速

</details>

<details>
<summary><b>☁️ Cloudflare 集成</b></summary>

- **IP 优选** - IPv4/IPv6 扫描、DC 映射、IP 段收藏
- **Worker 管理** - 部署、更新、环境变量、KV 存储、路由
- **WARP 管理** - WARP+ 注册、配置生成、Zero Trust
- **账户管理** - 多账户切换、API Token 管理
- **ECH 部署** - Encrypted Client Hello 配置

</details>

<details>
<summary><b>🖥️ 虚拟化 (VM)</b></summary>

- **虚拟机管理** - libvirt/QEMU/KVM、完整生命周期、VNC/SPICE 控制台
- **存储管理** - 存储池（目录/LVM/NFS/iSCSI）、卷管理、ISO 镜像库
- **网络管理** - 虚拟网络（NAT/桥接/隔离）
- **模板系统** - 11 个预设（Ubuntu、Debian、CentOS、Windows、OpenWrt...）
- **企业级功能** - 计划快照、Cloud-init、高可用集群、实时迁移
- **AI 智能调优** - 资源预测、优化建议、异常检测

</details>

<details>
<summary><b>🐳 Docker 管理</b></summary>

- **容器管理** - 完整生命周期、日志、终端、资源监控
- **镜像管理** - 拉取、删除、构建、列表
- **网络与卷** - 创建/删除网络和卷
- **Compose** - docker-compose 文件管理
- **一键安装** - 多平台 Docker 安装

</details>

<details>
<summary><b>🔐 VPN 与安全</b></summary>

- **WireGuard** - 配置管理、密钥生成、二维码分享
- **IKEv2** - 证书管理、连接处理
- **L2TP** - IPSec 配置、预共享密钥管理
- **SSL 证书** - ACME 自动申请、Let's Encrypt 集成
- **加密工具** - Base64、URL 编码、MD5/SHA256、AES、JWT、UUID

</details>

<details>
<summary><b>⚙️ 系统管理</b></summary>

- **系统控制** - 重启、关机、更新、版本管理
- **Nginx 管理** - 配置、HTTPS、反向代理（Linux/macOS/Windows）
- **网络优化** - IP 转发、BBR、系统调优
- **定时重启** - Cron 调度
- **系统监控** - CPU、内存、磁盘、网络实时统计
- **WebSSH** - 终端、SFTP、批量操作、会话录制
- **文件管理** - 浏览、上传/下载、编辑
- **磁盘工具** - 分区、格式化、挂载

</details>

<details>
<summary><b>📊 仪表盘与 UI</b></summary>

- **实时统计** - 流量、DNS、路由、IP 信息、代理组
- **连接管理** - 活跃连接、详情、断开
- **日志查看** - 核心日志筛选与导出
- **主题系统** - macOS/iOS 风格、深色/浅色模式
- **国际化** - 中文、英文、俄语、乌尔都语

</details>

---

## 📸 Screenshots / 截图

<table>
<tr>
<td width="50%">

### Dashboard / 仪表盘
Real-time traffic, DNS stats, routing, system info

实时流量、DNS 统计、路由、系统信息

![Dashboard](https://raw.githubusercontent.com/p-box2025/P-BOX/main/1.png)

</td>
<td width="50%">

### Core Management / 核心管理
Manage Mihomo and Sing-box cores

管理 Mihomo 和 Sing-box 核心

![Core](https://raw.githubusercontent.com/p-box2025/P-BOX/main/2.png)

</td>
</tr>
<tr>
<td width="50%">

### Config / 配置
DNS, routing, rulesets, TLS, TUN settings

DNS、路由、规则集、TLS、TUN 设置

![Config](https://raw.githubusercontent.com/p-box2025/P-BOX/main/3.png)

</td>
<td width="50%">

### Traffic History / 流量历史
Traffic trends, upload/download stats

流量趋势、上传/下载统计

![Traffic](https://raw.githubusercontent.com/p-box2025/P-BOX/main/4.png)

</td>
</tr>
</table>

---

## 🚀 Quick Start / 快速开始

### Linux One-Click Install / Linux 一键安装

```bash
curl -fsSL https://raw.githubusercontent.com/p-box2025/P-BOX/main/install.sh | sudo bash
```

Auto-detects architecture (amd64/arm64), installs to `/etc/p-box`, starts on port **8383**.

自动检测架构（amd64/arm64），安装到 `/etc/p-box`，端口 **8383** 启动。

### Manual Installation / 手动安装

Download from [Releases](../../releases):

| Platform | File |
|:---|:---|
| macOS Apple Silicon | `p-box-darwin-arm64.tar.gz` |
| macOS Intel | `p-box-darwin-amd64.tar.gz` |
| Linux x64 | `p-box-linux-amd64.tar.gz` |
| Linux ARM64 | `p-box-linux-arm64.tar.gz` |
| Windows x64 | `p-box-windows-amd64.zip` |

```bash
tar -xzf p-box-*.tar.gz && cd p-box-* && ./p-box
```

Visit / 访问: http://localhost:8383

---

## 🛠️ Development / 开发

### Prerequisites / 前置要求
- Go 1.21+
- Node.js 18+

### Setup / 设置

```bash
git clone https://github.com/p-box2025/P-BOX.git
cd P-BOX

# Backend
cd backend && go mod tidy && go build -o p-box . && cd ..

# Frontend
cd frontend && npm install && cd ..

# Run
./start-all.sh
```

---

## 📁 Project Structure / 项目结构

```
p-box/
├── backend/          # Go Backend / Go 后端
├── frontend/         # React Frontend / React 前端
├── data/             # Runtime data / 运行时数据
├── build.sh          # Build script / 构建脚本
├── install.sh        # Installer / 安装脚本
└── start-all.sh      # Dev startup / 开发启动
```

---

## 🙏 Acknowledgments / 致谢

- [Sing-box](https://github.com/SagerNet/sing-box) - Universal proxy platform
- [Mihomo](https://github.com/MetaCubeX/mihomo) - High-performance proxy core
- [React](https://react.dev) - Frontend framework
- [Tailwind CSS](https://tailwindcss.com) - CSS framework

---

## 📜 License / 许可证

[MIT License](LICENSE)

---

<div align="center">

## 💖 Support This Project / 支持本项目

**Your support keeps P-BOX free and continuously improving!**

**您的支持让 P-BOX 保持免费并持续改进！**

<br/>

<table>
<tr>
<td align="center">

### 🎁 XLayer (OKX Layer 2)

```
0xf628bc88a210b436512349ca1b09bcb2d020f5e1
```

</td>
</tr>
</table>

<br/>

> 💝 **Every donation matters!** Whether it's a coffee ☕ or more, your generosity helps us:
> - 🖥️ Maintain servers and infrastructure
> - ⏰ Dedicate more time to development
> - 🆓 Keep P-BOX free for everyone
> - 🚀 Add new features and improvements
>
> 💝 **每一份捐赠都很重要！** 无论是一杯咖啡 ☕ 还是更多，您的慷慨帮助我们：
> - 🖥️ 维护服务器和基础设施
> - ⏰ 投入更多时间开发
> - 🆓 让 P-BOX 对所有人免费
> - 🚀 添加新功能和改进

<br/>

**⭐ If you find P-BOX helpful, please give it a Star! ⭐**

**⭐ 如果 P-BOX 对您有帮助，请给个 Star！⭐**

</div>
