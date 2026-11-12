# makemind

**Let AI execute anything. Every MCP server is an app.**

Open-source Dart & Flutter framework for turning any MCP server into a
controllable app — UI, bundles, knowledge, and runtime kernels, built on the
Model Context Protocol.

- 📦 **Packages** — [pub.dev/publishers/makemind.dev](https://pub.dev/publishers/makemind.dev/packages)
- 📖 **Specifications** — [app-appplayer/specs](https://github.com/app-appplayer/specs)
- 🌐 **Site** — [app-appplayer.github.io/makemind](https://app-appplayer.github.io/makemind)
- 🧪 **Samples** — [github.com/makemind-academy](https://github.com/makemind-academy) · clone one, run `bash verify.sh`
- 🎓 **Lessons** — [academy.makemind.dev](https://academy.makemind.dev)
- 📰 **Magazine** — [makemind.dev](https://makemind.dev)

## The stack

| Layer | Packages |
|---|---|
| **Runtime / orchestration** | `mcp_bundle` · `mcp_gateway` · `mcp_flow_runtime` · `mcp_canvas` |
| **MCP protocol** | `mcp_client` · `mcp_server` · `mcp_llm` · `flutter_mcp` |
| **Knowledge** | `mcp_knowledge` · `mcp_fact_graph` · `mcp_skill` · `mcp_profile` · `mcp_knowledge_ops` · `mcp_philosophy` |
| **UI** | `flutter_mcp_ui_core` · `flutter_mcp_ui_runtime` · `flutter_mcp_ui_generator` · `appplayer_ui_view` |
| **IO** | `mcp_io` (+ websocket · http · mqtt · serial · can · modbus · opcua · scpi) |
| **Specialized** | `mcp_channel` · `mcp_form` · `mcp_analysis` · `mcp_ingest` · `mcp_browser` |
| **Cores** | `appplayer_core` · `brain_kernel` · `flowbrain_core` |
| **Utilities** | `appplayer_secure` · `appplayer_claude_code_provider` |

## Apps

- **AppPlayer Standard** — open reference player; one Flutter codebase across
  Android, iOS, Linux, macOS, Web, Windows.
- **AppPlayer Studio** — universal desktop host that loads any installed domain
  bundle (`.mcpb`) into a workspace, with built-in App Builder / Ops / Scene
  Builder.

---

Built on the [Model Context Protocol](https://modelcontextprotocol.io).
