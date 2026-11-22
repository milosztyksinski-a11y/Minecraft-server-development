# Minecraft Server Gameplay Toolkit

An open-source, community-oriented collection of Minecraft server utilities and example gameplay scripts for administrators and creators working with **Paper / Spigot** and **Skript**.

> **Project status: Early development.** This repository currently contains a starter example and documentation. The advanced systems listed in the roadmap are **proposed features**, not finished releases. No download counts, GitHub stars, contributors, or user numbers are claimed.

## Why this project exists

Configuring custom gameplay can be difficult for small Minecraft communities. This project aims to make common server features easier to understand and reuse with modular scripts, clear setup instructions, and code examples.

## Who it is for

- Minecraft server administrators looking for configurable gameplay systems.
- Community developers learning Skript or maintaining custom servers.
- Contributors interested in sharing and improving open-source server utilities.

## What is included today

| Component | Purpose | Status |
| --- | --- | --- |
| [`examples/cooldown-demo.sk`](examples/cooldown-demo.sk) | Simple command-based speed ability with per-player cooldown | Example (requires in-server testing) |
| [`docs/installation.md`](docs/installation.md) | Basic installation and testing guidance | Available |
| [`docs/roadmap.md`](docs/roadmap.md) | Transparent proposed features and milestones | Available |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Instructions for proposing changes | Available |

## Planned areas of development

- Reusable custom PvP item abilities and their cooldowns.
- Configurable server events and reward systems.
- Region-specific gameplay rules and integrations where supported.
- Better configuration, localization, examples, and documentation.
- Compatibility checks for commonly used server versions and plugins.

These features are **not included unless explicitly added to the repository**.

## Requirements

- A working Minecraft Java Edition server using a compatible Paper or Spigot build.
- The Skript plugin compatible with that server version.
- Optional dependencies such as SkBee and WorldGuard only for future modules that explicitly require them.

Check each plugin's own documentation for supported versions. This starter example has not been validated against every server or Skript version.

## Quick start

1. Download or clone this repository.
2. Read [`docs/installation.md`](docs/installation.md).
3. Place `examples/cooldown-demo.sk` in `plugins/Skript/scripts/` on a **test** server.
4. Run `/sk reload cooldown-demo` from the server console (or with appropriate permissions).
5. In game, try `/toolkitboost`; review the server console for errors.

## Contributing

Ideas, bug reports, documentation fixes, and pull requests are welcome. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Project transparency

This is an initial public project skeleton. Adoption metrics should always be taken from GitHub and real release/download analytics; targets or examples should never be presented as achieved results.

## License

MIT License — see [`LICENSE`](LICENSE).

Minecraft is a trademark of Mojang Studios / Microsoft. This project is an independent community effort and is not affiliated with or endorsed by them.
