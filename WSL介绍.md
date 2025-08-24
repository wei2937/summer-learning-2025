# WSL 是什么？

WSL（Windows Subsystem for Linux）是一个让你在 Windows 系统里运行 Linux 环境的工具，让你不用安装双系统或虚拟机，就能使用 Linux 的命令、软件和开发环境。

## 一、WSL 的核心功能

1. **运行 Linux 命令行**  
   直接在 Windows 上打开终端（如 Ubuntu、Debian），运行各种 Linux 命令，操作体验如同在真实的 Linux 系统中。

2. **安装多个 Linux 发行版**  
   支持从 Microsoft Store 一键安装多种 Linux 系统。

3. **与 Windows 文件系统无缝交互**  
   - 在 Linux 中访问 Windows 文件  
   - 在 Windows 中打开 Linux 文件夹  
   开发过程中可轻松共享文件。

4. **支持原生 Linux 软件和工具链**  
   WSL2（第二代）支持运行原生 Linux 程序，包括：  
   - C/C++ 编译器（gcc/g++）  
   - Python、Node.js、Ruby 等开发环境  
   - 包管理器（apt、pip、npm 等）  
   - AI/机器学习框架（如 PyTorch、TensorFlow）

6. **网络功能强大**  
   - 在 WSL 中启动 Web 服务（如 Flask、Node.js 项目）  
   - 通过 `localhost:端口号` 在浏览器直接访问  
    无需像虚拟机一样配置复杂网络。

7. **启动速度快、性能高**  
   - 启动时间短于 1 秒  
   - 比虚拟机占用资源更少，无需单独分配内存和硬盘空间。

8. **快照和持久存储**  
   - 文件和配置持久化，关机/重启不丢失  
   - 可自定义开发环境并长期使用项目代码。

---

### 优势总结
不用离开 Windows 也能享受 Linux 命令行和工具，轻松实现代码编写、调试和部署，将 Windows 机器变身为“开发神器”。
# 安装配置
启动Windows Subsystem for Linux
通过控制面板
打开屏幕左下角“Cortana搜索框”输入“control panel”搜索并打开搜索结果中的“控制面板”
!(E:\图片\1.png)

找到启用或关闭Windows功能，如图所示，打开“程序”——“启用或关闭Windows功能”，找到并勾选“适用于Linux的Windows子系统”，点击“确定”。
!(E:\图片\2.png)


安装完成后重启电脑~

## 通过应用商店安装Linux发行版
打开Win10应用商店搜索你喜欢的Linux发行版并安装。目前，WSL支持Ubuntu，Kali Linux，GNU，OpenSUSE等发行版。通过应用商店安装的Linux发行版只支持安装在C盘！

以安装Ubuntu为例，安装完成后搜索并打开Ubuntu执行后续安装。
!(E:\图片\3.png)
!(E:\图片\4.png)

安装完成后按提示输入默认用户名、密码。
!(E:\图片\5.png)

全部完成！今后我们可以通过Ubuntu应用打开一个WSL的Ubuntu命令行窗口。Enjoy!
