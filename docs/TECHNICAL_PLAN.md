# Technical Plan — NEON//REIGN

## Phase 1: Offline playable prototype
- TypeScript + Vite + React for a lightweight browser game.
- Pure, deterministic TypeScript game engine independent of UI.
- Seeded AI opponent; no paid services or wallet required.
- Unit tests for card abilities, energy, turn progression and victory.

## Phase 2: Multiplayer
- Server-authoritative match state and validation.
- Authenticated matchmaking, reconnect and anti-cheat.
- Persist player profiles and decks; rate-limit APIs.
- Never trust client-submitted combat results.

## Phase 3: Base
- Wallet sign-in as optional account linking, not a requirement to play.
- Base Sepolia for smart contract and marketplace testing.
- Carefully audited or established NFT standards for tradable cards.
- Fixed-price USDC payments only after security review.
- Minimize transactions; battle state stays offchain for responsiveness.
- Never ask players for seed phrases or private keys.
- Account for legal, consumer protection, tax and platform requirements before paid sales.

## Scope and spending
- Budget cap: $20. No expenses approved yet.
- Free-tier development first. Verify provider pricing and quotas before adopting services.
- No paid infrastructure, production contracts, or mainnet transactions until explicitly approved.

## Implementation milestones
1. Rules, five starter cards and deterministic engine.
2. Interactive board with three sectors and a basic AI.
3. Playtesting, balance changes and tutorial.
4. Online PvP prototype.
5. Wallet integration and testnet ownership.
6. Optional production marketplace after review.

## Non-goals for first release
- Token issuance, staking, buyback mechanisms.
- Onchain combat, paid random packs, gambling features.
- Automatically generated competitive card stats.
