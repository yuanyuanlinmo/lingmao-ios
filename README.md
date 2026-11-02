# 灵猫 2.0 苹果安装页

本仓库用于分发已签名的 iOS Ad Hoc 安装包和无需开发者账号的 Web Clip，不包含 Flutter 应用源码、接口配置或密钥。

- 当前版本：`2.0.21 (2221)`
- Bundle ID：`xin.linmo.lingmao.v2`
- 当前安装入口：`/c0fb87cadbb20ab4/`
- 回退版本：`2.0.20 (2220)`，保存在 `/c0fb87cadbb20ab4/archive/2.0.20/`

## Web Clip

- 安装入口：`https://yuanyuanlinmo.github.io/lingmao-ios/webclip/`
- 当前最新版：`2.0.21 (2221)`
- 桌面图标打开稳定地址 `/latest/`；后续更新网页版本时无需重新安装桌面图标。
- Web Clip 与 IPA 是两个独立入口，不会互相覆盖。

公开 GitHub Pages 页面可以安装和打开最新版 UI；真实登录与业务数据仍依赖可提供同源 `/api` 代理的正式预览域名。

## 文件校验

- `2.0.21` SHA-256：`aa946d77c4fd96d75abb7686ff53a16b5bf0341c5b52df018edb386b0c7fbde8`
- `2.0.20` SHA-256：`9c2d192a5d6563abc52df7c0a2d3bce95e289f4ede9815a3aca5f8e30546f226`

安装页公开可访问，但只有已登记在 Ad Hoc 描述文件中的 iPhone 才能完成安装。
