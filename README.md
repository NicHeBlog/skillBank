# skillBank
collection of skills

1. system-requirement-analyzer-v2（系统建设需求分析工具）
version: 2.0.0
description: >
  分析客户系统建设需求，评估复杂度，推荐最合适的飞书工具（aPaaS、aily专业版、aily自定义智能体、aily工作流、妙搭）或工具组合，输出详细的建设方案。
  当用户描述系统建设需求、询问"该用什么工具"、"如何建设"、"需求分析"、"方案比选"、"工具推荐"、"系统选型"、"aPaaS还是智能体"、"建系统"、"搭建系统"、"用什么方案"、"哪个工具合适"时使用此技能。
  不适用于：纯代码开发需求、非飞书生态工具选型、硬件选型。


2. customer-insight-analyzer（全维度客户透视分析）
description: 当用户输入客户名称并需要进行深度B2B战略分析时使用。适用于销售、商务拓展、战略咨询等场景，通过四维模型（Identity/Momentum/Human/Action）对目标客户进行全方位透视分析，输出可行动的商业洞察。

3. garment-vision-pro-optimized（衣图转换大师V2）
description: 将服装设计手绘稿、草图转化为高精度实物样衣效果图，支持面料材质渲染和多版本模特上身图生成，最终输出整合PDF文档。适用于服装设计师、品牌主理人、电商运营人员。当用户上传服装手绘稿/设计草图，或要求"将设计图转为实物图"、"生成模特上身图"、"制作服装效果图"时触发此技能。
allowed-tools:
  - bash
  - image_generate
  - file
  - aily-pdf