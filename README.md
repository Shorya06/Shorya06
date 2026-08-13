<!--
  Shorya06 — GitHub profile README
  Concept: "SRE Console" — a monitoring surface for one engineer.
  THESIS: The profile reads like the systems it builds: dark console,
  amber instrumentation accents, projects as service cards, real data only.
  FIRST VIEWPORT: name + headline + one status line, the animated
  distributed-system diagram, then a contact strip. One accent (#E3B341).
  Palettes: bg #0d1117 · panel #161b22 · border #30363d · text #e6edf3
            muted #8b949e · accent #E3B341 · healthy #3fb950
-->

<div align="center" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif; padding: 28px 16px 24px; border: 1px solid #30363d; border-radius: 12px; background: #0d1117;">

<h1 style="font-size: 2.4em; font-weight: 700; margin: 0 0 8px; letter-spacing: -0.02em;">Shorya Tripathi</h1>

<p style="font-size: 1.15em; color: #e6edf3; margin: 0;">Backend engineer building <b>distributed systems</b>, Kubernetes platforms, and AI-powered automation.</p>

<p style="margin: 18px 0 0; font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 13px; color: #8b949e;">
<span style="color: #3fb950;">●</span>&nbsp; final-year B.Tech CSE &nbsp;·&nbsp; open to backend engineering internships
</p>

<br>

<img src="hero.gif" alt="Animated network diagram: traffic flows from CLIENT through an NGINX load balancer into three gateway replicas, whose shared Redis state enforces rate limits with atomic Lua scripts." width="880" style="max-width: 100%; border: 1px solid #30363d; border-radius: 12px;">

<br>

<p style="margin: 22px 0 0; font-size: 14px;">
<a href="https://github.com/Shorya06">github.com/Shorya06</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/shoryatri06">linkedin.com/in/shoryatri06</a> &nbsp;·&nbsp;
<a href="mailto:shoryatripathi0606@gmail.com">shoryatripathi0606@gmail.com</a> &nbsp;·&nbsp;
<a href="https://leetcode.com/u/shoryatripathi/">leetcode.com/u/shoryatripathi</a>
</p>

</div>

<br>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> about</h2>

<p style="margin: 4px 0; color: #e6edf3;">I build backend systems that stay up under load — and teach them to fix themselves when they don't.</p>
<p style="margin: 6px 0; color: #8b949e;">Currently focused on distributed systems, Kubernetes platform engineering, and LLM-driven operations.</p>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> featured projects</h2>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 6px; font-size: 17px; font-weight: 600;"><a href="https://github.com/Shorya06/Distributed-Rate-Limiter">Distributed Rate Limiter &amp; API Gateway</a></h3>

<p style="margin: 0 0 10px; color: #8b949e;">Horizontally scalable API gateway with atomic, cross-instance rate limiting backed by shared Redis.</p>

<ul style="margin: 0 0 10px; padding-left: 20px; color: #e6edf3;">
<li style="margin: 4px 0;">Token-bucket and sliding-window strategies as pluggable Spring Cloud Gateway filters — each check is a single atomic Redis Lua script, so concurrent gateways can never over-admit.</li>
<li style="margin: 4px 0;">3 replicas behind an Nginx load balancer sharing one Redis state; an instance killed mid-load-test failed over with zero downtime.</li>
<li style="margin: 4px 0;">k6 load test: <b>850 req/s at 45ms p95</b>, sustained over 5 minutes.</li>
</ul>

<p style="margin: 0;">
<span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Java</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Spring Cloud Gateway</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Redis · Lua</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Nginx</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Prometheus + Grafana</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">k6</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px;">Docker</span>
</p>

</div>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 6px; font-size: 17px; font-weight: 600;"><a href="https://github.com/Shorya06/Project-AIOPS">Project-AIOPS — Self-Healing Kubernetes Platform</a></h3>

<p style="margin: 0 0 10px; color: #8b949e;">A closed-loop AIOps platform: 5 microservices that watch Kubernetes, diagnose failures with an LLM, and patch them.</p>

<ul style="margin: 0 0 10px; padding-left: 20px; color: #e6edf3;">
<li style="margin: 4px 0;">Alertmanager alerts and pod crash logs are analyzed by Gemini; structured diagnoses drive whitelisted mutations — confidence-gated replica caps and cooldowns keep the loop safe.</li>
<li style="margin: 4px 0;">Mutates live clusters through the Kubernetes Java client (Strategic Merge Patch, scale subresource) with RBAC-scoped service accounts.</li>
<li style="margin: 4px 0;">React 19 + TypeScript SRE console: live CPU/memory timelines, healing audit drawers, distributed <code>correlationId</code> tracing.</li>
</ul>

<p style="margin: 0;">
<span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Java 17</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Spring Boot</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Kubernetes</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Gemini LLM</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">PostgreSQL</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Prometheus</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px;">React 19</span>
</p>

</div>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 6px; font-size: 17px; font-weight: 600;"><a href="https://github.com/Shorya06/UniConnect-Student-Forum">UniConnect — Student Forum &amp; Resource Platform</a></h3>

<p style="margin: 0 0 10px; color: #8b949e;">Full-stack discussion and resource-sharing platform for students and faculty, with role-based access.</p>

<ul style="margin: 0 0 10px; padding-left: 20px; color: #e6edf3;">
<li style="margin: 4px 0;">JWT authentication and RBAC with distinct student / faculty / admin views and capabilities.</li>
<li style="margin: 4px 0;">Posts, comments, likes, and validated resource uploads — built with production habits: loading skeletons, empty states, toasts.</li>
</ul>

<p style="margin: 0;">
<span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">React 19</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Node.js</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Express</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">MySQL</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">JWT</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px;">Tailwind</span>
</p>

</div>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 6px; font-size: 17px; font-weight: 600;"><a href="https://github.com/Shorya06/Ast-Code-Optimizer">Ast-Code-Optimizer</a></h3>

<p style="margin: 0 0 10px; color: #8b949e;">A compiler front-end for a C-like language that parses source into an AST and rewrites it through multi-pass optimizations.</p>

<ul style="margin: 0 0 10px; padding-left: 20px; color: #e6edf3;">
<li style="margin: 4px 0;">Flex + Bison lexer/parser, AST builder with Graphviz DOT output, and real optimization passes — constant folding, constant propagation, strength reduction, dead-code elimination — followed by C code generation.</li>
</ul>

<p style="margin: 0;">
<span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">C</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Flex</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; margin-right: 4px;">Bison</span><span style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #8b949e; background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px;">Make</span>
</p>

</div>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> experience</h2>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 4px; font-size: 17px; font-weight: 600;">Backend Engineering Intern — <a href="https://flyrank.ai/">FlyRank AI</a> <span style="font-size: 13px; color: #8b949e; font-weight: 500;">· 2026</span></h3>

<p style="margin: 0 0 10px; color: #8b949e;">Worked through weekly backend stages: REST APIs with OpenAPI/Swagger docs, SQLite → PostgreSQL persistence, Docker Compose orchestration with volumes and connection retries, and Supabase auth integration. <a href="https://github.com/Shorya06/Flyrank-Internship">Internship workspace</a></p>

<p style="margin: 0; font-size: 14px; color: #e6edf3;"><b>Education</b> — B.Tech Computer Science &amp; Engineering, <a href="https://www.geu.ac.in/">Graphic Era University</a>, Dehradun · 2023–2027</p>

</div>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> open source &amp; systems</h2>

<div style="border: 1px solid #30363d; border-radius: 10px; padding: 18px 22px; margin: 12px 0; background: #161b22;">

<h3 style="margin: 0 0 4px; font-size: 17px; font-weight: 600;">Home Assistant — <a href="https://github.com/home-assistant/core">home-assistant/core</a> <span style="font-size: 13px; color: #8b949e; font-weight: 500;">· contributing</span></h3>

<p style="margin: 0 0 10px; color: #8b949e;">Two CLA-signed PRs in review, aligned with the project's config-flow guidelines: <a href="https://github.com/home-assistant/core/pull/172690">SolarEdge config</a> · <a href="https://github.com/home-assistant/core/pull/172818">Xiaomi Aqara config flow</a>.</p>

<h3 style="margin: 16px 0 4px; font-size: 17px; font-weight: 600;"><a href="https://github.com/Shorya06/xv6-Mini-Kernal-OS">xv6 kernel — MLFQ framework &amp; diagnostics</a> <span style="font-size: 13px; color: #8b949e; font-weight: 500;">· team lead, 4-member team</span></h3>

<p style="margin: 0; color: #8b949e;">Extended the xv6 kernel with a multi-level feedback-queue scheduling framework, live queue-state diagnostics (<code>mlfqstatus</code>), a <code>getsysinfo</code> syscall, and deadlock-detection infrastructure. C · x86 assembly · QEMU.</p>

</div>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> achievements &amp; certifications</h2>

<ul style="margin: 0; padding-left: 20px; color: #e6edf3;">
<li style="margin: 6px 0;"><b>300+ DSA problems solved</b> — LeetCode · GeeksforGeeks · CodeStudio</li>
<li style="margin: 6px 0;"><b>AWS Cloud Practitioner Essentials</b> — certified</li>
<li style="margin: 6px 0;"><b>JPMorgan Chase SWE Simulation</b> (Forage) — Kafka messaging on Spring Boot, persisted via Spring Data JPA, verified with acceptance tests</li>
<li style="margin: 6px 0;"><b>Skyscanner Front-End Simulation</b> (Forage) — React date picker with Backpack</li>
<li style="margin: 6px 0;"><b>AWS Skill Builder labs</b> — EC2 · S3 · IAM · VPC</li>
</ul>

<h2 style="font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 14px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #8b949e; margin: 40px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #21262d;"><span style="color: #e3b341;">▸</span> stats</h2>

<!-- STATS:BEGIN -->
<div style="border: 1px solid #30363d; border-radius: 10px; padding: 16px 8px; margin: 12px 0; background: #161b22; display: flex; flex-wrap: wrap; justify-content: space-around;">

<div style="flex: 1 1 120px; text-align: center; padding: 8px 4px;">
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 24px; font-weight: 700; color: #e3b341;">18</div>
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; letter-spacing: 0.04em; text-transform: uppercase; color: #8b949e;">repositories</div>
</div>

<div style="flex: 1 1 120px; text-align: center; padding: 8px 4px;">
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 24px; font-weight: 700; color: #e3b341;">122+</div>
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; letter-spacing: 0.04em; text-transform: uppercase; color: #8b949e;">commits</div>
</div>

<div style="flex: 1 1 120px; text-align: center; padding: 8px 4px;">
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 24px; font-weight: 700; color: #e3b341;">5</div>
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; letter-spacing: 0.04em; text-transform: uppercase; color: #8b949e;">languages</div>
</div>

<div style="flex: 1 1 120px; text-align: center; padding: 8px 4px;">
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 24px; font-weight: 700; color: #e3b341;">2</div>
<div style="font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; letter-spacing: 0.04em; text-transform: uppercase; color: #8b949e;">OSS PRs in review</div>
</div>

</div>

<p align="center" style="margin: 10px 0 0; font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 12px; color: #484f58;">auto-refreshed weekly via GitHub Actions &middot; commits &amp; repositories counted across non-fork repos</p>
<!-- STATS:END -->

<details>
<summary style="cursor: pointer; font-family: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, monospace; font-size: 13px; color: #8b949e; margin-top: 36px;">earlier work &amp; experiments</summary>

<ul style="padding-left: 20px; color: #8b949e;">
<li style="margin: 6px 0;">AlgoScope — algorithm benchmarking &amp; visualizer tooling (<b>Python</b>)</li>
<li style="margin: 6px 0;">Smart-Hospital-Management — hospital management system (<b>Python</b>)</li>
<li style="margin: 6px 0;">personality-predictor — ML experiment (<b>Python</b>)</li>
</ul>

</details>
