# 创业路·价值判断 + 三区结构 — HTML 演讲稿

## 模板

现已统一为 **TEKUMA × MLA+** scroll-snap 模板（与 `source/template-ref.html` 同族）：

- 色板：`--ink / --paper / --orange / --sea / --forest` 等
- 字体：Inter + PingFang / Microsoft YaHei（**无** Noto Serif / 宋体标题；**无** Google Fonts 依赖，`file://` 可离线打开）
- 结构：`<main class="slides">` + `<section class="slide">`，纵向 scroll-snap（100svh）
- 顶栏 `.topbar`（mix-blend-mode: difference）+ 底栏 `.bottom-controls`（← → / N 讲述提示 / F 全屏）
- 键盘：← →、空格、PageUp/Down、Home/End

上一版（衬线 + fade 单屏翻页）备份为 `index.serif-prev.html`。

## 如何打开

1. 用 Chrome / Edge / Safari 打开 `index.html`（支持 `file://`）。
2. 翻页：键盘 `←` `→` / `空格`，或底部按钮；`N` 讲述提示，`F` 全屏。
3. GitHub Pages：https://yuechencui.github.io/chuangyelu-value-html/?v=13

## 页面结构（20 页）

### 价值判断（01–07）
| # | 主题 | 视觉 |
|---|------|------|
| 01 | 深圳是一座包容的城市 | **SVG 矢量**人口预测图 |
| 02 | AI 正在重写创新的基本单元 | **SVG** 传统大公司 → AI 原生 |
| 03 | 街巷与第三空间 | SF 拼贴 |
| 04 | 创新活力从硅谷迁入旧金山 | 迁移地图 + 50%/60%/33% |
| 05 | 新一代产业人才 | Kimi / Splay 拼贴 |
| 06 | 创业路的独特禀赋 | 海山城航拍 |
| 07 | 存量如何成为未来 | 结题挑战条 |

### 桥接（08）
| # | 主题 | 视觉 |
|---|------|------|
| 08 | 总体战略定位 | `.slide.dark` 航拍全Bleed + 白字标题卡 |

### 三区结构（09–20）
| # | 主题 | 视觉 |
|---|------|------|
| 09 | 三类创新生态总览 | 总图 + 三区主张 |
| 10 | 海心 · 宝安中心区 | 片区地图 + 侧栏 |
| 11 | 具身智能港 | 企业集聚图 |
| 12 | 宝安中心区生活舞台 | 生活拼贴 |
| 13 | 城心 · 灵芝片区 | 片区地图 + 侧栏 |
| 14 | L1 低成本弹性产业空间 | 生命周期曲线 SVG |
| 15 | L2 街巷特征 | 曼哈顿 / 新安对比 |
| 16 | L3 微更新策略 | 轴测图 hero |
| 17 | L4 创意社区转型 | 密板全幅图 |
| 18 | L5 街—巷—道体系 | 目的地系统地图 |
| 19 | L6 街巷道三例 | 道 / 街 / 巷 三案 |
| 20 | 山心 · 尖岗山片区 | 片区地图 + 侧栏 |

## 目录

```
assets/                 # 拼贴、地图、桥接背景、lingzhi/
assets/lingzhi/         # 城心六页专用图
index.html              # TEKUMA×MLA+ scroll-snap 主文件
index.serif-prev.html   # 旧版衬线/fade 备份
README.md
```
