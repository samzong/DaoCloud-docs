# 大模型服务平台 Release Notes

本页列出大模型服务平台的 Release Notes，便于您了解各版本的演进路径和特性变化。

*[hydra]: DaoCloud 大模型服务平台的内部开发代号

## 2025-07-04

### v0.7.0

- **新增** 支持文本模型的深度思考功能
- **新增** 支持文本模型的消息复制和重新生成
- **新增** 图生文模型支持同时生成多张图片
- **新增** 图生文模型支持自定义正反提示词，支持自定义图片尺寸
- **新增** 支持 100% 兼容标准的 OpenAI SDK 调用
- **新增** 支持按 API Key、模型类型、调用时间等维度进行调用统计
- **新增** 快速展示调用总量、输入 token 总数、输出 token 总数
- **新增** 支持多模型用量对比
- **新增** 支持卡片视图展示模型列表，直观呈现模型信息。
- **新增** 支持展示模型的详细介绍及 API 调用示例
- **新增** 支持文本模型的快速部署、体验
- **新增** 支持对模型根据名称、供应商、模型类型分类搜索
- **新增** 支持多模态模型的体验
- **新增** 支持图生文模型体验
- **新增** 支持已部署的模型服务列表展示
- **新增** 支持多种类模型列表，支持快速选择待部署的模型
- **新增** 支持模型服务实例的扩缩容
- **新增** 支持实例数配置：允许横向扩展实例数量
- **新增** 支持已部署的模型服务在线体验
- **新增** 支持对已部署的模型提供多种方式、多种语言的 API 调用示例：curl、python、node.js
- **新增** 支持提供一键体验功能，用于快速验证服务可用性
- **新增** 支持文本生成模型配置多种参数：system prompt（设置系统提示信息）、temperature（控制生成结果的随机性）、top_p（调整生成概率分布）
- **新增** 支持同种类型的多个模型间对比
- **新增** 支持 API Key 列表展示
- **新增** 支持一键复制完整 Key
- **新增** 支持删除指定 Key（不可恢复）
- **新增** 支持生成新 API Key，并设置自定义名称
