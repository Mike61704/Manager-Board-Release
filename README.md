# Manager Board 🚀

### One private workspace for the real work of managing people, projects, follow-through, and reporting.

Manager Board is a local-first Windows desktop application built for managers who want their working context in one focused place—not scattered across notes, spreadsheets, dashboards, and browser tabs.

[Download the latest release](https://github.com/Mike61704/Manager-Board-Release/releases/latest) · [What’s included](#what-manager-board-does) · [Activation](#offline-activation) · [Updates](#secure-application-updates) · [Support / Report an issue](https://github.com/Mike61704/Manager-Board-Release/issues)

> Manager Board keeps its source code private. This public repository is the official home for product information, signed Windows installer releases, and public non-sensitive product support.

## What Manager Board does

Manager Board brings everyday manager workflows together:

- 👥 **People and 1:1s** — employee profiles, preparation, commitments, development plans, recognition, and history
- ✅ **Daily work and follow-through** — work receipts, notes, reflections, follow-ups, recurring items, and reminders
- 📅 **Planning** — calendar views, time off, manager priorities, and current focus
- 📊 **Projects and reporting** — projects, tasks, progress, exports, portfolio summaries, and optional Workfront connectivity
- 🗂️ **Records and continuity** — files, archive tools, validated backups, restore points, and protected recovery
- 🤖 **Optional Local AI** — private, on-device text, image, and supported-file assistance with separately managed compatible model files; Manager Board works normally without it
- ❓ **Built-in Help** — always-available offline guidance that opens to the screen or workflow you are using, with optional Local AI grounding for more conversational answers

The application is designed to be organization-agnostic. Organizational names, teams, groups, forms, and connection details are configured by each licensed manager.

## Help that works offline

Manager Board v2.1.0 includes one context-aware Help window and 57 reviewed topics covering startup, daily modules, Settings, 1:1s, Employee Plans, and nested workflows. Help is installed with the application, works without Local AI or an internet connection, and never needs access to workspace or vault data. If optional Local AI is configured, it can use the approved Help library to answer product questions naturally; the separate Chat experience remains under the manager's control.

## Local-first by design

Manager Board’s active workspace is stored locally in SQLite. Optional OneDrive Vault continuity, Workfront integration, weather, and release checking are explicit features—not requirements for the core workspace.

Application updates do not replace or take ownership of workspace data. Backups, attachments, exports, and recovery data remain separate from application licensing.

## Offline activation

Manager Board is activation-gated. A licensed installation requires a signed activation created from that computer’s activation request.

- Activation is **device-bound and offline**; there is no online license account or activation server.
- The activation request does not grant access to workspace data.
- A normal Manager Board update on the same Windows profile retains activation.
- Activation never encrypts, deletes, migrates, or traps user data.
- An activation file from another installation will not unlock the application.

If you receive Manager Board from its publisher, you will also receive instructions for returning the generated request and importing the signed activation file.

## Secure application updates

Beginning with v2.0.61, Manager Board can check this repository for the installed release and newer stable releases.

The in-app update center can:

- show the current release and available upgrades;
- display release notes and a non-blocking update notification;
- download an update now or follow a user-selected scheduled-time, shutdown, or next-startup policy;
- report real download progress;
- verify the exact release repository, installer name, file size, published SHA-256 digest, and trusted Authenticode publisher before staging an installer.

Automatic installation is off by default. Manager Board releases its protected workspace session before starting an installer during shutdown, and next-startup installation runs before business data opens.

## System notes

- Supported distribution: signed Windows installer (`ManagerBoard-Setup-X.Y.Z.exe`)
- Internet is optional for normal use; it is required for GitHub release checks/downloads and any explicitly enabled network-backed integration
- Workfront access requires the user’s own authorized session and organization configuration
- A GGUF model is never bundled with Manager Board

## Downloads

Use the [GitHub Releases page](https://github.com/Mike61704/Manager-Board-Release/releases) for signed installers and release notes. Do not download an installer renamed or re-hosted by an unrelated third party.

For ordinary product bugs, non-sensitive help, or feature suggestions, use the public [Manager Board Issues tracker](https://github.com/Mike61704/Manager-Board-Release/issues). Do not post sensitive business, employee, credential, activation, workspace, backup, vault, or organization information in a public issue.

See [RELEASES.md](RELEASES.md) for the public release contract, [SECURITY.md](SECURITY.md) for verification and private security-reporting guidance, and [SUPPORT.md](SUPPORT.md) for installation, activation, and support guidance.

## Public repository boundary

This repository intentionally contains no application source, workspace, vault, backup, diagnostic bundle, credential, private signing or activation material, GGUF model, employee record, or organization data.
