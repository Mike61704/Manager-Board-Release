# Security

## Installer verification

Download Manager Board only from this repository’s GitHub Releases page. A release installer must:

- use the exact `ManagerBoard-Setup-X.Y.Z.exe` naming pattern;
- have a valid Windows Authenticode signature from the expected Manager Board publisher;
- match the SHA-256 digest published by GitHub for the release asset.

The Manager Board updater performs these checks before it stages a downloaded installer. If validation fails, the update is rejected and the existing installation remains in place.

## Activation boundary

Offline activation controls whether the application starts. It does not encrypt, delete, migrate, or hold workspace data. Private activation-signing material is not included in this repository or the Manager Board installer.

## Sensitive data

Do not attach workspaces, backups, vaults, diagnostic bundles, activation files, credentials, employee records, or organization data to a public GitHub issue.

For a suspected security problem, contact the Manager Board publisher privately using the channel through which you received the application. Include the Manager Board version and a description of the behavior, but remove sensitive business and personal data.
