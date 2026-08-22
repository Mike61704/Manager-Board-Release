# Manager Board release channel

This repository is the official stable Windows release channel for Manager Board.

Current stable release: **v2.0.65 — Unified Local AI Runtime Correction**

## Release contract

Every supported release uses all of the following:

- Git tag: `vX.Y.Z`
- Installer asset: `ManagerBoard-Setup-X.Y.Z.exe`
- Stable GitHub Release state (not draft and not prerelease)
- Release notes describing user-visible changes and preserved safety boundaries
- GitHub asset metadata containing a SHA-256 digest
- A valid Authenticode signature from the expected Manager Board publisher

Manager Board’s updater rejects a release that does not satisfy this contract.

## What is published

- Public product and support documentation
- Signed Windows installer releases
- User-facing release notes

## What is never published

- Manager Board source code
- Private activation or code-signing keys
- Credentials, tokens, or connection sessions
- Workspace, Vault, backup, restore, attachment, export, or diagnostic data
- Employee or organization-specific information
- Bundled Local AI models

## Upgrade behavior

The installer upgrades Manager Board in place while keeping application data and activation outside the install directory. Users can choose a release from the in-app update center and decide whether to install manually, at a configured time, during protected shutdown, or on the next startup.

Rollbacks should be performed only with a trusted earlier signed installer and an appropriate validated data backup. Application version rollback does not imply a schema or workspace rollback.
