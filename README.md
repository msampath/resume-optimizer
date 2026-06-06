# resume-optimizer

Optimize your resume with an LLM. Works for any industry, any role, any seniority.

## Get started in 60 seconds

1. **Download** `resume-optimizer.skill` (zipped) or `resume-optimizer/SKILL.md` (raw)
2. **Load it into your LLM** (Claude, GPT, Gemini, etc.)
3. **Share your resume and target role.** Let the LLM ask questions before drafting.
   *Example: "I'm a senior mechanical engineer applying for Principal Engineer roles at aerospace primes."*

---

## What This Is

A structured `SKILL.md` document that an LLM uses to optimize resumes against observed patterns from real resumes that got callbacks and offers at competitive employers.

All examples in the skill are illustrative and created by LLM.

The skill body is **LLM-agnostic** — the YAML frontmatter is Claude-specific for auto-triggering, but the patterns work with any capable assistant. For non-Claude LLMs, paste `SKILL.md` as context.

## What's Inside

**6-step framework:** Strategic Positioning → Recruiter 10-Second Test → Achievement Rewrite → Summary → ATS Alignment → Final Polish

**34 patterns** across five confidence tiers (`[CONFIRMED]`, `[OBSERVED]`, `[CONTEXT-DEPENDENT]`, `[PEER-REVIEW-SOURCED]`, `[METHODOLOGY]`) covering headline formatting, bullet construction, quantification strategy, positioning tactics, domain vocabulary, and credibility markers.

**19 anti-patterns** — common mistakes that disqualify otherwise-strong candidates, each with detection criteria and a fix.

**Career Level Positioning Framework** — distinct signal requirements for Entry, Mid, Senior, Executive, and C-Suite.

**Function Pattern Library Scaffold** — structural scaffolds for 14 function families. Tech functions (SWE, TPM, PM) have validated patterns; non-tech families have scaffolds awaiting contributor fill-in.

**Appendix A: Named Entity Reference Lists** — 12 categorized lists (tier-1 employers, hyperscalers, analyst firms, analyst report names, consulting/SIs, devtools, SaaS, verifiability hosts, ATS, healthcare EHRs, regulators, tier descriptors) that patterns reference instead of hardcoding individual names.

## Domain Portability

The skill auto-adapts per candidate via three methodology patterns that run before any tactical pattern is applied:

- **Pattern 26** — researches current title conventions via web search before selecting a resume title
- **Pattern 27** — validates every domain-specific term (regulations, standards, frameworks, tools) via web search before placing it on the resume
- **Pattern 28** — infers the candidate's industry, role, and seniority from the uploaded resume, runs five explicit binary checks to confirm the inference, then produces an explicit apply/skip pattern list before proceeding

Known bias: source material skews senior-level tech. The methodology patterns mitigate this at runtime; the Function Pattern Library Scaffold identifies where non-tech tactical patterns are still missing.

## Limitations

- Source material skews senior-level tech recruiting cultures. Less validated for other industries and non-senior levels — Pattern 28 adapts at runtime, but pre-built tactical patterns for non-tech functions are sparse.
- Function Pattern Library Scaffold is partially empty — most non-tech families have structural scaffolds, not validated tactical patterns. Contributions welcomed.
- LLM assistants can still make mistakes. Patterns 27 and 28 exist specifically because LLM-assisted resume drafting produces domain errors and assumption failures. Use the methodology patterns as guardrails; review output before submitting.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT — see [LICENSE](LICENSE). Use, modify, fork, and adapt freely.

## Disclaimer

This skill provides observed patterns and methodology guidance. It is not a guarantee of interview callbacks or job offers. Use it as one tool among several.
