# 太空躲陨石 · SPACE METEOR DODGE

复古像素风躲陨石网页小游戏 —— 纯静态、零依赖、单文件 Canvas。

▶ **在线试玩：<https://sumomo0222.github.io/meteor-dodge/>**

## 操作

- 桌面：**← → ↑ ↓ / WASD** 移动飞船（Enter / Space 开始或重开）
- 手机：**手指拖动**屏幕控制飞船

## 特性

- 得分系统：生存计分 + 躲过陨石奖励（小 +10 / 中 +15 / 大 +25），localStorage 最高分
- 难度递增 LV1-15：陨石密度、下落速度、横向漂移逐级提升，LV5 起概率双发
- 粒子爆炸：坠毁爆散、引擎尾焰、屏幕震动 + 白闪
- 复古像素风：320×480 低分辨率画布 + pixelated 放大、CRT 扫描线滤镜、3×5 像素字体
- WebAudio 芯片音效（可静音），桌面 / 手机自适应

## 结构

- `dist/index.html` —— 游戏本体（Pages 部署 `dist/`）
- `.github/workflows/deploy.yml` —— GitHub Pages Actions 部署
