<picture>
  <source media="(prefers-color-scheme: dark)" srcset="rotascale-logo-reversed.svg">
  <img src="rotascale-logo.svg" alt="Rotascale" width="280">
</picture>

**Autonomy, with authority.**

Software for putting AI agents to work on things that matter, and answering for what they did.

- **RotaGrant** decides what an agent may do, before it acts. A named person grants bounded authority, each consequential action is checked against it in a fixed order, and the outcome is recorded either way.
- **RotaForge** makes the APIs you already run ready for agents. Reads are served, every change waits for a named person, and what the document cannot justify is not built.

They are separate products, and each is used on its own. Both run in your environment.

### Open here

- [agent-governance-spec](https://github.com/rotascale/agent-governance-spec): the specification behind the authority model. A vocabulary for stating what an agent may do, and for recording what was decided. Apache 2.0.
- [rotascale-sdks](https://github.com/rotascale/rotascale-sdks): the client libraries for RotaGrant, in Python and TypeScript, and the MCP proxy. Apache 2.0.

[rotascale.com](https://rotascale.com) · [Documentation](https://docs.rotascale.com) · [See it live](https://rotascale.com/demo/)
