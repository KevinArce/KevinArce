<div align="center">

# Kevin Arce

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1200&color=CBA6F7&center=true&vCenter=true&width=680&lines=AI+Native+Engineer+%40+TELUS+Digital;TypeScript+by+trade%2C+Rust+when+I'm+annoyed;MSc+Quantum+Computing+in+progress+%E2%9A%9B;My+code+works+and+fails+simultaneously)](https://arcelabs.com)

[![Website](https://img.shields.io/badge/arcelabs.com-1E1E2E?style=for-the-badge&logo=hexo&logoColor=CBA6F7)](https://arcelabs.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1E1E2E?style=for-the-badge&logo=linkedin&logoColor=89B4FA)](https://linkedin.com/in/kevarce)
[![Kaggle](https://img.shields.io/badge/Kaggle-1E1E2E?style=for-the-badge&logo=kaggle&logoColor=94E2D5)](https://kaggle.com/kevarce)
[![Medium](https://img.shields.io/badge/Medium-1E1E2E?style=for-the-badge&logo=medium&logoColor=FAB387)](https://medium.com/@kevarce)

</div>

> **I build cloud backends that have to stay up, and small sharp tools for the things that annoy me on the way there.**
> Currently studying quantum computing, which means my code now works *and* fails simultaneously.

---

## `whoami`

|    |    |
| :--: | :-- |
| ☁️ | **AI Native Engineer** at **TELUS Digital** — backend, cloud and LLM work on **SmartHome+**, their flagship IoT platform |
| ⚛️ | **MSc in Quantum Computing**, Universidad de La Rioja · *in progress* |
| 🎓 | **Computer Science Engineer**, Universidad Francisco Gavidia — by way of Mathematics and Physics |
| 📦 | Things I've written live on **npm**, **crates.io**, and the **Reddit app directory** |
| 🇸🇻 | El Salvador · `UTC−6` |

---

## What I actually build

Not a skills dump — this is the map of where each thing gets used.

| Layer | What I do there | Working set |
| :-- | :-- | :-- |
| ☁️&nbsp;**Cloud&nbsp;backends** | Build *and operate* the services behind a production IoT platform. Infrastructure as code, test automation for regression and progression, and an on-call rotation that occasionally disagrees with my sleep schedule. | `TypeScript` `AWS CDK` `Lambda` `DynamoDB` `NestJS` |
| 🤖&nbsp;**LLM&nbsp;plumbing** | Wiring models into products real people actually use — moderation bots, assistants, typed workflow graphs. And working agent-first day to day: user stories and a technical spec exist *before* anything gets delegated. | `Gemini` `OpenAI` `Llama 2` `Workers AI` `Copilot` `Jules` |
| 🧰&nbsp;**Developer&nbsp;tooling** | Small, opinionated CLIs and bots that each delete exactly one recurring annoyance — then actually get published instead of rotting in a folder. | `TypeScript` `Rust` `ts-morph` `Probot` |
| 🐍&nbsp;**Python&nbsp;&&nbsp;ML** | scikit-learn, dataset building, and the occasional cryptography rabbit hole. Yes, I implemented Diffie–Hellman by hand. No, nobody asked me to. | `Python` `scikit-learn` `Jupyter` `FastAPI` |
| ⚛️&nbsp;**Quantum** | Where the Maths and Physics background stops being small talk and starts being homework. | `Linear algebra` `Qubits` `Coffee` |

<details>
<summary><b>🧳 The full toolbox</b> — for the curious and the keyword-searching</summary>

<br>

**Languages** — TypeScript · JavaScript · Python · Rust · Dart · Shell

**Runtimes & frameworks** — Node.js (Express, NestJS) · Bun (Elysia) · FastAPI · Flask · Flutter

**Cloud & infra** — AWS (CDK, Lambda, EC2, S3, SES, CloudWatch) · Cloudflare Workers · Docker · Kubernetes · GitHub Actions · Turborepo

**Data** — PostgreSQL · MySQL · MariaDB · MongoDB · Redis · DynamoDB · Firebase

**Observability & testing** — Sentry · Prometheus · PagerDuty · Jest · Vitest

**Ways of working** — Agile / Scrum / Kanban · trunk-adjacent PR flow · specs before agents

</details>

---

## Things I built because they annoyed me

| Project | What it is, and why it's worth a look | Built with |
| :-- | :-- | :-- |
| **[BreakPoint](https://github.com/KevinArce/BreakPoint)** | A GitHub App that fails your PR when you quietly break your own API. It generates OpenAPI schemas for the PR *and* the base branch, diffs them, and checks that your version bump matches the size of the damage. Split into two layers on purpose: Probot owns GitHub, Actions owns compute. | `TypeScript` `Probot` `OpenAPI` `Actions` |
| **[Botditor](https://developers.reddit.com/apps/botditor)** | A Reddit moderation bot that's actually live in Reddit's app directory. It ingests comments through the `CommentSubmit` trigger and runs them past an LLM — because, as its own tagline asks, was that comment written by a human or a slightly sentient toaster? | `TypeScript` `Devvit` `Gemini` `OpenAI` |
| **[Envinator](https://www.npmjs.com/package/envinator-cli)** | *"Come with me if you want to deploy."* `npx envinator-cli` walks your AST with ts-morph, finds every `process.env` you forgot to document, and interrogates you until your `.env` is complete. Real parsing, not regex — it won't be fooled by a comment. Masks secrets in its own logs. | `TypeScript` `Node.js` `ts-morph` |
| **[bun-cli](https://crates.io/crates/bun-cli)** | A Bun project scaffolder written in Rust — my most-starred repo, later torn down and rebuilt around a `Result<T, E>` core with a modular, cross-platform layout. Shipped to crates.io, where it's been pulled **5k+ times**. | `Rust` `Bun` |
| **[ghostforge](https://github.com/KevinArce/ghostforge)** | My entire macOS terminal, reduced to one `install.sh`. Ghostty + Starship + zoxide/fzf/eza/bat/yazi/lazygit, with Catppuccin that follows the system between light and true-black OLED dark. Backs up your `.zshrc` before it touches a thing. | `Shell` `Zsh` `Ghostty` |

### Also on the record

- 🤟 **[LESSA](https://www.kaggle.com/datasets/kevarce/lenguaje-de-seas-de-el-salvador-lessa)** — about five years ago I built El Salvador's first Salvadoran Sign Language image dataset, because one didn't exist. It's since become one of the most downloaded open datasets to come out of the country.
- 🎧 **[Merged into Linux-Arctis-Manager](https://github.com/elegos/Linux-Arctis-Manager/pull/7)** — chased a headset pairing bug down to the USB layer of an open-source SteelSeries driver and fixed it there: device reset on initialization, re-claiming interfaces after kernel detach.
- 📱 **[GermanFromZeroToHero](https://github.com/KevinArce/GermanFromZeroToHero)** — a Flutter German-learning app from the Firebase era, and one of the first things I ever sold. Still the reason I know exactly what a `StreamBuilder` does.

---

## Currently in superposition

- ⚛️ Working through David J. Griffiths' **Introduction to Quantum Mechanics**, one chapter at a time, for the MSc.
- 🧪 **[ArceLabs](https://arcelabs.com)** — my own platform sandbox: NestJS services folded into a Turborepo/Bun monorepo, Kubernetes underneath, Prometheus and PagerDuty on top. Essentially me handing myself the on-call problems I don't get to redesign at work.
- 🕸️ **Agent workflow graphs** — modelling LLM steps as typed nodes in a graph instead of one heroic mega-prompt.
- 🖥️ Ricing my terminal well past the point of reasonable return.

---

## Beyond the terminal

- 🎤 **TEDx speaker** at UTEC, El Salvador — on writing science fiction and fantasy. Not one slide about code.
- 🚀 **NASA Space Apps Challenge** participant, 2021.
- 🔬 Ad-honorem **researcher** at UFG's Centro de Modelaje Matemático.
- ♟️ Chess, mostly as a structured way to lose to strangers on the internet.

---

<div align="center">

<img src="https://streak-stats.demolab.com/?user=KevinArce&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KevinArce&theme=tokyonight" alt="Profile details" />

<br><br>

**If you read this far, you're the kind of person who reads READMEs.**
Something tells me we'd get along — [say hi](https://linkedin.com/in/kevarce).

[![ORCiD](https://img.shields.io/badge/ORCiD-0000--0003--3453--6551-1E1E2E?style=flat-square&logo=orcid&logoColor=A6E3A1)](https://orcid.org/0000-0003-3453-6551)

</div>
