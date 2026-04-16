# UnityMCP

这是一个基于 Unity 的 MCP 插件项目，用于把 AI 助手和 MCP 客户端连接到 Unity 编辑器，方便进行自动化开发与编辑器交互。

This is a Unity-based MCP plugin project that connects AI assistants and MCP clients to the Unity Editor for automated development and editor interaction.

## 项目内容 / Project contents

- `Assets/MCPForUnity/` — 插件核心源码、界面、服务和资源 / plugin core source, UI, services, and resources
- `Packages/` — Unity 包清单与锁定文件 / Unity package manifest and lock file
- `ProjectSettings/` — Unity 项目配置 / Unity project configuration
- `.gitignore` — Unity 生成文件忽略规则 / ignore rules for Unity-generated files

## 运行要求 / Requirements

- Unity **2021.3.44f1**
- `Packages/manifest.json` 中声明的依赖包 / dependencies declared in `Packages/manifest.json`

## 项目作用 / What this project does

MCP for Unity 通过编辑器桥接，让 AI 工具和 MCP 客户端可以与 Unity 交互。它提供了自动配置、客户端设置、桥接控制和编辑器工具。

MCP for Unity enables AI tools and MCP clients to interact with Unity through an editor bridge. It provides auto-setup, client configuration, bridge controls, and editor utilities.

## 开始使用 / Getting started

1. 使用 Unity 2021.3 打开项目。 / Open the project in Unity 2021.3.
2. 等待 Unity 完成导入。 / Wait for Unity to finish importing the project.
3. 从菜单打开插件窗口： / Open the plugin window from:
   - `Window > MCP for Unity`
4. 点击 **Auto-Setup** 完成桥接与客户端配置。 / Click **Auto-Setup** to configure the bridge and supported clients.
5. 如有需要，启动桥接，然后连接你的 MCP 客户端。 / Start the bridge if needed, then connect your MCP client.

## 注意事项 / Notes

- `Library/`、`Logs/`、`obj/`、`Temp/` 和 `UserSettings/` 等生成目录已被忽略。 / Generated folders such as `Library/`, `Logs/`, `obj/`, `Temp/`, and `UserSettings/` are intentionally ignored.
- 更详细的插件说明请查看 `Assets/MCPForUnity/README.md`。 / For more details, see `Assets/MCPForUnity/README.md`.

## 许可证 / License

如果你计划公开发布这个仓库，请在此补充项目许可证。 / Add your project license here if you plan to publish this repository publicly.
