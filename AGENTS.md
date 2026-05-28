# 项目协作规则

## GitHub 操作

本项目中所有 GitHub 相关操作必须基于云端流程完成，不要从本地进行上传。

- 默认 GitHub 仓库为 `NickSquirrel/WitcherTaskCreator`：https://github.com/NickSquirrel/WitcherTaskCreator
- 当用户没有另行指定仓库时，所有 GitHub 查询、创建、更新、文件写入、Issue、Pull Request 和 CI 相关操作都默认作用于该仓库。
- 不要从本地执行 `git push`、`gh repo sync`、`gh pr create` 或任何会把本地提交、分支、文件、发布包上传到 GitHub 的命令。
- 如需查看仓库、Issue、Pull Request、Review、CI 或云端文件状态，优先使用 GitHub 云端工具、连接器或网页/API 查询。
- 如需创建、更新或发布 Pull Request，应先确认可用的云端流程；如果只能通过本地上传完成，必须停止并向用户说明限制。
- 可以在本地编辑、验证和整理文件，但不得把这些本地变更直接上传到 GitHub。
