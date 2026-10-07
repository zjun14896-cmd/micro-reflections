# Micro Reflections

把中文语音转写、夹杂英文的碎片感受或一天的零散记录，整理成多个简短、具体、可以继续行动的小复盘。

> Turn messy daily notes into small, honest reflections with one practical next step.

当前版本：`v0.1.0`

## 它解决什么问题

一天里经常会留下很多零散内容：一句突然想到的话、一段语音转写、一次身体感受，或者一个还没想完整的发现。它们不适合写成长篇日记，但直接丢在聊天记录里又很容易消失。

这个 Skill 使用一个轻量结构，把每个主题整理为独立的小复盘：

```text
零散口述或文字
      ↓
识别不同事件与发现
      ↓
拆成多个 micro reflections
      ↓
Fact → Notice → Tiny Action
```

每条复盘固定包含：

- `What I did`：发生了什么
- `What I noticed`：我注意到了什么
- `Next time`：下一次可以做的一个小动作

## 适合谁

- 经常使用语音输入记录想法的人
- 想做日常小复盘，但不想每天写长篇日记的人
- 记录里经常中英文混用的人
- 希望保留生活细节，而不是被 AI 总结成抽象口号的人
- 想把反思落到一个很小、可执行动作上的人

## 核心原则

- 一个复盘只围绕一个中心发现。
- 保留第一人称、真实语气和具体生活细节。
- 不把一次经历拔高成普遍规律。
- `Next time` 只保留一个小动作，也允许“继续保持”或“暂时不调整”。
- AI 新增的建议必须使用 Markdown 斜体标记，不冒充用户原本的想法。
- 默认不增加日期、标签、金句、评分或额外总结。

## 整理前后示例

- [原始记录](examples/raw-notes.md)
- [整理结果](examples/micro-reflections.md)

## 安装

### 下载 ZIP

1. 在 GitHub 页面选择 **Code → Download ZIP**。
2. 解压后，把整个 `micro-reflections` 文件夹放进 Codex 的个人 Skills 目录。
3. Windows 默认位置通常是：

```text
C:\Users\你的用户名\.codex\skills\micro-reflections
```

### 使用 Git

```powershell
git clone https://github.com/zjun14896-cmd/micro-reflections.git "$env:USERPROFILE\.codex\skills\micro-reflections"
```

## 使用

把一天的零散文字或语音转写交给 Codex，然后说：

```text
请用 $micro-reflections 帮我做一个小复盘。
```

也可以自然地说：

```text
把这些零散记录按 What I did / What I noticed / Next time 整理一下。
```

## 它不会做什么

- 不会把内容扩写成长篇日记或公开文章。
- 不会为了显得深刻而添加宏大结论。
- 不会把多个行动建议塞进一条复盘。
- 不会自动保存、移动或覆盖你的原始文件，除非你明确要求。

## v0.1.0 范围

当前版本专注于：理解零散输入、拆分主题、保留具体体验，并整理为结构稳定的短复盘。

## License

[MIT](LICENSE)
