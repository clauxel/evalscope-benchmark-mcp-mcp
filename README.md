# EvalScope Benchmark MCP

EvalScope Benchmark MCP is a hosted remote MCP for AI SDK benchmark dashboard.

This repository is a public documentation project for EvalScope Benchmark MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://evalscopebench.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=evalscopebench_public_docs&utm_content=readme_home
- Pricing: https://evalscopebench.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=evalscopebench_public_docs&utm_content=readme_pricing
- Checkout: https://evalscopebench.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=evalscopebench_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://evalscopebench.clauxel.com/mcp
- Server card: https://evalscopebench.clauxel.com/server-card.json
- Registry name: `com.clauxel.evalscopebench/evalscopebench-mcp`
- Tools: `run_benchmark_gate`, `compare_model_scores`, `read_benchmark_report`, `issue_benchmark_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI governance teams, policy reviewers, trust and safety leads, and compliance operators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: run_benchmark_gate
- MCP tool: compare_model_scores
- MCP tool: read_benchmark_report
- MCP tool: issue_benchmark_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
