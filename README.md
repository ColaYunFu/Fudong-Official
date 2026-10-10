# 符冬便利店官网（V0.7 预览版）

符冬便利店的独立静态官网，展示品牌介绍、语音频道、社群入口与公告。项目只使用原生 HTML、CSS、JavaScript 和本地图片资源，无需后端、账号系统、依赖安装或构建步骤。

## 页面功能

- 夜间便利店背景与半透明雾化玻璃视觉。
- FD 品牌标识、浏览器标签页图标、实时北京时间与日期。
- 顶部分类导航：关于我们、语音频道、社群链接、公告栏。
- 分类聚焦效果：选中面板放大，其他页面内容和背景虚化；可通过 Esc、点击背景或返回全览退出。
- 关于我们面板：频道内容介绍、直播间常驻内容与开播提醒。
- 语音平台外链：Discord、OOPZ、黑盒语音、KOOK，点击后在新标签页打开。
- 社群入口：哔哩哔哩主页外链；QQ 社群采用二维码聚焦面板，并展示群号 `650848558` 和复制群号入口。
- 公告栏空状态：暂无最新公告。
- 桌面、平板与手机布局适配。

## 文件结构

```text
.
├── index.html
├── README.md
├── CHANGELOG.md
├── VERSION
├── .nojekyll
└── assets/
    ├── fudong-store-night-background.webp
    ├── about-character.webp
    └── qq-group-qrcode.png
```

## 本地预览

直接用现代浏览器打开 `index.html` 即可。请保留 `index.html` 与 `assets/` 的相对路径。

## 部署到 GitHub Pages

1. 在 GitHub 建立一个独立仓库，建议名称：`Fudong-Official`。
2. 将本项目所有文件上传到仓库根目录，保留 `assets/` 目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择分支 `main` 和目录 `/(root)`，保存后等待部署完成。
6. 在 Pages 页面打开 GitHub 提供的网站地址。

## 已配置的外部入口

- Discord：<https://discord.gg/xC4yqAu88t>
- OOPZ：<https://oopz.cn/i/b5Vz7k>
- 黑盒语音：<https://chat.xiaoheihe.cn/i93dvtd4>
- KOOK：<https://kook.vip/oYlbRg>
- 哔哩哔哩：<https://space.bilibili.com/481636456>
- QQ 社群：通过页面二维码加入，群号 `650848558`

## 版本说明

当前为 V0.7 预览版。公告栏仍为空状态，正式公告正文可后续补充。本版本不收集或上传网站访客数据；用户访问外部平台时会离开本网站并遵循对应平台规则。

发布前建议在实际设备上确认 QQ 群二维码能正常扫描，并逐个点击外部平台入口确认邀请仍然有效。
