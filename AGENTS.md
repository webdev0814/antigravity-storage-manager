# Agent Briefing: antigravity-storage-manager

## 1. Repository Overview & Purpose
- **Repository Name**: `antigravity-storage-manager`
- **Visibility**: `Public`
- **Default Branch**: `master`
- **Last Updated / Pushed**: 2026-09-03
- **Description**: Unified AI Gateway with visual dashboard, secure Google Drive sync, Telegram notifications, multi-account profiles, real-time quota monitoring, Proxy support, MCP server, and advanced backup tools.
- **Context from README**: <p align="center"> <img src="https://raw.githubusercontent.com/unchase/antigravity-storage-manager/master/banner.png" alt="Antigravity Storage Manager"> </p> <p align="center">


---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: TypeScript, JavaScript, Node.js
- **Key Directories**: `.agent/`, `.github/`, `images/`, `l10n/`, `screenshots/`, `src/`
- **Notable Top-Level Files**: `.gitignore`, `.vscodeignore`, `CHANGELOG.md`, `CONTRIBUTING.md`, `LICENSE`, `README.md`, `SYNC_SETUP.md`, `banner.png`, `check_l10n_bundles.js`, `check_nls_keys.js`, `esbuild.js`, `eslint.config.mjs`

---

## 3. Setup & Execution Commands
### Environment Setup & Installation
```bash
npm install
```

### Running / Starting
```bash
# Check main entry point scripts or config files.
```

### Testing / Verification
```bash
npm test
```

---

## 4. Recent Commit Activity (Where We Left Off)
The most recent commits show the latest development trajectory:
- `[d863465]` (2026-07-01) feat: SQLite support, installation ID protection, markdown export fixes, and localization updates (v0.14.5)
- `[d30a5ca]` (2026-07-01) feat: restore rich quota tooltip, consolidate Gemini models, and bump to v0.14.4
- `[b991678]` (2026-04-05) fix(ci): replace tail|head with sed to avoid Broken pipe in changelog extraction
- `[694eff7]` (2026-04-05) feat: resolve issues #6, #15, #16, #17 — auth UX, backup restore, workspace re-link, markdown export
- `[dc81d5f]` (2026-04-05) chore: pre-issues-fix state — sync, l10n, localStorage updates
- `[cc88e45]` (2026-03-08) feat: grouped quota headers, per-profile usage history, UI improvements (v0.14.2)
- `[154e15a]` (2026-03-08) fix: MCP Servers panel fallback to mcp_config.json when API returns empty
- `[4e68df7]` (2026-03-06) fix(proxy): filter MCP commands by content, supporting custom commands
- `[3483e6a]` (2026-03-06) docs: update README for v0.14.1 features
- `[2739712]` (2026-03-06) fix(proxy): Test Quota account selection and infinite loading

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `master`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Agent Working Guidelines & Gotchas
- **Cross-Platform Compatibility**: Code may run across Windows, macOS, or Linux agent environments. Ensure path manipulations use OS-agnostic methods (e.g. `pathlib.Path` or `path.join`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
- **Git Commit Etiquette**: Use concise, conventional commit messages (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
- **Tooling Compatibility**: This briefing is kept aligned for Antigravity (`GEMINI.md`), Claude Code / Codex (`CLAUDE.md`), and general autonomous agents (`AGENTS.md`).
