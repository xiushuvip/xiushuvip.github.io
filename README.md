🌙 交互式观月助手 (Interactive Moon Observer)
一个精美的实时月相观测工具，提供准确的月亮位置、月相信息和月出月落时间。
✨ 特性
🌍 多语言支持 - 支持中文、英文、日文、西班牙语、法语
🌙 实时月相显示 - 精确的月相计算和可视化
🎯 3D交互月亮 - 可拖拽旋转的逼真月亮模型
⏰ 实时时间更新 - 每秒更新的精确时间显示
📍 自动定位 - 基于地理位置的精确计算
🌅 月出月落时间 - 今日和明日的月出月落预测
🧭 天空方位 - 月亮在天空中的准确方向
📱 响应式设计 - 完美适配手机和桌面设备
✨ 动态星空背景 - 闪烁的星星和脉动光晕效果
🚀 使用方法
直接使用 - 在浏览器中打开 index.html 文件
无需安装 - 纯前端实现，无需服务器
允许定位 - 首次使用时允许浏览器获取您的位置
切换语言 - 点击右上角的地球图标选择语言
交互操作 - 拖拽月亮进行3D旋转查看
🛠️ 技术特点
纯前端实现 - 仅使用 HTML、CSS、JavaScript
无依赖框架 - 原生 JavaScript，无需额外库
精确天文算法 - 基于天文算法的月相和位置计算
SVG矢量图形 - 高质量的月亮渲染
现代CSS效果 - 毛玻璃、动画、渐变等视觉效果
本地存储 - 语言偏好自动保存
📊 功能详解
月相信息
新月、蛾眉月、上弦月、盈凸月、满月、亏凸月、下弦月、残月
被照亮比例精确到小数点后一位
实时月相SVG渲染，包含陨石坑和高光效果
位置信息
自动获取用户地理位置
显示月亮在天空中的方位（北、东北、东、东南、南、西南、西、西北）
计算月出月落时间（今日和明日）
交互体验
3D月亮可360度旋转查看
惯性动画效果
声音反馈（可关闭）
触摸屏支持
🌍 多语言支持
🇨🇳 简体中文
🇺🇸 English
🇯🇵 日本語
🇪🇸 Español
🇫🇷 Français
📱 兼容性
✅ Chrome 60+
✅ Firefox 55+
✅ Safari 12+
✅ Edge 79+
✅ 移动端浏览器
✅ 触摸屏设备
🎯 使用场景
🌙 天文爱好者 - 观测月亮的最佳时间
📸 摄影师 - 规划月光摄影
🏕️ 户外活动 - 了解夜间光照情况
🎓 教育用途 - 学习月相变化规律
🌍 旅行规划 - 了解目的地的月相情况
📁 文件结构
moon-observer/
├── index.html          # 主页面文件
└── README.md           # 说明文档
🚀 部署
GitHub Pages
将代码上传到 GitHub 仓库
在仓库设置中启用 GitHub Pages
选择 main 分支作为源
访问 https://username.github.io/repository-name
本地运行
# 使用 Python 3
python -m http.server 8000
# 使用 Node.js
npx http-server
# 使用 PHP
php -S localhost:8000
然后访问 http://localhost:8000
🎨 自定义
修改主题颜色
在 CSS 中修改以下变量：
.container {
    background: rgba(255, 255, 255, 0.05); /* 背景透明度 */
    border: 1px solid rgba(255, 255, 255, 0.18); /* 边框颜色 */
}
添加新语言
在 translations 对象中添加新的语言翻译
在 HTML 中添加新的语言选项
更新语言选择器
修改星星效果
.star {
    animation-duration: 2s; /* 调整闪烁速度 */
    opacity: 0.8; /* 调整透明度 */
}
🤝 贡献
欢迎提交 Issue 和 Pull Request！
Fork 本仓库
创建特性分支 (git checkout -b feature/AmazingFeature)
提交更改 (git commit -m 'Add some AmazingFeature')
推送到分支 (git push origin feature/AmazingFeature)
开启 Pull Request
📄 许可证
本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情
🙏 致谢
天文算法基于 Jean Meeus 的《天文算法》
月亮纹理和效果灵感来自 NASA 月球数据
星空背景效果参考了多个天文观测应用

⭐ 如果这个项目对您有帮助，请给个 Star！
