<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo">

<h1 align="center">Microsoft 激活脚本 (MAS)</h1>

<p align="center">开源的 Windows 与 Office 激活工具，支持 HWID、Ohook、TSforge、在线 KMS 等多种激活方案，附带高级故障排查能力。

<hr>

## 如何激活 Windows / Office / 扩展安全更新 (ESU)？

### 方法一 - PowerShell ❤️

1. 点击 **开始菜单**，搜索 `PowerShell` 并打开。
2. 复制下方代码粘贴到窗口，按 **回车**：
   - **适用于 Windows 8.1 / 10 / 11**：
     ```
     irm https://get.activated.win | iex
     ```
	 如果上述地址被屏蔽（由ISP/DNS导致），请尝试此命令（需已更新的Windows 10或11）:  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
	- **脚本无法启动？尝试方法2**
3. 弹出菜单后，输入**绿色高亮选项**对应的数字，按回车执行。

---

### 方法二 - 传统模式（支持 Windows Vista 及以上）

1. 下载脚本：
- [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true)（直接下载单文件脚本）
- [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip)（如果浏览器拦截直接下载链接，请下载压缩包）
2. 双击运行 `MAS_AIO.cmd`。
3. 弹出菜单后，输入**绿色高亮选项**对应的数字，按回车执行。

---

> [!TIP]
> - 部分运营商或DNS服务商会屏蔽我们的域名，可在浏览器开启 [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) 绕过限制。
> - **遇到问题？** 可访问 [故障排查页面](https://massgrave.dev/troubleshoot)，或在 [GitHub Issues](https://github.com/massgravel/Microsoft-Activation-Scripts/issues) 提交反馈。

> [!NOTE]
> - PowerShell 中 `irm` 用于下载脚本，`iex` 用于执行脚本。
> - 执行前务必核对URL地址，手动下载请确认来源可信。
> - 警惕第三方篡改PowerShell命令中的URL，将恶意软件伪装成MAS传播。

---

<div align="center">

### 项目主页 - [https://massgrave.dev/](https://massgrave.dev/)

[![Discord]][Discord-Link]
[![Reddit]][Reddit-Link]
[![Bluesky]][Bluesky-Link]
[![X/Twitter]][X-Link]
[![GitHub]][GitHub-Link]
[![Azure DevOps]][Azure-Link]
[![自建Git]][Gitea-Link]
[![汉化Git]][Chinese-Link]

[Discord]: https://massgrave.dev/img/logo_discord.png "(无需注册，直接加入聊天)"
[Reddit]: https://massgrave.dev/img/logo_reddit.png "(Reddit社区)"
[Bluesky]: https://massgrave.dev/img/logo_bluesky.png "(Bluesky主页)"
[X/Twitter]: https://massgrave.dev/img/logo_x.png "(X/Twitter主页)"

[GitHub]: https://massgrave.dev/img/logo_github.png "(GitHub仓库)"
[Azure DevOps]: https://massgrave.dev/img/logo_azuredevops.png "(Azure DevOps仓库)"
[自建Git]: https://massgrave.dev/img/logo_gitea.png "(自建Git仓库)"
[汉化Git]:https://massgrave.dev/img/logo_github.png "(汉化仓库)"
[Discord-Link]: https://discord.gg/j2yFsV5ZVC
[Reddit-Link]: https://www.reddit.com/r/MAS_Activator
[Bluesky-Link]: https://bsky.app/profile/massgrave.dev
[X-Link]: https://twitter.com/massgravel
[GitHub-Link]: https://github.com/massgravel/Microsoft-Activation-Scripts
[Chinese-Link]: https://github.com/MoyuanMaris/Microsoft-Activation-Scripts-Chinese
[Azure-Link]: https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts
[Gitea-Link]: https://git.activated.win/Microsoft-Activation-Scripts

---
