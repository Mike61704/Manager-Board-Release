# Manager Board support

## Installation

1. Download the latest `ManagerBoard-Setup-X.Y.Z.exe` from [GitHub Releases](https://github.com/Mike61704/Manager-Board-Release/releases).
2. Confirm Windows reports a valid expected publisher before running it.
3. Install Manager Board and launch it.
4. On first use, copy or export the activation request.
5. Send that request to the Manager Board publisher using your established private channel.
6. Import the returned `.mbl` activation file or paste the signed activation code.

## Updating

Open **Settings → About / Version** to check releases, read release notes, download an upgrade, or choose an optional automatic-install schedule. Automatic installation is disabled until the user selects a policy.

## Common questions

### Does Manager Board require internet access?

No for the core local workspace and offline activation. Internet access is needed for release checks/downloads and any network integration the user explicitly enables.

### Is a Local AI model included?

No. Local AI is optional and uses a separate user-managed compatible model. Manager Board works normally without one.

### Will reinstalling delete my workspace?

The application install directory is separate from Manager Board workspace and activation data. Keep validated backups anyway, especially before major environment changes.

### Why did activation fail after moving the file?

Activation is bound to the installation that generated the request. Generate a new request on the target Windows installation and ask the publisher for a matching activation.

### Where should I report a problem?

Use the private support channel provided with your license. Never post business data, activation files, credentials, backups, or diagnostics publicly.
