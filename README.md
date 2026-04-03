# Prompt Generator

专业的 Prompt 生成器 Skill，帮助创建结构化、可验证、低幻觉的高质量 prompts。

## 简介

> 原创作者：Dan Koe  
> Skill 封装：清华虎姜妈

基于 meta-prompting 最佳实践，通过任务分解、专家协作和迭代验证来生成高质量 prompts。

## 核心特性

- 任务分解：将复杂请求分解为更小的子任务
- 独立验证：使用不同的"专家"进行独立审查
- 迭代验证：强调验证过程，减少错误和幻觉
- 避免猜测：不确定时明确声明
- 专家协作：召唤专门的"专家"角色协助
- 简洁高效：仅在必要时询问澄清问题

## 安装

将 `prompt-generator.md` 文件复制到 `~/.claude/skills/` 目录。

## 使用方法

在 Claude Code 中使用：

```
/prompt-generator
```

然后按照提示回答问题，系统会帮助您生成高质量的 prompt。

## 作者

清华虎姜妈 - 小红书内容创作者
