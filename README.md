# NGINX Link

Nginx 可视化远程管理面板：通过 SSH/SFTP 统一管理多台服务器的站点、证书、配置与文件，被管服务器无需安装任何组件。

本仓库仅发布编译好的二进制，**不提供源代码**。

## 下载

在 [Releases](../../releases) 页面下载对应平台的压缩包：

| 文件 | 平台 | 说明 |
| --- | --- | --- |
| `nginxlink-vX.Y.Z-darwin-arm64-gui.tar.gz` | macOS（Apple 芯片） | 图形界面版，菜单栏托盘 |
| `nginxlink-vX.Y.Z-linux-amd64.tar.gz` | Linux 服务器（x86_64） | 普通版，命令行运行 |
| `nginxlink-vX.Y.Z-windows-amd64-gui.zip` | Windows | 图形界面版，系统托盘 |

## 快速开始

解压后直接运行可执行文件，默认监听 8080 端口：

```bash
./nginxlink      # Linux / macOS
nginxlink.exe    # Windows
```

浏览器访问 http://127.0.0.1:8080 ，首次登录默认账号 admin / admin，登录后请立即修改密码。
