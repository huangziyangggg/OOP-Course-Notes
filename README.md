# OOP Course Notes · Python BootCamp

> **Harbin Institute of Technology × emlyon business school** · BSc in Applied Data Science · Object Oriented Programming
>
> **哈尔滨工业大学 × 法国里昂商学院** · 应用数据科学本科 · 面向对象编程课程笔记

[![OOP](https://img.shields.io/badge/OOP-121p-blue)](OOP.pdf)
[![Practice](https://img.shields.io/badge/Practice-50p-green)](Practice.pdf)
[![Command](https://img.shields.io/badge/Command-30p-orange)](Command.pdf)
[![Syntax](https://img.shields.io/badge/Syntax-23p-purple)](Syntax.pdf)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

---

## Table of Contents / 目录

- [English Version](#english-version)
- [中文版本](#中文版本)

---

## English Version

### About This Repository

This repository contains the complete course notes for **Object Oriented Programming** (Course Code: 22EM31202C), a core course in the **BSc in Applied Data Science** program jointly offered by Harbin Institute of Technology and emlyon business school. All notes are written in LaTeX, bilingual (English/Chinese), and meticulously structured for exam review and daily reference.

### Course Information

| Field | Details |
|-------|---------|
| **Course Name** | Object Oriented Programming |
| **Course Code** | 22EM31202C |
| **Instructors** | Imène BRIGUI / Saeed VARASTEN YAZDI |
| **School** | School of Management, HIT |
| **Program** | Big Data Management and Application (Sino-Foreign Cooperative) |
| **Institutions** | Harbin Institute of Technology × emlyon business school |
| **Credits** | 2 Credits / 32 Credit Hours |
| **Assessment** | 50% Final Exam + 50% Project |
| **Term** | Spring Semester, First Year |

### File Overview

| File | Description |
|------|-------------|
| 📄 `OOP.pdf` | **Full compiled notes** (121 pages) — Cover, Preface, TOC, 9 Chapters, 2 Practice Sets, Appendix |
| 📝 `OOP.tex` | Master LaTeX source file (~5,000 lines) |
| 📊 `Practice.pdf` | **Practice Case Collection** (50 pages, 159 examples) — All example boxes extracted |
| 📝 `Practice.tex` | Practice case LaTeX source file |
| 📋 `Command.pdf` | **Standalone Command Reference** (30 pages, ~300 commands, 14 sections) — Complete quick reference |
| 📝 `Command.tex` | Command reference LaTeX source file |
| 📗 `Syntax.pdf` | **Python Basic Syntax Tutorial** (23 pages, 8 chapters) — Concise syntax guide for beginners |
| 📝 `Syntax.tex` | Syntax tutorial LaTeX source file |
| 📘 `OOP.doc` | Official course syllabus |
| 🖼️ `HIT_logo.png` | Harbin Institute of Technology logo |
| 🖼️ `emlyon_logo.png` | emlyon business school logo |

### Chapter Overview

| # | Chapter | Key Topics |
|---|---------|------------|
| **01** | Variables & Data Types | Variables, primitive types, strings, operators, type casting, string formatting, user input |
| **02** | Control Structures | Conditionals (if/elif/else), functions, scope, loops (for/while), control keywords (break/continue/pass) |
| **03** | Data Structures | Tuples, lists, dictionaries, sets, list comprehensions, sorting, reference pitfalls |
| **04** | Modules & Packages | Import variations, standard library (copy, math, time), pip, NumPy basics (arrays, reshape, masking) |
| **05** | Object-Oriented Programming | Classes, `__init__`, attributes, methods, `__str__`, inheritance, `super()`, `@property`/setter, polymorphism, destructor |
| **06** | File I/O & Error Handling | `open()` modes, `with` statement, CSV read/write, try/except/else/finally/raise, PEP-8 style guide, debugging |
| **07** | Visualization (Matplotlib) | Figure/Axes hierarchy, `subplots()`, colors/markers/linestyles, colormaps, legends, ticks, spines, mathtext |
| **08** | Pandas Library I | DataFrame/Series, creation (dict/list/CSV), indexing (.loc/.iloc/.at/.iat), metadata, data manipulation, join/merge, groupby |
| **09** | Pandas Library II | Data cleaning (NaN, renaming, type conversion), feature engineering (lambda, binning, encoding), pivot tables, crosstabs, **10 plot types** (line/bar/barh/hist/box/scatter/area/pie/density/hexbin) |
| **P1** | Practice Set 01 — COVID-19 | France COVID dataset: groupby aggregation, bar plots, line plots (Seaborn) |
| **P2** | Practice Set 02 — Netflix | Netflix titles dataset: dictionary operations, text filtering, director rankings, bar charts |
| **📎** | Appendix | **Complete Command Reference** (~300 commands, 14 sections — also available standalone as `Command.pdf`) |

### Notebook Features

- ✅ **Bilingual** — Every concept, warning, and example has English + Chinese explanations
- ✅ **Three Colored Callout Boxes** — Concept (blue), Warning (red), Example (green)
- ✅ **Code Line Numbers** — All Python code blocks have syntax highlighting + line numbers
- ✅ **PDF Bookmarks** — Hierarchical navigation by chapters/sections/subsections
- ✅ **Page Headers & Footers** — Chapter name + page number on every page
- ✅ **Structured TOC** — Dot leaders, colored entries, indented subsections
- ✅ **HIT × emlyon Cover** — Dual university logos, author name + ID (二叉苹果树)
- ✅ **Preface** — Course info, author bio, acknowledgments (Claude Code + DeepSeek V4 Pro)
- ✅ **Visualizations** — Actual rendered charts (Matplotlib/Seaborn) embedded in Practice Sets

### Chapter Folders

Each subfolder (`01 - Variables/` through `09 - Pandas Library II/`) contains:
- `main.tex` — Standalone chapter source
- `main.pdf` — English-only compiled version
- `main_cn.pdf` — Bilingual compiled version (where available)

### Tech Stack

| Component | Tool |
|-----------|------|
| **Typesetting** | XeLaTeX + xeCJK (MiKTeX) |
| **Code Highlighting** | `listings` package |
| **Visualizations** | Matplotlib + Seaborn |
| **Data Analysis** | Pandas + NumPy |
| **AI Assistance** | Claude Code + DeepSeek V4 Pro |

### About the Author

**Ziyang Huang** (ID: 二叉苹果树) — Class of 2025, School of Management, Harbin Institute of Technology. BSc in Big Data Management and Application (Sino-Foreign Cooperative Program with emlyon business school).

These notes were originally created during final exam preparation by reorganizing 9 course PDFs into structured bilingual LaTeX notes. Formatting, title unification, appendix compilation, and cover design were assisted by Claude Code + DeepSeek V4 Pro.

---

## 中文版本

### 关于本仓库

本仓库是 **面向对象编程**（课程代码：22EM31202C）的完整课程学习笔记。该课程是哈尔滨工业大学与法国里昂商学院联合举办的**应用数据科学本科项目**（BSc in Applied Data Science）一年级春季学期专业核心课。所有笔记使用 LaTeX 编写，中英双语对照，结构严谨，适合期末复习和日常参考。

### 课程信息

| 项目 | 内容 |
|------|------|
| **课程名称** | Object Oriented Programming（面向对象编程） |
| **课程代码** | 22EM31202C |
| **授课教师** | Imène BRIGUI / Saeed VARASTEN YAZDI |
| **开课学院** | 经济与管理学院 |
| **专业** | 大数据管理与应用（中外合作办学） |
| **合作院校** | 哈尔滨工业大学 × 法国里昂商学院 |
| **学分/学时** | 2 学分 / 32 学时 |
| **考核方式** | 期末考试 50% + 项目 50% |
| **学期** | 一年级春季学期 |

### 文件说明

| 文件 | 说明 |
|------|------|
| 📄 `OOP.pdf` | **完整合并版笔记**（121 页）——含封面、前言、目录、9 章正文、2 套练习题、附录速查表 |
| 📝 `OOP.tex` | 合并版 LaTeX 源文件（约 5000 行） |
| 📊 `Practice.pdf` | **实战案例合集**（50 页，159 个案例）——提取全书的 examplebox 独立成册 |
| 📝 `Practice.tex` | 实战案例 LaTeX 源文件 |
| 📋 `Command.pdf` | **独立命令速查表**（30 页，约 300 条命令，14 个分类）——完整快速查阅手册 |
| 📝 `Command.tex` | 命令速查表 LaTeX 源文件 |
| 📗 `Syntax.pdf` | **Python 基础语法教程**（23 页，8 章）——精简版语法入门指南 |
| 📝 `Syntax.tex` | 语法教程 LaTeX 源文件 |
| 📘 `OOP.doc` | 官方课程教学大纲 |
| 🖼️ `HIT_logo.png` | 哈尔滨工业大学校徽 |
| 🖼️ `emlyon_logo.png` | 法国里昂商学院校徽 |

### 章节内容总览

| 章节 | 标题 | 核心内容 |
|------|------|----------|
| **01** | 变量与数据类型 | 变量基础、原始类型、字符串完全指南、运算符、类型转换、格式化输出、用户输入 |
| **02** | 控制结构 | 条件判断（if/elif/else）、函数定义与调用、作用域、循环（for/while）、break/continue/pass |
| **03** | 数据结构 | 元组、列表、字典、集合、列表推导式、排序、引用陷阱（重要考点） |
| **04** | 模块与包 | 四种导入方式、标准库（copy/math/time）、pip 包管理、NumPy 数值计算（数组创建/变形/掩码） |
| **05** | 面向对象编程 | 类定义、`__init__` 构造函数、属性、方法、`__str__` 魔术方法、继承、`super()`、`@property`/setter、**多态**、**析构函数** |
| **06** | 文件IO与错误处理 | `open()` 模式、`with` 语句上下文管理器、CSV 读写、try/except/else/finally/raise 完整异常处理、PEP-8 编码规范、调试技巧 |
| **07** | 数据可视化（Matplotlib） | Figure/Axes 容器层级、`subplots()` 子图管理、颜色/标记/线型、色图、图例、刻度、边框、数学公式 |
| **08** | Pandas 库 I | DataFrame/Series 两大核心、创建方式（字典/列表/CSV）、索引切片（.loc/.iloc/.at/.iat）、数据修改、join/merge、groupby 分组聚合 |
| **09** | Pandas 库 II | 数据清洗（NaN/重命名/类型转换）、特征工程（lambda/分箱/编码）、透视表/交叉表、**10 种绘图**（折线/柱状/水平/直方/箱线/散点/面积/饼图/密度/六边形） |
| **P1** | 练习题集 01 — 新冠疫情 | 法国新冠数据集：分组聚合、柱状图、折线图（Seaborn） |
| **P2** | 练习题集 02 — Netflix | Netflix 影视数据集：字典操作、文本筛选、导演排行、柱状图 |
| **📎** | 附录 | **全课程命令速查表**（约 300 条，14 个分类 —— 也可独立查阅 `Command.pdf`） |

### 笔记特色

- ✅ **中英双语** — 每个概念框、避坑指南、实战案例均有中英文对照解释
- ✅ **三色提示框** — 核心概念（蓝色）、避坑指南（红色）、实战案例（绿色）
- ✅ **代码行号** — 所有 Python 代码块含语法高亮 + 行号
- ✅ **PDF 书签** — 章/节/子节三级层级导航
- ✅ **页眉页脚** — 每页显示章节名称 + 页码
- ✅ **目录美化** — 引导点连线、彩色条目、子节缩进
- ✅ **双校徽封面** — HIT + emlyon 校徽、作者姓名 + ID（二叉苹果树）
- ✅ **前言页** — 课程介绍、作者简介、工具致谢
- ✅ **可视化图表** — Practice Set 中嵌入 Matplotlib/Seaborn 实际生成的图表

### 章节文件夹

每个子文件夹（`01 - Variables/` 至 `09 - Pandas Library II/`）包含：
- `main.tex` — 独立章节 LaTeX 源文件
- `main.pdf` — 纯英文编译版
- `main_cn.pdf` — 中英双语编译版（如有）

### 技术栈

| 功能 | 工具 |
|------|------|
| **排版引擎** | XeLaTeX + xeCJK（MiKTeX） |
| **代码高亮** | `listings` 宏包 |
| **数据可视化** | Matplotlib + Seaborn |
| **数据分析** | Pandas + NumPy |
| **AI 辅助** | Claude Code + DeepSeek V4 Pro |

### 关于作者

**黄子扬**（ID：二叉苹果树）— 哈尔滨工业大学经济与管理学院 2025 级本科生，大数据管理与应用（中外合作办学）专业。

本笔记诞生于期末备考阶段——将 9 章课程 PDF 逐一拆解，用 LaTeX 重排为结构化双语笔记，确保覆盖原课件全部内容。初稿完成后，借助 Claude Code + DeepSeek V4 Pro 辅助完成了格式优化、标题统一、附录速查、封面排版等打磨工作，最终形成这份完整的课程笔记。

### 更新日志

| 日期 | 版本 | 更新内容 |
|------|------|----------|
| 2026-06 | v3.1 | 新增 `Command.pdf`（独立命令速查表，30页/300条/14类）和 `Syntax.pdf`（Python基础语法教程，23页/8章） |
| 2026-06 | v3.0 | 新增 Practice Set 01（COVID-19）和 02（Netflix），含可视化图表；新增多态与析构函数章节；Pandas 可视化扩展至 10 种；全文中英双语完善 |
| 2026-05 | v2.0 | 全面优化：代码行号、页眉页脚、PDF 书签、titlesec 标题格式、tocloft 目录、封面美化、附录速查表 |
| 2026-05 | v1.0 | 初始版本，9 章笔记合并 |

---

*If you find this helpful, feel free to star ⭐ this repo! 如果这份笔记对你有帮助，欢迎点亮 Star ⭐！*
