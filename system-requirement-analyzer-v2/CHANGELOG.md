# 版本变更记录

## v2.0.0 (2026-03-30)

### 重大变更
- **流程重构**：从"自由分析"改为"结构化采集 → 量化评估 → 规则匹配 → 方案输出"四阶段标准化流程
- **量化评分**：六维度评估从"强/中/弱"定性描述改为 1-5 分量化评分，每个分值有明确判定标准
- **决策规则化**：决策树从伪代码文本改为可执行的条件-结论规则表
- **模块化拆分**：消除 SKILL.md 与 references 的内容重复，遵循 Single Source of Truth 原则

### 新增
- 信息不足时的追问机制（前置信息完整性校验）
- 推荐置信度评级（高/中/低）
- 用户角色自适应输出（业务负责人 / 技术同学）
- 反模式校验步骤（推荐前强制检查）
- 反面案例/失败案例（anti_patterns.md）
- 简要版输出模板（output_template_brief.md）
- CHANGELOG 版本管理
- 关键假设显式标注机制

### 优化
- description 触发词扩充（增加"方案比选""工具推荐""系统选型"等）
- 增加否定边界说明（不适用于纯代码开发等）
- 组合方案增加优先级排序规则和触发条件
- 案例库增加 eval 用例格式（期望输出标注）

### 文件结构变更
- 新增 `CHANGELOG.md`
- 新增 `references/decision_rules.md`（原决策矩阵+评分标准合并重构）
- 新增 `references/combination_guide.md`（从 decision_matrix.md 拆出）
- 新增 `references/anti_patterns.md`（从 decision_matrix.md 拆出并扩充）
- 新增 `references/output_template_detailed.md`
- 新增 `references/output_template_brief.md`
- 重构 `references/tools_capability.md`（增加版本号和更新日期）
- 重构 `references/examples.md`（增加 eval 标注）
- 删除 `references/decision_matrix.md`（内容拆分到多个专项文件）

---

## v1.0.0 (初始版本)

- 初始版本，包含基础分析流程、决策树、工具能力说明和案例库
