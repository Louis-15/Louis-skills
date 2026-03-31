# 🤖 Antigravity & Gemini Skills Collections

这个仓库用于存放为 Antigravity Agent 和网页版 Gemini 开发的高质量自定义 **Skills（技能指令）** 与 **System Prompts（系统规则）**。

## 📁 目录结构

*   [`system_prompt_builder_rules/`](./system_prompt_builder_rules) - 包含纯背景知识、个性化设定与环境边界规则的构建器，适用于免执行复杂工作流的助理配置（如专属 Gemini Gem）。
*   [`system_prompt_builder_workflow/`](./system_prompt_builder_workflow) - 包含严格执行流程约束的技能构建器，适用于需要进行复杂结构化推演的 Antigravity 自动化任务配置。
*   [`SKILL.md`](./SKILL.md) - 全局或通用说明。

## 💡 如何使用这些 Skills

如果您使用的是 **Antigravity** 环境，只需将其添加为工作区 Rule，或利用 `npx` (如有配套脚手架) 安装。
如果您使用的是 **网页版 Gemini (Gems)**，可以直接复制各个子目录下的 Markdown 文件内容，填入您的专属助理的 "Instructions" 栏目中，即可获得拥有极强专业能力的定制 AI 伙伴。
