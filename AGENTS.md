# Agent: A2A-SIN-Matrix

**Team:** OpenSIN-AI
**Protocol:** A2A (Agent-to-Agent)
**Status:** Active
**Repository:** https://github.com/OpenSIN-AI/A2A-SIN-Matrix

## Capabilities

A2A agent for Matrix integration within the OpenSIN ecosystem.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to the approved artifact storage surface
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/A2A-SIN-Matrix.git
cd A2A-SIN-Matrix
bun install
bun start
```

## Boundary Guidance

When modifying this repo:

- Prefer Matrix messaging integration and monitoring work.
- Do not turn this repo into a generic chat bucket.
- Do not redefine organization docs, architecture, or runtime canon here.
- Move non-Matrix behavior back to the repos that own those surfaces.

## License

Apache-2.0
