# 🤖 Antigravity & Gemini Skills Collections

这个仓库用于存放为 Antigravity Agent 和网页版 Gemini 开发的高质量自定义 **Skills（技能指令）** 与 **System Prompts（系统规则）**。

## 📁 目录结构

*   [`system_prompt_builder_rules/`](./system_prompt_builder_rules) - 包含纯背景知识、个性化设定与环境边界规则的构建器，适用于免执行复杂工作流的助理配置（如专属 Gemini Gem）。
*   [`system_prompt_builder_workflow/`](./system_prompt_builder_workflow) - 包含严格执行流程约束的技能构建器，适用于需要进行复杂结构化推演的 Antigravity 自动化任务配置。
*   [`SKILL.md`](./SKILL.md) - 全局或通用说明。

## 💡 如何安装和使用这些 Skills

### 📥 针对 Antigravity 用户
大语言模型的专属构建技能，允许在终端一键拉取。请复制对应区块的命令直接运行：

**1. 安装纯背景设定的系统提示词构建器（适合辅助咨询助手配置）**
```bash
npx skills add https://github.com/Louis-15/Louis-skills --skill system_prompt_builder_rules
```

**2. 安装带严谨流水线的工作流系统提示词构建器（包含完整的深挖交互步骤闭环）**
```bash
npx skills add https://github.com/Louis-15/Louis-skills --skill system_prompt_builder_workflow
```

### 📝 针对网页版 Gemini (Gems) 用户
由于不可调用终端，您可以直接进入上述对应名录中，复制文件内的所有的纯文本 Markdown 正文，直接粘贴至您的专属助理的 "Instructions" 栏目里使用。
