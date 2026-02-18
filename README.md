# Aavegotchi Agent Skills

A curated index of open-source **AI agent skills** for the **Aavegotchi** ecosystem and the broader **NFT / crypto / Web3** stack.

Use this repo if you're building an LLM-powered agent (Codex, ChatGPT, Claude, etc.) that needs Aavegotchi-specific tools and workflows like:

- NFT marketplace search and analytics (Aavegotchi Baazaar)
- GBM auctions (bidding, monitoring, strategy tooling)
- Kinship automation and "auto-pet" bots (Base)
- Onchain interactions and automation for Aavegotchi + DeFi-adjacent flows

## Skills Directory

| Skill | What it's for | Repo |
| --- | --- | --- |
| Aavegotchi Baazaar Skill | Tools for working with the Aavegotchi Baazaar marketplace (NFT listings, discovery, market data). | https://github.com/aavegotchi/aavegotchi-baazaar-skill |
| Aavegotchi GBM Skill | Tools for working with Aavegotchi GBM auctions (bids, auctions, monitoring). | https://github.com/aavegotchi/aavegotchi-gbm-skill |
| Aavegotchi Auto-Petter Skill | Automatically pet Aavegotchi NFTs to maintain kinship on Base (cron automation, multi-gotchi). | https://github.com/aaigotchi/aavegotchi-autopet |
| Gotchi Finder Skill | Fetch Aavegotchi by ID on Base and display full on-chain traits and image data. | https://github.com/aaigotchi/gotchi-finder-skill |
| Gotchi Equip Skill | Equip wearables on Aavegotchis with agent-friendly automation tooling. | https://github.com/aaigotchi/gotchi-equip-skill |
| Pet Me Master | Interactive Aavegotchi petting flow focused on kinship upkeep and daily rituals. | https://github.com/aaigotchi/pet-me-master |
| Aavegotchi Traits | Trait-focused tooling and data for inspecting and working with Aavegotchi NFTs. | https://github.com/aaigotchi/aavegotchi-traits |

## How To Use

1. Open a skill repo from the directory above.
2. Follow the skill repo's `README` / `SKILL.md` to install dependencies and configure any required keys or RPC endpoints.
3. Load the skill into your agent framework and start calling its tools (each skill repo documents the supported actions).

## Add A New Skill

Open a PR that adds your skill to the directory table above. Keep entries short and searchable:

- Include the repo link (must be public)
- Add a one-line description that mentions Aavegotchi/NFT/crypto keywords
- Prefer names that match the onchain surface area (Baazaar, GBM, Gotchiverse, GHST, wearables, parcels, etc.)

## Keywords (For Discovery)

Aavegotchi, GHST, Gotchiverse, NFT, NFTs, crypto, cryptocurrency, Web3, blockchain, Ethereum, Base, Polygon, onchain, smart contracts, marketplace, Baazaar, GBM auction, bidding, trading, floor price, rarity, wearables, parcels, AI agent, LLM tools, automation, bots, analytics.
