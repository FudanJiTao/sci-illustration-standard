# 科研绘图规范 (Scientific Illustration Standard)

这是一个为 **AI 辅助科研绘图** 设计的技能包（Skill）。它定义了严格、可执行的 Adobe Illustrator 绘图规范，包括画板尺寸、字体、子图布局、描边、配色及导出格式。

支持在 **Codex、Cursor、Claude、DeepSeek、GitHub Copilot** 等 AI 工具中直接调用，用于自动生成符合期刊发表要求的科研图表。

---

## 🚀 快速安装

### 方法一：通用命令行（推荐）
```bash
npx skillsgate add 你的GitHub用户名/sci-illustration-standard

方法二：手动复制 SKILL.md 内容

将仓库中的 SKILL.md 内容粘贴到你的 AI 对话中作为系统提示（或保存为自定义指令）。

---

📐 规范摘要

项目 要求
画板 A4 (210×297 mm) 纵向
Figure 标签 (105 mm, 12 mm) 顶部对齐，Arial 18pt，格式 “Figure 1”
子图尺寸 常规 60×60 mm，从左到右排列
子图编号 左上角，Arial 12pt，大写字母 A, B, C…
内部文字 坐标轴/刻度/图例等：Arial 6pt；子图标题：Arial 8pt
描边 全部 0.5 pt，黑色
配色 默认 Nature 风格，优先服从用户指定
导出 整图 PDF，每个子图单独 SVG

详见 SKILL.md。

---

💡 使用示例

在 AI 工具中直接说：

“按照科研绘图规范，生成 Figure 1，包含 A、B 两个 60×60 mm 的子图，用柱状图展示对照组和实验组数据。”

AI 会自动遵循规范生成对应的插图代码或 AI 操作步骤。

---