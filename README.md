# Prompt Daily·每日魔咒 — 隐私政策

本仓库只做一件事：托管 **Prompt Daily·每日魔咒** 浏览器扩展的隐私政策静态页。  
This repository hosts the privacy policy for the **Prompt Daily** browser extension. Static pages only.

> 扩展本体不在这个仓库里。这里没有可安装的代码，只有三个 HTML 文件。

## 在线地址

| 页面                       | URL                                                      |
| ------------------------ | -------------------------------------------------------- |
| 首页（语言选择）                 | <https://cambern.github.io/prompt-daily/>                |
| 隐私政策（中文）                 | <https://cambern.github.io/prompt-daily/privacy.html>    |
| Privacy Policy (English) | <https://cambern.github.io/prompt-daily/privacy.en.html> |

Chrome Web Store 与 Edge Add-ons 的 Privacy policy URL 填第三个（英文版）。

## 文件

| 文件                | 说明              |
| ----------------- | --------------- |
| `index.html`      | 落地页，两张语言卡片      |
| `privacy.html`    | 中文隐私政策，10 节     |
| `privacy.en.html` | 英文隐私政策，10 节逐节对应 |

三个文件互为相对链接，可以整目录下载后离线打开。

## 更新流程

1. 本地改完 HTML，在本仓库 **Add file → Upload files** 覆盖同名文件
2. Commit 后等 1～3 分钟，GitHub Pages 自动重新构建（`Actions` 标签里能看到 `pages build and deployment`）
3. 打开页面加 `?v=2` 可绕过 CDN 缓存立即验证

**不要删除本仓库，也不要改仓库名**——商店里登记过的 URL 会长期校验，改名即失效。

## 关于这些页面

- 纯静态 HTML，样式内联，**零外部请求**：不加载字体、脚本、图片或任何第三方资源
- 不使用 Cookie，不包含任何统计或追踪代码
- 页面内容即扩展的实际行为，与商店「Privacy practices」中的声明逐条一致

## 联系

任何疑问、投诉或数据相关请求：**<nerbmac@163.com>**（通常 7 个工作日内回复）

For any question regarding this policy: **<nerbmac@163.com>**
