# MUBA-GUARDIAN module map

Architecture source: [MUBA/architecture/03-guardian](https://github.com/MUBA-RH/MUBA/tree/main/architecture/03-guardian). Active code and deployment remain at their current locations. Listed areas are ownership boundaries, not evidence of an implemented standalone service.

| Area | Responsibility |
| --- | --- |
| [DEV-AUTHORITY](modules/DEV-AUTHORITY/CONTENT/README.md) | Module boundary |
| [COMMAND-CONTROL](modules/COMMAND-CONTROL/CONTENT/README.md) | Module boundary |
| [SECURITY-POLICY](modules/SECURITY-POLICY/CONTENT/README.md) | Module boundary |
| [SCAM-FAKE-CA](modules/SCAM-FAKE-CA/CONTENT/README.md) | Module boundary |
| [LINK-CONTROL](modules/LINK-CONTROL/CONTENT/README.md) | Module boundary |
| [FLOOD-CONTROL](modules/FLOOD-CONTROL/CONTENT/README.md) | Module boundary |
| [MODERATION](modules/MODERATION/CONTENT/README.md) | Module boundary |
| [SECURITY-MODES](modules/SECURITY-MODES/CONTENT/README.md) | Module boundary |
| [VIOLATION-HISTORY](modules/VIOLATION-HISTORY/CONTENT/README.md) | Module boundary |

Each area has CONTENT / UPDATE / TEST / STABLE. See [LIFECYCLE.md](LIFECYCLE.md). No new Render service, Telegram bot, token, key, Vault, or deployment trigger is created here.
