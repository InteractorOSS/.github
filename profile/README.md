<h1 align="center">Interactor Open Source</h1>

<p align="center">
  <strong>Open-source business apps, powered by Interactor Agent OS.</strong><br/>
  CRM · Ticketing · Project Management · Meeting · Growth · Social · Chat · Personal Productivity
</p>

<p align="center">
  <a href="https://interactor.com/products"><img alt="Products" src="https://img.shields.io/badge/products-interactor.com%2Fproducts-0891B2?style=flat-square"></a>
  <a href="https://interactor.com/docs"><img alt="Docs" src="https://img.shields.io/badge/docs-interactor.com%2Fdocs-7C3AED?style=flat-square"></a>
  <a href="https://build.interactor.com"><img alt="License" src="https://img.shields.io/badge/license-see%20build.interactor.com-059669?style=flat-square"></a>
  <a href="https://discord.gg/nzZzGY6KdV"><img alt="Discord" src="https://img.shields.io/badge/discord-join-5865F2?style=flat-square&logo=discord&logoColor=white"></a>
  <a href="https://join.slack.com/t/interactorteam/shared_invite/zt-eqx0mnh0-BkZWPzmh3DUJSTYxAJHmqw"><img alt="Slack" src="https://img.shields.io/badge/slack-join-4A154B?style=flat-square&logo=slack&logoColor=white"></a>
</p>

<p align="center">
  ❤️ <strong>Thank you for your stars, your issues, and your pull requests.</strong> We really love open source.
</p>

---

## What is Interactor Open Source?

Interactor Open Source is a portfolio of self-hostable business applications — CRM, ticketing, project management, meetings, growth analytics, social posting, team chat, and personal productivity — built on the **Interactor Agent OS** platform. Every product ships with a free, fully-featured community edition you can run yourself, and a managed hosted tier at [interactor.com](https://interactor.com) for teams that want SLAs, SSO, audit logs, and enterprise support.

We believe AI agents should be embedded in the tools you already use — not sold as a separate layer on top. Every product in this organization is **agent-native**: the Interactor Agent OS gives each application planning, memory, tool-use, and conversational interfaces out of the box.

## Featured products

Each product has its own repository in this org. The marketing page, documentation, and hosted SaaS for each live on [interactor.com](https://interactor.com).

### 🐾 Productivity & collaboration

| Product | Repo | What it does | Marketing | Hosted |
|---|---|---|---|---|
| **Build** | [InteractorOSS/build](https://github.com/InteractorOSS/build) | Open-source product management with public roadmaps, changelogs, and feedback boards. | [interactor.com/products/build](https://interactor.com/products/build) | [Try free](https://interactor.com/products/build/app) |

### 🧩 Templates & references

Sample projects, reference implementations, and proof-of-concept work live under repos prefixed `template-`. Use them as starting points for your own agents and applications.

## Built on Interactor Agent OS

All products in this organization are powered by **[Interactor Agent OS](https://interactor.com/agent-os)** — the open platform for building AI agents that plan, remember, and act with tools. Agent OS provides:

- **Conversational interface** — every app gets chat-driven UX for free
- **Tool use** — agents invoke product capabilities through a unified MCP-style contract
- **Memory** — short-term context plus long-term knowledge bases (KB, SKB, UKB)
- **Multi-agent orchestration** — products can compose agents across the portfolio
- **Auth and identity** — single sign-on across all hosted products

Learn more: [interactor.com/agent-os](https://interactor.com/agent-os) · [docs](https://interactor.com/docs/agent-os)

## Getting started

### Try the hosted version

Every product has a free hosted tier with no install required. Sign up once at [interactor.com](https://interactor.com) and access any product:

- [Interactor Build](https://interactor.com/products/build/app)

### Self-host

Each repo includes Docker Compose and Helm chart options for self-hosting. Quickstart:

```bash
git clone https://github.com/InteractorOSS/<product>.git
cd <product>
docker compose up
```

See the per-product docs at [interactor.com/docs](https://interactor.com/docs) for production deployment, scaling, and configuration.

### Build your own

The Interactor Agent OS is itself the foundation you can build new agents on. Start from `template-agent` to scaffold a new agent application, or extend any existing product. See [interactor.com/docs/agent-os/build](https://interactor.com/docs/agent-os/build).

## Community & support

We genuinely love open source. If you need help, ask — we'll show up.

- 💬 **Discord** — [join here](https://discord.gg/nzZzGY6KdV) for general chat, questions, and showcases
- 💼 **Slack** — [join here](https://join.slack.com/t/interactorteam/shared_invite/zt-eqx0mnh0-BkZWPzmh3DUJSTYxAJHmqw) for the Interactor team channel
- 🐛 **Issues** — open an issue on the relevant product repo
- ✉️ **Email** — [support@interactor.com](mailto:support@interactor.com) for general questions
- 🔒 **Security** — [security@interactor.com](mailto:security@interactor.com) for vulnerability reports (please don't open public issues)

## Enterprise & hosted

For teams that need SLAs, SSO/SAML, audit logs, advanced RBAC, dedicated support, or compliance certifications (SOC 2, HIPAA, GDPR), see our hosted tiers and Enterprise plans:

- **Pricing** — [interactor.com/pricing](https://interactor.com/pricing)
- **Trust & security** — [interactor.com/security](https://interactor.com/security)
- **Contact sales** — [interactor.com/contact](https://interactor.com/contact)

The community edition of every product is and will remain free, fully-featured for self-host, and open source. We do not gate core functionality.

## License

Each repository in this organization is open source under the license declared in its `LICENSE` file. License terms, contribution requirements, and build instructions for each product are documented at **[build.interactor.com](https://build.interactor.com)**.

In short:

- **Community edition** — free to self-host and modify in accordance with the per-product license
- **Hosted tier** — managed by Interactor with optional commercial terms for SLAs and enterprise features
- **Commercial use** of source code in non-self-host scenarios may require a commercial license — see the product's `LICENSE` and [build.interactor.com](https://build.interactor.com) for specifics

## Contributing

We welcome contributions of all kinds — bug fixes, new features, docs improvements, translations, examples.

1. Read the [Contributor Guide](https://github.com/InteractorOSS/.github/blob/main/CONTRIBUTING.md)
2. Sign the [Contributor License Agreement (CLA)](https://github.com/InteractorOSS/.github/blob/main/CLA.md)
3. Open a pull request against the relevant product repo
4. Follow the code style and tests in each repo's `CONTRIBUTING.md`

For larger features or breaking changes, please open a Discussion first or post in the `#design` channel on Discord.

## Code of conduct

We follow the [Contributor Covenant](https://github.com/InteractorOSS/.github/blob/main/CODE_OF_CONDUCT.md). Be kind. Help others. Disagree respectfully.

---

<p align="center">
  <a href="https://interactor.com">interactor.com</a> ·
  <a href="https://interactor.com/products">Products</a> ·
  <a href="https://interactor.com/docs">Docs</a> ·
  <a href="https://interactor.com/blog">Blog</a> ·
  <a href="https://interactor.com/changelog">Changelog</a> ·
  <a href="https://interactor.com/security">Security</a>
</p>

<p align="center">
  <sub>Made with ❤️ in the open by the Interactor community.</sub>
</p>
