# John Brahy

Long Beach, CA. I build systems software and the businesses around it: an
operating system kernel, a coding agent, an antivirus product with its own
licensing and billing service, and the iOS and macOS apps in between.

**Open to new work.** Reach me at [john@brahy.com](mailto:john@brahy.com).

## What I am building

| Project | What it is | Stack |
|---|---|---|
| [**BraiNIX**](https://github.com/jbrahy/BraiNIXOS) | A capability-based, security-first microkernel built to serve LLM inference to remote clients. Written end to end in `no_std` Rust, targeting Apple Silicon. W^X, KPTI, measured boot, synchronous IPC. Every security invariant is named and individually checkable. | Rust (`no_std`), aarch64 |
| [**GopherMind**](https://github.com/jbrahy/gophermind.com) | A single-binary AI coding agent for the terminal, pointed at any OpenAI-compatible model you control. Path containment, a shell deny-list, and an approval gate on every mutating action. | Go, Charm TUI |
| [**NexGuard**](https://github.com/jbrahy/nexguard) | A hash-based antivirus CLI and background watcher, plus the Go service that sells the premium tier: accounts, Stripe checkout, license issuance and revocation, per-IP rate limiting. | Go, MySQL, Stripe |
| [**HuShield**](https://github.com/Hushield/hushield) | A community-driven spam call and text filter for iOS with no accounts and no PII. Device identity is an Apple App Attest key and nothing else. Verified end to end on real hardware. | Go, MySQL, Swift |
| [**mfa**](https://github.com/jbrahy/desktop-mfa) | TOTP codes on the macOS desktop: Dock app, global hotkey, webcam importer for Google Authenticator transfers. RFC 6238 and 4226 implemented against the published vectors. Secrets stay in the login keychain. | Rust, AppKit via `objc2` |
| [**Markup**](https://github.com/jbrahy/markup) | A native desktop Markdown editor: split-pane editing with live preview, no backend and no network calls. | Tauri 2, React, TypeScript |

## How I work

Every one of those repositories carries its design spec and its plan alongside
the code, and each README says plainly what the project does **not** do yet.
NexGuard's detection is hash-only and says so. BraiNIX boots a hardened
microkernel but does not serve inference yet and says so. HuShield lists which
behaviours are verified on real hardware and which are still unproven. I would
rather ship a documented boundary than an implied capability.

## Working in

`Rust` · `Go` · `TypeScript` / `React` · `Swift` · `PHP` · `Python` · `MySQL` ·
`Tauri` · `AWS`

## Elsewhere

- Email: [john@brahy.com](mailto:john@brahy.com)
- Company: Popular Marketing
