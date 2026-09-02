<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" alt="Kripa Sindhu — Software Engineer @ BeatRoute. Production frontends by day, distributed systems you can watch work: real benchmarks, chaos tests, honest docs." width="100%">
</picture>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kripasindhu007-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kripasindhu007/)
[![Email](https://img.shields.io/badge/Email-contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sindhukripa007@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Knight_·_1914-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/kripa-sindhu-007/)

</div>

<img src="assets/divider.svg" width="100%" alt="">

## Flagship work

### [feature-flag-system](https://github.com/kripa-sindhu-007/feature-flag-system) — a feature-flag platform proven under failure

[<img src="assets/flagplane-overview.png" alt="FlagPlane dashboard — a flag flip propagating through Postgres, Redis, and 3 backend nodes, converged in 59 ms" width="100%">](https://github.com/kripa-sindhu-007/feature-flag-system)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/metrics-ff-dark.svg">
  <img src="assets/metrics-ff-light.svg" alt="p99 192 ms propagation with 5,000 SSE clients · ~74M local evals/sec · 6/6 chaos scenarios pass · 22-min soak with 0 violations" width="100%">
</picture>

Self-hosted flags with percentage rollouts, real-time SSE propagation, and local-eval SDKs (TypeScript + Go) — running as a **3-node cluster behind nginx** with Prometheus, Grafana, and OpenTelemetry. Versioned config with optimistic concurrency, a durable event log, and gap-detect + reconcile clients. The dashboard above shows a real flip reaching every server and the browser, live. Every number is measured, every guarantee is chaos-tested, every limitation is documented → [BENCHMARKS](https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/BENCHMARKS.md) · [CHAOS](https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/CHAOS.md) · [LIMITATIONS](https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/LIMITATIONS.md)

`Go` `PostgreSQL` `Redis` `Next.js` `nginx` `Prometheus` `Grafana` `OpenTelemetry`

<br>

### [task-queue-educational-dashboard](https://github.com/kripa-sindhu-007/task-queue-educational-dashboard) — a distributed task queue you can *see*

[<img src="https://raw.githubusercontent.com/kripa-sindhu-007/task-queue-educational-dashboard/main/docs/images/landing.png" alt="Task Queue — animated visualization of work flowing from producer through Redis queue to workers" width="100%">](https://github.com/kripa-sindhu-007/task-queue-educational-dashboard)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/metrics-tq-dark.svg">
  <img src="assets/metrics-tq-light.svg" alt="At-least-once delivery · leader election · backpressure · zero task loss under chaos" width="100%">
</picture>

A live dashboard that visualizes every stage of a distributed queue — enqueue, lease, process, retry, dead-letter. Kill a worker (or the leader) and watch the system recover with **zero task loss**, in real time, on full Prometheus/Grafana observability.

`Go` `Redis` `Next.js` `Docker` `GitHub Actions`

<br>

### [prahari](https://github.com/kripa-sindhu-007/prahari) — type-safe env config that *can't* quietly drift

[<img src="https://raw.githubusercontent.com/kripa-sindhu-007/prahari/main/assets/demo.svg" alt="prahari doctor reporting three invalid environment variables with the secret redacted, then prahari sync catching .env.example drift and exiting 1" width="100%">](https://github.com/kripa-sindhu-007/prahari)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/metrics-prahari-dark.svg">
  <img src="assets/metrics-prahari-light.svg" alt="0 runtime dependencies · Standard Schema compatible — bring your own Zod/Valibot/ArkType · >97% coverage with the public API frozen by contract tests · prahari sync exits 1 so .env.example cannot drift" width="100%">
</picture>

`process.env.*` is a bag of untyped strings your app trusts blindly, so a misconfigured deploy doesn't fail when you ship it — it fails **later, in production, far from the cause**. prahari validates the whole environment **once at boot** and crashes with a single readable table of everything that's wrong, secrets redacted. The part no other env library has is the CLI: `prahari sync` diffs your schema against `.env.example` and **exits 1 in CI** when they disagree, so the file can't silently stop describing reality. Published to npm with signed provenance, zero runtime dependencies, and a public API frozen by contract tests → [**npm**](https://www.npmjs.com/package/prahari) · [**docs**](https://prahari-azure.vercel.app) · [**API reference**](https://github.com/kripa-sindhu-007/prahari/blob/main/docs/api.md)

`TypeScript` `Node.js` `Standard Schema` `Vitest` `tsup` `npm`

<img src="assets/divider.svg" width="100%" alt="">

## At work — BeatRoute · Software Engineer · May 2025 – present

- Ship production SaaS frontends used by field teams across **15+ countries** (Angular, TypeScript)
- Led the **Angular 14 → 19 migration** of two production apps — zero downtime, full backward compatibility
- Co-built the internal **UI component library** adopted across teams (**~30 % less** feature dev effort)
- Architected the **Report Builder** frontend (flagship feature) and a Jasmine/Karma test framework with **90 %+ coverage**

<img src="assets/divider.svg" width="100%" alt="">

## Beyond code

- 📄 **Published researcher** — co-author of *EV-GREEN*, [**Computing** (Springer Nature), Vol. 108, Feb 2026](https://github.com/kripa-sindhu-007/ev-routing-green-v2g) — EV eco-routing via hybrid MILP + graph heuristics
- 🏅 **GATE CSE — top 5 % nationwide**, twice (2024 & 2025)
- ⚔️ **LeetCode Knight** — peak rating 1914, 1000+ problems solved
- 🎓 B.Tech CSE, **IIIT Guwahati** (2021 – 2025)

<img src="assets/divider.svg" width="100%" alt="">

<div align="center">

## Stack

<img src="https://skillicons.dev/icons?i=go,ts,js,python,angular,react,nextjs,nodejs,postgres,redis,mongodb,docker,aws,githubactions&perline=7" alt="Go, TypeScript, JavaScript, Python, Angular, React, Next.js, Node.js, PostgreSQL, Redis, MongoDB, Docker, AWS, GitHub Actions" height="88">

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=kripa-sindhu-007&show_icons=true&hide_border=true&bg_color=00000000&title_color=818cf8&icon_color=818cf8&text_color=c9d1d9">
  <img src="https://github-readme-stats.vercel.app/api?username=kripa-sindhu-007&show_icons=true&hide_border=true&bg_color=00000000&title_color=4f46e5&icon_color=4f46e5&text_color=24292f" alt="GitHub stats" height="165">
</picture>

**Building systems that scale — and proving it.**
Reach me at [sindhukripa007@gmail.com](mailto:sindhukripa007@gmail.com)

</div>
