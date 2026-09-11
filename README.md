<!-- L4XB / lab notes. Keep the assets/lab-notes directory next to this file. -->

<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="assets/lab-notes/header-mobile-dark.svg" />
  <source media="(max-width: 640px) and (prefers-color-scheme: light)" srcset="assets/lab-notes/header-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/lab-notes/header-dark.svg" />
  <img src="assets/lab-notes/header-light.svg" width="100%" alt="Lukas Buck · L4XB. LLMs, agents and security. An agent sketch with tools, memory and an untrusted input." />
</picture>

<p>
  <a href="https://www.linkedin.com/in/lukas-buck-664384237/"><img src="assets/lab-notes/contact-linkedin.svg" height="31" alt="LinkedIn" /></a>
  <a href="https://www.researchgate.net/profile/Lukas-Buck"><img src="assets/lab-notes/contact-researchgate.svg" height="31" alt="ResearchGate" /></a>
  <a href="mailto:Lukas.Buck@Student.Reutlingen-University.de"><img src="assets/lab-notes/contact-email.svg" height="31" alt="Email" /></a>
</p>

I'm a master's student and academic assistant at Reutlingen University, focused on applied AI. My bachelor's thesis was on prompt injection. I haven't quite left that rabbit hole.

<br/>

<img src="assets/lab-notes/branch.svg" width="24" height="24" alt="" /> 01 / on my desk

I'm building SixSentences ↗ solo. It covers paper screening, AI-led voice interviews and surveys, analysis, and LaTeX writing. I also fine-tune the transformer encoders used for screening.

At university, I teach programming and practical sessions on AI-assisted development with coding agents.

<br/>

<img src="assets/lab-notes/research.svg" width="24" height="24" alt="" /> 02 / research notes

Can LLMs Chain Bugs into Breaches?
Attack Path Discovery in Terraform.
<sub>IEEE ICSME 2026 · Visions and Emerging Results · Accepted, to appear.</sub>

I'm also investigating hallucinated Terraform resources, brittle evaluation oracles, and the security of LLM-generated infrastructure.

<details>
<summary>Open the research notebook</summary>

<br/>

Manuscript in preparation
Hallucinated Resources, Brittle Oracles, Decoupled Security: An Empirical Study of LLM-Generated Terraform.

Ongoing collaboration
Security evaluation of LLM-generated Terraform with J. Höll and W. Blochinger at Reutlingen University.

B.Sc. thesis
Prompt Injection Attacks on Transformer-Based Language Models.

</details>

<br/>

<img src="assets/lab-notes/merge.svg" width="24" height="24" alt="" /> 03 / patch log

A few merged fixes to AI tooling, shown as before/after notes:

claude-mem · #3949 ↗

- Failed memory writes could get skipped forever.
+ Keep failed observations pending.

omlx · #3545 ↗

- Embedding responses could contain NaN / Inf.
+ Reject non-finite embeddings.

Logfire · #2404 ↗

- Exporter failures could deadlock logging.
+ Use a re-entrant lock.

<details>
<summary>More merged fixes</summary>

<br/>

Project

Patch

Graphify

Make SQL indexes visible in the knowledge graph. ↗

OpenSandbox

Recognise Podman when resolving a container's host IP. ↗

fastmcp · TypeScript

Keep the tools capability when access rules hide every tool. ↗

PI-Desktop

Deliver delegate-agent reports that arrive before the parent goes idle. ↗

MemPalace

Keep a busy daemon registered instead of starting a duplicate. ↗

AstrBot

Space out queued requests instead of releasing them all at once. ↗

</details>

<br/>

All merged pull requests ↗

<p align="center">
  <sub>This is a README, not a system prompt.</sub>
</p>
