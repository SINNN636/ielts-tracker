# 🎯 IELTS TRACKER · 雅思备考追踪系统

> 一个**零依赖、完全在浏览器本地运行**的雅思备考追踪工具。
> 数据存在你自己的浏览器里，不上传任何服务器，不注册账号。

[🌐 在线预览](https://你的用户名.github.io/ielts-tracker/) · [📖 使用说明](#-30-秒上手) · [⚙️ 配置](#-配置)

---

## ✨ 它能做什么

| 模块 | 功能 |
| --- | --- |
| 📊 **仪表板** | 考试倒数日 · 连续打卡 · 今日完成度 · 四科雷达图 · 本周时间柱状图 |
| 🎯 **阶段计划** | 自定义阶段（默认 4 个），含任务清单与目标分 |
| ✅ **每日打卡** | 8 项训练项目（听 / 说 / 读 / 写 / 词 / 题 / 测 / 复盘），记录"今天最难的问题" |
| 📖 **词汇库** | 《雅思词汇真经》22 章 3674 词，支持浏览 / 搜索 / 跟打练习 |
| 📝 **单词本** | 自定义词汇、4 级掌握度（生词→认识→熟悉→掌握）、闪卡模式 |
| 🎪 **话题库** | 8 大话题分类（教育 / 环境 / 科技 …），气泡图索引 |
| 📕 **错题本** | 按题型分类（L1-L5 / R1-R5），追踪错误模式 |
| 🧪 **模考记录** | 记录 L / R / W / S 单项分与总成绩，看趋势 |
| 📈 **数据分析** | 30 天趋势、任务达成率、问题分布、词汇增长曲线 |
| ⚙️ **设置** | 考试日期 · 目标分 · 训练项自定义 · 数据导入导出 |

---

## 🖼️ 预览

<table>
  <tr>
    <td width="50%"><img src="screenshots/01-dashboard.png" alt="仪表板"><br><sub>📊 <b>仪表板</b> — 倒数日 · 连续打卡 · 四科雷达图 · 本周时间</sub></td>
    <td width="50%"><img src="screenshots/02-phases.png" alt="阶段计划"><br><sub>🎯 <b>阶段计划</b> — 自定义阶段 · 任务清单 · 进度时间线</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="screenshots/03-checkin.png" alt="每日打卡"><br><sub>✅ <b>每日打卡</b> — 训练记录 · 今日最大问题 · 打卡贡献</sub></td>
    <td width="50%"><img src="screenshots/04-checkin-todos.png" alt="今日待办"><br><sub>🗒️ <b>今日待办</b> — 每项训练的目标与完成量</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="screenshots/05-vocabulary.png" alt="词汇库"><br><sub>📖 <b>词汇库</b> — 22 章 3674 词 · 章节进度</sub></td>
    <td width="50%"><img src="screenshots/06-vocabulary-chapter.png" alt="词汇章节"><br><sub>🔤 <b>词汇章节</b> — 词组 / 释义 / 例句 / L1-L4 掌握度</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="screenshots/07-wordbook.png" alt="单词本"><br><sub>📝 <b>单词本</b> — 4 级掌握度 · 分类统计 · 闪卡模式</sub></td>
    <td width="50%"><img src="screenshots/08-topics.png" alt="话题库"><br><sub>🎪 <b>话题库</b> — 8 大话题 · 覆盖雷达图 · 核心词</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="screenshots/09-errors.png" alt="错题本"><br><sub>📕 <b>错题本</b> — L1-L5 / R1-R5 分类 · 错误模式追踪</sub></td>
    <td width="50%"><img src="screenshots/10-mock-tests.png" alt="模考记录"><br><sub>🧪 <b>模考记录</b> — L/R/W/S 单项分 · 分数趋势</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="screenshots/11-analytics.png" alt="数据分析"><br><sub>📈 <b>数据分析</b> — 30 天趋势 · 时间占比 · 达成率</sub></td>
    <td width="50%"><img src="screenshots/12-settings.png" alt="设置"><br><sub>⚙️ <b>设置</b> — 考试日期 · 目标分 · 数据导入导出</sub></td>
  </tr>
</table>

---

## 🚀 30 秒上手

### 1️⃣ 打开网页

直接访问你的 GitHub Pages 链接：

```
https://你的用户名.github.io/ielts-tracker/
```

### 2️⃣ 首次设置

首次进入会在顶部看到提示条 **👋 首次使用？去设置**

- 进入 **设置** 页面
- 填写 **考试日期**（驱动倒数日、阶段进度、热力图）
- 填写 **目标分数**（Overall，通常 6.5 / 7.0 / 7.5 / 8.0）
- 勾选要追踪的 **训练项目**（每项可设每日目标）

### 3️⃣ 开始打卡

- 每天进 **✅ 每日打卡**，如实填写各项训练时间
- 记录"今天最难的问题"——日后回顾能看清成长轨迹
- 数据自动存进浏览器 `localStorage`，**关闭网页也不丢**

---

## 💾 数据存储与迁移

| 操作 | 入口 | 说明 |
| --- | --- | --- |
| 📤 **导出** | 设置 → 数据管理 → 导出 | 下载 JSON 备份文件 |
| 📥 **导入** | 设置 → 数据管理 → 导入 | 恢复之前的备份 |
| 🗑️ **清空** | 设置 → 数据管理 → 清空全部 | 一键重置（不可恢复） |

数据存储位置：浏览器 `localStorage`，键名 `ielts-tracker-v1`。
**注意**：换浏览器 / 清缓存 = 数据丢失，请定期导出备份。

---

## 🌐 部署到 GitHub Pages

1. 把本目录所有文件上传到一个 GitHub 仓库（Public）
2. 仓库 → **Settings** → **Pages**
3. **Source**: Deploy from a branch · **Branch**: `main` / `(root)` → Save
4. 等待 1–2 分钟，访问 `https://你的用户名.github.io/<仓库名>/`

完整图文教程见 [如何部署](#)。

---

## 🎨 自定义外观

页面顶部的 CSS 变量控制主色与背景，改一处全站跟随：

```css
:root {
  --bg-page: #C9D3D3;   /* 页面背景 */
  --accent:  #D10047;   /* 主强调色（按钮 / 图表 / 今天） */
  /* 其他微调变量见 index.html 顶部 :root */
}
```

---

## 🧩 技术栈

- **HTML + CSS + 原生 JavaScript**（无构建步骤、无 npm）
- **Chart.js 4.x**（CDN 加载，画所有图表）
- **localStorage**（数据持久化）
- **vocab-book.js**（《雅思词汇真经》22 章词组数据）

不收集任何用户数据，没有后端，没有第三方追踪。

---

## 🙏 致谢

- 📚 词汇数据来源：刘洪波《雅思词汇真经》
- 📊 图表库：[Chart.js](https://www.chartjs.org/)
- 🍜 还有一碗越南河粉

---

## 📜 许可

MIT — 自由使用、修改、再发布。如果对你有帮助，欢迎点 ⭐！

---

<p align="center">
  <sub>雅思备考不易，祝你早日上岸 🦆</sub>
</p>