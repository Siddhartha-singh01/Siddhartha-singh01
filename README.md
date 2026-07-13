# Siddhartha Singh

**Co founder & CTO, [EliteFolks](https://elitefolks.in)** · Bangalore  
Full stack and AI engineer · IIT Madras (BS, class of 2028)

I design and ship products end to end · product architecture, UI systems, backend services, and the operational path to production. Most of my time goes into [EliteFolks](https://elitefolks.in), an AI powered learning platform for developers. Outside the company I publish packages, contribute upstream, and write software people can actually run.

**Elsewhere**

| | |
| :--- | :--- |
| Portfolio | [siddhartha.pro](https://www.siddhartha.pro/) |
| LinkedIn | [linkedin.com/in/siddhartha-singh-3ab11426b](https://www.linkedin.com/in/siddhartha-singh-3ab11426b) |
| npm | [npmjs.com/~siddharthasingh](https://www.npmjs.com/~siddharthasingh) |
| Email | [siddharthagithub0007@gmail.com](mailto:siddharthagithub0007@gmail.com) |
| Writing | [Medium](https://medium.com/@siddhartha_23998) |
| X | [x.com/siddhartha_664](https://x.com/siddhartha_664) |

---

## Now

| | |
| :--- | :--- |
| Building | EliteFolks · courses, compiler, Forge arena, EliteInterview, payments |
| Shipping | npm tooling for MCP and voice, product work on EliteFolks and Milestonenest |
| Contributing | Grafana, Score Spec, Prometheus ecosystem, and related open source |
| Learning | AWS architecture, Kubernetes, distributed systems |
| Open to | Collaboration on open source, product engineering, speaking, and serious technical discussion |
| Teaching | Open source education for students · ~1700 learners reached |

---

## Community & speaking

I speak at colleges and student programs about open source in practice: what it actually looks like, how to start, how contribution works, and how to move from first issue to sustained work. The goal is not slogans · it is a clear path students can follow.

| | |
| :--- | :--- |
| Reach | Taught open source fundamentals to roughly **1700 students** across sessions and programs |
| GSSoC | Maintainer, GirlScript Summer of Code |
| Summer of Bitcoin | Selected · completed the first **3 weeks** of the program |
| Topics | Starting open source · reading a codebase · first PR · maintainer expectations · GSoC style programs |

**Featured session**

Resource person for *Getting Started with Google Summer of Code (GSoC 2026): From Beginner to Contributor* · **24 January 2026** · St. Joseph’s Group of Institutions, OMR, Chennai. The webinar drew **1231 students** (I, II, and III year) and covered the open source ecosystem, GSoC, and practical first steps for beginners.

Event note (organizer post): [LinkedIn · Praba M](https://www.linkedin.com/posts/praba-m-134b97281_gsoc2026-opensource-webinar-share-7425503949719367680-AJQJ)

Open to campus talks and workshops on the same themes. Prefer a clear audience and a concrete outcome for attendees.

---

## Products

### [EliteFolks](https://elitefolks.in) · AI coding assistant and training arena

I built EliteFolks from the ground up: structured courses, a browser compiler (40+ languages via Judge0), AI tutoring, competitive 1v1 battles (The Forge), voice based mock interviews (EliteInterview), gamified dashboards, and geo priced subscriptions through Razorpay.

| | |
| :--- | :--- |
| Stack | Next.js, TypeScript, Appwrite, LLMs, Judge0, Razorpay |
| Surface | Courses · online compiler · DSA / logic arena · ELO battles · AI voice interviews |
| Traction | Featured on [Product Hunt](https://www.producthunt.com) · pitched to Y Combinator · ~120k footfall · 800+ active users |
| Role | Co founder & CTO · product, architecture, security, payments, CI, growth surface |

Case study: [siddhartha.pro/projects/elitefolks](https://www.siddhartha.pro/projects/elitefolks)

### [Milestonenest](https://milestonenest.in) · focus first project workspace

A deliberately small project tool: Kanban, milestones, team auth, real time collaboration, and Gemini powered task summaries. Built for teams that want clarity over feature bloat.

| | |
| :--- | :--- |
| Stack | Next.js, Appwrite, Gemini AI |
| Source | [github.com/Siddhartha-singh01/Milstonenenest](https://github.com/Siddhartha-singh01/Milstonenenest) |
| Case study | [siddhartha.pro/projects/milestonenest](https://www.siddhartha.pro/projects/milestonenest) |

### [Nextly](https://www.siddhartha.pro/projects/nextly) · AI curated news

Cross platform news app with swipe feed, topic onboarding, reactions, and personalization. React Native + Firebase; Google OAuth and phone auth.

Case study: [siddhartha.pro/projects/nextly](https://www.siddhartha.pro/projects/nextly)

---

## npm packages

Published under [@siddharthasingh](https://www.npmjs.com/~siddharthasingh). Prefer small, focused libraries with zero or few dependencies.

| Package | Purpose |
| :--- | :--- |
| [`@siddharthasingh/mcp-sync`](https://www.npmjs.com/package/@siddharthasingh/mcp-sync) | One CLI to manage MCP servers across AI clients |
| [`@siddharthasingh/mcp-healthcheck`](https://www.npmjs.com/package/@siddharthasingh/mcp-healthcheck) | Trust score scanner for MCP servers |
| [`@siddharthasingh/mcp-shield`](https://www.npmjs.com/package/@siddharthasingh/mcp-shield) | Security middleware for MCP servers |
| [`react-use-voice`](https://www.npmjs.com/package/react-use-voice) | React hook for the Web Speech API (SSR safe, TypeScript first) |
| [`chain-utils-siddharthasingh`](https://www.npmjs.com/package/chain-utils-siddharthasingh) | Low level Bitcoin primitives: varint, tx parsing, Merkle, hashes |

Sources: [mcp-sync](https://github.com/Siddhartha-singh01/mcp-sync) · [mcp-healthcheck](https://github.com/Siddhartha-singh01/mcp-healthcheck) · [mcp-shield](https://github.com/Siddhartha-singh01/mcp-shield) · [react-use-voice](https://github.com/Siddhartha-singh01/react-use-voice) · [chain-utils](https://github.com/Siddhartha-singh01/chain-utils-)

---

## Selected upstream work

Listed by project. Merged work first; open work noted where relevant.

**[grafana/grafana](https://github.com/grafana/grafana)**  
Text panel button elements · dashboard multi value type handling · tracing span duration  
Open: provisioning / Git Sync permissions, Tempo search docs

**[score-spec](https://github.com/score-spec)**  
`score-compose`: envprov as loadable provisioner, sandbox file paths, provisioner recursion fix  
Docs: local state, container image overrides · open work on `score-go`

**[grafana/grafana-prometheus-datasource](https://github.com/grafana/grafana-prometheus-datasource)**  
Metrics fetch on series limit blur (merged)

**[prometheus/prometheus](https://github.com/prometheus/prometheus)**  
tsdb mmap head chunk deadlock investigation (open)

Also touched: simstudioai/sim, NVIDIA/NemoClaw, jenkinsci/jenkins, nodejs/node, openml, community OSS during Hacktoberfest.

Rough volume: **59** merged PRs · **~690** contributions in the last twelve months · **37+** merged PRs on EliteFolks alone.

---

## How I work

Comfortable across design and implementation · Figma through production deploy. Day to day stack centers on TypeScript, Next.js, React Native, Appwrite, Python for ML experimentation, and Docker / cloud when the problem needs it.

* Prefer small, reviewable changes over large opaque dumps.
* Fix the root cause; leave the next person a clearer system.
* Document the non obvious. Empty PR descriptions are usually a smell.
* Treat security and correctness as product features, not afterthoughts.
* Ship tools (and packages) that solve a real friction, then maintain them.

More on tools and hardware: [siddhartha.pro/uses](https://www.siddhartha.pro/uses)

---

## Contact

Prefer the portfolio contact form or LinkedIn for introductions; email for anything direct.

**Open to:** campus talks and open source workshops · OSS collaboration · product and systems engineering conversations

[siddhartha.pro](https://www.siddhartha.pro/) · [LinkedIn](https://www.linkedin.com/in/siddhartha-singh-3ab11426b) · [npm](https://www.npmjs.com/~siddharthasingh) · [Email](mailto:siddharthagithub0007@gmail.com)

If you maintain a project I have opened a PR on, or you want to talk about EliteFolks, open source, or systems work · write. I read carefully and reply when I can add something useful.

---

*"It is easier to change the specification to fit the program than vice versa."*  
· Alan Perlis
