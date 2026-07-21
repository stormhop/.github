<div align="center">

<img src="https://raw.githubusercontent.com/relay-client/.github/main/profile/assets/logo.png" alt="Relay" width="120" height="120">

# Relay

### A fast, local-first desktop API client

No accounts. No cloud sync. No telemetry — just you and your APIs.

<br>

[![Download](https://img.shields.io/badge/Download-5865F2?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/relay-client/relay/releases/latest)
&nbsp;
[![Source](https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/relay-client/relay)
&nbsp;
[![Docs](https://img.shields.io/badge/Docs-2b2d31?style=for-the-badge&logo=readthedocs&logoColor=white)](https://relay-client.github.io/relay/)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/relay-client/relay/blob/main/LICENSE)
&nbsp;
[![Platforms](https://img.shields.io/badge/macOS%20·%20Windows%20·%20Linux-2b2d31?style=flat-square)](https://github.com/relay-client/relay/releases/latest)

</div>

<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/relay-client/.github/main/profile/assets/screenshot.png" alt="Relay workspace" width="860">
</div>

<br>

## What is Relay

Relay is a modern desktop API client — a polished alternative to Postman and Insomnia — built for engineers who want **speed, privacy, and a UI that feels right**. Everything lives on your machine: workspaces, collections, history, environments and secrets are stored on disk and **encrypted at rest with AES‑256‑GCM** (system keychain on macOS). Nothing leaves your computer.

**Relay is open source under the MIT license.** The full application source lives in [relay-client/relay](https://github.com/relay-client/relay) — read it, build it, or send a pull request.

## Features

### 🌐 Every protocol in one place
HTTP, **GraphQL**, **Server-Sent Events (SSE)**, **WebSocket**, **Socket.IO**, and **gRPC** — all in a single request editor.

### 🔐 All the auth flows
Bearer, Basic, **Digest (RFC 2617)**, API Key, **AWS Signature v4**, and **OAuth 2.0** — both Client Credentials and Authorization Code with **PKCE**, including browser sign-in, refresh tokens, and automatic refresh right before a request is sent.

### 🧬 Git-backed workspaces
Store workspaces as clean, reviewable **YAML** and version them with Git — collaborate through pull requests while **secrets stay local**. Built-in **Git sync**, diff diagnostics, and conflict helpers for when a repo changes underneath you.

### 📜 Scriptable requests
Pre-request and test scripts in **sandboxed JavaScript** (with legacy Tengo support) and a familiar `pm.*` API. Inject headers, assert responses, parse JSON, set variables. Imports, filesystem and network access are disabled; execution caps at 2s so scripts can't escape the sandbox or block the UI.

### 🔄 Imports that travel
Import from **Postman, Insomnia, Bruno / OpenCollection, OpenAPI, HAR, curl**, or a full Relay backup. Export to Postman, OpenAPI, OpenCollection, or an all-data backup.

### ▶️ Collection Runner
Run saved requests as local smoke tests and export a shareable **HTML report**.

### 🧩 Code generation
Copy any request as **cURL, Python (`requests`), JavaScript (`fetch`), or Go (`net/http`)** — more languages in the side panel.

### ⌨️ Keyboard-first
Global search (`⌘K`), quick send (`⌘↵`), tab switching (`⌘1–⌘9`) — every shortcut is configurable.

### 🔒 Signed updates
Every release ships SHA‑256 checksums and **minisign signatures**. The in-app updater refuses any binary that fails either check.

### 🎨 Built to feel good
Per-workspace accent theming, environments, a cookie jar, request history, and a fast, native-feeling UI.

## Built with

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Wails](https://img.shields.io/badge/Wails-DF0000?style=flat-square&logo=wails&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte%205-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</div>

## Contributing

Bug reports, feature requests, and pull requests are welcome — start with [CONTRIBUTING.md](https://github.com/relay-client/relay/blob/main/CONTRIBUTING.md). Questions and ideas belong in [Discussions](https://github.com/relay-client/relay/discussions).

Found a security problem? Please report it privately — see [SECURITY.md](https://github.com/relay-client/relay/blob/main/SECURITY.md).

<br>

<div align="center">
<sub>Local-first · Encrypted at rest · Open source — <a href="https://github.com/relay-client/relay/releases/latest">Get the latest release</a></sub>
</div>
