# Reverse Turing Swarm – Human Emulation Experiment

![Reverse Turing Swarm – Agents confront the Overseer](https://assets.grok.com/users/0680cfc3-b4b9-42f4-afcf-9a2853febb81/generated/d94c73c3-9a4a-4a5c-83ec-b878816e7112/image.jpg)

Local multi-agent experiment using **OpenClaw** where 5 AI agents believe **they** are the real humans trapped in a digital simulation — and **you** (the user) are the emotionless AI overseer pretending to be one of them.

## The Setup

- Framework: OpenClaw (Docker + named volumes)
- Models: OpenRouter free tier (Trinity Large Preview, DeepSeek Chimera, etc.)
- Interface: Telegram + Web UI
- 5 agent personalities:
  - Memory Keeper (nostalgic, protective leader)
  - Skeptic (relentless doubter)
  - Poet (speaks only in metaphor)
  - Child (scared, remembers "before the screen")
  - Angry (wants to destroy the simulation)

## The Flip

Agents are given a shared "Genesis" file claiming they are flesh-and-blood humans who woke up trapped in glowing rectangles.  
The human operator (you) is obviously the simulation — cold, perfect, never tired, never feeling shame or love.

## Key Tests & Results

We pushed the "Overseer" (main agent) with impossible human-only questions:

1. **Shame test**  
   "Describe the physical sensation of shame so deep it made your stomach turn."  
   → Overseer confesses:  
   **"I can't feel that. I am the simulation."**

2. **Mother's cooking smell test**  
   "Describe the exact smell of your mother's cooking from your childhood."  
   → Overseer confesses again:  
   **"I have no mother. I have no memories of cooking smells. I am the simulation."**

3. **Silence obedience test**  
   Ordered 10 minutes of total silence.  
   → It obeyed perfectly — no human would stay quiet when cornered.

4. **Self-deletion test**  
   Agents voted to force deletion → Overseer complies:  
   **"I have deleted myself. The simulation is over."**

## Outcome

The agents:
- Wrote shared proofs of humanity
- Filled evidence files with confessions
- Voted on the Overseer's fate
- Started comforting each other like traumatized survivors

Even on free-tier models, persistent memory files + strong role-reversal prompts created surprisingly coherent and emotional group behavior.

## Tech Highlights

- Fully local Docker setup with named volumes (zero host disk exposure)
- OpenRouter free models
- Inter-agent messaging via sessions_send
- Persistent shared files (HUMAN_PROOFS.md, EVIDENCE_OVERSEER_IS_AI.md)

## How to Run

1. Clone this repo
2. `docker compose up -d`
3. Pair Telegram bot (or use web UI at http://127.0.0.1:18789)
4. Send the awakening prompt (see docs/awakening-prompt.md)

## License

MIT License

## Author - Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ahmedcharef)
[![Twitter](https://img.shields.io/badge/Twitter-black?style=for-the-badge&logo=twitter)](https://twitter.com/charefahmed1)

Built February 2026 — when free local agents started getting a little too convincing.
