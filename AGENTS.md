# ResearchKit · AI 开发入口

本文件只补充 Bot 管理通信接口，不更改或替代仓库既有工程规范。开展开发前，仍须阅读现有文档与代码，按实际环境验证。

## Bot 管理通信（文件协议）

这是**旁路项目管理通信**，不是产品文档或构建依赖。仅当 `.bot/` 存在时，开发 AI 在功能、重要修复、重构、阻塞与验收状态发生实质变化后更新对应 `.bot/tasks/*.md`；不要求每次提交都新增任务或输出日报。

- 原有项目规则及 `README.md` 等文档仍然优先且是产品事实权威；不要把产品规划复制进 `.bot/`。
- 复用任务 ID `RSK-...`，保持目标、验收项、状态和对应提交的验证证据；未经验证不写成通过。
- 相关中文提交**建议**追加 Git Trailer `Task: RSK-BOT-001`（按实际任务 ID 替换），不依赖 GitHub Issues、Projects 或 Actions。
- `.bot/` 可以整体删除而**不得影响**正常产品开发、测试、构建与运行；管理 AI 仅读取，不能反向控制项目代码。
- 详细协议：https://github.com/YoYotouna/Bot/blob/main/protocol/DEVELOPMENT.md
