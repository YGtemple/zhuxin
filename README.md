# 王佳琦 · 个人简历与作品集

> 一个现代化的个人简历单页网站，展示专业技能、项目经历、教育背景、竞赛获奖与技术分享。

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 👤 个人简介

**王佳琦**，郑州升达经贸管理学院翻译专业大二在读。以 C++ 参与算法竞赛（码蹄杯、百度之星省赛银奖），从 Qt 桌面开发到 AI 应用全栈开发，兼具游戏开发与 AIGC 创作能力。

- 📧 邮箱：1744059451@qq.com
- 💬 微信：15314662965
- 📍 所在地：河南南阳
- 🐙 GitHub：[github.com/YGtemple](https://github.com/YGtemple)

## 📖 项目简介

本项目是个人简历与作品集的纯静态单页网站，采用 HTML + CSS + JavaScript 实现，无需后端依赖。页面以现代化的视觉设计和流畅的交互体验，系统展示个人专业技能、项目经历、教育背景、竞赛获奖、技术分享与运营经历，可作为求职、实习、社群展示的个人名片。

## ✨ 功能亮点

- **响应式导航栏** — 固定顶部导航，支持锚点平滑滚动跳转
- **个人简介区** — 头像、基本信息、个人陈述一目了然
- **专业技能展示** — 五大技能方向，每个方向配有详细技术栈标签
- **项目经历卡片** — 每个项目包含时间、描述、技术栈、项目亮点
- **教育经历** — 学校、专业、在读状态
- **竞赛获奖** — 赛事名称、奖项等级
- **技术分享与运营** — 社群运营、内容创作经历
- **联系方式** — 邮箱、微信、GitHub 多渠道
- **移动端适配** — 完美适配手机、平板、桌面端

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| 标记语言 | HTML5（语义化标签） |
| 样式 | CSS3（Flexbox、Grid、动画、渐变、响应式媒体查询） |
| 交互 | 原生 JavaScript（平滑滚动、导航高亮） |
| 图标 | 内联 SVG / Unicode 图标 |
| 字体 | 系统字体栈 |
| 部署 | 任意静态托管平台 |

## 📁 项目结构

```
zhuxin/
├── index.html      # 主页面（包含全部内容、样式与脚本）
└── README.md       # 项目说明文档
```

## 🚀 快速开始

### 本地预览

```bash
# 直接用浏览器打开
open index.html

# 或使用本地服务器
python3 -m http.server 8080
# 访问 http://localhost:8080
```

### 部署上线

**GitHub Pages：**
```bash
git init
git add .
git commit -m "init: 个人简历网站"
git branch -M main
git remote add origin https://github.com/YGtemple/zhuxin.git
git push -u origin main
# Settings → Pages 启用 GitHub Pages
```

也可部署到 Netlify、Vercel、Cloudflare Pages 等平台。

## 📋 页面板块

### 1. 导航栏
- 首页 / 技能 / 项目 / 教育 / 获奖 / 联系
- 滚动时自动高亮当前板块

### 2. 个人简介
- 姓名、邮箱、微信、所在地、GitHub
- 个人陈述：专业背景 + 技术方向 + 核心能力

### 3. 专业技能（五大方向）

| 方向 | 核心技术 |
|------|----------|
| **算法竞赛** | C++、STL、C语言、数据结构（栈/队列/链表/哈希）、排序/二分/双指针、前缀和/差分、快速幂/取模、组合数学/容斥、位运算 |
| **全栈开发** | Qt 6.7.0、HTML/CSS/JS、HiAgent 工作流、Agent Skill 开发、RESTful API、Netlify 部署、架构文档 |
| **游戏开发** | Cocos Creator 3.8、TypeScript、微信小游戏、Unity、Spine |
| **工程协作** | GitHub 协作、扣子/HiAgent、Linux 基础、Obsidian、知识库搭建 |
| **AIGC 内容创作** | ComfyUI、提示词工程、SDXL/FLUX、视频生成、动漫短剧、分镜脚本、LoRA |

### 4. 项目经历

- **智言（TEDify V2）** — 面向路演、面试、会议、公开演讲的个人表达训练系统，六步闭环流程
- **融研智笔 — Web 端** — 英语写作 AI 智能体 Web 应用，HiAgent 后端 + HTML 前端，覆盖七类考试评分标准
- **智序 — AI 日程助手** — TRAE AI 创造力大赛参赛作品，纯前端单 HTML 实现，14 项升级
- **长隆灵犀 — AI 智慧伴游** — 2026 AI 先锋未来人才大赛参赛作品，游客情绪驱动的实时伴游 Agent
- **智能题库与学习分析平台** — 面向大学生期末复习，七份架构文档，四阶段演进路径

### 5. 教育经历
- 郑州升达经贸管理学院 · 翻译专业 · 大二在读

### 6. 竞赛获奖
- 码蹄杯
- 百度之星 · 省赛银奖
- 蓝桥杯

### 7. 技术分享与运营
- 社群运营、技术分享、内容创作经历

### 8. 联系方式
- 邮箱、微信、GitHub

## 🎨 设计特点

- **现代化卡片式布局** — 信息层次清晰
- **渐变与阴影** — 营造科技感与深度
- **技能标签云** — 技术栈可视化展示
- **项目卡片** — 每个项目独立卡片，含技术栈徽章
- **平滑滚动** — 导航点击平滑跳转
- **响应式断点** — 移动端自动调整布局

## 📝 自定义指南

### 修改个人信息
在 `index.html` 中搜索对应文本直接替换：
- 姓名、邮箱、微信、所在地
- 个人陈述段落
- GitHub 链接

### 添加新项目
在项目经历板块复制一个项目卡片，修改：
- 项目名称与年份
- 项目描述
- 技术栈标签
- 项目亮点徽章

### 添加新技能
在对应技能方向的标签列表中添加新的 `<span>` 标签即可。

## 📄 许可证

本项目为个人简历展示用途，内容版权归本人所有。

## 📮 联系方式

- GitHub：[@YGtemple](https://github.com/YGtemple)
- 邮箱：1744059451@qq.com
- 微信：15314662965
