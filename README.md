# Blitz Del

Blitz Del 是一个仅适用于 Windows 的 VS Code 扩展，项目目标是解决 `node_modules` 删除过慢的问题，并服务于习惯在资源管理器右键菜单中删除文件的用户。

## 可执行文件来源

- 扩展内置二进制文件：`bin/blitz-del.exe`
- 来源仓库：<https://github.com/CeeVeeX/blitz-del>
- 说明：该 `exe` 为上述仓库的编译产物

## 功能

- 在资源管理器文件右键菜单中提供“闪电删除 / Blitz Delete”命令
- 重点优化大目录（如 `node_modules`）删除体验
- 调用 `bin/blitz-del.exe` 对选中文件执行删除操作

## 适用环境

- 操作系统：Windows (`win32`)

## 开发与调试

- 安装依赖：`pnpm install`
- 调试扩展：在 VS Code 中按 `F5` 运行 `Run Extension`
