## 🛠️ macOS Brew 安装实用工具集

> 使用 [Homebrew](https://brew.sh) 快速安装常用软件，提升 macOS 使用效率。

---

### 🔧 系统增强工具

```sh
# One Switch：菜单栏开关合集，快速切换深色模式、隐藏桌面图标等
brew install --cask one-switch

# Bartender：菜单栏图标管理神器，自定义隐藏与排序
brew install --cask bartender
```

---

### 🐳 替代 Docker Desktop

```sh
# OrbStack：轻量级 macOS 虚拟化容器工具，替代 Docker Desktop
brew install orbstack
```

---

### 💻 SSH 工具推荐

```sh
# Tabby：跨平台终端 + SSH 客户端，界面美观、插件丰富
brew install --cask tabby

# Termius：现代化 SSH 客户端，支持分组和云同步
brew install --cask termius
```

---

### 🧰 效率工具

```sh
# uTools：国产效率神器，插件丰富、启动迅速
brew install --cask utools

# Pixpin：截图 + 注释工具，适合标注说明文档或 UI 反馈
brew install --cask pixpin

# ChatGPT：原生桌面版 ChatGPT 工具，方便随时调用
brew install --cask chatgpt
```

---

### 🧠 开发者工具

```sh
# PyCharm：专业版和社区版 Python IDE
brew install --cask pycharm
brew install --cask pycharm-ce

# Joplin：开源 Markdown 笔记工具，支持加密和多端同步
brew install --cask joplin
```

---

### 🌐 浏览器推荐

```sh
# Chrome 和 Firefox：主流开发/测试浏览器
brew install --cask google-chrome
brew install --cask firefox
```

---

### 📥 下载与压缩工具

```sh
# Downie：视频下载神器，支持 YouTube、Bilibili 等
brew install --cask downie

# 7-Zip：强力压缩/解压工具，适用于多种压缩格式
brew install sevenzip
```

---

### 💡 运行 Windows 应用

```sh
# Crossover：无需虚拟机即可运行大部分 Windows 应用
brew install --cask crossover
```

---

### 🧪 其他工具

```sh
# Opera 浏览器：内置 VPN 和 AI 助手
brew install --cask opera
```

---

如需批量安装，可将命令保存为 `brew-install.sh` 并执行：

```sh
chmod +x brew-install.sh
./brew-install.sh
```
