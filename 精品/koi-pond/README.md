# Koi Pond — 33⅓ RPM

一张旋转的黑胶唱片化作锦鲤池：锦鲤在唱片上悠游，拖动唱针落到唱片上即可播放雨声氛围乐，点击水面可以添加新的锦鲤（上限 20 条）。

## 运行

无需构建，直接用浏览器打开 `index.html` 即可（音频需要本地 HTTP 服务或浏览器允许自动播放策略，推荐 `python -m http.server` 后访问）。

## 交互

- 拖动唱针到唱片上 —— 唱片开始旋转，播放雨声氛围音乐（左侧滑块调音量）
- 点击水面 —— 添加一条锦鲤，带落水飞溅与「扑通」音效
- 拖回唱针 —— 停止播放

## 文件

- `index.html` —— 全部 Canvas 动画与交互逻辑（单文件）
- `assets/duckweed.webp` —— 浮萍贴图
- `assets/orange-paper-background.webp` —— 橙纸纹理背景
- `assets/raining-instrument.mp3` —— 雨声氛围音轨（4:45，循环）

## 来源

效果复刻自 [bubbbly.com/app/koi-pond.html](https://www.bubbbly.com/app/koi-pond.html)（Built by Claude Fable 5 on TypingMind），仅作学习研究用途，素材版权归原作所有。
