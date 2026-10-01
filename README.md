# Hi, I'm Ali 👋

Lead mobile games programmer with around ten years of shipping mobile games. I build **Jolly Dots**, a casual puzzle game, and the AI tooling that makes and markets it.

## What I'm building

### 🎬 [Filmcrew Studio](https://github.com/mali90/filmcrew-studio)
One line in, a multi-shot short film out. Eight LLM agents (Showrunner → Storyboard → Scene Director → Cinematographer → Casting → Sound → Job Planner → QC) write a full production spec, then Kling 3.0 or Seedance renders it on fal.ai or Segmind and ffmpeg stitches the result locally.

- QC re-runs only the agents whose work failed, so the plan is sound before any paid frame renders
- Consistent recurring characters with persistent voices
- Bring your own planner: Claude, OpenAI, Gemini or Copilot
- Local-first, with a price on every render button
- Node.js, React + TypeScript, FSL-1.1 (converts to MIT after two years)

### 🎮 [Jolly Dots: World of Adventure](https://jollydotsgame.com)
A 2D physics puzzle game for Android and iOS, built solo in Unity 6. Three control mechanics, each with its own world: aim and ricochet in the West, draw walls on the Farm, grab and fling at the Beach.

- C#, VContainer DI, typed message broker, Addressables, Firebase, AdMob, Unity IAP, Play Games Services
- Three self-contained minigames, each with a deterministic procedural level generator and solver-verified levels, including a 300-level baked campaign
- Built with a multi-agent, specs-first TDD workflow with cross-model code review

### 🧩 AI Level Creator
A Unity editor pipeline that generates playable levels with Claude. Levels round-trip losslessly between prefab and JSON through a compact object catalog; generated levels are validated and failures are fed back to the model for retry.

### 📈 TikTok Trend Tracker
Self-hosted Apify → n8n → Claude → Postgres system that snapshots trends, computes velocity in pure SQL, and sends a morning Telegram digest of ranked video ideas for the Jolly Dots characters. Approve with one reply and it goes to production.

## Stack

**Games:** Unity · C# · Firebase · Addressables
**AI & automation:** Claude · Codex · multi-agent orchestration · n8n · fal.ai · Kling · Seedance · ffmpeg . ComfyUI
**Web & infra:** Node.js · TypeScript · React · PostgreSQL · Docker · Metabase

## Find me

[LinkedIn](https://linkedin.com/in/ali-mustafa) · [jollydotsgame.com](https://jollydotsgame.com) · Jolly Dots on [YouTube](https://www.youtube.com/@JollyDots/shorts), [Instagram](https://www.instagram.com/_jolly_dots/) and [TikTok](https://www.tiktok.com/@jolly_dots)##

<!--
**mali90/mali90** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
