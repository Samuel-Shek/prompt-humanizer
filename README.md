# Prompt Humanizer

提示词优化 + 中文去 AI 味，二合一 Skill。给 Work Buddy / Claude Code / Codex 等支持 Agent Skills 的工具用。

## 安装（Work Buddy）

1. 下载或克隆本仓库
2. 把 `prompt-humanizer` 文件夹放到 Work Buddy 的技能目录：

```bash
# macOS 默认路径
cp -r prompt-humanizer ~/.workbuddy/skills/
```

3. 重启 Work Buddy，或新开一个会话

其他工具同理：把文件夹放进该工具的 skills 目录即可（如 `~/.claude/skills/`、`~/.agents/skills/`）。

## 怎么用

**优化提示词：**

> 优化提示词：帮我写个分析销售数据的 prompt

**去 AI 味 / 润色：**

> 去 AI 味：（粘贴你的正文）

**两步一起：**

> 写个周报提示词，写完再去下 AI 味

## 两个模式

| 模式 | 触发词 | 做什么 |
|---|---|---|
| 提示词优化 | 优化提示词、改写 prompt、精简/扩写 System Prompt | 产出一份可直接复制的终版提示词 |
| 人类写作 | 去 AI 味、润色、改自然点、说人话 | 保真去掉 AI 腔，不改事实 |

- 默认**保真**：不编造数据、不改事实、原文已经自然就原样返回
- 要更大幅度改写，需明确说「启用创作模式」

## 不适用

从零写文章 / 写爆文 / 起标题 / 改代码 / 改配置 / 翻译

## 许可

MIT。人类写作部分衍生自 [blader/humanizer](https://github.com/blader/humanizer) → [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)。
