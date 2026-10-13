# Hermes

**Control your desktop dev environment from your phone.**

Hermes is a remote developer tool that lets you run AI coding tasks, monitor terminals, browse files, and manage your Jira/GitHub workflow — all from a React Native mobile app connected to your Mac over LAN or a secure WebSocket relay.

---

## How It Works

1. **Pair once** — scan a QR code on the desktop app; your phone and Mac exchange keys and stay connected over LAN or relay.
2. **Queue tasks** — describe what you want built; Hermes runs Claude (or Codex / Gemini) in your project directory and streams live output to your phone.
3. **Stay in the loop** — review diffs, approve plans, answer gate questions, merge PRs, and monitor terminals from anywhere.

---

## Key Features

- **AI Task Queue** — submit natural-language tasks; the desktop spawns a Claude CLI process, streams output in real time, and pauses at human-gate checkpoints for your approval.
- **Kanban + Conveyor** — Jira and Linear boards with an AI pipeline (Analyze → Plan → Implement → Review) that moves cards through stages automatically, escalating only when it needs you.
- **Terminal Access** — full PTY terminal multiplexer; run any shell command on your Mac from the mobile xterm.js view.
- **File Transfer** — browse your desktop file system, download files to your phone, or stream large files in adaptive chunks.
- **GitHub / PR Reviews** — list pull requests, trigger AI code reviews, and see review results without opening a laptop.
- **Database Browser** — connect to SQLite, MySQL, or Elasticsearch via the desktop relay and run queries from your phone.
- **Encrypted End-to-End** — all traffic uses NaCl (tweetnacl) shared-secret encryption; the relay never sees plaintext.

---

## AI Integrations

| CLI | Notes |
|-----|-------|
| Claude (Anthropic) | Primary; full plan/implement/audit pipeline |
| Codex (OpenAI) | Supported via multi-CLI toolbox |
| Gemini (Google) | Supported via multi-CLI toolbox |

Model and reasoning-effort preferences are synced to your phone in real time.

---

## Downloads

macOS only. Requires macOS 12+ (Apple Silicon or Intel).

| Release | Apple Silicon | Intel |
|---------|--------------|-------|
| [Latest (v0.2.2)](https://github.com/alexandruseverin/hermes-releases/releases/latest) | [Hermes-arm64.dmg](https://github.com/alexandruseverin/hermes-releases/releases/latest/download/Hermes-arm64.dmg) | [Hermes-x64.dmg](https://github.com/alexandruseverin/hermes-releases/releases/latest/download/Hermes-x64.dmg) |

All releases → [Releases page](https://github.com/alexandruseverin/hermes-releases/releases)

> **Mobile app** — search for **Hermes** on the App Store (iOS) or Google Play (Android).

---

## More

- Website & docs — coming soon
- Issues & feedback — open an issue in this repository

---

*Hermes is under active development. APIs and protocols may change between releases.*
