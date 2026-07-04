# Security & Compliance Hardening

**AppSec & staff engineers: harden every stage of the SDLC and pass your SOC 2 audit.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you own security for an engineering team and need to harden the whole software lifecycle, not just run a scanner. It walks you from design-time threat modeling and supply-chain/dependency risk, through secrets hygiene and security-focused code review, to triaging real exploitable findings out of scanner noise and assembling the evidence that gets you through a SOC 2 audit. Opinionated, senior-level defaults so you ship with confidence and survive the audit without the busywork.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/security-compliance-hardening](https://skillme.dev/pack/security-compliance-hardening) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/security-compliance-hardening`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Threat Model STRIDE](skills/threat-model-stride/SKILL.md)** — Applies STRIDE threat modeling to a feature or system design and produces a prioritized threat table with concrete mitigations ranked by exploitability and impact.
- **[Dependency Risk Audit](skills/dependency-risk-audit/SKILL.md)** — Audits third-party dependencies for exploitable CVEs, abandonment, license exposure, and supply-chain hygiene, and delivers a ranked findings report with a remediation order.
- **[Secrets Hygiene](skills/secrets-hygiene/SKILL.md)** — Guides detection, emergency rotation, and prevention of leaked secrets and credentials across source code, git history, CI pipelines, logs, and infrastructure config.
- **[SOC 2 Evidence Helper](skills/soc2-evidence-helper/SKILL.md)** — Maps engineering controls to SOC 2 Trust Service Criteria, builds a continuous evidence-collection plan with cadences per control family, and produces the control-to-evidence table auditors work from.
- **[Vulnerability Triage](skills/vulnerability-triage/SKILL.md)** — Prioritizes vulnerability findings from scanners, pentest reports, and bug bounty submissions by real-world exploitability rather than raw CVSS, assigning internal severity tiers with fix SLAs.
- **[Secure Code Review](skills/secure-code-review/SKILL.md)** — Reviews code for the security flaw classes that cause the most breaches — broken authorization and IDOR, injection, SSRF, mass assignment, and unsafe deserialization — and returns a short, focused findings list with concrete fixes.
- **[Security Audit](https://skillme.dev/skill/security-audit)** — Reviews code for OWASP Top 10 vulnerabilities with concrete fix recommendations. _(external — see source)_
- **[PII Scrubber](skills/pii-scrubber/SKILL.md)** — Detects and redacts personally identifiable information from text, logs, datasets, and LLM prompts using layered pattern, checksum, and NER detection, then picks the right redaction mode for each downstream use.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
