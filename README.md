# 开发技能集

四个独立的中文开发技能，可按项目需要单独使用。

| 技能 | 调用标识 | 适用场景 |
| --- | --- | --- |
| [PC 产品界面设计](skills/dev-pc-product-ui-design/SKILL.md) | `$dev-pc-product-ui-design` | 设计 PC 业务页面，对照原型交互，优化布局、功能入口、文案与组件迁移 |
| [业务接口联调](skills/dev-business-api-integration/SKILL.md) | `$dev-business-api-integration` | 核对接口契约与搜索完整性，接通查询、分页、保存回读并处理请求状态 |
| [业务权限与流程](skills/dev-business-permission-workflow/SKILL.md) | `$dev-business-permission-workflow` | 核对菜单、搜索与快捷入口的权限，保持接口数据范围和状态流程一致 |
| [编辑器状态与操作](skills/dev-editor-state-interaction/SKILL.md) | `$dev-editor-state-interaction` | 梳理画布编辑、撤销重做、保存恢复与组件素材接入，保持编辑状态一致 |

## 本地使用

将所需的完整技能目录从 `skills/` 复制到本机技能目录（例如 `~/.codex/skills/`），保留目录名及其内部结构。若已安装旧版，请将旧目录移出技能发现路径，避免重复。新标识即原标识加 `dev-` 前缀；旧脚本或提示词中的显式调用也需同步。
