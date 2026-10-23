# 第三方资源与外部依赖说明

## 1. DuMate / Dots AI

- 类型：第三方 AI 平台与 API 服务
- 使用方式：用于 Agent 运行、模型推理和相关任务执行
- 运行参数：由用户在本地自行配置 API Key、服务地址和模型
- 重要限制：遵守平台服务协议、输入输出规则、数据安全要求和品牌使用规则；不得公开 API Key，不得将平台内部实现冒充为本项目代码
- 本项目关系：PetMind AI 是基于平台能力开发的应用和业务 Skill，不代表平台官方产品或官方合作

## 2. `pdf` 与 `visualized-output`

- 类型：DuMate 平台提供的外部公共 Skill
- 使用方式：PetMind Agent 在平台环境中调用 PDF 生成和可视化输出能力
- 本仓库状态：仅作为外部依赖说明，不包含其内部实现文件
- 许可证/授权：以 DuMate 平台当前公布的规则和授权说明为准；本仓库 MIT License 不扩展到这些平台能力

## 3. Chart.js

- 类型：开源 JavaScript 图表库
- 版本：4.4.1
- 来源：jsDelivr CDN
- 许可证：MIT
- 官方许可证：https://github.com/chartjs/Chart.js/blob/master/LICENSE.md
- 使用方式：用于网页端趋势图表和指标可视化

## 4. 其他依赖

如后续增加第三方库、模型、数据集、图片、字体或其他素材，应在本文件中补充其版本、来源、许可证、使用方式和限制条件。
