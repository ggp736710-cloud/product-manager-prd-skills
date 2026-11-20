# 产品经理 PRD Skills

一组面向产品经理的 Codex Skills，覆盖从需求澄清到交互原型的常见工作：需求分析、方案设计、PRD 编写、PRD 质量审查和交互原型生成。

这些 Skills 用来帮助整理材料、暴露缺口、形成可评审产物，不替代产品经理、业务方或研发对未确认事项作出决策。每个 Skill 都要求区分已知事实、推断、假设和待确认项，避免把没有依据的猜测写成需求承诺。

## 包含的 Skills

| Skill | 适用任务 |
|---|---|
| `requirement-analysis` | 分析需求背景、用户场景、范围、约束、依赖和变更影响 |
| `product-solution-design` | 设计产品能力、流程、规则、方案选项和风险 |
| `prd-specification` | 编写或维护可追溯的 PRD、业务规则与验收标准 |
| `prd-quality-review` | 审查 PRD 的流程、状态、权限、数据、验收和证据缺口 |
| `prd-prototype` | 根据需求生成与页面形态匹配的交互原型 |

## 使用方式

将需要的 Skill 文件夹复制到 Codex 的 skills 目录中，或在支持项目级 Skills 的环境中将仓库作为 Skills 来源。每个文件夹中的 `SKILL.md` 是入口。使用时可通过 Skill 名称调用，也可以直接描述任务，让 Codex 判断是否适用。

建议按以下顺序串联使用：

1. `requirement-analysis`：澄清问题、场景和边界。
2. `product-solution-design`：把需求转成可评审方案。
3. `prd-specification`：生成或维护 PRD。
4. `prd-quality-review`：评审 PRD 并列出可定位的问题。
5. `prd-prototype`：为评审制作匹配需求的交互原型。

五个 Skill 也可以按任务需要单独使用，不要求每次走完整流程。

## 设计约定

- 不强制凑用户、场景、评分、图表或章节。
- 无依据的业务指标、技术能力和性能目标保留为待确认，不编造。
- 按需求复杂度选择方案和交付内容。
- 评审结论是质量意见，不代替业务批准。
- 原型明确区分已确认需求、演示假设和模拟行为。

## 贡献

欢迎提交 Issue 或 Pull Request，说明使用场景、问题和建议改动。涉及规则变更时，请尽量提供复现材料，并说明它会如何影响其他工作流阶段。

## License

本项目按 MIT License 发布，详见 [LICENSE](LICENSE)。