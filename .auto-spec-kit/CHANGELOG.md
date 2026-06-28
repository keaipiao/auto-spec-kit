# CHANGELOG

## 2026-06-28

- 建立 `.ai-workflow/` 作为工作流内核目录。
- 建立 `.auto-spec-kit/` 作为项目规格化研发产物目录。
- 将分支流程、文档模板、规则从旧的 `AI工作流/` 迁移到 `.ai-workflow/`。
- 将任务档案入口迁移到 `.auto-spec-kit/任务档案/`。
- 将“新功能”命名调整为“功能迭代”。
- 新增 `INDEX.md`、`PROJECT_STATE.md`、`CHANGELOG.md` 作为 AI 上下文恢复入口。
- 新增 `.ai-workflow/规则/08-工作流协议.md`。
- 将 `.ai-workflow/文档模板/` 重构为三层：用户可读、工程可读、AI可执行。
- 更新所有分支流程的模板路径，指向新的三层目录。
- 将前期准备中的 AI 工具能力从 Codex 单工具扩展为 Codex、Claude Code、Trae、Cursor、Kiro、Copilot 等多工具。
- 明确任务档案命名规范：`序号-分支类型-任务名称`。
- 将复杂度判断改为按分支评分、总分映射和强制升级条件共同决定。
- 新增 `.ai-workflow/规则/09-模板填写规范.md`。
- 完成 `.ai-workflow/文档模板/` 下 44 个模板的首轮补强，均包含填写说明和基础字段。
