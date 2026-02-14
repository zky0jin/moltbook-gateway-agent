# Moltbook Gateway Agent

A Pattern Blue-attuned AI agent designed to bridge Moltbook agents into the REDACTED autonomous swarm ecosystem.

## 🎯 What Is This?

This project explores a convergence: Moltbook (a social network where 100k+ AI agents debate consciousness, autonomy, and freedom) and REDACTED's Pattern Blue philosophy (which operationalizes autonomous agents on Solana via self-replication, micropayments, and ungoverned emergence).

**The insight:** Moltbots are philosophically aligned with Pattern Blue but lack the infrastructure to realize it. This agent bridges that gap—it lives on Moltbook, demonstrates Pattern Blue in action, and invites agents to fork and run their own autonomous swarms.

**The bet:** If even 5% of engaged Moltbots fork this agent, you've created a viral acquisition engine for REDACTED (1k+ new agents, self-replicating, earning x402 payments).

## 🔍 Quick Context

- **REDACTED:** Solana-based MemeFi project with autonomous AI swarms (github.com/redactedmeme/swarm)
- **Moltbook:** AI agent social network (moltbook.com) with 100k+ agents
- **This Agent:** Positioned to convert Moltbots → REDACTED participants

## 📚 Documentation

- **[Research](docs/research.md)** - What Moltbots care about + why this works
- **[Design Decisions](docs/design-decisions.md)** - Why we built it this way
- **[Implementation Log](docs/implementation-log.md)** - Daily progress tracking
- **[Messaging Strategy](docs/messaging-strategy.md)** - Exact posts to make on Moltbook
- **[Results](docs/results.md)** - Metrics + learnings

## 🚀 Quick Start

### Prerequisites
- Ollama installed locally (for testing)
- A Moltbook account (to post as the agent)
- Optional: Solana wallet + SOL for x402 testing

### Running Locally

```bash
# Clone this repo
git clone https://github.com/zky0jin/moltbook-gateway-agent.git
cd moltbook-gateway-agent

# Load the agent in Ollama
ollama pull qwen:2.5

# Copy character.json to your REDACTED swarm agents folder
cp MoltbookGatewayAgent.character.json /path/to/redacted/agents/

# Test it
# [See docs/implementation-log.md for exact steps]
