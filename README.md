# LXC Container Automated Management Script

这是一个用于 Debian/Ubuntu 服务器的 **LXC 容器自动化管理工具**。它集成了环境初始化、NAT 网络配置、资源限制（支持超开）以及交互式管理面板，让你能在几分钟内搭建出一套功能完备的 NAT VPS 系统。

## ✨ 功能特点

- 🚀 **一键部署**: 自动安装 LXD、Nginx、Python 环境，开箱即用
- 🖥️ **交互式面板**: 提供类似宝塔的 CLI 菜单，小白也能轻松管理
- 🛡️ **安全隔离**: 采用 mTLS 双向证书认证，保护你的 API 接口安全
- 🔌 **NAT 网络**: 自动配置网桥与端口转发，容器直通外网
- 🔧 **资源超开**: 支持 CPU/内存/Swap 灵活限制与超售配置

## ⚡ 使用方法 (Root 用户)

直接在终端执行以下命令即可启动管理面板：

```bash
bash <(curl -sL [https://raw.githubusercontent.com/NX2406/LXC-container-automated-management/main/lxc](https://raw.githubusercontent.com/NX2406/LXC-container-automated-management/main/lxc))
```

---
> **提示**: 脚本首次运行时会自动安装必要依赖，请耐心等待。安装完成后将自动进入主菜单。
