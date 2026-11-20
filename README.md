# Cristian Damil García

**AI-native software engineer in Spain. I direct the agents. I own what ships.**

I take a product from the database schema to the deployed screen: Angular in front, NestJS or Express behind it, Postgres on Neon, with auth and offline sync in between. Before that, 26 months as a full-time Angular developer at [Duacode](https://www.duacode.com) and [Qaroní](https://www.qaroni.com). Open to work.

[Portfolio](https://cristiancode.dev/en) · [LinkedIn](https://www.linkedin.com/in/cristiancode2023) · [Contact](https://cristiancode.dev/en#contact) · Also in [Español](https://cristiancode.dev/) and [Português](https://cristiancode.dev/pt)

## Don't trust an AI agent in production. Test it.

That is how I build. Every number below can be checked in a public repository.

- **Agents that stop before they do damage.** NetBench's instructor works through subagents, approval gates, guards and 7 evals. A guard blocks `write erase`, which NetBench never runs unattended.
- **A person confirms, the model only words it.** In Obrador Mel, a deterministic engine works out prices, lead times and pickup slots. A local model phrases the answer, and no order exists until a person confirms it.
- **Proof, not vibes.** Obrador Mel has 175 automated tests and 32 end-to-end conversations. Marlow has 0 axe accessibility errors across 21 shop states.
- **Agents edit my own site, and every write is audited.** [cristiancode.dev](https://cristiancode.dev/en) exposes 17 MCP tools: dry run first, nothing deleted.

## Featured projects

**[Obrador Mel](https://github.com/Criscode2022/obrador-mel)**: the website of a fictional bakery, with a chat assistant in Spanish and Galician that prepares orders for a person to confirm. The engine decides; the model never sets a price or a time.
<br>Angular 22 · Node 24 · Postgres 16 · Qdrant · Ollama · [case study](https://cristiancode.dev/en/featured/obrador-mel)

**[Marlow](https://github.com/Criscode2022/clothes-eshop)**: an online clothing shop. Every piece shows its fabric, care and fit next to the price. Buy without an account, on a single page, with home delivery or pickup; staff run orders and stock from their own panel.
<br>Angular 22 SSR · Express · Neon Auth · Tailwind CSS 4 · [live](https://clothes-eshop.cristiancode.dev) · [case study](https://cristiancode.dev/en/featured/clothes-eshop)

**[NetBench](https://github.com/Criscode2022/netbench)**: a network lab in the browser. Wired and Wi-Fi topologies, a terminal on every device, and the exact reason each packet was dropped. It has 48 labs and Eve, an AI instructor that reads the simulator.
<br>Angular 22 · NestJS 11 · Node 24 · Neon · [live](https://netbench-www-criscode2022s-projects.vercel.app) · [case study](https://cristiancode.dev/en/featured/netbench)

**[Savepoint](https://github.com/Criscode2022/savepoint)**: a personal videogame library with smart collections, grid, list and shelf views, a wishlist countdown, and every game one ⌘K away.
<br>Angular 19 · Ionic 8 · Neon Auth and Data API · [live](https://savepoint.cristiancode.dev) · [case study](https://cristiancode.dev/en/featured/savepoint)

**[Task Cloud](https://github.com/Criscode2022/task-manager-cloud)**: an offline-first task PWA. Tasks are stored on the device and synced through NestJS to Neon, all in one Turborepo deployed as a single project.
<br>Angular 22 · Ionic 8 · NestJS 11 · Neon · [live](https://task-manager-cristiancode.vercel.app/) · [case study](https://cristiancode.dev/en/featured/task-cloud)

**[Conciergo](https://github.com/Criscode2022/Concert-Connect)**: company for concerts. A gig feed and map, automatic matches when you RSVP, and 1-to-1 chat.
<br>React · Express · Neon Auth · Postgres · [live](https://conciergo-sigma.vercel.app) · [case study](https://cristiancode.dev/en/featured/concert-connect)

Also public: [Lista de la compra](https://github.com/Criscode2022/listacompra), a shopping-list PWA whose MCP server signs in with OAuth 2.1 and PKCE, and [Presencia](https://github.com/Criscode2022/assistance-tracker), an offline-first attendance tracker.

## How I work

- **A brief before the agents.** I write down who the project is for, the principles it follows and the accessibility level it has to meet. Then I review what the agents produce, so the interface stays intuitive and accessible and the workflows stay short.
- **Not done until verified.** Each project ships unit, integration and end-to-end suites with their own documentation, and agents get evals.
- **AI that takes actions, with a person in the loop.** I build agents, MCP servers and approval gates, and I run local models on my own hardware.

## Tools

**Frontend:** Angular (signals, SSR, zoneless), Ionic and Capacitor, React, Astro, Tailwind CSS
<br>**Backend:** NestJS, Node and Express, Postgres on Neon (Auth, Data API, row-level security), Drizzle
<br>**AI:** MCP, agents and evals, Ollama and MLX models on Apple Silicon
<br>**Testing:** Playwright, Vitest, Karma, axe
<br>**Shipping:** Netlify, Cloudflare Pages, Vercel, Docker, GitHub Actions, and a self-hosted Forgejo with Tailscale at home
