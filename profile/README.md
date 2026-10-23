<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stormhop/.github/main/profile/assets/profile-logo-dark.png">
  <img src="https://raw.githubusercontent.com/stormhop/.github/main/profile/assets/profile-logo-light.png" alt="Kurlo" width="104" height="104">
</picture>

# Kurlo

**The open-source Postman alternative your AI agent can drive.**

No account. No paid plan. No telemetry. Collections live as YAML in your Git repo.

<br>

[![Download](https://img.shields.io/badge/Download-5865F2?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/stormhop/kurlo/releases/latest)
&nbsp;
[![MCP server](https://img.shields.io/badge/MCP%20server-2b2d31?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)](https://kurlo.dev/mcp/)
&nbsp;
[![Docs](https://img.shields.io/badge/Docs-2b2d31?style=for-the-badge&logo=readthedocs&logoColor=white)](https://kurlo.dev/docs/getting-started/installation/)

[![Release](https://img.shields.io/github/v/release/stormhop/kurlo?style=flat-square&color=5865F2&label=release)](https://github.com/stormhop/kurlo/releases/latest)
&nbsp;
[![Stars](https://img.shields.io/github/stars/stormhop/kurlo?style=flat-square&color=2b2d31)](https://github.com/stormhop/kurlo/stargazers)
&nbsp;
[![npm](https://img.shields.io/npm/v/@kurlo/cli?style=flat-square&color=2b2d31&label=%40kurlo%2Fcli)](https://www.npmjs.com/package/@kurlo/cli)
&nbsp;
[![License: MIT](https://img.shields.io/badge/license-MIT-2b2d31?style=flat-square)](https://github.com/stormhop/kurlo/blob/main/LICENSE)

<br>

<img src="https://raw.githubusercontent.com/stormhop/.github/main/profile/assets/demo.gif" alt="Claude Code adds tests to a Kurlo collection over MCP, finds a pricing bug and fixes it, while the tests appear in Kurlo" width="860">

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

#### 🧬 Lives in your repo
Every request is a readable YAML file, reviewed in the same pull request as the API change. Secrets stay encrypted on your machine.

</td>
<td width="50%" valign="top">

#### 🤖 Your agent can press Send
`kurlo mcp` lets Claude Code, Cursor and Codex run saved requests with their auth and tests, write new ones, and explain the last failure.

</td>
</tr>
<tr>
<td valign="top">

#### 📜 Postman scripts, unchanged
Import Postman, Insomnia, Bruno, OpenAPI or HAR. `pm.test`, chai and `pm.sendRequest` run as they were written.

</td>
<td valign="top">

#### 🌐 Sees CORS before your users do
Send a request under a browser's CORS and CSP rules and get the error in Kurlo, not in production.

</td>
</tr>
<tr>
<td valign="top">

#### 🧪 Mock it, test it, run it in CI
Saved examples become a local mock server. `kurlo run` runs the same tests in CI with JSON and JUnit reports.

</td>
<td valign="top">

#### ⚡ Small and native
Go and the system WebView instead of Electron: 22 MB on macOS, 11 MB on Linux. HTTP, GraphQL, gRPC, WebSocket, SSE and MCP.

</td>
</tr>
</table>

## Get started

Download the app for macOS, Windows or Linux from the [latest release](https://github.com/stormhop/kurlo/releases/latest), or connect your AI agent with one command:

```bash
npx -y @kurlo/cli mcp install
```

## Contributing

Bug reports, ideas and pull requests are welcome in [stormhop/kurlo](https://github.com/stormhop/kurlo) — start with [CONTRIBUTING.md](https://github.com/stormhop/kurlo/blob/main/CONTRIBUTING.md) or open a [Discussion](https://github.com/stormhop/kurlo/discussions). Security issues go through [SECURITY.md](https://github.com/stormhop/kurlo/blob/main/SECURITY.md).

<br>

<div align="center">
<sub>If Kurlo saves you time, a <a href="https://github.com/stormhop/kurlo">⭐ on the repo</a> helps other people find it.</sub>
</div>
