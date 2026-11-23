# Changelog

## 0.3.0 — 2026-11-23

- 「初始化与接入」明确全跟踪、常规跟踪、只公开核心成果三类跟踪边界，不再讨论仓外版本与跨机可达。
- 补充不暴露被排除项的做法：`.gitignore` 用通配黑名单配显式白名单，通配未覆盖的本机私有项写入 `.git/info/exclude`，已跟踪的文件、注释与提交说明不提及未跟踪内容。
- 去掉 `SKILL.md` 中纯装饰性的粗体标记与冗余引导词。

## 0.2.0 — 2026-11-22

- skill 目录迁至 `skills/project-handoff/`。已安装的用户照常运行 `npx skills add briqt/project-handoff -g -y` 或 `npx skills update project-handoff` 即可，安装器会自动定位新路径。
- description 改为按能力边界描述，不再枚举触发词和场景。
- SKILL.md 增加 `metadata.version`。方法论正文没有变化。

## 0.1.0 — 2026-11-20

首个公开版本：四条指导思想（成事优先、随时可接、沉淀宁缺毋滥、规则从简）与一条底线（项目自足），以及落点、初始化与接入、规则三部分。
