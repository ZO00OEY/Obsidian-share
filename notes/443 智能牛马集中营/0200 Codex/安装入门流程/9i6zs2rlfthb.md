
# Codex Skills 推荐

这篇只放最常用、最值得优先安装的 Skills。先不要装一大堆，用得上再加。

## 必装：Ponytail

Ponytail 的核心作用是让 Codex 少写废代码，优先选择最简单、最短、能跑通的方案。

安装命令：

```powershell
codex.exe plugin marketplace add DietrichGebert/ponytail
```

安装后在 Codex 里输入 `/plugins`，找到 Ponytail 并安装。安装完成后重启 Codex，再新建一个线程使用。

适合：

- 写脚本
- 改小功能
- 修 bug
- 整理教程笔记
- 避免过度设计

如果只装一个增强类 Skill，优先装它。

## 必装：Obsidian Skills

这是 Kepano 整理的 Obsidian 相关 Skills，适合让 Codex 更懂 Obsidian 笔记、Markdown、双链和库内整理。

安装命令：

```bash
npx skills add kepano/obsidian-skills
```

适合：

- 整理 Obsidian 笔记
- 写教程型 Markdown
- 维护双链
- 做知识库归档

## 选装：前端设计 Skill

如果经常让 Codex 做网页、组件、落地页、展示页，可以再装前端设计相关 Skill。

安装命令：

```bash
npx skills add frontend-design
```

适合：

- 做前端页面
- 改 UI
- 写展示站
- 做交互 demo

如果暂时主要是写教程、跑命令、整理笔记，可以先不装。
