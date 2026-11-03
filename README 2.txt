心动来电｜闫桉篇 iPhone 网页 App 包

包含：
- index.html：恋爱模拟器
- manifest.webmanifest：主屏幕应用配置
- sw.js：基础离线缓存
- icon-192.png / icon-512.png：应用图标

重要说明：
这是 PWA 网页应用包，不是签名后的原生 iOS IPA。需要先部署到 HTTPS 网站，再通过 iPhone Safari 添加到主屏幕。
本地存档保存在当前网站的浏览器存储空间。不同网址/域名之间的存档不会自动迁移；可在游戏“设置”中导出 JSON，再在新网站导入 JSON。
主动消息仅在页面运行时模拟；系统级后台推送、AI 服务和 App Store 发布尚未配置。
