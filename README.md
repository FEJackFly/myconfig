---
theme: channing-cyan
---

## 软件篇

1. **clash** 懂的都懂
2. **chrome** 前端必备
3. **docker** 有需要的下
4. **OpenVPN** 公司 vpn 连接
5. **OpenInterminal** 快速按路径打开终端编辑器
6. **uTools** 工具神器
7. **Tencent Lemon** 腾讯免费电脑管家 该有的都有
8. **阿里云盘** 不限速
9. **Visual Studio Code**
10. **Blender** 建模软件
11. **Typora** MarkDown 写作工具
12. **WPS** 这个不用介绍了吧
13. **Synergy** 一套键鼠控制多台电脑 插网线更流畅
14. **CheatShee** mac 长安 CMD 显示各个场景快捷键
15. **终端** 看自己喜好 下面详细介绍
    - Hyper
    - Iterm2

## 字体安装

https://www.nerdfonts.com/font-downloads

我喜欢的字体 **Caskaydia** 有连字 有表情 很好看，终端 编辑器都用的上

## 终端配置

### brew 安装

    $/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"$

### zsh 安装

    brew install zsh

### oh my zsh 安装

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### oh my zsh 插件

~/.zshrc 修改 zsh 配置文件

    plugins=(z git macos zsh-autosuggestions zsh-syntax-highlighting)

zsh-autosuggestions 命令自动补全 终端执行

    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

sh-syntax-highlighting 命令错误提示 终端执行

    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

### [starship](https://starship.rs/zh-CN/) 终端美化

安装

    brew install starship

~/.zshrc 修改 zsh 配置文件 最后一行添加

    eval "$(starship init zsh)"

配置 https://starship.rs/zh-CN/config/

我的预览

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3dc65412270a4d1894648fd73ca6fafb~tplv-k3u1fbpfcp-watermark.image?)

### neofetch

命令行查看机器信息

    brew install neofetch

### Hyper 终端

个人比较喜欢 但打开多个会卡

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e9662a281ffc4ffeb62914e695c7bba4~tplv-k3u1fbpfcp-watermark.image?)

### Iterm2 终端

流畅 功能强大

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/5308472f5f844a6d91df2e753d98ec84~tplv-k3u1fbpfcp-watermark.image?)

## node

1. n
2. yarn
3. live-server
4. pm2

## 编辑器配置
