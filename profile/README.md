<img src="https://raw.githubusercontent.com/xdev-asia/site/main/public/assets/logo.png" alt="" width="64" height="64">

# xDev

Local-first project knowledge for humans and AI agents. **[xdev.asia](https://xdev.asia)**

Your Markdown docs stay the source of truth. xDev indexes them, flags docs that went stale after code changed, hands the right context to coding agents (Claude Code, Codex, Gemini CLI, Cursor) over files and MCP, and runs agent tasks in their own git worktrees so nothing lands without your review.

> Status: early preview. Builds are unsigned; expect breaking changes.

## Repositories

| Repo | What | Status |
|---|---|---|
| [xdev](https://github.com/xdev-asia/xdev) | Rust core, `xdev` CLI, desktop app (Tauri 2), architecture decisions | Active |
| [registry](https://github.com/xdev-asia/registry) | Signed index of app packs the desktop app can install, plus a block list | Placeholder |
| [site](https://github.com/xdev-asia/site) | Website at [xdev.asia](https://xdev.asia) (Next.js, static export) | Active |

## Get it

Installers for Windows (x64, ARM64), macOS (Apple silicon, Intel) and Linux (x64, ARM64) are on the [xdev releases page](https://github.com/xdev-asia/xdev/releases). The app updates itself when a new version ships.

## Principles

- Files you own come first: Markdown in your repo, SQLite only as an index.
- Works offline; AI is optional and you choose the provider.
- Agents act through tasks you can review, with a policy you own.
- Plugins run sandboxed and reach data only through `xdev-api`.

## License

Open source under Apache-2.0.
