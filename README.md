
文档：[claude-code-binary-tool-calling-re.md](./claude-code-binary-tool-calling-re.md)

对最新官方稳定版 `claude` 2.1.301（darwin-arm64，Oct 15, 2026）进行了逆向，下面是整理的文件，包含：报告、Mach-O、字符串命中与 CLI 记录

| 文件 | 介绍 |
|------|------|
| `triage.md` | Craft 对 `claude` 的首诊：Mach-O arm64、已 strip、建议下一步工具。 |
| `macho.md` | Mach-O 头、链接库、导入导出与代码签名等加载结构明细。 |
| `sections.md` | 段/节列表，标出 `__text`、`__bun`、`__jsc_int` 等关键区。 |
| `cli-runtime.txt` | 实际跑 CLI：`version`/`auth`/`mcp help` 与工具相关 flags。 |
| `feature-tool_use.md` | 以 `tool_use` 做特征追踪：命中字符串多、函数 xref 为 0。 |
| `strings-tool.txt` | 第一轮字符串猎捕：`tool_use`、`mcp__`、`PreToolUse` 等命中汇总。 |
| `strings-tool-surface.txt` | 工具面深挖：权限、MCP、`BashTool` 等符号与文案。 |
| `strings-tool-classes.txt` | 按 `*Tool` 类名检索：`FileReadTool`、`getAllBaseTools` 等。 |
| `strings-harness-core.txt` | harness 核心入口：`runToolUse`、`streamingToolExecutor`、hooks。 |
| `mcp-prefix-strings.json` | `mcp__` 相关字符串的 JSON 证据（命名/权限规则等）。 |
| `pairing-strings.json` | `ensureToolResultPairing` 的配对校验/修复相关字符串证据。 |
| `tool-class-names.txt` | 正则扫出的含 `Tool` 的原始字符串列表。 |
| `tool-classes-clean.txt` | 过滤后的干净 `XxxTool` 类名清单，便于对照官方工具表。 |