# 🧠 个人大脑

> 我的第二大脑 — 由 AI Agent 自动维护和进化

## 目录结构

```
个人大脑/
├── wiki/          # 知识库 — Agent 自动生成的 Markdown 页面
├── raw/           # 原始素材 — 丢进去的文件，Agent 会自动消化
├── graph/         # 知识图谱可视化
└── tools/         # 工具脚本
```

## 如何使用

### 手动添加知识
1. 把文件（PDF、文本、JSON 等）丢进 `raw/` 文件夹
2. 告诉 Agent："消化 raw 文件夹"
3. Agent 会读取、提取知识、写入 `wiki/`

### 查询知识
- 在 Obsidian 中打开 `wiki/index.md` 浏览索引
- 直接在 Obsidian 搜索
- 告诉 Agent："查一下 XXX"

### 多端同步
- **Windows 电脑**：Obsidian 打开 `D:\个人大脑`
- **安卓手机**：Obsidian App + Git 插件同步 GitHub 仓库

## 技术栈

- **存储**：纯 Markdown + Git
- **同步**：GitHub（免费）
- **Agent**：AI 自动读写 wiki/ 目录
- **前端**：Obsidian（Windows + Android）

---

*最后更新：$(date +%Y-%m-%d)*
