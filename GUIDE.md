# Public documentation guide

[Documentation hub](README.md)

## Status terminology

- **Implemented in private development:** described as integrated in the public launcher documentation; this is not evidence of a publicly released build.
- **In development:** being prepared and subject to change.
- **Planned:** a proposed public area without an available implementation or compatibility commitment.
- **Released:** use this label only with a public release and matching documentation.

## Launcher and Client

The [Launcher](https://github.com/Lapinite/Leviathan-Launcher) remains in private development. Public repository access does not provide a public binary. Client systems are in development; do not assume availability or compatibility from a feature listing.

## Authentication

The launcher documents Microsoft, Xbox Live, XSTS, and Minecraft Services integration in private development. Minecraft AppID review is approved. Full production authentication validation remains separate. Use a legitimate Microsoft account with Minecraft: Java Edition entitlement. Never provide a Microsoft password directly to Leviathan or reuse the launcher's application registration in another product.

See the [authentication guide](https://github.com/Lapinite/Leviathan-Launcher/blob/main/docs/AUTHENTICATION.md). Application and administrative identifiers are intentionally omitted.

## Minecraft installation

Installation management is in development. No public installation package is currently offered. Follow the [installation notice](https://github.com/Lapinite/Leviathan-Launcher/blob/main/docs/INSTALLATION.md); do not treat private development instructions as a public download route.

## Instances and profiles

Instance management and multiple profiles are in development. An instance groups a game's version, configuration, and related files; a profile records a selected configuration. Back up worlds before changing a setup. Account credentials must not be exported with a profile. Public import/export formats are not yet specified.

## Java and runtime management

The launcher documentation targets Java 21 for development. Minecraft versions can require different runtimes. Runtime management is in development; consult the selected game's requirements and future release compatibility notes. Never assume the launcher's runtime is suitable for every game version.

## Cast TV

Cast TV is a planned documentation area. No supported devices, pairing flow, transport, or availability commitment is specified here. Do not infer a released casting feature.

## APIs and developer tooling

Public API contracts and SDK installation instructions are being prepared. Start with [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) and [SDK](https://github.com/Lapinite/Leviathan-SDK). No production endpoint or package installation command is asserted by this guide.

## Integrations

Minecraft plugins, Discord, webhooks, and third-party adapters are planned public integration areas. Use the [integration guide](https://github.com/Lapinite/Leviathan-Integrations) for permission boundaries and lifecycle expectations. Support must be documented per released adapter.

## Server tooling and Nimbus

[Server Tools](https://github.com/Lapinite/Leviathan-Server-Tools) covers public utilities, plugins, and staff tooling. Nimbus is the ecosystem's server protection area. Public Nimbus documentation will cover installation, compatibility, permissions, and support as releases become available. Detection internals and bypass-relevant details are outside public documentation.

## Security and privacy

Use [SECURITY.md](SECURITY.md) for reporting guidance. Remove account information, administrative identifiers, local paths, and credentials from reports. Authentication data should be used only for its intended purpose. See the launcher's [privacy documentation](https://github.com/Lapinite/Leviathan-Launcher/blob/main/PRIVACY.md) for its current policy.

## Troubleshooting

Record the product version, affected action, sanitized error code, and time of failure. Review logs and screenshots before sharing. Keep credentials and diagnostic identifiers out of public issues. The [launcher troubleshooting guide](https://github.com/Lapinite/Leviathan-Launcher/blob/main/docs/TROUBLESHOOTING.md) covers the current private development context.

## Releases

Use public release announcements as the source for available builds, supported versions, known issues, and installation instructions. The launcher currently has no public release. Planned features and private version notes are not availability promises. See its [release policy](https://github.com/Lapinite/Leviathan-Launcher/blob/main/docs/RELEASE_POLICY.md).
