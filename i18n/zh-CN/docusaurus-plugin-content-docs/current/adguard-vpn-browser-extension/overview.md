---
title: 功能概述
sidebar_position: 1
---

AdGuard VPN Browser extension is available for Chrome, Firefox, Opera, and Edge. UI 和功能在浏览器之间并没有区别，因此下面将概述所有用于浏览器的 AdGuard VPN 。

> 请注意，您只能在登录 AdGuard VPN 时使用浏览器扩展。 您可以使用 AdGuard 账号或通过 Google、Facebook 或 Apple 登录。 在后一种情况下，请确保您的账号与 AdGuard 账号绑定在同一个电子邮件地址上。 如果您有 [AdGuard VPN 订阅](/general/subscription.md)，它将会在 AdGuard VPN 浏览器扩展中自动激活。 如果您没有 AdGuard 账号， [请点击这里。](https://auth.adguard.com/registration.html)。

To manage your AdGuard VPN Browser extension:

* Either click its icon on the browser's panel, click the hamburger menu icon, and select *Settings*,
* Or go to the *Manage extensions* page in your browser, click *Details* below *AdGuard VPN* and manage its settings from there.

完成后，您将看到几个在左侧的选项卡：

## 设置

此选项卡中有一些重要设置。 在这里，您可以选择一个 DNS 服务器来使用，从浏览器的上下文菜单中添加或删除 AdGuard VPN 图标，拦截 WebRTC，改变扩展的主题，并允许 AdGuard 收集匿名的崩溃报告和技术数据。

### 选择一个 DNS 服务器

默认情况下选择的是由您的 ISP 提供的[系统 DNS 服务器](https://adguard-dns.io/kb/general/dns-filtering/#what-is-dns) ，但它可能会损害您的隐私。 凭借 AdGuard VPN 浏览器扩展，您可以选择一个提供更好的速度和安全性，甚至阻止广告或有潜在危险的域名的 DNS 服务器。 以下对于 DNS 服务器的简要说明将帮助您导航并做出决定。

了解更多有关[来自不同服务商的DNS服务器](https://adguard-dns.io/kb/general/dns-providers/)。

## 排除项

下一个选项卡包含 AdGuard VPN 的主要特点之一，即有独立的排除项列表的两种模式。

在 **通用模式**，除了用户添加到排除项列表的网站除外，AdGuard VPN 默认在所有网站都运行。 在 **选择模式**，反之亦然，AdGuard VPN 默认在任何地方都不工作。 You can add any websites where you'd like it to work to an exclusions list, separate from the one you saw in the **General mode**.

在添加网站到排除项列表时，用户可以手动输入网站或**从列表中**选择它们。 在后一种情况下，用户会看到八个类别（例如： *购物*， *通信*等等），每个类别包含几个流行服务。 用户可以一键排除这些服务中的任何一项，该操作将把与该特定服务相关的所有域名添加到排除项中。

### 导入和导出

用户不仅可以添加和删除网站，还可以将准备好的排除项列表转移到安装 AdGuard VPN 的其他设备上。 要导出你的排除项列表，请按照以下 4 步说明操作：

1. 在您想要导出排除项列表的设备上打开 AdGuard VPN 浏览器扩展。 找到相应的部分并单击「导出」按钮。 `exclusions.zip` 档案将被下载。
2. There are two `.txt` files inside the archive, one for each of the General and Selective lists. 用户可以在其中添加更多的排除项，删除现有的排除项，重命名文件，或者也可以将存档中的文件内容保持不变。
3. 在不同设备之间传输时，将 `.zip` 文件发送到设备上进行导入。
4. 在该设备上打开 AdGuard VPN。 找到相应的部分，单击「导入」按钮并选择存档。 完成！

## 账号

AdGuard VPN 浏览器扩展的第三个标签是完全简约的，只包含用户用来登录账号的电子邮件地址和两个按钮，「*管理*」和「*退出*」。 点击「*管理*」按钮，用户就会进入个人 AdGuard 账号，在那里您可以看到当前所有的许可证和订阅，以及与之连接的设备。

## 支持

用户可以在「常见问题」部分找到常见问题的答案，或留下反馈意见：如果您面临问题无法正常运行应用程序，请您报告错误，建议增加一个新功能，或在社交媒体平台上讨论 AdGuard。

## 关于

另一个小标签，用户可以查看扩展的版本，访问官网，并查看 EULA（最终用户许可协议） 或隐私政策。
