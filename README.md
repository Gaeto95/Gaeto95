# Gaeto95

**Independent builder working across games, software, infrastructure, automation, and AI.**

I build and operate systems end to end.

Most of my serious work lives in private repositories and spans online game technology, browser-based game systems, native launchers, backend services, automation, AI tooling, production infrastructure, data engineering, developer tools, and experimental products.

I tend to work where frontend, backend, infrastructure, data, game systems, automation, AI, and product decisions all collide.

I like taking systems that are old, fragmented, complicated, or painfully manual and making the complexity disappear for the person using them.

---

## What I Build

### Games & Game Technology

- Online game platforms and live-service systems
- Legacy game modernization and browser implementations
- Native launchers, patchers, repair and distribution systems
- Game-data parsers, editors, exporters, diffing and migration tools
- Unity and browser/desktop game development
- Multiplayer, combat, progression and gameplay systems
- 3D model, animation, VFX and asset pipelines
- Internal tools for operating and evolving live games

### Full-Stack Systems

- Large web applications and internal platforms
- React, Next.js, Svelte and SvelteKit frontends
- Django, FastAPI, Fastify and Node.js backends
- PostgreSQL, Supabase, SQLite and Redis systems
- Authentication, payments, accounts and reward systems
- Admin dashboards, analytics and reporting
- APIs, workers, queues and realtime systems

### Infrastructure & Automation

- Dockerized production environments
- Linux and Windows infrastructure
- Production migrations and cutovers
- Databases, object storage, DNS and distribution
- CI/CD and deployment verification
- Browser automation with Playwright / Chromium
- Discord bots and persistent autonomous services
- Monitoring, recovery and operational tooling
- Backup, rollback and integrity-verification systems

### Data, Reverse Engineering & Tooling

- Legacy binary and structured data formats
- Parsers and format reconstruction
- Structural comparison and validation
- Large searchable data explorers
- Migration and compatibility tooling
- Source-of-truth reconstruction across old systems
- Exact binary/data repairs with invariant checking

---

## AI-Native Development

AI is not a separate tool I occasionally ask for code.

It is part of my development environment.

I use multiple frontier models, coding agents and local models depending on the job. That includes systems from OpenAI, Anthropic, Google and open/local model ecosystems rather than relying on a single provider or model.

Different models end up acting as different kinds of workers:

- implementation
- architecture
- research
- debugging
- code review
- reverse engineering
- infrastructure
- testing and QA
- security review
- documentation
- visual/product iteration
- long-running autonomous work

I regularly have multiple agent sessions working simultaneously across different parts of larger systems, sometimes with those agents spawning their own subagents or recurring automations.

Information and work move between them.

One model may investigate a problem, another challenge the conclusion, another implement it, and another verify what actually happened.

So my workflow increasingly looks like:

**define → decompose → delegate → connect → challenge → verify → ship**

The important part is not generating more code.

It is being able to direct much more technical work without giving up judgment, source-of-truth control, or verification.

---

## Multi-Model Workflow

I deliberately avoid treating any model as universally "best."

I use combinations of:

- **OpenAI / Codex**
- **ChatGPT**
- **Claude / Claude Code**
- **Gemini**
- **Local and open-weight models**
- Specialized agents, tools and automation around them

Models are selected and combined based on reasoning depth, coding ability, context requirements, latency, autonomy, cost, privacy and the type of work being performed.

For some problems I want a very strong frontier reasoning model.

For others I want an agent that can work inside a repository for hours.

For repetitive or private workloads, local models can make more sense.

For difficult decisions, I often prefer disagreement between independent models over trusting the first convincing answer.

---

## How I Work

I care a lot about the difference between something that looks finished and something that is actually finished.

A typical progression is:

`investigated`
→ `implemented`
→ `tested`
→ `CI verified`
→ `deployed`
→ `runtime verified`

Those are not the same state.

My general rules are:

- Find the real source of truth before changing things.
- Prefer evidence over remembered state.
- Keep production changes narrow and reversible.
- Let agents solve recoverable problems instead of constantly asking permission.
- Use independent verification for important work.
- Preserve tests, hashes, reports, logs and useful artifacts.
- Record negative results instead of forcing a successful conclusion.
- Parallelize aggressively when tasks can safely be separated.
- Keep final authority over destructive, financial and production decisions.

---

## Selected Work

Most production repositories are private, but my work includes:

- A large interconnected online game ecosystem spanning client, launcher, web, backend, databases, bots, infrastructure and live operations
- An ongoing browser implementation and modernization of legacy game technology
- Custom editors and tooling for large legacy game-data formats
- AI-powered developer and operational systems
- A full-stack local AI video creation/editing platform
- Unity horror and action-game development
- Automated research and simulation systems
- Large production infrastructure migrations
- Payment and security hardening
- Discord and browser automation systems
- 3D model and game-data explorers
- Internal tooling that turns complicated operational workflows into repeatable systems

---

## Technology

### Languages

`TypeScript` `JavaScript` `Python` `C#` `SQL` `PowerShell`

### Web

`React` `Next.js` `Svelte` `SvelteKit` `Tailwind`  
`WebGL` `Canvas` `Babylon.js`

### Backend & Data

`Django` `FastAPI` `Fastify` `Node.js`  
`PostgreSQL` `Supabase` `SQLite` `Redis`

### Games & Graphics

`Unity` `Blender` `WebGL` `Babylon.js`

### Infrastructure

`Docker` `Linux` `Windows` `WSL`  
`GitHub Actions` `Playwright` `Chromium`

### AI

`Codex` `ChatGPT` `Claude Code` `Gemini`  
`Local / Open-Weight Models`  
`Agents` `Subagents` `Automations` `Tool-Using Systems`

---

## Philosophy

I am less interested in specializing in one layer of software than understanding enough of the entire system to make the pieces work together.

AI has pushed that much further.

The limiting factor is increasingly not how quickly I can type an implementation.

It is how well I can decide **what should exist, how the problem should be divided, which results should be trusted, and how all of the pieces fit together.**

> **Build the complicated thing. Make using it feel simple.**

---

Most production, infrastructure and game-service repositories are intentionally private.

The public GitHub profile represents only a small part of the work.
