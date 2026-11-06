# mygod

mygod is a self-hosted music engine built to be driven by AI agents.

It unites several online music providers and your local music library into
one playback session — one queue, one position, one volume — and exposes
two interfaces for control:

- **mygod-mcp** — an MCP stdio server for Trae, Codex, WorkBuddy, and any
  agent that speaks MCP
- **mygod-cli** — a command-line tool for scripts, hotkeys, and shells

You talk to it in natural language: "play that song I half-remember with
lyrics 'late wind through the old alley', name might be 风起时" — the agent
queries every configured source, ranks candidates by artist, duration, and
release info, resolves the match, builds the queue, and starts playback.

Self-hosted · no account · no data upload · macOS Apple Silicon (arm64) now,
other platforms by request.