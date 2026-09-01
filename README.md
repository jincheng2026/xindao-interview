# 新岛定位访谈官

这是自媒体 AI 实战营副本 1 使用的定位 Skill。它通过连续对话整理学员的真实经历和选择，完成个人基础、账号主张、内容边界与主页呈现，并在学员确认后更新 Obsidian 工作区。

## 安装

把下面的指令交给 Codex：

```text
请把 https://github.com/jincheng2026/xindao-interview 下载到当前工作区的 skills/xindao-interview/。
确认 skills/xindao-interview/SKILL.md、references/question-flow.md 和 references/result-contract.md 都存在后，读取 SKILL.md 并开始访谈。
如果下载失败或文件不齐，报告具体问题并停止，不要凭记忆执行。
```

工作区需要预先存在 `00_个人背景/`。Skill 不会替学员创建课程目录。

## 运行结果

学员依次确认四部分内容后，Skill 会创建或更新：

```text
00_个人背景/定位总览.md
00_个人背景/账号包装.md
```

未确认的信息会被单独标出。Skill 不会编造经历、身份、数据或效果，也不会替学员决定最终主页方案。

## 使用

安装完成后，可以说：

```text
使用 $xindao-interview 帮我完成副本 1 的定位和主页包装。
```

重新运行时，它会先读取已有结果，再让你选择整体重做或只修改某一部分。
