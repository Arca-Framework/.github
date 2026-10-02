# Arca Framework

<p align="center">
  <strong>A modern, modular foundation for FiveM.</strong>
</p>

<p align="center">
  <a href="https://github.com/arca-framework">GitHub</a>
  ·
  <a href="https://docs.arca.dev">Documentation</a>
  ·
  <a href="https://discord.gg/YOUR-INVITE">Discord</a>
</p>

---

## About

**Arca Framework** is a modern, modular, and developer-focused framework for FiveM, built from the ground up to provide a clean foundation for creating scalable and reliable roleplay servers.

Arca is designed around simplicity, flexibility, and maintainability. Rather than forcing developers into a rigid ecosystem, Arca provides the core systems and tooling needed to build your server your way.

Whether you're building a small community server or a large-scale roleplay experience, Arca aims to provide the foundation you need without unnecessary complexity.

---

## Why Arca?

Arca is built with a simple philosophy:

> **The framework should work for you, not the other way around.**

### Modular by design

Use the systems you need without being forced to use everything.

### Developer focused

Clean APIs, predictable behaviour, and an architecture designed with resource developers in mind.

### Lightweight

Keep your server focused on the resources and features that actually matter.

### Extensible

Build your own systems and integrate Arca into your existing infrastructure.

### Open source

Arca is built in the open, allowing the community to contribute, review, and improve the framework together.

Arca is designed around a modular architecture where individual systems can evolve independently.

---

## Ecosystem

Arca is intended to grow beyond a single framework resource.

```text
[arca]
├── arca_core
├── arca_identity
├── arca_characters
├── arca_inventory
├── arca_target
├── arca_hud
├── arca_loadingscreen
├── arca_spawn
├── arca_phone
└── ...
```

Each component is designed to have a clear responsibility and communicate through well-defined APIs.

---

## Getting Started

> Installation instructions will be added as Arca approaches its first public release.

### Requirements

* FiveM Server
* FXServer
* OX MYSQL
* Node.js where required by individual resources

### Installation

```bash
git clone https://github.com/arca-framework/arca-core.git
```

Place the resource inside your server's resources directory and follow the installation instructions provided in the documentation.

```text
resources/
└── [arca]/
    ├── arca_core/
    └── ...
```

Then add the required resources to your server configuration.

```cfg
ensure arca_core
```

For complete installation instructions, see the documentation.

---

## Development

Arca is designed to be easy to develop against and easy to extend.

Example:

```lua
local player = Arca.GetPlayer(source)

if player then
    print(player:getIdentifier())
end
```

The API is still evolving and examples will be expanded as development progresses.

## Contributing

Arca is intended to be a community-driven project.

Contributions are welcome once the contribution guidelines are published.

Before opening a pull request:

1. Check existing issues and pull requests.
2. Follow the project's coding conventions.
3. Keep changes focused.
4. Test your changes locally.
5. Update documentation where necessary.
6. Provide a clear description of your changes.

More information will be available in `CONTRIBUTING.md`.

---

## Community

Have a question, found a bug, or want to discuss Arca?

Join the community:

<p align="center">
  <a href="https://discord.gg/YOUR-INVITE">
    <img src="https://img.shields.io/badge/Discord-Join%20the%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
</p>

---

## Support

If you've found a bug, please open an issue in the appropriate repository.

For questions, development discussions, and community support, use the Discord server.

Please avoid opening issues for general support requests unless the issue represents a reproducible bug.

---

## Philosophy

Arca isn't intended to be a collection of features for the sake of having features.

The goal is to provide a solid foundation that developers can build upon.

**Simple core.
Clear APIs.
Modular systems.
No unnecessary restrictions.**

---

## License

Arca Framework is open source.

Individual repositories may use different licenses. Please check the `LICENSE` file within the relevant repository before using or redistributing code.

---

<p align="center">
  <strong>Arca Framework</strong>
  <br>
  A modern foundation for FiveM.
</p>

<p align="center">
  <sub>Built for developers. Designed for communities.</sub>
</p>
