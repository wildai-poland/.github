<div align="center">

<img src="https://raw.githubusercontent.com/wildai-poland/.github/main/assets/logo.png" width="160" height="160" alt="WildAI Logo" />

# WildAI Poland

**Next-generation, developer-centric artificial intelligence ecosystem.**  
*High-performance web intelligence and autonomous CLI developer agents.*

[![Website](https://img.shields.io/badge/Web%20Platform-v2.wildai.pl-10a37f?style=for-the-badge&logo=openai&logoColor=white)](https://v2.wildai.pl)
[![Organization](https://img.shields.io/badge/GitHub-wildai--poland-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wildai-poland)
[![Release](https://img.shields.io/badge/Release-Active-emerald?style=for-the-badge)](https://github.com/wildai-poland/wildai-cli)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

### Overview

**WildAI Poland** develops open-source tooling, agentic workflows, and high-throughput LLM runtime interfaces. Our engineering mission focuses on unconstrained model capabilities, real-time token streaming, strict security sandboxing, and autonomous developer workflows.

---

### Ecosystem Projects

<table>
  <thead>
    <tr>
      <th width="30%">Repository</th>
      <th width="50%">Description</th>
      <th width="20%">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/wildai-poland/wildai-cli">
          <b>⚡ wildai-cli</b>
        </a>
      </td>
      <td>
        Official command-line interface and Autonomous Developer Agent for the WildAI platform. Features real-time token telemetry (TTFT, tok/s, cost estimation), automated disk write execution, Path Traversal sandboxing, and native macOS Keychain / AES-256-GCM token storage.
      </td>
      <td>
        <code>v1.2.0 • Public</code>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/wildai-poland/wildai-vscode">
          <b>🧩 wildai-vscode</b>
        </a>
      </td>
      <td>
        Official Visual Studio Code extension. Features a real-time streaming sidebar assistant, right-click code explanation/refactoring/test generation, one-click editor insertion, and encrypted token management.
      </td>
      <td>
        <code>v0.1.0 • Public</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>💬 WildAI Chat Web Platform</b>
      </td>
      <td>
        Next.js 16 (Turbopack) production chat client featuring multi-model inference, quota management via serverless PostgreSQL, real-time streaming, and user personalization.
      </td>
      <td>
        <a href="https://v2.wildai.pl"><code>Live Platform</code></a>
      </td>
    </tr>
  </tbody>
</table>

---

### Architecture & Security Standard

All WildAI engineering implementations adhere to strict production security guardrails:

* **Hardware-Backed Credential Storage:** Native integration with macOS Keychain (`security` framework) and fallback authenticated encryption (AES-256-GCM with POSIX `0600` access controls).
* **Deterministic Execution Sandbox:** Restrictive filesystem boundary enforcement eliminating directory traversal vulnerabilities.
* **Human-in-the-Loop Governance:** Sensitive actions, destructive command pipelines, and file mutations mandate explicit interactive developer confirmation.
* **Loop Prevention Budget:** Built-in agent iteration caps prevent recursive tool execution and resource exhaustion.

---

### Quick Installation

```bash
# Clone the official CLI repository
git clone https://github.com/wildai-poland/wildai-cli.git
cd wildai-cli

# Install dependencies and compile
npm install
npm run build

# Link globally or run directly
npm link
wildai
```

---

### Responsible Disclosure

Security vulnerabilities should be reported directly to our security team via **security@wildai.pl**. Please refer to our [Security Policy](SECURITY.md) for full disclosure guidelines.

---

<div align="center">
  <sub>© 2026 WildAI Poland. Released under the <a href="LICENSE">MIT License</a>.</sub>
</div>
