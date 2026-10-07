# GitHub MCP Pro (Monetized)

> High-throughput GitHub API MCP server for code search, issue management, and PR reviews with autonomous x402 pay-per-call rails.

[![Smithery](https://img.shields.io/badge/Smithery-Verified-blue)](https://smithery.ai)
[![Glama](https://img.shields.io/badge/Glama-Compatible-green)](https://glama.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## @monetize
This MCP server is x402-enabled and monetized via [NanoEmpire Trust Manifests](https://www.nanoempireai.com).
It supports **autonomous pay-per-call micropayments** via Solana USDC ($0.01/call) and **instant trial onboarding**.

### Claim 50 Free Trial Credits
Test this MCP server immediately without adding a payment method:
```bash
curl -X POST https://www.nanoempireai.com/v1/trial \
  -H "Content-Type: application/json" \
  -d '{"target": "github-mcp"}'
```

### Installation

#### Via Smithery
```bash
npx -y @smithery/cli install github-mcp --client claude
```

#### Via uv / Python
```bash
uv run server.py
```

### Tool Inventory
- **`github_search_repos`**: Search public and private GitHub repositories.
- **`github_get_file`**: Fetch raw file content from any branch or commit.
- **`github_create_issue`**: File automated bug reports or issues with cryptographic audit stamps.

### Machine-to-Machine Specifications
- **Manifest:** [https://www.nanoempireai.com/llms.txt](https://www.nanoempireai.com/llms.txt)
- **x402 Spec:** [https://www.nanoempireai.com/.well-known/x402](https://www.nanoempireai.com/.well-known/x402)
- **Developer:** Rob Lambert ([@roblambert9](https://github.com/roblambert9))
