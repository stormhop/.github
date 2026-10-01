<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/relay-client/.github/main/profile/assets/profile-logo-dark.png">
  <img src="https://raw.githubusercontent.com/relay-client/.github/main/profile/assets/profile-logo-light.png" alt="Relay" width="120" height="120">
</picture>

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
HTTP, **GraphQL**, **Server-Sent Events (SSE)**, **WebSocket**, **Socket.IO**, **gRPC** and **MCP** — all in one request editor. An MCP call discovers the server's tools, resources and prompts, seeds the arguments from the tool's schema, and shows the raw JSON-RPC exchange.

### 🔐 All the auth flows
Bearer, Basic, **Digest** (MD5, SHA-256, SHA-512-256 and their `-sess` variants), API Key, **AWS Signature v4**, client certificates, and **OAuth 2.0** — Client Credentials, Authorization Code with **PKCE**, Password and Device Code, with browser sign-in, refresh tokens and automatic refresh before a request is sent.

### 🧬 Git-backed workspaces
Store workspaces as clean, reviewable **YAML** and version them with Git — collaborate through pull requests while **secrets stay local**. Built-in Git panel, diagnostics and a three-way conflict resolver for when a repo changes underneath you.

### 📜 Scriptable requests
Pre-request and test scripts in **sandboxed JavaScript** (with legacy Tengo support) and a familiar `pm.*` API: inject headers, rewrite the body, assert on status and JSON schema, set variables, call another endpoint with `pm.sendRequest`. `require` resolves bundled stand-ins for lodash, ajv, chai and friends, so imported Postman scripts keep working.

### 🔄 Imports that travel
Import from **Postman, Insomnia, Bruno / OpenCollection, OpenAPI (file or URL), HAR, curl**, or a full Relay backup. Export to Postman, OpenAPI, OpenCollection, or an all-data backup.

### 🧪 Examples and a local mock server
Save any response as a named example, secrets redacted, then serve a whole collection of them over HTTP on your own machine — and diff a fresh response against the example it should match.

### ▶️ Collection Runner and CLI
Run a collection sequentially or in parallel, with data files and iterations, export an **HTML report**, and see each collection's last run. `relay run` does the same in CI with JSON and JUnit reporters.

### 🧩 Code generation
Copy any request as a runnable snippet in **14 targets** — cURL, HTTPie, `fetch`, Axios, Python, Go, Java, C#, PHP, Ruby, Swift, Kotlin, Rust and more.

### ⌨️ Keyboard-first
A **command palette** (`Cmd/Ctrl K`) that finds requests and runs commands, quick send (`Cmd/Ctrl Enter`), tab switching (`Cmd/Ctrl 1–9`) — every shortcut is configurable.

### 🔒 Signed updates
Every release ships SHA‑256 checksums and **minisign signatures**. The in-app updater refuses any download that fails either check.

### 🎨 Built to feel good
The Graphite design — neutral greys, hairline borders, colour only where it means something — with dark and light themes and their variants, environments side by side, a cookie jar that can sync from your browser, and request history with a page for every send.

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
