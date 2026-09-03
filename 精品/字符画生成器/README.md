# ASCII Field — 图片转字符画

把任意图片转成打字机风格的 ASCII 字符画：上传图片后可调分辨率、亮度、对比度、暗部裁剪、字符集与墨色，还带一个"Lens Liquidness"液态透镜扭曲效果，最后可复制文本或导出 PNG。默认加载一张蝴蝶示例图。

## 运行

无需构建，浏览器直接打开 `index.html` 即可。

## 交互

- `Load Image` —— 上传任意图片（默认蝴蝶示例）
- Resolution / Brightness / Contrast / Cutoff —— 调整渲染参数
- Charset —— 五种预设字符集（Dotted / Sketch / Classic / Blocks / Dots）或自定义（暗 → 亮）
- Ink Color —— 墨色（米色 / 淡绿 / 白 / 琥珀 / 青 / 跟随原图色彩）
- Lens Liquidness —— 透镜液态扭曲强度（鼠标悬停可拖动查看）
- `⧉ Text` / `↓ PNG` —— 复制文本 / 导出图片

## 文件

- `index.html` —— 全部逻辑（单文件）
- `assets/butterfly.webp` —— 默认示例图

## 来源

效果复刻自 [bubbbly.com/app/ascii-art.html](https://www.bubbbly.com/app/ascii-art.html)（Built by Claude Fable 5 on TypingMind），仅作学习研究用途，素材版权归原作所有。
