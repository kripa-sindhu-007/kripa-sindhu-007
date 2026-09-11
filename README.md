<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" alt="Kripa Sindhu — Software Engineer at BeatRoute. Work, open source, side projects, family and fun." width="100%">
</picture>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kripasindhu007-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kripasindhu007/)
[![Email](https://img.shields.io/badge/Email-mail%40kripasindhu.dev-EA4335?style=for-the-badge)](mailto:mail@kripasindhu.dev)
[![Blog](https://img.shields.io/badge/Blog-kripasindhu.dev-4F46E5?style=for-the-badge)](https://kripasindhu.dev/blog)

</div>

<img src="assets/divider.svg" width="100%" alt="">

## Flagship work

<table>
<tr>
<td width="33%" valign="top" align="center">

<a href="https://github.com/kripa-sindhu-007/feature-flag-system"><img src="assets/flagplane-overview.png" width="100%" alt="FlagPlane dashboard — a flag flip propagating through Postgres, Redis and 3 backend nodes, converged in 59 ms"></a>

<a href="https://github.com/kripa-sindhu-007/feature-flag-system"><b>feature-flag-system</b></a>

<sub>Self-hosted flags with percentage rollouts and real-time SSE propagation, running as a <b>3-node cluster</b>. Versioned config, durable event log, gap-detect clients.</sub>

<sub><b>p99 192 ms · ~74M evals/s · 6/6 chaos scenarios</b></sub>

<sub><code>Go</code> <code>PostgreSQL</code> <code>Redis</code> <code>Next.js</code> <code>nginx</code> <code>Prometheus</code></sub>

<sub><a href="https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/BENCHMARKS.md">Benchmarks</a> · <a href="https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/CHAOS.md">Chaos</a> · <a href="https://github.com/kripa-sindhu-007/feature-flag-system/blob/main/docs/LIMITATIONS.md">Limitations</a></sub>

</td>
<td width="33%" valign="top" align="center">

<a href="https://github.com/kripa-sindhu-007/task-queue-educational-dashboard"><img src="https://raw.githubusercontent.com/kripa-sindhu-007/task-queue-educational-dashboard/main/docs/images/landing.png" width="100%" alt="Task Queue — animated visualization of work flowing from producer through Redis queue to workers"></a>

<a href="https://github.com/kripa-sindhu-007/task-queue-educational-dashboard"><b>task-queue-educational-dashboard</b></a>

<sub>A live dashboard of every stage of a distributed queue — enqueue, lease, process, retry, dead-letter. Kill a worker or the leader and watch it recover.</sub>

<sub><b>Zero task loss under chaos · at-least-once · leader election</b></sub>

<sub><code>Go</code> <code>Redis</code> <code>Next.js</code> <code>Docker</code> <code>GitHub Actions</code></sub>

</td>
<td width="33%" valign="top" align="center">

<a href="https://github.com/kripa-sindhu-007/prahari"><img src="https://raw.githubusercontent.com/kripa-sindhu-007/prahari/main/assets/demo.svg" width="100%" alt="prahari doctor reporting three invalid environment variables with the secret redacted, then prahari sync catching .env.example drift and exiting 1"></a>

<a href="https://github.com/kripa-sindhu-007/prahari"><b>prahari</b></a>

<sub>Validates the whole environment <b>once at boot</b> and fails with one readable table, secrets redacted. <code>prahari sync</code> exits 1 in CI so <code>.env.example</code> cannot drift.</sub>

<sub><b>0 runtime deps · &gt;97% coverage · API frozen by contract tests</b></sub>

<sub><code>TypeScript</code> <code>Node.js</code> <code>Standard Schema</code> <code>Vitest</code> <code>npm</code></sub>

<sub><a href="https://www.npmjs.com/package/prahari">npm</a> · <a href="https://prahari.kripasindhu.dev">Docs</a> · <a href="https://github.com/kripa-sindhu-007/prahari/blob/main/docs/api.md">API</a></sub>

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## At work — BeatRoute · Software Engineer · May 2025 – present

- Architected the **Report Builder** end to end — the Angular configuration/visualization UI *and* the Cube.js query layer over a multi-tenant PostgreSQL warehouse — driving a **30 % increase** in self-serve report creation
- Modeled and extended the **Cube.js semantic layer** (cubes, measures, dimensions, joins) and designed pre-aggregations that cut average query latency **40 %** on high-volume analytics
- Closed 20+ data-layer edge cases including **row-level-security gaps**, hardening multi-tenant isolation and cutting query-related support tickets **30 %**
- Built a real-time chatbot over **WebSockets** — sub-200 ms bi-directional delivery for customers across **15+ countries**
- Led the **Angular 14 → 19 migration** of two production apps with zero downtime, and co-built a **40+ component** internal library used by 5+ teams (**~30 % less** feature effort, WCAG 2.1)

<img src="assets/divider.svg" width="100%" alt="">

## Open source

Upstream work on [**OpenFeature**](https://openfeature.dev) — the CNCF feature-flagging standard — and on [**go-git**](https://github.com/go-git/go-git), the pure-Go implementation of Git.

| Project | What I work on | Contributions |
|---|---|---|
| [**open-feature/go-sdk**](https://github.com/open-feature/go-sdk) | Spec conformance in flag evaluation, hooks and error handling | [PRs &rarr;](https://github.com/open-feature/go-sdk/pulls?q=is%3Apr+author%3Akripa-sindhu-007) |
| [**open-feature/spec**](https://github.com/open-feature/spec) | Pinning down behaviour the SDKs currently read two ways | [PRs &rarr;](https://github.com/open-feature/spec/pulls?q=is%3Apr+author%3Akripa-sindhu-007) |
| [**go-git/go-git**](https://github.com/go-git/go-git) | Remote and shallow-clone correctness, proven against upstream Git | [PRs &rarr;](https://github.com/go-git/go-git/pulls?q=is%3Apr+author%3Akripa-sindhu-007) |

Every fix starts as a reproduction against the public API at a known commit, with the test proven to fail without it — for example [`go-sdk#566`](https://github.com/open-feature/go-sdk/pull/566), where `ObjectValueDetails` returned Go's zero value on an abnormal evaluation instead of the default the caller passed in.

<img src="assets/divider.svg" width="100%" alt="">

## Beyond code

- 📄 **Published researcher** — co-author of *EV-GREEN*, [**Computing** (Springer Nature), Vol. 108, Feb 2026](https://github.com/kripa-sindhu-007/ev-routing-green-v2g) — EV eco-routing via hybrid MILP + graph heuristics
- 🏅 **GATE CSE — top 5 % nationwide**, twice (2024 & 2025)
- ⚔️ **LeetCode Knight** — peak rating 1914, 1000+ problems solved
- 🎓 B.Tech CSE, **IIIT Guwahati** (2021 – 2025)

<img src="assets/divider.svg" width="100%" alt="">

<div align="center">

## Stack

<img src="https://skillicons.dev/icons?i=go,ts,js,python,postgres,redis,mongodb,nodejs,express,nextjs,react,angular,docker,aws,githubactions&perline=8" alt="Go, TypeScript, JavaScript, Python, PostgreSQL, Redis, MongoDB, Node.js, Express, Next.js, React, Angular, Docker, AWS, GitHub Actions" height="88">

<sub><b>Cube.js</b> · WebSockets · Prometheus · Grafana · Linux</sub>

<br><br>

**Building systems that scale — and proving it.**
Reach me at [mail@kripasindhu.dev](mailto:mail@kripasindhu.dev)

</div>
