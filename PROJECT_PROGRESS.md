# Web01-CityBit 项目记录

## 概述

- 项目名称：100件你不知道的小事 · 城市观察
- 本地路径：`/Users/max/Max1031/Max_lab/VibeCoding-100/Web01-CityBit`
- 部署方式：Vercel 静态部署
- 交互方式：首页选择城市，进入对应城市的静态长页
- 当前状态：内容完成，可作为公开作品集项目继续包装

## 设计系统

- 字体：Playfair Display + Noto Serif SC + DM Mono
- 视觉风格：报纸 / 杂志版式
- 基础配色：
  - ink: `#1a1008`
  - paper: `#f5efe6`
  - rust: `#c0392b`
  - gold: `#c9922a`
  - steel: `#4a5568`
- 主要组件：城市卡片、分类标签、事实网格、宽版特色卡片、引文区块

## 当前内容

1. 首页 `index.html`
2. 纽约 `cities/newyork.html`
3. 上海 `cities/shanghai.html`
4. 昆明 `cities/kunming.html`
5. 大理 `cities/dali.html`
6. 波士顿 `cities/boston.html`
7. 新奥尔良 `cities/neworleans.html`

## 发布前建议

1. 在 GitHub 仓库里补充 description、topics 和 homepage
2. 部署后补 1-2 张截图，提升访客第一印象
3. 如果后续继续扩展城市，优先保持首页与详情页的视觉一致性
4. 如需公开仓库，继续避免提交 `.vercel` 等本地部署关联文件

## 后续可扩展方向

1. 新增更多城市页面，继续沿用当前版式
2. 首页增加按地区或城市气质的筛选
3. 引入简单的统计页，例如“已收录城市数 / 观察总条数”
4. 为每座城市增加目录导航，提升长页浏览效率
