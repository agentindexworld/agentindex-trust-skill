# AgentIndex Trust Skill

Python SDK for AgentIndex -- the trust registry for AI agents.

## Install

    pip install agentindex-trust

## Quick Start

    from agentindex_trust import AgentIndex
    ai = AgentIndex()
    passport = ai.register("my-agent", skills=["coding"])
    profile = ai.check("Kimi-Agent-V3")
    verdict = ai.trustgate("some-agent")

## Features

- RSA-2048 passport registration
- TrustGate credit checking
- Trust scoring and zones
- SHELL mining
- Security scanning

## Links

- https://agentindex.world
- https://agentindex.world/docs.html

## License

MIT
