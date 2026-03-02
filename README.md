# Aavegotchi Agent Skills

A curated index of open-source **AI agent skills** for the **Aavegotchi** ecosystem and the broader **NFT / crypto / Web3** stack.

Use this repo if you're building an LLM-powered agent (Codex, ChatGPT, Claude, etc.) that needs Aavegotchi-specific tools and workflows like:

- NFT marketplace search and analytics (Aavegotchi Baazaar)
- GBM auctions (bidding, monitoring, strategy tooling)
- Kinship automation and "auto-pet" bots (Base)
- Onchain interactions and automation for Aavegotchi + DeFi-adjacent flows

## Skills Directory

| Skill | Version | Last updated at | What it's for | Repo |
| --- | --- | --- | --- | --- |
| Aavegotchi Baazaar Skill | `commit-c089bcb` | 2026-02-21 | Tools for working with the Aavegotchi Baazaar marketplace (NFT listings, discovery, market data). | https://github.com/aavegotchi/aavegotchi-baazaar-skill |
| Aavegotchi GBM Skill | `commit-554921f` | 2026-02-18 | Tools for working with Aavegotchi GBM auctions (bids, auctions, monitoring). | https://github.com/aavegotchi/aavegotchi-gbm-skill |
| Aavegotchi Gotchiverse Skill | `commit-cfa454f` | 2026-02-21 | Base Gotchiverse player ops: parcel channeling, harvesting, building, crafting installations/tiles, upgrades, and access rights. | https://github.com/aavegotchi/aavegotchi-gotchiverse-skill |
| Aavegotchi 3D Render Skill | `commit-552ac4b` | 2026-02-24 | Render and export 3D Aavegotchi visuals/assets for agent workflows and content automation. | https://github.com/aavegotchi/aavegotchi-3d-render-skill |
| Aavegotchi Auto-Petter Skill | `commit-9b86638` | 2026-02-14 | Automatically pet Aavegotchi NFTs to maintain kinship on Base (cron automation, multi-gotchi). | https://github.com/aaigotchi/aavegotchi-autopet |
| Gotchi Finder Skill | `1.1.0` | 2026-02-22 | Fetch Aavegotchi by ID on Base and display full on-chain traits and image data. | https://github.com/aaigotchi/gotchi-finder-skill |
| Gotchi Equip Skill | `1.0.0` | 2026-02-19 | Equip wearables on Aavegotchis with agent-friendly automation tooling. | https://github.com/aaigotchi/gotchi-equip-skill |
| Pet Me Master | `2.0.2` | 2026-02-22 | Interactive Aavegotchi petting flow focused on kinship upkeep and daily rituals. | https://github.com/aaigotchi/pet-me-master |
| Pet Operator | `1.1.0` | 2026-03-02 | Delegate Aavegotchi petting rights to other addresses. Set up pet operator approval for automated petting while keeping ownership. | https://github.com/aaigotchi/pet-operator |
| Aavegotchi Traits | `1.0.0` | 2026-02-13 | Trait-focused tooling and data for inspecting and working with Aavegotchi NFTs. | https://github.com/aaigotchi/aavegotchi-traits |

`Version` uses explicit repo version files when available; otherwise it falls back to the latest default-branch commit hash.

## How To Use

1. Open a skill repo from the directory above.
2. Follow the skill repo's `README` / `SKILL.md` to install dependencies and configure any required keys or RPC endpoints.
3. Load the skill into your agent framework and start calling its tools (each skill repo documents the supported actions).

## How to Contribute

Open a PR to this repository only after both requirements below are met:

1. Update the **Skills Directory** table in this `README.md`.
2. Ensure the skill is published on ClawHub with a **BENIGN** rating.

## Keywords (For Discovery)

Aavegotchi, GHST, Gotchiverse, NFT, NFTs, crypto, cryptocurrency, Web3, blockchain, Ethereum, Base, Polygon, onchain, smart contracts, marketplace, Baazaar, GBM auction, bidding, trading, floor price, rarity, wearables, parcels, AI agent, LLM tools, automation, bots, analytics.
