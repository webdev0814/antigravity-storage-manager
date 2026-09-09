# Agent Briefing: antigravity-storage-manager

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/antigravity-storage-manager`
- **Visibility**: `Public`
- **Default Branch**: `master`
- **Last Updated / Pushed**: 2026-09-08
- **Description**: Unified AI Gateway with visual dashboard, secure Google Drive sync, Telegram notifications, multi-account profiles, real-time quota monitoring, Proxy support, MCP server, and advanced backup tools.
- **Context from README**: <p align="center"> <img src="https://raw.githubusercontent.com/unchase/antigravity-storage-manager/master/banner.png" alt="Antigravity Storage Manager"> </p> <p align="center">


---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: TypeScript, JavaScript, Node.js
- **Key Directories**: `.agent/`, `.github/`, `images/`, `l10n/`, `screenshots/`, `src/`
- **Notable Top-Level Files**: `.gitignore`, `.vscodeignore`, `AGENTS.md`, `CHANGELOG.md`, `CLAUDE.md`, `CONTRIBUTING.md`, `GEMINI.md`, `LICENSE`, `README.md`, `SYNC_SETUP.md`, `banner.png`, `check_l10n_bundles.js`

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
- `[bc5c409]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[d1ee53e]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[c0d88a6]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[93ea76c]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[e5e7e8d]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[e26df7f]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[5340f52]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[9a486e1]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[522e6d3]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[fe3d475]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `master`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Multi-Computer Handoff & Git Sync Protocol
- **On Session Start**: Always run `git pull` when opening this repository on any computer to synchronize the latest changes.
- **On Task Completion**: Before ending any agent session, the agent **MUST**:
  1. Update Section 5 (Current State & Next Steps) in this `AGENTS.md` file.
  2. Stage all modifications (`git add .`).
  3. Commit with a concise conventional message (`git commit -m "feat/fix: ..."`).
  4. Push directly to GitHub (`git push`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
