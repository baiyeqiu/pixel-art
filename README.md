# 🎨 像素画生成器 (Pixel Art Generator)

在线像素画创作工具 —— 1:1 还原 Android 原版全部功能。

**在线体验:** [baiyeqiu.github.io/pixel-art](https://baiyeqiu.github.io/pixel-art)

---

## ✨ 功能

### ✏️ 自由画板
- **7 种绘图工具**: 画笔、橡皮、填充桶、取色器、直线、矩形、圆形
- **对称绘画**: 水平 / 垂直 / 四象限对称模式
- **6 档笔刷**: 1~8px 可调
- **画布尺寸**: 4x4 ~ 256x256 自由调整
- **🆕 最近使用色块**: 颜色面板旁 2 个快捷色块，点击即选
- **🆕 项目保存/加载**: 本地存储，刷新不丢失
- 撤销/重做 (Ctrl+Z/Y)
- 网格线、快捷键

### 📷 图片转换
- 上传 PNG/JPG/WEBP → 像素画
- 调色板提取 / 黑白 / 灰度三种模式
- 2~64 色可选
- 一键发到画板继续编辑

### 🤖 AI 生图
- 文字描述 → AI 生成图片
- 免费 Pollinations.AI 引擎
- 支持 256/512/768/1024 尺寸
- 一键像素化或发到画板

### 💾 导出
- 保存 PNG (1x / 4x 放大)
- 支持系统分享
- 自动保存到相册（PWA 安装后）

---

## 🚀 技术栈

- 纯原生 HTML/CSS/JS，零依赖
- Canvas 2D 像素渲染引擎
- HSV 颜色空间 + 拾色器
- Uint8Array RGBA 像素存储
- PWA 支持（可安装为桌面应用）
- GitHub Pages 部署

---

## 📱 PWA 安装

1. 用 Chrome/Safari 打开网站
2. 地址栏右侧出现安装图标
3. 点击「安装」即可像原生 App 一样使用

---

## 🛠 本地运行

```bash
# 任意 HTTP 服务器即可
python3 -m http.server 8080
# 或
npx serve .
```

浏览器打开 `http://localhost:8080`

---

## 📄 开源协议

MIT License
