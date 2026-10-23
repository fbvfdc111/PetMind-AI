# PetMind AI

PetMind AI 是一个基于 AI Agent 的宠物主动健康观察辅助应用，帮助用户建立宠物档案、记录连续行为数据、识别多指标变化、生成七日观察计划，并输出结构化报告。

## 项目组成

- `PetMind_AI_v3a.html`：单文件网页应用，支持宠物档案、行为记录、趋势分析、事件记录、观察计划和报告展示。
- `PetMind_AI_DuMate_Skill/`：PetMind AI 自主设计的 DuMate 插件、Agent 配置、业务 Skill 和测试用例。
- `PetMind_AI_DuMate_Skill/skills/petmind-ai/tests/cases.json`：标准化功能测试用例。

## 运行说明

直接打开 `PetMind_AI_v3a.html` 即可体验基础功能。网页中的云端 AI 功能需要用户自行配置 Dots AI API Key；API Key 仅应在本地运行时输入，不应写入代码或提交到公开仓库。

PDF 生成和可视化输出依赖 DuMate 平台提供的外部公共能力。本仓库不包含这些平台能力的内部实现。

## 开源范围

本仓库公开作者自主开发的网页代码、Agent 配置、PetMind 业务 Skill、测试用例和说明文档。示例数据仅用于功能演示，不构成医学样本或诊断依据。

## 安全与使用边界

PetMind AI 仅用于宠物日常健康观察和信息整理辅助，不进行医学诊断，也不能替代执业兽医的检查、诊断和治疗建议。涉及持续或加重的异常情况，应及时咨询专业兽医。

请勿在公开仓库中提交 API Key、个人信息、未授权的第三方素材、平台内部文件或其他敏感配置。

## 许可证

本项目自主开发部分采用 MIT License，第三方服务和平台公共能力不包含在本项目许可证范围内，具体说明见 `THIRD_PARTY_NOTICES.md`。
