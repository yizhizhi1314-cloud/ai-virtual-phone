# 🪄 SillyTavern 魔棒快捷菜单收纳器

把 SillyTavern 左下角扩展菜单整理成更好点、更适合手机的可视化弹窗。

## 功能
- 🔍 工具搜索
- 🗂️ 自动分类
- ⭐ 收藏常用工具
- 🌓 浅色 / 深色 / 自动主题
- 📱 手机端底部抽屉布局
- ⌨️ Ctrl/Cmd + K 快速打开
- Esc 或点击背景关闭
- 尽量调用 SillyTavern 原来的菜单按钮，不重复实现原功能

## 一键安装

使用 Tampermonkey 或 Violentmonkey 安装这个 Raw 脚本：

https://raw.githubusercontent.com/yizhizhi1314-cloud/ai-virtual-phone/main/sillytavern-magic-wand/magic-wand-organizer.user.js

## 排错
浏览器控制台执行：

    MagicWandOrganizer.inspect()

正常应看到 buttonFound: true 和 menuFound: true。

## 注意
当前 @match 覆盖 127.0.0.1 和 localhost 的任意端口。如果你的酒馆使用局域网 IP（例如 192.168.x.x），告诉我地址，我再给你补上。