---
name: resume-optimizer
description: Executive-level resume optimization using a proven 6-step framework with career-level positioning (Entry, Mid, Senior, Executive, C-Suite). Use this skill when the user wants to optimize their resume, prepare for job applications, rewrite experience sections for specific roles, get recruiter perspective, tailor their resume to job descriptions, improve resume clarity or positioning, create professional summaries, achieve ATS-friendly formatting, add keyword optimization, quantify achievements with metrics, highlight key wins, refine executive tone, determine appropriate career-level positioning, identify gaps via the worksheet method, or translate internal awards into externally legible names. Also trigger for resume reviews, career documents, job search preparation, LinkedIn profile optimization, leadership positioning requests, or questions about how to position for Director, VP, or C-Suite roles.
---

# Resume Optimizer

A comprehensive 6-step framework for transforming resumes into executive-level positioning documents that pass ATS systems, impress recruiters in 10 seconds, and highlight measurable impact.

## Using This with Different LLMs

This document is designed to be LLM-agnostic. The body content uses neutral language throughout and works equally well with Claude, Gemini, ChatGPT, or other large language models.

**For Claude users:** The YAML frontmatter at the top of this file lets Claude auto-trigger the skill when relevant. Upload the `.skill` file via the Claude Skills UI, and Claude will activate this framework on resume-related queries.

**For Gemini, ChatGPT, or other LLM users:** Paste the Markdown content of this document into your conversation as context (the YAML frontmatter at the top is optional — strip it or include it; either works). Then tell the assistant: *"Use this resume optimization framework to help me with my resume."* The framework's content is self-contained and works without Claude-specific features.

**For all users:** When sharing this with an assistant, share the full document. The patterns reference each other (e.g., Pattern 10 connects to Pattern 4 Variant B), so partial excerpts lose context.

## Core Optimization Elements

This skill delivers complete resume transformation across eight critical dimensions:

• **Career Level Positioning** – Calibrate to correct tier (Entry/Mid/Senior/Executive/C-Suite) with appropriate signals
• **ATS-Friendly Format** – Restructure with clean, modern templates that pass through applicant tracking systems
• **Executive Summary** – Craft powerful openings that showcase leadership value (including pipe-separated headline format)
• **Quantify Achievements** – Add metrics and results demonstrating real impact (revenue, team size, budgets, scale)
• **Highlight Key Wins** – Position strongest accomplishments front and center
• **Keyword Optimization** – Incorporate industry-specific terms to improve searchability
• **Executive Tone** – Refine language to reflect confident, results-driven leadership voice
• **Observed Patterns** – Apply techniques drawn from resumes that landed roles at competitive employers

## Overview

This skill implements proven methodology used by senior recruiters and executive resume writers to optimize resumes for leadership roles. Rather than treating resumes as job histories, it positions candidates strategically for target roles using impact metrics, ATS-optimized keywords, and executive-level clarity.

## Executive Recruiter Standards

Executive search firms consistently surface a small set of requirements that distinguish executive-shortlisted resumes from senior-IC resumes:
- **Career progression** and leadership trajectory
- **Leadership impact** and strategic influence
- **Platform ownership** and architecture authority
- **Enterprise-scale transformation** initiatives

**Key Requirements for Executive Shortlisting:**

**1. Chronological Executive Format (Non-Negotiable)**
- Clear career progression visible at a glance
- Leadership trajectory: IC → Senior IC → Manager → Senior Manager → Director
- Strictly reverse chronological (most recent first)
- No functional or hybrid formats (these obscure progression)
- Dates, titles, and companies immediately scannable
- Promotions within same company clearly shown

**2. Leadership Impact Emphasis**
- Team size quantified: "Led [N]-person [scope] team"
- Budget authority: "Managed $[X]M [type] budget"
- Organizational scope: "Across [N] [regions]", "Supporting [N]M [users/members]"
- Cross-functional influence: "[Verb] with [executive level]"
- Strategic initiatives: "[Tier-1 verb] [enterprise-scope initiative]"
- Business outcomes: Revenue, cost savings, efficiency gains

**3. Platform Ownership Signals**
- Architecture authority: "[Verb: Architected/Designed] [end-to-end scope]"
- Technology decisions: "[Verb: Selected/Evaluated/Implemented] [named technology]"
- Platform accountability: "[Verb: Owned] production [platform] serving [scale]"
- Strategic roadmap: "[Verb: Defined] [N]-year [scope] strategy"
- Vendor evaluation: "[Verb: Led] RFP process for $[X]M [investment type]"
- Technical leadership: "[Verb: Established/Built] [standards/frameworks]"

**4. Enterprise-Scale Transformation Indicators**
- Magnitude: [user/member count], [$ savings/revenue], [integration/project count]
- Complexity: Multi-system, multi-state, multi-regulation
- Duration: Multi-year programs, not just projects
- Organizational change: "[Verb] adoption across [N] [orgs/teams/regions]"
- Compliance: Federal mandates, regulatory deadlines
- Stakeholder management: Multiple C-level stakeholders

**5. Executive System Compatibility** *(ATS systems and recruiting platforms: see Appendix A.9)*
- **HireVue parsing**: Simple formatting, standard sections
- **Workday ATS**: Specific field mapping requirements (Workday Recruiting is the dominant enterprise ATS — see Appendix A.9 for the full list including Greenhouse, Lever, iCIMS, Taleo, etc.)
- **Executive review**: Board-level readability
- **Stakeholder circulation**: Clean format for email/print

**What Disqualifies Resumes at Executive Level:**

❌ **Career Progression Issues:**
- Unclear trajectory or unexplained lateral moves
- Promotions not highlighted
- Gaps in timeline not addressed
- Too many short tenures (<2 years)

❌ **Leadership Gaps:**
- No team size quantification
- Missing budget/scope indicators
- Individual contributor language at senior level
- No cross-functional leadership evidence

❌ **Technical Without Strategic:**
- Deep technical detail without business context
- Implementation focus without platform ownership
- Tactical execution without strategic framing
- Tools list without architecture decisions

❌ **Scale Indicators Missing:**
- No enterprise-level metrics
- Single-organization experience only
- Project-level vs. program-level scope
- No multi-year transformation evidence

❌ **Formatting Problems:**
- Complex layouts that break ATS parsing
- Functional format obscuring progression
- Inconsistent date formats
- Missing standard sections

❌ **Executive Presence Absent:**
- Junior language ("helped", "assisted")
- Passive voice throughout
- Responsibilities vs. achievements
- No evidence of strategic thinking

**This Skill Addresses All Requirements:**
- Step 1: Strategic positioning and career trajectory
- Step 2: Executive presence check
- Step 3: Leadership impact quantification
- Step 4: Executive summary for shortlisting
- Step 5: System compatibility (ATS/Workday/HireVue)
- Step 6: Final executive-level polish

## Patterns

*This section captures patterns observed in resumes that landed interview callbacks or offers at competitive employers. These are working tactics from senior professionals, not theoretical principles. Each pattern is marked with its confidence level: **[CONFIRMED]** = observed across multiple sources; **[OBSERVED]** = single-source pattern; **[CONTEXT-DEPENDENT]** = works in some scenarios, not others; **[METHODOLOGY]** = required upstream procedure (Patterns 26, 27, 28).*

**Sample sources analyzed:**
- Sanitized and deidentified data from many senior-level resumes across TPM, SWE, PM, Data Engineer, Customer Success, and Tech Lead job functions (8–15 years experience each)
- Candidates span multiple large technology employers and Series A–F startups
- Examples throughout are illustrative and created by LLM

**Sample composition note:** Source material reflects senior-level tech recruiting cultures with some cluster bias. The skill is most reliable for senior IC and program-management roles at large technology employers; less validated for non-tech industries and non-senior levels. Pattern 28 (Industry and Role Inference) mitigates this via runtime adaptation. For any target market, lean on the universal patterns and methodology patterns (26, 27, 28); de-emphasize patterns explicitly labeled as culture-specific.

**Critical meta-principle:** What carries one resume may not carry another. Strong content can overcome weak design, weak verbs, or buzzword summaries when business-impact metrics are heavy enough. The patterns below are individually valuable but should be applied selectively based on the candidate's strengths and target role.

### Pattern 1: The Pipe-Separated Profile Headline [OBSERVED]

An alternative to the traditional summary paragraph that wins the 10-second scan.

**Why this works:**
- Reads as 4 distinct billboards instead of a paragraph the recruiter has to parse
- Each pipe-segment contains a quantified achievement
- Numbers do the persuasion — no buzzwords like "results-driven" or "proven leader"
- Scannable in 3 seconds; the entire pitch lands before the recruiter starts reading bullets
- Identity and quantified wins fuse into the same headline

**Structural formula:**
`[Identity statement] | [Years] | [Signature win #1 with metric] | [Signature win #2 with metric] | [Signature win #3 with metric]`

**Adaptation by function:**
- **Program/TPM leaders:** program scale, operational efficiency, cost reduction through systems/models, cycle-time improvements via frameworks. Note: PMs/TPMs operate through influence, not direct authority — "led team of N" usually means coordinating an N-person delivery org, not N direct reports.
- **Software Engineer ICs:** revenue attribution, scale of systems, performance improvements, technical scope. Pipe format may feel less natural since IC wins are tied to specific code/systems; consider the 3-paragraph summary (Pattern 23) instead.
- **People-leader executives (Director/VP+):** explicit P&L and headcount signals required.
- **Solutions Architects:** architecture/scale wins.
- **Data Scientists:** model performance metrics.
- **Product Managers:** revenue/user metrics.

Adapt the format but keep the structure (quantified billboards separated by pipes).

**Use this format when:**
- The candidate has 3+ truly headline-worthy quantified achievements
- The candidate is at Senior, Executive, or C-Suite level
- The target role values pattern-recognition over narrative (most tech/program roles)

**Avoid this format when:**
- Quantified wins are weak (results in awkward filler)
- The candidate is at Entry or Mid level (over-positions)
- The target role is narrative-heavy (academia, certain consulting paths)

### Pattern 2: Numbers Do The Persuasion [CONFIRMED]

The strongest resumes don't *describe* the candidate — they *list quantified wins* and let the numbers position the person. Numbers density is the single most reliable signal of a strong resume.

**Number density targets:**

*Program-leader resumes:* aim for 40+ distinct numbers across two pages, drawn from these categories:
- Team scale (headcount, org size)
- Money (budgets, savings, revenue, cost reduction)
- Multipliers (Nx growth, Nx efficiency)
- Percentages (improvement, efficiency gain, reduction)
- Timeframes (delivery speed, time ahead of deadline)
- Scope (markets, sites, users, members, geographic footprint)

*Software Engineer IC resumes:* prioritize big-dollar business attribution:
- Revenue enabled or protected by code/system ownership
- Cost savings from infrastructure or process improvements
- Risk exposure reduced or eliminated
- Scale metrics (transaction volume, user base, data throughput)
- Operational efficiency (on-call reduction, incident reduction)

**Target density:** ~2 quantified data points per bullet. Bullets with no number are weak; bullets with 3+ numbers risk feeling like statistics dumps. The sweet spot is 1-2.

**Number types that work hardest (in observed effectiveness order):**
1. **Money** — strongest signal (revenue, savings, budgets, ARR)
2. **Multipliers** (Nx) — feel bigger than percentages
3. **Scale** (team size, user count, scope)
4. **Speed/efficiency percentages** — easy to grasp, easy to verify mentally

**Verb-to-number proximity rule:** Numbers land harder when adjacent to the action verb.
- ❌ Weak pattern: `"[Weak verb] various initiatives that resulted in a [N]% improvement in [area] over time"` — number buried past word 10
- ✅ Strong pattern: `"[Strong verb] [area] [N]%"` — number adjacent to verb, within first 5 words

**Front-load your biggest numbers:** A common failure mode is burying the strongest bullets at positions 4-5 in a role's section rather than leading with them. Lead each role with your strongest quantified win. Recruiters scanning fast may never reach bullet #5.

### Pattern 3: Signature Themes (Personal Brand Repetition) [CONTEXT-DEPENDENT]

Observed more often in program-leader resumes than in Software Engineer IC resumes. Works powerfully when applied but isn't universally adopted.

**Principle:** High-performing resumes repeat the same signature competency across multiple roles. This signals expertise — not coincidence.

**Detection pattern (strong):** The same role-relevant competency vocabulary appears in 2-3 different role sections, using slightly varied phrasing. A recruiter scanning the resume walks away with a clear sense of "this person does X" — not "this person did a lot of unrelated stuff."

**Detection pattern (weak):** The candidate has clear signature themes in the underlying work, but doesn't foreground them as repeating themes across roles. The expertise is there but the recruiter has to assemble the pattern themselves.

**Signature theme selection rule:** Pick competencies that are central to the *target* role, not just things you happened to do repeatedly. The theme is doing double work — showing repeated expertise AND demonstrating role-appropriate vocabulary.

**How to apply:**
1. Identify the 1-2 competencies most relevant to target roles
2. Find authentic examples of those competencies in multiple prior roles
3. Use **similar language** for them across roles (not identical — vary slightly)
4. Lead bullets in each role with the signature theme when possible

**Signature theme keywords by role type:**
- Program Manager: "capacity planning framework", "resource allocation model", "intake mechanism", "cross-functional sequencing"
- Engineering leader: "platform architecture", "scaling teams", "technical roadmap"
- Software Engineer IC: "system redesign", "data pipeline ownership", "performance at scale"
- CSM: "account growth", "retention", "executive stakeholder management"
- Solutions Architect: "reference architecture", "platform standards", "technology selection"
- Operations leader: "operational model", "efficiency improvement", "process standardization"
- Product Manager: "user research", "experimentation framework", "roadmap prioritization"

**Honesty check:** Don't manufacture signature themes from work you didn't do. The themes only work if they're authentic across the roles cited.

### Pattern 4: Bullet Construction Formula [CONFIRMED — with two valid variants]

Two valid bullet styles work for different company cultures. Both can succeed.

#### Variant A: Tight Impact Bullet (Universal Default)

**Formula:** `[Action verb] [what was done] to [why/strategic purpose], [quantified outcome] and [quantified outcome]`

**Target:** 20-30 words, single sentence, 1-2 quantified outcomes baked in.

**Best for:**
- Most large technology employers
- Recruiting cultures that prioritize scan-density over narrative depth
- Resumes optimized for 10-second recruiter scans

#### Variant B: Document-Heavy Narrative Bullet (Culture-Specific)

Some technology employers maintain a writing-heavy operational culture — they evaluate engineers and PMs on internal narrative documents (press-release-style product memos, incident retrospectives, promotion documents), and their recruiting culture extends that preference into resume review. For those employers, a longer multi-sentence narrative bullet outperforms a tight pipe-separated bullet.

**Formula:** `[Context/trigger event] → [problem identified with specifics] → [your action with named artifacts] → [outcome with specifics] → [scope/ongoing impact]`

**Target:** 80-150 words per bullet. Multi-sentence narrative.

**Best for:**
- Employers with documented narrative-writing cultures (look for "writing-first," "memo culture," or "narrative document" signals in their public engineering blogs or interview-prep materials)
- Hiring managers who came from those cultures, even at other companies
- Roles where context-rich storytelling outperforms scan-density

**Why this style works at those employers:**
- Mirrors how they evaluate performance internally
- Shows the candidate can write in the style their culture rewards
- Demonstrates depth on each project rather than breadth across many
- The "context → action → outcome → scope" structure is recognized as competent narrative

**How to identify whether your target falls into this category:**
- Web-search the target employer's engineering blog for writing-culture signals
- Look for public references to internal document conventions (post-mortems, design docs, press-release memos)
- Check Glassdoor and similar sites for interview-prep notes mentioning narrative writing
- If the target uses tight-bullet conventions instead, use Variant A

#### Common Principles (Apply to BOTH Variants)

**Number placement:** Put the quantified outcome in the **front half** when possible. Even narrative bullets benefit from leading with the headline number when one exists.

**Strong verbs:** Both variants reject weak verbs (see Pattern 5). Long-form narrative is not a license for weak verbs like "Collaborated to support testing efforts."

**Specificity over abstraction:** Both variants name specific projects, dates, regions, tools, and outcomes. Vague language ("led various initiatives") fails in either format.

**Front-load the strongest bullet:** In multi-bullet roles, lead with the highest-impact bullet regardless of variant.

#### Choosing Between Variants

**Use Variant A (Tight) when:**
- Targeting employers whose recruiting culture prioritizes scan-density
- The candidate has many achievements to surface
- The recruiter scan is the bottleneck
- The candidate's wins are easily quantified in single metrics

**Use Variant B (Narrative) when:**
- Targeting employers with documented narrative-writing cultures
- The candidate's wins require context to land
- The candidate's roles are deeper/longer (3+ years per role)
- The work involves multi-team initiatives that need scope context

**Mixing variants:** Acceptable. Use Variant B for the 2-3 most important bullets in your current role, Variant A for compression in older roles.

### Pattern 5: The Verb Banishment List [CONFIRMED]

**Lesson:** Strong metrics can rescue weak verbs, but strong verbs always outperform weak ones. If bullets have heavy quantified outcomes, weak verbs are survivable. If they don't, weak verbs are fatal.

**Default-avoid verbs (weak in most senior+ contexts):**

These verbs are weak by default at Senior+ level because they describe participation rather than ownership. Each has a note on when it may be appropriate.

| Verb | Why weak by default | When it may be appropriate |
|---|---|---|
| Helped | Positions the candidate as an auxiliary, not a contributor | Almost never appropriate — substitute with the specific contribution ("Designed the X component...") |
| Assisted | Same as "helped" | Almost never appropriate at Senior+ level |
| Supported | Frames the candidate as a support function | Acceptable as a noun in "Provided technical support to [team]" only when the work genuinely was support-function work |
| Worked on | Zero signal — describes presence, not contribution | Never appropriate — always replaceable with what you actually did |
| Participated in | Same as "worked on" | Never appropriate — replace with your specific contribution |
| Was responsible for | Passive; describes a job description, not achievement | Never appropriate in bullet context; acceptable only in a lead-line (Pattern 22) framing scope |
| Contributed to | Weak when ownership was higher | Acceptable only when the work was a genuine partial contribution to a larger effort owned by others — in that case, say "Contributed [specific thing] to [initiative]" |
| Collaborated with | Overused and vague | Acceptable when the point of the bullet is the cross-functional relationship itself ("Collaborated with Legal and Compliance to establish [X]"), not the work product |
| Involved in | No ownership signal | Never appropriate |
| Engaged in | Same as "involved in" | Never appropriate |
| Duties included | Responsibility framing, not achievement framing | Never appropriate in bullets; belongs only in a job description, not a resume |
| Tasked with | Same as "duties included" | Never appropriate |

**Filler intensifiers to remove regardless of context:**
- Extensively, significantly, substantially, meaningfully — add words without adding information

**✅ Strong verbs (in observed frequency order):**

*Tier 1 (ownership and initiative):*
- Built, Designed, Launched, Led, Delivered, Developed, Scaled, Drove, Spearheaded, Architected

*Tier 2 (strategic action):*
- Established, Instituted, Standardized, Migrated, Engineered, Orchestrated, Directed, Defined, Owned, Created

*Tier 3 (outcome and result):*
- Reduced, Improved, Accelerated, Achieved, Increased, Optimized, Expanded, Enabled, Mitigated, Saved

**Honesty check:** The verb must match the actual scope of contribution. Don't upgrade "Helped" to "Led" if you didn't lead — that's falsification. Better to use a Tier 2 or 3 verb accurately than a Tier 1 verb falsely. The default-avoid list is a prompt to ask "did I actually own this?" — not a mandate to overstate ownership.

**Real-world calibration:** When a candidate genuinely was not the lead:
1. Lead with what they personally did: `"[Verb] [specific component] within [team-led initiative]"`
2. Name the specific contribution: `"Designed the [X] module of [larger initiative]"`
3. Use "collaborated" only when the cross-functional relationship is the signal: `"Collaborated with [function] to establish [outcome]"`

### Pattern 6: Strategic Brevity at Senior Level [CONFIRMED — by counter-example]

Strong senior+ resumes omit these sections entirely; weaker resumes include them — and they add no value at senior level.

**What's NOT on the strong resumes:**
- ❌ No "Skills" section
- ❌ No "Certifications" laundry list
- ❌ No "Core Competencies" matrix
- ❌ No technical stack inventory
- ❌ No "Areas of Expertise" with 20 keywords

**Counter-pattern signals (common in weaker senior resumes):**
- "Core Competencies" section listing generic competencies (Project Management, OOP, System Design, Problem-Solving)
- "Technical Skills" section listing IDEs (any code editor), operating systems (any OS), and universal ticketing tools (any project management platform)

**What this signals to recruiters:**
- "Object-Oriented Programming" as a competency = table stakes for any engineer, not a Principal MTS differentiator
- Listing operating systems = junior engineer pattern
- Listing IDEs = no one cares which editor you use
- "Problem-Solving" as a core competency = meaningless

**The principle:** At Senior+ levels, work history IS the expertise. Skills sections are mid-level signals — they imply "let me list what I know" rather than "let me show what I've done." A candidate who has been a Sr. Manager at a BigTech-tier company or a Principal Engineer at an enterprise-software employer doesn't need to list "leadership" or "Java" as a skill.

**Exception:** Include a Core Competencies section when:
- Target role has specific keyword requirements for ATS
- Candidate is in a domain where specific certifications/tools matter (e.g., specific cloud platforms, regulated industries)
- Candidate is making a domain transition and needs to surface transferable expertise
- Industry convention demands it (e.g., government roles, certain consulting paths)

**For engineering resumes specifically:** see Pattern 10 (Per-Role Technologies Sub-Line) for a stronger alternative to a standalone Skills section.

**When in doubt at Senior+ level:** cut the Skills section, expand the experience bullets to demonstrate the same skills through actual work.

### Pattern 7: Older Roles Compression [CONFIRMED — by counter-example]

Strong resumes compress older roles tightly; weaker resumes give equal weight to older roles and bloat unnecessarily as a result.

**Typical structure from compressed resumes:**
- Current role: 5-6 bullets, detailed
- Previous role: 4-5 bullets
- 3rd most recent: 3-4 bullets
- 4-5 years back: 2-3 bullets
- 6+ years back: 1-2 bullets, single-line each
- 10+ years back: optional 1-line summary or removed

**Counter-pattern:** Giving 5+ bullets to a role from 8+ years ago adds visual real estate but no selection value. A current recruiter reading detailed bullets about decade-old work is spending attention on context that doesn't transfer to the next role.

**Why compression works:**
- Reflects what recruiters actually care about (recent work)
- Allows page-length compression without losing signal
- Signals self-awareness — the candidate knows what's relevant
- Older roles that get equal treatment look like padding

**Counterintuitive:** A candidate with 15 years of experience often makes their resume *worse* by detailing all 15 years equally. Compression is a strength signal.

**The "Recent Role is Thin" Trap:**
When a candidate has changed jobs recently (e.g., 5-month stints), the most recent section may genuinely lack substantive accomplishments. Two paths forward:
1. **Compress thin recent roles** to 2-3 bullets max — let the older, accomplished role get more space
2. **Strategically frame thin roles** with context (e.g., "Joined to scope X; early focus on Y") rather than padding with mundane tasks

Either path is better than featuring a current role's weak bullets ("Collaborated with [peers] to support [task]") above a previous role's strongest wins. Recruiters read top-down — make sure the top is your strongest.

### Pattern 8: The "Despite vs. Because" Test [CONFIRMED]

Some resumes get callbacks *despite* weak summary buzzwords, weak verbs in some bullets, and a redundant Skills+Technical Skills section — because their strong business-attribution carries them. Others get callbacks more cleanly because strong content is paired with workable design.

**Lesson:** Strong quantified content can overcome almost any weakness *except* missing impact. Weak design, weak verbs, and even weak summaries are recoverable if the numbers are there.

When analyzing any "winning" resume:
- **Strong content + weak design** → the content carried it. Replicate the content patterns; don't replicate the design.
- **Weak content + strong design** → likely got through ATS/screening but won't survive interviews. Don't replicate.
- **Strong content + strong design** → replicate both, with appropriate caution about over-fitting.

**Common "despite" features to avoid replicating:**
- 2010s-era Word templates with sidebars or curved shapes
- Two-column layouts (ATS-hostile)
- Decorative color blocks or banners
- Mixed serif/sans-serif inconsistency
- Generic stock graphics
- Drop-cap colored letters (template signature)
- Page footer logos / monograms

**Hold the resume's content patterns separately from its visual choices.** The patterns travel; the templates often don't.

### Pattern 9: Specific Company Identifiers Get Prime Real Estate [CONFIRMED]

Recognizable employer names — high-bar employers, unicorns, well-known brands (see Appendix A.1 for the canonical list of tier-1 / high-bar tech employers, organized by region and segment) — should be visually emphasized — bold, right-aligned, larger weight, or otherwise prominent.

A recruiter scanning fast should be able to spot company names in 2 seconds. If a candidate has tier-1 employers on their resume, that pattern should jump off the page.

**Implementation:**
- Bold company names
- Right-align company names if title is left-aligned (creates visual scan pattern)
- Use slightly larger font for company name than title
- Never hide a strong employer name in italics or muted color

**Mid-tier or unknown employers:** treat with standard formatting. Don't try to artificially elevate them visually.

**Promotion ladder visibility:** Strong resumes visibly showcase career progression within a single employer through stacked sub-titles with sub-dates. Don't hide promotions by listing only the current title — separate them with sub-dates and progression arrows where space permits.

### Pattern 10: Per-Role Technologies Sub-Line (Software Engineer Resumes) [OBSERVED — default good practice]

The default good practice for software engineering resumes: list the tech stack as a sub-line under each role's title rather than in a separate Skills section. The choice between Pattern 10 (sub-line) and bullet-embedded tech (Variant B) is connected to bullet style (Pattern 4).

**Why this is the default good practice:**
- Gives ATS a dense keyword cluster tied to each role (better than a decontextualized Skills list)
- Lets recruiters see tech stack at a glance per role
- Avoids the "Skills" laundry list problem at the bottom of the resume
- Shows tech evolution across career (Java → Python → AWS → Kubernetes)
- Eliminates redundancy of stating skills both in a list and in bullets

**Alternative path (when bullets carry the tech):**

If using Bullet Variant B (narrative variant — see Pattern 4), the bullets naturally embed technologies inline within the prose. In that case, a separate Technologies sub-line becomes redundant — the narrative bullets are already keyword-dense.

**Decision rule:**
- **Using Bullet Variant A (tight, 20-30 words)?** → Use the Technologies sub-line. Tight bullets can't carry tech keywords without it.
- **Using Bullet Variant B (narrative variant, 80-150 words)?** → Sub-line is optional. The narrative bullets already do the work. Adding a sub-line creates redundancy.
- **Mixed bullet styles?** → Include the sub-line. It costs little and helps ATS parsing for the tight bullets.

**Roles where this convention applies:**
- Software Engineer (IC, all levels)
- Data Engineer / ML Engineer
- DevOps / SRE / Platform Engineer
- Mobile Engineer
- Embedded / Firmware Engineer

**Roles where this convention does NOT apply (don't force it):**
- TPM, Program Manager — use "Methods" instead (Agile, RICE, OKRs)
- Solutions Architect — use "Architectures" instead (microservices, event-driven, etc.)
- Product Manager — typically no equivalent; PM skills go in summary or omit
- Data Scientist — sometimes uses "Tools" line, but optional
- Engineering Manager — depends; if they still code, include; if pure people-leader, omit

**Implementation notes:**
- Italicize the Technologies line (visual distinction from bullets)
- Use a smaller font size than bullets if space is tight
- List 5-10 most relevant technologies per role
- Order: languages → frameworks → infrastructure → specialized tools
- Skip versions unless the version is meaningful (e.g., "Java 17" only if relevant)

**Why this works:**
- Gives ATS a dense keyword cluster tied to each role (better than a decontextualized Skills list)
- Lets recruiters see tech stack at a glance per role
- Avoids the "Skills" laundry list problem at the bottom of the resume
- Shows tech evolution across career (Java → Python → AWS → Kubernetes)
- Eliminates redundancy of stating skills both in a list and in bullets

**Implementation:**
- Italicize the Technologies line (visual distinction from bullets)
- Use a smaller font size than bullets if space is tight
- List 5-10 most relevant technologies per role
- Order: languages → frameworks → infrastructure → specialized tools
- Skip versions unless the version is meaningful (e.g., "Java 17" only if relevant)

**For non-engineering resumes:** the equivalent is including domain-specific tools/methodologies in a similar sub-line (e.g., for a TPM: "Methods: Agile, OKRs, RICE prioritization, dependency graphs"). Tighter than a Core Competencies section, more contextual than a Skills list.

### Pattern 11: Software Engineer Big-Dollar Business Attribution [OBSERVED — rare and valuable]

Software engineers who can attribute large business outcomes (multi-million-dollar, hundred-million-dollar) to their technical work send a rare and powerful signal. This pattern is **especially valuable for software engineers** because most engineers don't think in business-impact terms.

**Why this signal is engineer-specific:**
- PMs and CSMs are *expected* to talk in business terms — $X revenue is table stakes
- Software engineers typically describe what they built, not what it generated
- An engineer who connects code → dollars stands out from peers automatically
- Promotion committees at high-bar companies explicitly look for this

**Bullet formula for this pattern:** `[Tier-1 verb] [system/feature], [scale or volume metric] in [business context]` — connects technical work to business impact.

**Why this is rare:**
Most engineers describe what they built ("designed a payment system") without connecting it to business impact ("processing $X in transactions"). The ICs who make this connection signal three things:
1. **Strategic thinking** — they understand why the work matters
2. **Business literacy** — they can talk to executives, not just engineers
3. **Promotion readiness** — they think beyond ticket execution

**How to apply (for any engineer):**
1. For each major project, ask: *What revenue, savings, or risk did this code enable/prevent/protect?*
2. Get the number from finance, product, or analytics (don't fabricate)
3. Use it in the bullet — even if it's a projection (with care; see Pattern 14)

**Caution:** This signal works only if the math is defensible. Recruiters won't verify, but hiring managers and panel interviewers will probe. The specific dollar figure should have a real answer ready in the interview.

### Pattern 12: Specific Project Naming [OBSERVED]

Naming actual project handles signals concrete experience over abstractions. Strong resumes name specific internal project codenames and product initiatives by name rather than using generic descriptions.

**Why this works:**
- Specific project names suggest the candidate genuinely owned the work
- Abstract descriptions ("payment processing system") could describe anyone's work
- A named project invites follow-up questions in interviews, which the candidate can answer
- Project names often appear in industry vocabulary, signaling domain expertise

**Formula:** `[Verb] [Project Codename or Initiative Name] [system/scope], [outcome with metric]`

**Detection patterns:**
- ✅ Strong: Bullet names a specific internal codename or initiative, hyperlinked when public (see Pattern 18)
- ❌ Weak: Generic descriptions ("Built [system type]", "Worked on [system type]", "Developed [tool category]") — these could describe anyone's work

**Honesty check:** Use project names only when you genuinely owned or led that named project. Co-contributors should say so ("contributed core component of [project name]").

### Pattern 13: Hyperlinked Icon Contact Block [OBSERVED — modern best practice]

Contact information should use small icons (phone, email, LinkedIn) with hyperlinked text rather than plain-text URLs.

**Implementation:**
- Phone icon · Phone number (as `tel:` link or plain)
- Email icon · Email address (mailto: link, blue/underlined)
- LinkedIn icon · LinkedIn URL (https:// link, blue/underlined)
- All on a single line under name/title

**Why this works:**
- Recruiter clicks the LinkedIn link directly from PDF → faster path to profile
- Mailto: link opens email composer in one click
- Looks modern; signals candidate is current with conventions
- Saves horizontal space vs. spelling out full URLs

**ATS compatibility:** Most ATS systems handle this fine. Confirm by saving as PDF (not Word's special export) and testing whether links remain clickable.

**Warning:** Don't overdo icons elsewhere on the resume. Icons in the contact line are functional; icons next to section headers (📌, 🎯) are template energy.

### Pattern 14: Projection vs. Measurement Language [OBSERVED]

Some achievements use projected numbers ("poised to contribute," "estimated to add," "potential loss of"). These are softer signals than measured outcomes and should be flagged.

**Detection patterns:**

✅ **Measured language (strongest):** Past-tense verbs paired with realized metrics — `"[Verb] [metric] by [N]"` where the outcome has already occurred and is measurable.

⚠️ **Projection language (softer):** Phrasing like `"poised to..."`, `"estimated to add..."`, `"potential loss of..."`, `"projected to..."` — these are forward-looking claims that haven't been realized yet.

**Decision rules for using each:**
1. Lead with measured outcomes when available
2. Be transparent about projections — `"$[X]M projected annually"` is more credible than `"$[X]M annually"` for unrealized impact
3. Be ready to defend projection math in interviews
4. Never stack multiple projections in one bullet — diminishing returns; recruiters discount
5. Avoid the phrase "poised to" — it's a soft hedge that adds no information

**Best phrasing template for projections:** `"[Verb] [feature/system], [estimated to/projected to] [outcome metric] [in/within timeframe]"`

### Pattern 15: Culture-Fit Vocabulary Signaling [OBSERVED — high-leverage]

**Embedding 1-2 company-specific vocabulary terms signals "I know how this place operates" to insider recruiters and hiring managers.**

When a candidate uses a target company's trademark vocabulary in a way that reflects how they actually operated, it's an instant culture-fit signal — they don't just have relevant experience; they think in that culture's idioms.

**The methodology (not a lookup table):**

Rather than memorize specific vocabulary lists (which go stale and create awkward "I read the careers page" signaling), apply Pattern 27 (Business Context Validation): web-search the target company's public materials at the time of application:

1. The company's engineering blog
2. Public talks by their senior engineers/PMs at industry conferences
3. Their published culture documents, operating principles, or values pages
4. Their hiring-team blog posts about their interview process
5. Industry coverage describing their internal methodologies

Identify 1-2 phrases that genuinely describe how you operated. Embed them naturally in bullets. Don't stack them.

**Examples of where you'd find this kind of vocabulary:**

| Source type | What to look for |
|---|---|
| Engineering blog posts | Recurring methodology terms (often capitalized) |
| Leadership talks at conferences | Names of internal frameworks or rituals |
| Published values/operating principles | Trademark phrases the company uses to describe how it works |
| Glassdoor interview-prep notes | Vocabulary that recurs across candidate experiences |
| Public job descriptions | Phrases that recur across the company's postings |

**Caution:**
- Only use vocabulary that genuinely describes your work
- Don't claim certified status (e.g., interview-certification roles) you don't have
- Don't reference legacy programs (e.g., a discontinued benefit or initiative) as if they still exist
- Wrong vocabulary signals cultural ignorance, not cultural fit
- Internal-jargon stacking ("I worked-backwards using customer-obsession to drive single-threaded leadership") reads as keyword-stuffed and fake

**Why this is high-leverage:**
This is one of the few things you can add to a resume that takes ~10 words and signals deep cultural knowledge. Most candidates miss this entirely. Ex-employees recognize it instantly. **But it requires Pattern 27 validation every time** — vocabulary changes, programs get discontinued, and stale references signal the opposite of cultural fluency.

### Pattern 16: External Credibility Markers [OBSERVED — Principal+/Staff+ accelerator]

Publications, patents, conference talks, open-source contributions, and other external validation signals serve as accelerators for senior IC engineering roles.

**Structural template for surfacing publications/patents:**
- `[Paper title or topic] — [top-tier venue: conference/journal name]` — list publications with venue tier visible
- `[Patent number] ([filing year]; granted [year]) covering [technical area]` — list patents with timeline

**Why this matters at senior levels:**
- Most senior SWEs **don't have** publications or patents — having any is a differentiator
- Top-tier systems-conference papers signal genuine technical depth
- Granted US patents signal novel work that's been independently validated
- For Principal/Staff/Senior Principal IC roles, these become **significant signals** of technical leadership

**Types of credibility markers (ranked by approximate weight for senior SWE roles):**
1. **Top-tier peer-reviewed papers** (illustrative venues: ASPLOS, SOSP, OSDI, NSDI, SIGCOMM, ICML, NeurIPS; see Appendix A.8 for verifiability hosts) — strongest
2. **Granted US/international patents** — strong, especially with citations (patent offices: see Appendix A.8)
3. **Open-source maintainership** (committer/maintainer status on widely-used projects) — strong
4. **Conference talks** at major events (illustrative: re:Invent, Strange Loop, QCon, USENIX) — moderate-to-strong
5. **Industry blog posts on personal/company blog** with traction — moderate
6. **Technical book authorship** — moderate (depends on publisher)
7. **Stack Overflow / technical Q&A reputation** — minor at senior levels
8. **Active GitHub portfolio** — table stakes; absence is a weakness

**Optimization rule — connect credentials to context:**
A common gap is listing publications and patents without connecting them to actual work or contextualizing their weight. The citation count, conference tier, and follow-on impact are the credibility signals — don't bury them.

**Detection patterns:**
- ❌ Weak: Neutral listing of patent number and generic title with no context
- ✅ Strong: Patent listing includes filing timeline, technical area, and link to production work (where applicable)
- ✅ Strong: Publication listing includes venue tier, citation count, and brief description of follow-on impact

**For roles where this matters most:**
- Principal/Staff/Distinguished Engineer (any company)
- Research Engineer roles at top-tier AI labs (see Appendix A.1 — *Top-tier AI labs / research-heavy employers*)
- Architect roles at cloud hyperscalers (see Appendix A.2 — *Hyperscalers*)
- Roles at companies with strong publication cultures (see Appendix A.1; representative examples: large-cap tech employers and research divisions of hyperscalers)

**For roles where this matters less:**
- Mid-level SWE roles (publications can read as "overqualified")
- Startup engineering (delivery > publications)
- Front-end or product-focused roles

### Pattern 17: Tenure as Strength Signal at High-Bar Employers [OBSERVED]

Long tenure (8+ years) at a single high-bar employer reads as a strength signal — despite the general industry preference for shorter tenures — when that employer has a reputation for selective hiring, high performance bar, and visible attrition. See Appendix A.1 for the canonical list of tier-1 / high-bar tech employers where this signal applies most strongly; for non-tech industries, apply Pattern 28 (Industry/Role Inference) to identify the equivalent high-bar set.

**Why this works at high-bar employers:**
- Their attrition is well-known — longevity signals capability and culture fit
- Long tenure at a high-bar company implies survival of multiple performance review and promotion cycles
- Recruiters who came from that employer (and recruiters in their adjacent market) recognize this signal explicitly
- Long tenure with visible internal promotions = strong senior-level signal

**How to surface tenure as strength:**
- Lead the role with the **highest title achieved** (not the entry title)
- Show progression within the company via sub-dates (e.g., Sr. SDE I → Sr. SDE II → Principal SDE)
- Mention scope expansion ("From X to Y projects" / "From 5-person team to 30+ team")
- Lean into the "I survived and grew" narrative if applicable

**When tenure is NOT a strength:**
- 10+ years at a single company **without visible progression** = stagnation signal
- 10+ years at a low-bar or non-recognized company = doesn't help
- Tenure that ended in role downgrade or sideways move = address explicitly

**Adjacency rules (relevance of long high-bar tenure to target companies):**
- ✅ Same employer → other roles at that employer or its subsidiaries: Direct relevance
- ✅ Same employer → other large technology peer employers: Strong relevance (peer-cohort recognition)
- ✅ Same employer → startups concentrated with that employer's alumni: Strong relevance
- ⚠️ Same employer → tech in different geographic markets / different cultures: Moderate relevance
- ⚠️ Same employer → enterprise / traditional industries: Mixed — possible culture clash
- ⚠️ Same employer → consulting / professional services: Different evaluation criteria

**Pattern 28 prerequisite:** Use Pattern 28 to determine whether the candidate's prior employer qualifies as "high-bar" for this signal to apply, and whether the target market recognizes that employer's culture.

### Pattern 18: Embedded Hyperlinks on Named Projects [OBSERVED — verifiability signal]

Named products, features, and references inside bullets should be hyperlinked to their public announcements, docs, or product pages.

**Hyperlink syntax in bullets:**
- `[Project/Product name](https://public-url)` — Markdown syntax
- In Word/PDF: Select project name → Insert Hyperlink → paste public URL
- Hyperlinked text retains visual styling (typically blue + underline)

**Why this matters:**
- Lets recruiters and hiring managers **verify the work exists** — one click takes them to a public reference
- Signals the candidate's claims are real (you can't fake a hyperlinked launch announcement)
- Indicates the candidate worked on **launched/public** products, not internal-only or vaporware
- Modern PDF viewers preserve these links; recruiters click them
- For senior IC roles, this is a subtle but strong credibility signal

**What to hyperlink (in priority order):**
1. **Launched products you worked on** → company product pages
2. **Public features you owned** → hyperscaler docs / what's-new pages, GitHub repos (see Appendix A.8 — *Cloud platform docs* and *Code*)
3. **Conference talks you gave** → YouTube videos, conference websites (see Appendix A.8 — *Conference talks*)
4. **Publications/papers** → DOI links, ACM/IEEE pages (see Appendix A.8 — *Academic publications*)
5. **Patents** → USPTO or international patent-office links (see Appendix A.8 — *Patents*)
6. **Open-source projects** → GitHub / GitLab / package-registry pages (see Appendix A.8 — *Code* and *Open-source ecosystem*)
7. **Press coverage** → reputable industry publications (apply Pattern 27 to validate the publication is recognized in the target market)

**What NOT to hyperlink:**
- Internal projects with no public face (link goes nowhere)
- Personal blog posts (unless they're substantive technical writing)
- Generic vendor docs unrelated to your work
- Links to job postings or company about pages (no signal value)

**Implementation:**
- In Word/Google Docs: select text → "Insert Hyperlink"
- In Markdown: `[text](URL)` — but verify the PDF export preserves the link
- Use a clear visual indicator (blue underline is conventional; some templates use just blue)
- Test by clicking the link in the exported PDF

**ATS compatibility:**
- Most ATS systems strip hyperlinks during parsing, so the link doesn't help with keyword matching
- But the **visible text** still parses normally, so there's no downside
- The hyperlink helps in the human review stage (recruiter scan + hiring manager review)
- Both the SEO and human stages benefit

**Caution:**
- Don't hyperlink everything — overuse makes the resume look cluttered
- Aim for 3-6 strategic links across the entire resume
- Verify every link works before exporting the final PDF
- Use HTTPS URLs only (HTTP can be flagged by security software)

**Why this is a high-leverage low-effort pattern:**
Most candidates don't hyperlink their work. Doing so takes 15 minutes and signals professional polish + verifiable credibility. It's a free win for any senior IC who has worked on public products.

### Pattern 19: The Worksheet Method (Placeholder Brackets + Tips) [PEER-REVIEW-SOURCED]

**A coaching/critique technique for surfacing missing quantification.** When working with a candidate who has the right experience but hasn't quantified it on the resume, scaffold the bullets with explicit placeholders and accompanying "Tip" callouts that explain what kind of number to find.

**Format:** `[Bold theme prefix]: [Action verb] [what was done], [outcome with placeholder bracket]. *↳ Tip: [what category of number to find]*`

**Why this works as a workflow technique:**
- Teaches the candidate to think in numbers by showing exactly where they should appear
- The Tip clarifies *what category of number* to find (financial leak size, not headcount; cycle-time reduction, not team scale)
- Catches missing quantification before submission — visible blanks = "do this"
- Forces explicit confrontation with quantification gaps rather than vague placeholders

**Metric categories worth prompting for (the "what to look for" library):**

| Category | Example Tips |
|---|---|
| **Financial impact** | "What revenue did this enable/protect?" "What cost did this eliminate?" "What budget did you control?" |
| **Time/cycle** | "How much faster is this than before?" "How many hours/days saved per week?" |
| **Scale** | "How many users/members/transactions does this serve?" "How many systems/sources/teams?" |
| **Quality** | "What's the error rate before/after?" "What's the compliance rate?" |
| **Team/scope** | "How many people did you coordinate?" "How many functions did you span?" |
| **Growth/multiplier** | "What's the X-times improvement?" "What % expansion or growth?" |

**How to use in the 6-step workflow:**
Apply during **Step 3 (Achievement Rewrite)** when reviewing a candidate's existing bullets:
1. Scan each bullet for missing numbers
2. Insert `[INSERT NUMBER]` / `[$ AMOUNT]` / `[INSERT %]` placeholders where numbers should appear
3. Add a Tip clarifying what kind of number to find
4. Send back to the candidate as a worksheet
5. Have them fill in real numbers before moving to Step 6 (Final Polish)

**Critical guardrails:**
- ❗ The worksheet output is a **draft state, not a submittable state**. A resume with `[INSERT NUMBER]` brackets is not ready to send to recruiters.
- ❗ **Never replace existing real numbers with placeholders.** If a bullet already has a specific dollar figure in it, don't templatize it back to "[$ AMOUNT]" — that's a regression, not a coaching improvement.
- ❗ **Use placeholders only where numbers are genuinely missing.** They're for filling gaps, not for restructuring already-quantified content.
- ❗ **All brackets must be filled before submission.** Search for `[` characters in the final document — none should remain.

**Best use case:**
This pattern is most valuable when **someone helping a candidate** (peer reviewer, coach, or the candidate themselves doing a self-audit) wants to systematically identify quantification gaps. It's less useful for a final polish pass — at that stage, all brackets should already be filled.

### Pattern 20: Internal Award Translation [PEER-REVIEW-SOURCED]

**A legitimate technique for surfacing real recognition that has unrecognizable internal names.** Many companies use generic internal award names ("Star Award," "Growth Award," "Outstanding Contributor") that mean nothing to external recruiters. Translating these into externally legible names communicates what was actually recognized.

**Translation pattern:**

Take the internal award name and translate it to a name that communicates externally what it actually recognized:

| Internal name pattern | External translation pattern |
|---|---|
| Generic internal recognition name (e.g., "Star Award," "Spot Award," "Bravo Award") | Description of what the award recognized (e.g., "Cross-Team Impact Recognition," "Strategic Initiative Excellence") |
| Founder/CEO-level recognition with internal-only name | "Company-Wide [Innovation/Leadership/Impact] Recognition" |
| Internal innovation award with generic name | Specific descriptor of the innovation domain (e.g., "Platform Innovation Award") |
| Internal velocity/growth award | Descriptor of what the velocity applied to (e.g., "Velocity Distinction" if delivery-focused) |

**Why this works:**
- Recruiters outside your company don't know what a "Star Award" means
- Generic internal names underestimate the actual achievement
- An externally legible name communicates what was recognized
- Validates the achievement to people who haven't worked at your company

**How to translate honestly:**
1. **Identify the actual criteria** the award recognized (delivery excellence, innovation, customer impact, etc.)
2. **Choose a translation name** that reflects that criteria accurately
3. **Don't inflate the scope** — if it was a project completion award, don't translate to "Strategic Excellence Award"
4. **Be ready to explain the original name** if asked in an interview

**Honest interview phrasing if asked:**
"Internally at [Company], we called this the [original name] — it was awarded for [actual criteria]. I've translated it on my resume to [external name] because the internal term wouldn't communicate the recognition externally."

**Critical guardrails:**
- ❗ **The award must be real.** Translation is OK; invention is not.
- ❗ **The translation must reflect the actual criteria.** Don't translate "monthly attendance award" into "Sustained Excellence Recognition."
- ❗ **Don't translate every award the same way.** If you have multiple "Star Awards" for different reasons, give them different translated names that reflect what each was actually for.
- ❗ **Cap translated awards at credible scope.** A junior-level award translated as a "Strategic Leadership Distinction" reads as inflation, not translation.

**Where to place translated awards:**
- Dedicated "Awards & Recognition" section if you have 3+ to list
- Inline within the relevant role's bullets if you have 1-2
- Never in the Summary section (too prominent for individual awards)

### Pattern 21: Bold Theme Prefix in Bullets [CONFIRMED]

**Each bullet starts with a 2-4 word bold thematic label, followed by a colon, then the bullet content.** This convention creates strong visual scannability.

**Format:** `**[Bold Theme Prefix]:** [bullet content with quantified outcome]`

**Why this works:**
- Each bullet becomes scannable in 1 second (just read the labels down the left edge)
- A recruiter can map themes across roles to detect signature competencies (connects to Pattern 3)
- The label primes the recruiter for what the bullet covers — they decide whether to read the full bullet
- Makes long Bullet Variant B (narrative variant) bullets navigable; without prefixes, 150-word bullets become walls of text

**Implementation guidelines:**
- **Length:** 2-4 words, never more than 6
- **Content:** Theme-coded for the role (e.g., "Federal Compliance Program Delivery") — not just describing the bullet
- **Formatting:** Bold, followed by colon, then space, then bullet content (no line break)
- **Consistency:** Apply to all bullets in a role, or none. Don't mix.

**When the prefix should DESCRIBE vs. THEMATICALLY LABEL:**

❌ **Descriptive (weak):** The prefix just summarizes what the bullet says — redundant with the bullet content (e.g., a prefix like `"Built a Data Pipeline:"` followed by a bullet about building a data pipeline).

✅ **Thematic (strong):** The prefix names the underlying competency or theme — adds information beyond what the bullet states (e.g., a prefix like `"Real-Time Transaction Processing at Scale:"` followed by a bullet about a data pipeline that processes transactions at high volume).

The thematic label adds dimension; the descriptive label is redundant.

**Caution — what NOT to do:**
- ❌ Vague labels: "Various Improvements," "Multiple Achievements," "Key Wins"
- ❌ Buzzword stacks: "Synergistic Cross-Functional Excellence"
- ❌ Inconsistent labels across the same role
- ❌ Labels longer than 6 words (they become mini-sentences)
- ❌ Labels in different formatting from each other (some bold, some italic, etc.)

### Pattern 22: Lead-Line per Role [PEER-REVIEW-SOURCED — low priority]

**A single-sentence framing line under each role title, before the bullets begin, that establishes scope and context.**

**Format:** `*[Verb in present tense] [scope of role] to deliver [domain] at [scale] across [breadth] serving [audience].*`

Set as italicized single sentence, placed between role title line and first bullet.

**Why this can work:**
- Frames the entire role before the recruiter reads bullets
- Lets you state scope in present-tense narrative form
- Different from a Summary (which is for the whole resume) and from a Technologies sub-line (which is just a list)
- For senior roles where scope context matters, anchors what comes next

**Why this is marked low priority:**
- Not consistently observed in strong resumes
- Risk of redundancy with the first bullet (which often already states scope)
- Adds visual real estate; on a 2-page resume, every line costs
- The strongest first bullet usually frames the role implicitly without needing an explicit lead-line

**When to consider using it:**
- Senior+ roles where the *frame* and the *bullets* serve different purposes
- Roles where the title alone doesn't communicate scope (e.g., "Senior Manager" at a company where that title spans many functions)
- Mixed-format resumes where you have both Bullet Variant A and B styles and want the lead-line to set context for the tighter bullets

**When to skip it:**
- 1-page resumes (no room)
- When your first bullet already does the framing work
- When all your bullets use Variant B (narrative variant), which carries its own context
- When the role title + company + dates already tell the recruiter enough

**Caution:** The lead-line shouldn't repeat what the bullets will say. If you write "Led global teams delivering SaaS platforms" and then your first bullet is "Led delivery of SaaS platform...," you're being redundant. The lead-line should set the *frame* (who you serve, what scale, what mandate); bullets do the *evidence*.

### Pattern 23: The 3-Paragraph Structured Summary [PEER-REVIEW-SOURCED — confirmed outcome]

**An alternative to the pipe-separated headline (Pattern 1) for roles where pipe segments feel too constrained.**

**Structure:**

- **Paragraph 1 — Identity + scope + headline numbers:** `[Function/discipline] leader with [X]+ years building [system type] for [target audience]. Expert in [2-3 core competencies]. Proven track record partnering with [stakeholder types] to deliver [outcome] powering [headline $ or scale figure].`

- **Paragraph 2 — How you work + functional expertise:** `Fluent collaborating with [team types] in [methodology] — leading [activities such as roadmap prioritization, sprint planning, delivery]. Deep expertise in [domain-specific capabilities]. Strong cross-functional leader driving alignment across [function names] through [mechanisms].`

- **Paragraph 3 — Technical proficiency (tools/stack list):** `Technical proficiency: [languages], [tools], [platforms], [methods].`

**Why this works:**
- Three structured paragraphs each carry their own job (identity, working style, tools)
- The first paragraph still hits 10-second scan needs (identity + headline numbers in para 1)
- Lets you go deeper than a pipe headline on stakeholder model and methodology
- More natural for PM/consulting/cross-functional roles where work involves nuance that doesn't compress to pipe segments

**Pattern 1 vs Pattern 23 — when to use which:**

| Use Pattern 1 (Pipe Headline) | Use Pattern 23 (3-Paragraph) |
|---|---|
| TPM, Program Manager | Product Manager |
| Engineering Manager with quantified wins | Cross-functional roles with stakeholder nuance |
| Operations Leader | Consulting backgrounds |
| Roles where scannability beats depth | Roles where methodology signaling matters |
| Candidate has 3+ headline-grade quantified wins | Candidate has narrative scope but fewer hero numbers |
| Target audience values pattern-recognition | Target audience values working-style fit |

Both formats work; the choice depends on how much *narrative nuance* the function needs to communicate vs how much *quantified pattern-matching* the recruiter is doing.

### Pattern 24: Domain-Functional Vocabulary Signaling [CONFIRMED]

**Extends Pattern 15 (Culture-Fit Vocabulary).** Where Pattern 15 covers company-specific vocabulary (signature phrases of a target employer), Pattern 24 covers **function-specific and domain-specific vocabulary** that signals "I live in this world."

**Examples across functions:**

| Function/Domain | Vocabulary Signal Terms |
|---|---|
| **Product Management** | "North Star," "roadmap," "PRD/spec," "MVP," "launch criteria," "KPI definitions," "experimentation framework" |
| **Supply Chain PM** | "S&OP," "MAPE," "bias," "coverage," "BOM," "Super BOMs," "Wave/Discrete Picking," "capacity planning," "demand-supply balancing" |
| **Engineering / SWE** | Tech stack specifics, architecture patterns ("event-driven," "CQRS," "microservices") |
| **Customer Success** | "NRR," "GRR," "renewal rate," "expansion rate," "QBR," "executive sponsor," "time-to-value," "logo retention," "churn risk" |
| **Data Science / ML** | "MAPE," "AUC," "precision/recall," "feature engineering," "drift detection," "model registry," "A/B testing" |
| **DevOps / SRE** | "SLO," "SLI," "error budgets," "blameless postmortem," "MTTR," "incident response," "GitOps" |
| **Sales** | "ARR," "ACV," "pipeline," "win rate," "expansion," "land-and-expand," "champion building" |
| **Regulated Industries (generic)** | Domain-specific regulatory citations, industry-standard data exchange protocols, vendor-specific terminology validated per Pattern 27 |

**Note:** This table is illustrative, not exhaustive. For any specific industry/function not listed here (healthcare, finance, defense, manufacturing, legal, etc.), Pattern 27 (Business Context Validation) and Pattern 28 (Industry/Role Inference) will surface the right vocabulary at runtime via web search.

**Why this works:**
- Specialist recruiters search for these exact terms
- A specialist hiring manager reads vocabulary and instantly knows whether you actually do this work
- 5-10 well-placed vocabulary terms across a resume signal authentic domain expertise
- Domain vocabulary works alongside (not instead of) company-specific vocabulary

**How to apply:**
1. Identify your domain and function
2. List the 10-15 vocabulary terms that specialists in that world use natively (see the vocabulary table above for starting points by function)
3. Audit your resume — are you using 5+ of them naturally?
4. If not, identify bullets where the term is missing but the work involved it
5. Add the term, in context, where it authentically applies

**Honesty check:** Only use vocabulary that genuinely describes your work. Don't claim terminology, methodologies, or frameworks you don't actually use. Any vocabulary on the resume must back up to defensible interview answers — if a domain expert probes, you should be able to explain how you used the term in practice.

**Anti-pattern reminder:** Pattern 24 is the *opposite* of buzzword stuffing. The signals are domain-specific technical/methodology terms, not generic consulting-speak ("synergistic," "high-velocity," "transformational"). If a specialist wouldn't say it in a meeting, it's a buzzword, not a domain signal.

### Pattern 25: PM Outcome-Anchor Bullet Structure [OBSERVED — PM-specific]

**A bullet structure especially well-suited to Product Manager resumes** that combines launch context, front-loaded percentage outcomes, and a headline dollar anchor.

**Structure:**
`[Launch verb] [product/feature shipped] that [front-loaded % outcome] and [front-loaded % outcome], using [methodology/KPI vocabulary] and [validation/rollout criteria] to [headline $ anchor] and enable [strategic outcome].`

**Component breakdown:**
- **Launch verb:** Tier-1 verb such as "Launched," "Shipped," "Released"
- **What you shipped:** Specific named product, feature, or engine
- **% outcomes front-loaded:** 1-2 percentage-based operational improvements, placed early in the bullet
- **Methodology/KPI vocabulary:** Reference to the metrics framework used (see Pattern 24 for function-specific vocabulary)
- **Headline $ anchor:** Dollar-denominated business impact, placed at the end as the punch
- **Strategic outcome:** What capability or business mechanism the launch enabled going forward

**Why PM-specific:**
- PM work routinely produces large dollar attributions (revenue safeguarded, savings enabled, growth driven)
- The launch event is a natural narrative anchor (PMs ship things)
- KPI/methodology vocabulary signals product rigor (not just outcome claims)
- The headline $ anchor at the end gives the bullet its "big number" without burying it (Anti-Pattern 4)

**Why this differs from Bullet Variant A and B (Pattern 4):**
- Variant A is tight, 20-30 words, one-sentence
- Variant B is narrative-style, 80-150 words, context-problem-action-outcome-scope
- Pattern 25 is mid-length (40-60 words), launch-anchored, dual-quantified (% + $)

**Use Pattern 25 when:**
- The bullet describes a launched product, feature, or program (not just an internal initiative)
- The launch produced measurable operational improvements AND attributable business value
- The work involved a methodology/KPI framework worth signaling
- The role is Product Management, Product-adjacent TPM, or Customer Success with launch ownership

**Skip Pattern 25 when:**
- The bullet describes ongoing work with no clear launch event
- The work doesn't have both % outcomes AND $ outcomes (use Variant A instead)
- You don't have authentic methodology vocabulary to include

### Pattern 26: Title Research and Selection Methodology [METHODOLOGY — required at Step 1]

**A research-driven methodology for selecting the right title to use on a resume, rather than assuming the internal title or guessing what target employers expect.** This is the most upstream decision in resume optimization — the chosen title affects ATS matching, recruiter scan, summary framing, and every bullet's positioning. Get it wrong and the rest of the work is misaimed.

**Why this needs explicit methodology:**
- Internal titles often don't communicate externally; a long composite internal title rarely matches what the market calls the underlying work
- Title conventions vary across industries, seniority levels, and recruiting cultures
- Title conventions change over time; what was a rare title 10 years ago may be the dominant title today
- Candidates often default to titles they're familiar with rather than titles the market currently uses
- An assistant guessing at titles based on training-data assumptions will misalign with current market conventions

**Methodology — 5 steps:**

**Step A: Audit the actual work and responsibilities**

Pull from the candidate's existing resume bullets, conversation, and metrics. Identify the **functions** they perform, regardless of internal title. Common function clusters:

- **Customer Success / Account Management:** portfolio ownership, renewals, executive sponsor engagement, NRR/GRR accountability, QBR cadence, at-risk-account recovery
- **Technical Program Management:** cross-functional coordination, dependency management, federal/regulatory delivery, multi-team rollouts, executive stakeholder reporting
- **Tech Lead / Staff Engineer:** system architecture decisions, production reliability ownership, multi-engineer technical direction, performance/latency improvements
- **Product Manager:** roadmap ownership, launch criteria definition, KPI/north-star definition, stakeholder alignment, customer research
- **Engineering Manager:** people management, hiring, performance reviews, team-level OKRs, delivery accountability through reports

A single candidate often has functions from 2-3 clusters; their work spans the functional boundaries even when their internal title doesn't.

**Step B: Web-search current title conventions in the target market**

Use web search (not training-data assumptions) to research:
- Current titles for the function in the target industry, via specific industry + function + year search queries
- Current job postings at competitive employers in the target market
- LinkedIn search results for "people with title X at company Y"
- Title variations across seniority levels (Senior CSM vs Director of CSM vs VP of Customer Success)
- Industry-specific title conventions (e.g., "Solutions Engineer" common in some industries; "Sales Engineer" in others)

**Why web search is required here:** Title conventions evolve. A title that was current 2 years ago may be deprecated; a title that didn't exist may now be standard. Training data has a cutoff; current job postings reflect what recruiters and ATS systems index against today.

**Decision rule — how to select a recommended title from search results:**

After the web search, apply the following criteria in order:

1. **Frequency signal:** Which title appears most frequently across current job postings for this function+level combination? The highest-frequency title is the default recommendation, because it maximizes ATS keyword match probability.

2. **Defensibility check:** Does the candidate's actual work history support the high-frequency title? Map specific resume bullets to the job description requirements for that title. If ≥3 major responsibilities are supported by evidence in the resume → the title is defensible. If <3 → disqualify this title option and move to the next most frequent.

3. **Seniority calibration:** Does the high-frequency title at the target seniority match the candidate's scope signals (team size, budget, geographic reach)? If the title implies VP-level scope but the candidate's evidence supports Senior Manager scope → downgrade to the appropriate seniority variant.

4. **ATS variant check:** Are there significant variant spellings or adjacent titles that appear frequently enough to warrant a separate application variant? (e.g., "Technical Program Manager" vs "Engineering Program Manager" may both have high frequency — flag both.)

**Output of Step B:** A ranked shortlist of 2-3 title options with explicit frequency evidence, defensibility mapping, and seniority calibration for each. Not a gut-feel suggestion — a research-backed recommendation.

**Step C: Suggest 2-3 title options that authentically reflect the work**

Don't lock in a single title prematurely. Present:
- **Most direct title** — matches the dominant function the candidate performs
- **Adjacent title option** — for an alternate function the candidate could position toward, where supported by evidence
- **Hybrid title option** — if the work genuinely spans clusters, a hybrid title combining two function descriptors

For each option, explain:
- Which target roles it best fits
- What evidence in the candidate's work supports it
- What seniority signals it carries
- Any honesty/defensibility risks (see Anti-Pattern 15)

**Step D: Customize per specific job description**

If the candidate is applying to a specific role with a JD in hand:
- Mirror the JD's title closely (matters for ATS keyword matching)
- Adjust seniority signal in the title to match the JD (don't use a higher-level title when applying to a lower-level role)
- Note any scope mismatch and flag to the candidate
- Suggest a per-application title variant when worth the effort

**Step E: Build the versatile vs targeted strategy**

Help the candidate plan:
- **Versatile resume**: One title that fits the broadest set of target roles — used for default applications and cold outreach
- **Targeted variants**: Per-role title swaps for high-priority applications, only when the role is worth the customization effort
- **LinkedIn title**: Often matches the versatile resume title, since LinkedIn is many recruiters' first touch

**Output of Pattern 26:**
- The recommended title(s) for the candidate's resume(s)
- A defense rationale for the title (work evidence, market validation)
- A transparency phrasing for recruiter conversations (per Anti-Pattern 15)
- A versatile-vs-targeted decision about whether to maintain multiple resume variants

**Honesty guardrails:**
- Don't suggest a title the candidate cannot defend with concrete work examples
- Don't suggest a title that overstates seniority beyond what bullets support
- Don't suggest a title that hides material aspects of the role (Anti-Pattern 15)
- Always pair title pivots with the transparency-in-recruiter-call practice

**Honest principle:** "Position the title for the role; verify market alignment via current research; disclose the translation in the conversation."

### Pattern 27: Business Context Validation [METHODOLOGY — required throughout]

**Every domain-specific term, framework, regulation, standard, certification, or product name used in a resume must be web-search validated for accuracy before being placed on the resume. Assumptions and training-data recall are not sufficient — they fail systematically on specialized domains.**

This is the most critical guardrail in the entire skill. Domain-specific resumes (healthcare, finance, government, defense, biotech, energy, etc.) live or die by the accuracy of their domain vocabulary. A single misused term — using a spec name where a regulation name belongs, conflating an implementation guide with a program, mixing up versions, getting jurisdictional scope wrong — signals to a domain expert that the candidate doesn't know the field. The resume is then disqualified in the 10-second scan.

**Why this happens (failure mode of LLM-assisted resume writing):**
- LLMs have training-data familiarity with broad concepts but imprecise grasp of niche regulatory/technical distinctions
- "Familiarity" feels like knowledge — the assistant generates plausible-sounding text that's actually wrong
- The assistant doesn't know what it doesn't know, so it doesn't pause to verify
- The candidate may not catch the error if they trust the assistant's output
- Result: domain-specific resumes ship with subtle errors that domain experts immediately spot

**The validation requirement:**

Before placing any of the following on a resume, the assistant MUST web-search to confirm:

1. **Regulations and federal mandates** — official name, scope, deadline, version, agency
   - Example: Is this regulation a final rule or a proposed rule? What's its formal title? What's its effective date? What's its actual scope? (Applies to any industry: CMS rules in healthcare, Basel/Dodd-Frank in finance, NRC rules in nuclear, FAA rules in aviation, etc.)
   - Search: "[regulation citation] final rule" or the exact regulation number

2. **Standards and specifications** — distinguish standards from implementation guides, from frameworks, from versions
   - Example: Is "[term]" a standard, an implementation guide, a working group, a published methodology, or something else? Categories matter: a standard is different from a guidance document is different from a certification framework.
   - Search: "[term] standard" / "[term] implementation guide" / "[term] vs [related term]"

3. **Certifications and credentials** — exact name, current status, issuing body
   - Example: "AWS Solutions Architect Associate" vs "AWS Certified Solutions Architect – Associate" (the latter is correct)

4. **Domain tools, products, platforms** — current name, current version, vendor
   - Example: Has the product been renamed? Acquired? Deprecated?

5. **Industry-specific frameworks and methodologies** — current canonical name and definition
   - Example: Many domain frameworks are easy to mis-categorize. Is "[acronym]" a measure set, an agency, a reporting program, a standards body, or a methodology? The category determines how you describe the candidate's work with it.

6. **Quantitative claims tied to public data** — member counts, transaction volumes, regulatory scope, market size
   - Example: If you say "covering X units across Y regions," does that match the candidate's actual data? Has any underlying figure changed materially?

7. **Org names, role conventions, and hierarchy in target industry** — current title conventions, career-level expectations (overlaps with Pattern 26)

**The mandatory process:**

Before drafting any resume bullet that uses a domain-specific term:

1. **Identify the domain-specific terms** in the bullet (regulations, standards, IGs, frameworks, products, certifications, organizations)
2. **For each one, web-search to confirm:**
   - Exact name and abbreviation
   - Category (is this a regulation? a spec? an IG? a working group?)
   - Scope and applicability
   - Current status (active? deprecated? superseded?)
   - Relationship to other terms in the bullet
3. **Reconcile with candidate's actual data** — does the resume's claim match what the candidate told you? Any quantitative scope claim must equal the candidate's actual count.
4. **Only draft after validation** — never draft first and validate later, since the wrong term will sound plausible and may not get re-examined

**Categories of category-confusion errors this pattern catches:**

Each of the following error types recurs across regulated industries — mis-categorization rather than fabrication. Web search resolves each one quickly.

- **Regulation vs. standard vs. implementation guide:** Treating a federal regulation, an industry-standard specification, and a published implementation guide as if they were parallel "programs." They occupy different layers of a compliance stack and should be described as such.
- **Document vs. consortium vs. methodology:** Calling a published guidance document a "consortium framework" or "methodology" when the document itself is the standard.
- **Classification vs. process artifact:** Mis-categorizing a risk-level classification (e.g., assurance levels, severity tiers) as a "pipeline," "workflow," or other process artifact. Classifications are applied to processes; they are not processes.
- **Unverified quantitative scope:** Stating a count of units, regions, or members without verifying against the candidate's actual data.

**The fix is always the same:** web-search every domain term before placement. Confirm category (regulation? standard? IG? methodology?), confirm scope (what does it cover?), confirm version/status (active? deprecated?), confirm relationship to adjacent terms.

**Categories of business context to validate per industry:**

| Industry | Validate carefully |
|---|---|
| **Financial services** | Regulations (SOX, Dodd-Frank, GLBA, Basel III/IV), standards (FIX, SWIFT, ISO 20022), reporting (CCAR, DFAST), products (specific trading platforms, risk systems) |
| **Government / Defense** | Clearance levels, ATO/RMF frameworks, NIST controls, FedRAMP levels, specific contract vehicles (GWAC, IDIQ), agency-specific acronyms |
| **Aerospace / Aviation** | Certification standards (DO-178C, DO-254, ARP4754A, AS9100), FAA/EASA rules, DAL classifications, ITAR/EAR compliance, NASA Class A/B/C distinctions |
| **Biotech / Pharma** | FDA pathways (510k, PMA, BLA, ANDA), clinical phases (I-IV), GxP frameworks (GMP, GCP, GLP), ICH guidelines |
| **Energy / Utilities** | NERC CIP, FERC orders, ISO/RTO market structures, specific grid frameworks |
| **Healthcare** | Federal regulations (HIPAA + applicable CMS rules), data exchange standards (HL7, FHIR, USCDI versions, X12 EDI), implementation guides published by industry accelerators, reporting programs (HEDIS, MIPS/MACRA, STAR) |
| **Manufacturing / Industrial** | Standards (ISA-95, OPC UA, ISO 9001, ISO 14001), quality methodologies (Six Sigma, Lean, DMAIC), industry-specific certifications |
| **Cloud / DevOps** | Current cloud-vendor service names (these change), CNCF graduation status, current container/orchestration versions |

**Anti-pattern this defeats:** "Plausible-sounding domain language that's actually wrong" — the most insidious failure mode of AI-assisted resume drafting, because it sounds confident and passes superficial review but disqualifies the candidate when a domain expert reads it.

**Honest principle:** "If a term is domain-specific, web-search it before placing it on the resume. Familiarity is not knowledge. Plausibility is not accuracy."

### Pattern 28: Industry and Role Inference with Vocabulary Validation Gate [METHODOLOGY — required at Step 1, runs BEFORE Patterns 26 and 27]

**Before applying any pattern from this skill, the assistant must establish what industry, role family, and functional responsibilities the candidate actually has — and validate that understanding via explicit binary checks. This is a two-pass methodology with a five-check gate. All five checks must pass before pattern application proceeds.**

This pattern exists because **most of the patterns in this skill were extracted from senior-level tech samples**. Applying those patterns blindly to a COBOL developer, a mechanical engineer, a nurse practitioner, a paralegal, or a teacher would produce a resume that sounds wrong to recruiters in those fields. The skill is portable across industries **only if** the assistant first does the work of understanding which industry and role the candidate is in, validates that understanding, and then selects which patterns to apply accordingly.

**The two-pass methodology:**

**Pass 1 — Inference (read what's actually there):**

From the candidate's uploaded resume, conversation context, and any provided JD, infer:

1. **Industry / sector:** What world does this candidate work in? (Healthcare, defense, fintech, manufacturing, energy, biotech, education, legal, retail, hospitality, government, nonprofit, academia, etc.)
2. **Role family:** What kind of work do they do? (Engineering, product management, customer success, operations, sales, marketing, design, research, analyst, executive, individual contributor, people leader, etc.)
3. **Seniority level:** Entry, mid, senior, executive, or C-suite — per the Career Level Positioning Framework above
4. **Functional responsibilities:** What do they actually do day-to-day? Pull this from their resume bullets and any verbal descriptions. Don't accept the title at face value — read the work.
5. **Technical specialty (if applicable):** What specific tech/domain do they specialize in? Identify the specialty by name (e.g., a specific programming language, simulation methodology, interoperability standard, hardware design domain, trading vertical, statistical specialty, engineering discipline).
6. **Target market context:** Where are they applying? (Specific employer, industry tier, geography, remote vs onsite, etc.)

**Document each inference explicitly.** Don't apply patterns silently based on assumed context.

**Pass 2 — Validation (web-search to confirm vocabulary fit):**

For the inferred industry + role + specialty:

1. **Web-search current vocabulary:** What terminology do practitioners in this exact field use today? Search current job postings, industry publications, professional society pages, and authoritative sources.
2. **Web-search title conventions:** What titles describe this work in the target market today? (Feeds Pattern 26 — Title Research.)
3. **Web-search domain frameworks, regulations, certifications, tools:** What does the industry recognize? (Feeds Pattern 27 — Business Context Validation.)
4. **Map candidate's actual work to industry vocabulary:** Does the candidate's described work align with how practitioners describe similar work? Look for high terminology overlap.

**The Inference Validation Gate (binary checklist — all five must pass):**

Before proceeding to apply any pattern from this skill, run the following five binary checks. Each must return YES. A NO on any check is a hard stop.

**Check 1 — Industry confirmed?**
Can the assistant name the candidate's specific industry from the resume alone, without guessing?
- YES: The resume contains industry-specific terminology, employer names, or regulatory/standards references that unambiguously place the candidate in a named industry (e.g., "healthcare," "aerospace defense," "retail banking," "COBOL/mainframe financial services").
- NO: The resume uses only generic IT or corporate vocabulary with no industry anchors. → STOP. Ask: "What industry are you targeting? Your resume doesn't clearly signal one."

**Check 2 — Role family confirmed?**
Can the assistant name the candidate's primary function from the resume work descriptions — independent of their title?
- YES: Two or more role-specific activities (not generic management/leadership activities) are observable in the resume bullets and unambiguously map to a named function family (e.g., Customer Success, Technical Program Management, Software Engineering IC, Product Management).
- NO: All bullets use generic management/leadership vocabulary with no function-specific signals. → STOP. Ask: "What function are you primarily targeting — technical program management, engineering, customer success, product management, or something else? Your bullets don't clearly differentiate."

**Check 3 — Seniority confirmed?**
Do the resume's scope signals (team size, decision authority, budget, geographic reach, org impact) match the inferred seniority level?
- YES: At least two independent scope signals (e.g., team size AND budget size, or geographic reach AND stakeholder level) are consistent with the same Career Level tier from the framework above.
- NO: Scope signals are contradictory (e.g., IC-level bullets but Director-level title, or team sizes that don't match claimed leadership scope). → STOP. Ask: "Your title says [X] but your bullets describe [Y]-level work. Which level are you actually targeting, and do you have evidence to support it?"

**Check 4 — Domain vocabulary present and validated?**
Does the resume contain at least three terms native to the inferred industry/role that the web-search in Pass 2 confirmed are standard practitioner vocabulary?
- YES: Three or more industry-specific terms (not generic terms like "stakeholders," "deliverables," or "project management") appear in the resume AND were confirmed as current practitioner vocabulary by Pass 2 web search.
- NO: The resume uses only generic vocabulary even though the industry was otherwise identified. → Proceed, but flag to the candidate: "Your resume lacks industry-specific vocabulary. Applying Pattern 24 will be critical — the vocabulary signals your domain expertise. Let's identify which terms belong."

**Check 5 — Pattern set determinable?**
Can the assistant explicitly list which patterns from this skill apply and which don't, given the inferences from Checks 1-4?
- YES: Produce the explicit apply/skip list (use the pattern selection decision matrix below) before proceeding. This list is the output of the gate — it is not optional and should not be implicit.
- NO: The candidate's profile is ambiguous enough that the apply/skip list cannot be determined. → STOP. Ask clarifying questions until the list can be determined.

**Gate outcome:**
- All five YES → proceed to Patterns 26 and 27, then apply the explicit pattern set from Check 5.
- Any NO on Checks 1-3 → hard stop, ask clarifying question, re-run Passes 1 and 2.
- NO on Check 4 only → proceed with explicit flag to candidate about vocabulary gap.
- NO on Check 5 → ask clarifying questions until the apply/skip list is determinable.

**Pattern selection decision matrix (applies after Pass 2 validation succeeds):**

Once the industry/role inference is validated, select which patterns from this skill apply to the candidate. The table below shows which patterns activate for common candidate profiles. For any profile not listed, derive selection from the same logic: universal patterns always apply; function-specific patterns apply only when the candidate's function matches; culture-specific patterns apply only when the target employer's culture matches.

| Candidate profile | Apply | Skip |
|---|---|---|
| Tech IC (SWE/SRE/Data Engineer) | Patterns 1, 2, 4A, 5, 6, 7, 8, 10, 11, 12, 16, 18, 21 | Pattern 4B unless target employer has document-heavy writing culture; Pattern 25 (PM-specific) |
| Tech program/product leader | Patterns 1, 2, 3, 4A, 5, 6, 7, 8, 19, 20, 21, 22, 23, 24, 25 (if PM) | Pattern 10 (per-role tech sub-line); Pattern 11 (engineer-specific business attribution) |
| Non-software engineering (mech/civil/electrical/aerospace) | Patterns 2, 4A, 5, 6, 7, 8, 21, plus Pattern 16 adapted for PE licensure / professional society credentials; Pattern 24 adapted for industry vocabulary | Pattern 4B (tech writing culture); Patterns 10, 11, 12 (tech-IC-specific); Pattern 25 (PM-specific) |
| Legacy software / mainframe | Universal patterns + Pattern 10 (tech sub-line for legacy stack); Pattern 24 pivoted for mainframe vocabulary | Pattern 4B unless target culture matches; Pattern 15 culture-vocabulary unless target employer is researched |
| Clinical / regulated-industry IC | Universal patterns; Pattern 24 for domain vocabulary; Pattern 16 adapted for board certifications | Pattern 4B (writing culture); Pattern 11 (engineer business attribution); Pattern 25 (PM-specific) |
| Match gate failed (any binary check returns NO on Checks 1-3) | NONE — do not proceed. Ask clarifying questions and re-run Passes 1 and 2 with new information. |  |

**Why this pattern is critical for skill portability:**

The skill's patterns were extracted from a limited sample biased toward senior-level tech. Without Pattern 28, an LLM running this skill on a COBOL developer's resume might blindly apply narrative-variant bullets meant for document-heavy tech cultures, or PM outcome-anchor structures — producing a resume that's literally wrong for the candidate's market.

**With Pattern 28**, the LLM:
1. First reads what's actually there
2. Validates the inference against current industry vocabulary
3. Only then selects patterns that actually fit
4. Stops and asks if the match isn't strong enough

This makes the skill **genuinely portable across industries and functions**, not just tech-flavored.

**Relationship to other methodology patterns:**

- **Pattern 28 runs first** at Step 1 (Strategic Positioning).
- **Pattern 26 (Title Research)** runs second, scoped by Pattern 28's inferences.
- **Pattern 27 (Business Context Validation)** runs throughout, scoped by Pattern 28's industry/specialty.
- All three together form the **upstream methodology guardrails** that protect against the most common AI-assisted resume failure modes.

**Honest principle:** "Don't apply patterns until you've established who the candidate is and validated that understanding against the world they're actually applying into. Tech-resume tactics are not universally applicable; the methodology is."

### Pattern 29: Dual-Positioning via Resume Variants for Function-Adjacent Role Families [CONFIRMED]

**Maintain a small stable of resume variants (typically 2–3) when a candidate's experience legitimately supports adjacent but distinct target role families.** Distinct from Pattern 26's per-JD title customization: Pattern 26 tunes a single resume per application; Pattern 29 produces *structurally different resumes* aimed at different role families the candidate could credibly land.

**When to apply:**
- The candidate's actual work supports 2+ adjacent role framings (e.g., Product Manager *and* Platform/Infrastructure Leader; Engineering Manager *and* Director of Engineering; CSM Leader *and* Strategy/Operations Leader)
- The target role families have meaningfully different reader populations (different recruiters, different hiring managers, different stakeholder vocabulary)
- The candidate has been in role long enough that one resume can't optimize for both audiences without diluting either

**The variant unit is the role family, not the company:**
A "Product PM variant" and an "Infrastructure-Leader variant" are two role-family variants. Five different variants for five different companies in the same role family is Pattern 26, not Pattern 29.

**Structure of a variant pair:**
- **Variant A** — leads with one identity (e.g., PM craft: strategy, GTM, P&L, customer journeys, success metrics)
- **Variant B** — leads with the adjacent identity (e.g., infrastructure/platform leader: sovereign cloud, edge orchestration, regulated customers, analyst influence)
- Both are honest representations of the same underlying work; neither claims experience the other doesn't
- Shared bullets are reframed (see Pattern 31), not duplicated

**Skip when:**
- The candidate's work only supports one credible role framing — generating a second variant would force overreach
- The candidate doesn't have time to maintain variants (a stale variant is worse than no variant)
- The target roles are within the same family (use Pattern 26's per-JD tuning instead)

**Best for:** Senior/Principal/Director-level candidates with cross-domain scope, especially in platform, infrastructure, product, and program-management functions where role-family boundaries are blurry.

**Honesty check:** The same person, same job history, same scope numbers must appear in both variants. The variation is in *framing*, not *facts*. If a hiring manager from Role Family A interviewed the candidate using Variant A, then a hiring manager from Role Family B interviewed the same candidate using Variant B, both should recognize the same person — just emphasized for their respective lens.

**Related:** [[pattern-30-invariant-variant-split]] (mechanic), [[pattern-31-lead-verb-reframing]] (technique), [[anti-pattern-19-same-bullet-same-verb-across-variants]] (guardrail).

### Pattern 30: Identity-Preserving Variation — The Invariant/Variant Split [CONFIRMED]

**The operational recipe that makes Pattern 29 (Dual-Positioning) deployable without rewriting from scratch.** Defines what stays constant across variant resumes vs. what shifts — preserving identity verifiability while enabling audience-specific framing.

**Invariants (kept identical across all variants):**
- Header block: name, location, contact, LinkedIn
- Title line — the candidate's actual current/most-recent title (the *headline* may vary; the role title at each employer does not)
- Employer names, role titles, date ranges across all positions
- Patents, publications, certifications, education
- Scope/scale numbers within shared bullets (team size, $ figures, %, headcounts) — facts don't change between audiences
- Signature voice/tone line if used (Pattern 3 — e.g., a closing identity sentence in the summary)

**Variants (deliberately reframed per audience):**
- **Professional Summary** — almost entirely rewritten per variant; different leading identity, different vocabulary tier, different stakeholder emphasis
- **Core Competencies** — typically 40–60% overlap, with 30–50% swapped for audience-specific terms (see Pattern 24 vocabulary tables)
- **Lead bullet in current role** — reframed via Pattern 31 (lead-verb reframing)
- **Bullet emphasis and ordering within shared roles** — bullets relevant to Variant A's audience are kept and may lead; bullets less relevant may be compressed or moved down
- **Optional bullets** — some bullets appear in only one variant (e.g., the Infra variant in the source pair includes an "executive briefings and analyst conversations… regulated-edge scenarios" bullet that the Product variant omits — that audience cares; the other doesn't need it)
- **Modifier choices within shared bullets** — adjectives, verb tense, and rhetorical framing shift even when the underlying claim is identical

**The 60% rule (heuristic):**
At least ~60% of the textual content should be shared across variants. If less than 60% is shared, the variants are diverging too far — at least one is making claims that aren't backed by the same evidence base. If more than ~85% is shared, the variants aren't doing meaningful positioning work and the second resume isn't earning its maintenance cost.

**Why this works:**
- A reference check or background check surfaces the same employer/title/dates regardless of which variant was submitted — invariants protect verifiability
- Scope numbers stay defensible — the candidate can't tell one audience "$10M P&L" and another "$50M P&L" for the same role
- Variant framing is genuinely earned by reframing existing work, not inventing new work
- Maintenance cost stays manageable — most edits are surgical (summary + competencies + lead bullets), not wholesale

**Honesty check:** Before treating two variants as "ready to send," verify the invariant list above is *bit-for-bit identical* across both. Any drift in an invariant field (employer, dates, scope numbers, credentials) is a credibility risk if both variants ever land in front of the same recruiter or background-check team.

**Related:** [[pattern-29-dual-positioning-variants]] (when to deploy), [[pattern-31-lead-verb-reframing]] (variant technique).

### Pattern 31: Lead-Verb Reframing of Shared Bullets [CONFIRMED]

**Same underlying work, different lead verb, to signal different professional identity to different reader populations.** The bullet's facts, numbers, and scope stay constant; the opening verb shifts to match the variant resume's audience (see Pattern 29).

**Formula:**
`[Variant-specific lead verb] [same shared object] [same shared scope/numbers] [optionally reframed modifier phrase]`

**Verb cluster examples by identity:**

| Identity being signaled | Lead-verb cluster |
|---|---|
| **Product-craft / Steward** | Owned, Defined, Directed, Drove, Managed, Led (the strategy/roadmap/process) |
| **Architect / Originator** | Created, Designed, Built, Architected, Established, Founded |
| **Operator / Executor** | Coordinated, Standardized, Codified, Operationalized, Scaled, Executed |
| **Influencer / Strategist** | Aligned, Influenced, Shaped, Positioned, Negotiated, Persuaded |
| **People Leader** | Led and developed, Groomed, Coached, Hired, Mentored, Grew |

**Worked example:**
A bullet describing the same accountability — leading a unified platform strategy — can open with "**Owned** the product strategy for [platform]…" (steward framing for a Product audience) or "**Created** [platform]'s unified [domain] strategy…" (architect framing for an Infrastructure/Platform-leader audience). Same accountability; different identity signaled.

**When to apply:**
- Building variant resumes per Pattern 29 — Pattern 31 is the per-bullet mechanic
- A single bullet legitimately reads two ways depending on the lead verb (the work genuinely was both stewarded *and* originated, both led *and* coordinated)
- The reader population for each variant has meaningfully different scan vocabulary

**Skip when:**
- The lead verb shift would misrepresent the work (e.g., using "Created" for work the candidate inherited and only managed)
- The candidate didn't do both roles within the bullet — pick the most accurate verb and don't reframe
- The bullet's numbers and object alone carry the signal — the verb shift would be cosmetic noise

**Honesty check:** Both verb choices must be defensible in interview. If asked "did you *create* this strategy or *own* it once it existed?", the candidate should be able to answer specifically. The variant lead verb chosen for each audience should be the verb the candidate would naturally use when describing the work to that audience in person.

**Anti-pattern reminder:** See [[anti-pattern-19-same-bullet-same-verb-across-variants]] for the failure mode where variant resumes are built but the lead verbs aren't actually reframed — the variants then signal the same identity to both audiences and don't earn their maintenance cost.

### Pattern 32: Analyst-Influence Bullets as Senior-Platform Credibility Markers [CONFIRMED]

**A specific subtype of Pattern 16 (External Credibility Markers) for senior/principal/director-level candidates in platform, infrastructure, or product roles at enterprise software employers — surfacing direct engagement with industry analyst firms (see Appendix A.3 for the canonical list, including Gartner, Forrester, IDC, and vertical-specialty analysts) as a high-leverage credibility signal.**

**Why this works:**
- Analyst engagement is a *senior-only* signal — IC engineers and mid-level PMs rarely drive analyst conversations; the fact that the candidate did is itself a seniority marker
- For platform/enterprise/B2B products, analyst influence directly affects buyer behavior and competitive positioning — a candidate who shaped a top-tier analyst-report placement (see Appendix A.4 — *Analyst Report Brand Names*) has demonstrably moved a needle that matters to enterprise GTM
- Recognizable analyst-firm names act as Pattern 9 (specific company identifiers) — they make the bullet scannable and high-signal in a 10-second recruiter pass (choose the firm and report name appropriate to the candidate's actual engagement; use Appendix A.3 and A.4)
- Analyst-influence bullets are difficult to fabricate; they are easily verified by anyone who attends analyst events or follows the named report

**Formula:**
`[Verb: Represented / Authored / Delivered / Shaped / Influenced] [audience: analysts / named firm from Appendix A.3 / industry analysts] [activity: conversations / narratives / briefings / events] [outcome: how the market understood X / contributing to Y leadership position in Z named report from Appendix A.4 / strengthening positioning in W report]`

**Two well-formed shapes:**
- **Direct-engagement shape:** `Represented [product/platform] in analyst conversations and customer-facing events, influencing how the market understood [employer]'s [strategic positioning]`
- **Outcome-attribution shape:** `Played a key role in shaping how analysts viewed [product], contributing to [employer]'s leadership position in the [specific named report — see Appendix A.4]`

**Choosing the right analyst firm and report for the bullet:**
- Match the firm to the candidate's actual engagement history — never invent
- Match the firm to the target market: generalist IT analysts (Gartner, Forrester, IDC) carry weight broadly; vertical-specialty analysts (KLAS in healthcare IT, Celent in financial services) carry more weight inside their vertical (see Appendix A.3)
- Match the report format to what the firm actually publishes for the candidate's category — a "Magic Quadrant" reference must correspond to an actual Gartner MQ for that category; a "Wave" reference must correspond to an actual Forrester Wave (apply Pattern 27 to validate)

**Best for:**
- Senior, Principal, GPM, Director, VP-level resumes in enterprise software, platform, infrastructure, or B2B product roles
- Candidates whose work has measurable analyst-report impact (mentioned by name, contributed to leader/visionary placement, influenced a category definition)
- Variant resumes (Pattern 29) targeting senior-platform role families — analyst influence is a high-leverage signal that often belongs in the Infrastructure/Platform variant even if compressed in the Product-craft variant

**Skip when:**
- The candidate's analyst engagement was indirect (attended an event vs. drove the conversation) — overclaiming analyst influence is detectable by any reader who has been an analyst, briefed analysts, or read the actual reports
- The target role is at a startup or non-enterprise employer where analyst coverage isn't part of the GTM motion
- The candidate is below senior level — analyst-influence bullets on a mid-level resume read as overreach

**Honesty check:** "Direct engagement" means the candidate personally briefed analysts, authored the narrative used in briefings, or owned the analyst relationship — not that someone on their team did it. If pressed in interview, the candidate should be able to name the specific analyst firm, the specific analyst (if appropriate), the cadence of engagement, and the specific report or placement the work influenced.

**Related:** [[pattern-16-external-credibility-markers]] (parent pattern), [[pattern-9-specific-company-identifiers]] (named analyst firms as scannable signals), [[pattern-24-domain-functional-vocabulary]] (analyst-engagement vocabulary as senior-platform domain signal).

### Pattern 33: Multiplier-Ceil Rule for Growth Metrics [CONFIRMED]

**Convert every growth metric to multiplier form (Nx) and ceil to the next clean number on the resume; the precise underlying figure gets discussed in the recruiter or interview conversation.** Source-validated by feedback from many hiring managers across multiple resumes.

**The rule:**

1. **Convert to multiplier form whenever possible.** "2x revenue growth" reads more cleanly than "200% growth"; "3x portfolio expansion" reads more cleanly than "$800K → $1.95M (244%)."
2. **Ceil to the next integer** when the multiplier is ≥1.5x. So 2.44x → 3x. 3.12x → 4x. 1.7x → 2x.
3. **Ceil to 1.5x** when the multiplier is between 1.0x and 1.5x. So 112% NRR → 1.5x NRR. 1.3x → 1.5x.
4. **Applies to all growth claims:** revenue/ARR growth, portfolio expansion, retention multipliers, throughput improvements, headcount growth, percentage improvements that can be re-expressed as multipliers.
5. **Does NOT apply to static scope figures** (current ARR, current headcount, current member count, current portfolio size). Those stay precise — they're scale signals, not growth claims, and a recruiter cross-checking against LinkedIn would catch any rounding.
6. **The precise underlying figure stays defensible in conversation.** Recruiter asks "how much was the growth exactly?" — the candidate answers with the precise number ("$800K to $1.95M, so 2.44x over three renewal cycles") and the conversation continues. The resume just doesn't display the precise figure.

**Why this works:**
- **Scannability:** "3x portfolio expansion" is parsed in <1 second; "2.44x portfolio expansion" forces a half-second of mental math during a 10-second scan. The clean number lands harder.
- **Recruiter preference:** Hiring managers report that clean multipliers read as confident and senior; precise-decimal multipliers read as junior-coded (someone proudly reporting their exact spreadsheet output rather than a leader summarizing scope).
- **Conversation hook:** The clean number invites the follow-up question. "Tell me about the 3x growth — what drove it?" becomes the candidate's opening to walk through the substance. Precise decimals close that loop prematurely.
- **No overclaim risk when the underlying is defensible.** Ceiling 2.44x to 3x is not exaggeration — it's a stylistic compression that the candidate can immediately reconcile when asked. The substance is unchanged.

**Formula:**

| Underlying calculated value | Resume display |
|---|---|
| 1.0x to 1.5x | "1.5x" |
| 1.51x to 2.0x | "2x" |
| 2.01x to 3.0x | "3x" |
| 3.01x to 4.0x | "4x" |
| Percentages ≥100% that represent growth (not retention rates of <100%) | Convert to multiplier and ceil per above |
| Percentage improvements <100% (e.g., 30% efficiency gain) | Stay as percentage; ceil to nearest 5% only if presentation is cluttered |

**Worked examples:**

| Calculated | Resume displays |
|---|---|
| Anchor account grew $800K to $1.95M (2.44x) | "3x growth" |
| Portfolio scaled $3.7M to $7.35M peak (1.99x) | "2x portfolio scale-up" |
| Throughput improved 312% | "4x throughput improvement" |
| Net Revenue Retention 112% | "1.5x NRR" *(but note: NRR is industry-standard as a %; check audience before converting)* |
| Implementation timeline reduced from 8-12 weeks to 2 weeks (5x faster) | "5x faster onboarding" |
| Headcount grew from 5 to 13 over tenure (2.6x) | "3x team growth" |

**When to skip the rule:**
- **Industry-standard metric formats.** NRR is conventionally expressed as a percentage in SaaS/CSM circles (e.g., "112% NRR"); converting to "1.5x NRR" may confuse a CSM-specialist recruiter. Apply Pattern 28 to gauge the target audience's vocabulary expectations. When in doubt, keep the industry-standard format.
- **Regulated quantitative claims.** SLA compliance ("99.99% uptime"), audit pass rates ("6 of 6 audits passed"), and compliance percentages where the precise figure is the credibility signal — keep precise.
- **Static scale figures.** Current ARR, current headcount, current portfolio size — these are facts, not growth claims. Stay precise.
- **The growth happened over a window that needs the precise figure to be credible.** "$800K to $1.95M in a single quarter" is more impressive at the precision than rounded; "$800K to $1.95M across 3 renewal cycles" reads cleanly as "3x." Check whether the timeframe context demands precision.

**Honesty check:** The ceil is a presentation convention, not inflation. The candidate must be able to state the precise underlying figure on demand. If asked "is that exactly 3x?", the honest answer is "2.44x rounded — $800K to $1.95M across three renewal cycles" — which then becomes the substance of the conversation. Never use this rule to disguise weak underlying growth; if the calculated multiplier is 1.1x, displaying "1.5x" overstates the work.

**Combines with:** [[pattern-2-numbers-do-the-persuasion]] (clean multipliers are a number-density tactic), [[pattern-21-bold-theme-prefix-in-bullets]] (clean multipliers fit the scannable-prefix structure), [[pattern-25-pm-outcome-anchor-bullet-structure]] (the headline $ anchor at the end of PM bullets often benefits from multiplier framing).

**Conflicts with:** None directly. Watch for industry-vocabulary collisions (the NRR example above) and resolve via Pattern 28's audience inference.

### Pattern 34: Job-Function Title Selection [CONFIRMED]

**The resume title reflects the target role's job function, not the candidate's internal employer-assigned title. Internal title disclosure is a recruiter-conversation practice, not a document practice.** Source-validated by feedback from many hiring managers across multiple resumes.

This is the positive principle that supersedes the older "show internal title in italics underneath" convention. It governs how titles work on the resume document itself; Pattern 26 (Title Research) governs how to *choose* the job-function title.

**The rule:**

1. **The resume title is the target role's job function** — the title that describes the work the candidate does and the role they're applying into, expressed in the market's current vocabulary (see Pattern 26 for selection methodology).
2. **The candidate's internal employer-assigned title does not appear on the resume.** No parenthetical, no italicized "(Internal title: X)" line, no footnote, no asterisk. The resume shows one title per role.
3. **If asked about the internal title in a recruiter or hiring-manager conversation, answer truthfully** — but do not volunteer the information unsolicited. The resume's job is to position for the role; the conversation handles any title-mapping nuance if it comes up.
4. **The internal title is documented elsewhere** — LinkedIn (which can also mirror the job-function title), references, background-check disclosures, employment-verification records. The information is not hidden; it's just not the resume's job to surface it.

**Why this works (and why the older "italicized internal title" convention was wrong):**

- **Hiring managers don't care about the internal title.** The internal title reflects how an employer's leveling chart happens to label the work — not the work itself, and not the market's vocabulary for it. A hiring manager evaluating a candidate for a "Lead TPM" role wants to see "Lead TPM" — they're matching against their own job description and their own leveling chart. The internal-title disclosure adds visual noise without adding information the hiring manager will act on.
- **The parenthetical line splits the recruiter's scan.** The pipe-separated headline (Pattern 1) and the 10-second scan (Step 2) depend on visual density and clarity. A "(Internal title: X)" line under the title forces a second pass and makes the candidate look as though they're pre-defending against a question that almost never gets asked.
- **The italicized internal-title disclosure reads as anxiety, not transparency.** Candidates who volunteer the internal title on the document look as though they're worried the hiring manager might catch them. Confident senior candidates pick the right title for the role and trust the conversation to handle edge cases.
- **Background and reference checks already handle verification.** The system that catches title fraud isn't the resume document — it's the structured background-check process at offer stage, plus reference calls. Those processes surface the internal title regardless of what the resume said. The resume doesn't need to preempt them.

**Formula (per-role header format):**

```
[Employer]  |  [Job-function title that matches the target role]  |  [Date range]
```

That's the entire role header. No parenthetical line. No italic disclosure. No asterisk.

**Worked examples:**

| Internal title (per employer) | Target role family | Resume displays |
|---|---|---|
| "Senior TPM — Data, Interoperability & Customer Success" | Lead Technical Program Manager (federal compliance) | "Lead Technical Program Manager — Healthcare Interoperability & Federal Compliance" |
| "Senior TPM — Data, Interoperability & Customer Success" | Principal Data Platform Architect | "Principal Data Platform Architect" |
| "Senior TPM — Data, Interoperability & Customer Success" | Senior CSM (Enterprise) | "Senior Customer Success Manager (Enterprise Healthcare)" |
| "Technical Implementation Manager" | Customer Success Manager (Enterprise) | "Senior Customer Success Manager (Enterprise)" |
| "Engineering Manager II" | Director of Engineering | "Director of Engineering" *(only if scope evidence supports it; see Pattern 26)* |
| "Member of Technical Staff" | Principal Software Engineer | "Principal Software Engineer" *(only if scope evidence supports it)* |

**Recruiter-conversation script (only if asked):**

If the recruiter asks about the internal title, the candidate answers truthfully — briefly — and moves the conversation forward:

> "My title at [employer] is X. I've positioned this resume as Y because the role-function maps to Y in the market and matches what you're hiring for. Happy to walk through the work that backs it."

That's the entire disclosure. No apology, no over-explanation. The work backs the title; the conversation moves on.

**When to skip this rule (rare exceptions):**

- **Recently-renamed roles where the old title carries weight.** If the candidate just got promoted and the old title was widely recognized in their market while the new title is internal-only, leading with the recognized title and noting "newly promoted to [internal name]" can be appropriate. Apply Pattern 26 to confirm.
- **Roles where the internal title IS the job-function title.** When the employer's title happens to match exactly what the market calls the work, no pivot is needed and no disclosure question arises. The rule is moot.
- **Government / military / academic resumes with formal designations.** Some sectors require exact official titles on the document by convention (federal civilian GS-grade titles, military ranks, academic ranks). The rule about NOT showing internal titles still applies — but the "internal title" in these contexts often IS the only legitimate title, so there's nothing to pivot from.

**Honesty check:** The job-function title must be defensible against the candidate's actual work. Pattern 26 governs the selection — if the candidate can't map ≥3 major responsibilities of the target role to evidence in their resume bullets, the pivot is overreach (see Anti-Pattern 15 for the failure mode). Pattern 34 governs the display — once a defensible title is chosen, show only that title.

**Relationship to Anti-Pattern 15:** Anti-Pattern 15 flags the failure mode (pivoting without recruiter-conversation transparency, or pivoting to a title the work doesn't support). Pattern 34 is the corresponding positive guidance: how to display the title once chosen. Earlier guidance to "show internal title in italics underneath" has been retracted — it was reading as anxiety on the document and adding visual noise that hurt the 10-second scan. The transparency that Anti-Pattern 15 calls for happens in the conversation, not on the document.

**Combines with:** [[pattern-26-title-research-and-selection-methodology]] (governs title selection), [[pattern-29-dual-positioning-via-resume-variants]] (each variant gets its own job-function title per Pattern 34), [[pattern-30-identity-preserving-variation]] (the display title is a variant field; the candidate's actual work history stays invariant).

**Conflicts with:** Older "italicized internal-title disclosure" guidance previously in Anti-Pattern 15 — Pattern 34 supersedes that prescription.

### Pattern 35: AI Highlight Per Job Function [OBSERVED]

**Every resume in the 2026 hiring market must surface the candidate's AI work, AND the framing of that AI work must match the target job function's evaluation criteria. The same underlying AI work gets framed differently for an architect, a program manager, a customer-success leader, or any other role family. Generic "AI-Orchestration" boilerplate at the bottom of the resume is not sufficient.**

Field observation across the 2026 hiring market: there is almost no job posting at any seniority level in tech, healthcare-tech, fintech, govtech, or adjacent markets that does not surface AI capability in either the job description, the company's strategic narrative, or both. Hiring managers actively look for evidence the candidate has shipped AI work or driven AI adoption — not just listed AI tools on the skills line.

**The rule:**

1. **AI presence is mandatory on every variant.** If the candidate has done any AI work — shipped, architected, championed, automated, evaluated, or operationalized — it appears in the summary AND in the body of every resume variant.
2. **AI framing matches the target function's evaluation lens.** The same MCP-integration project reads differently to an architect-track hiring manager (architecture decision), a TPM-track hiring manager (program-delivery decision), and a CSM-track hiring manager (customer-experience decision). The resume reframes the work per audience (see Pattern 31 for the reframing mechanic).
3. **If the candidate has no AI work to honestly surface, the gap is the problem, not the resume.** Pattern 35 doesn't authorize inventing AI work. If the only AI exposure is "used ChatGPT to draft documents," that's not Pattern-35-surfaceable content — that's a gap to close before the next round of applications. Apply Pattern 19 (Worksheet Method) to identify whether real AI work is missing from the resume vs. genuinely absent from the career.
4. **Refactoring is expected.** Adding AI to a resume that doesn't currently lead with it often requires summary rewrites, competency-block reordering, new dedicated bullets, and sometimes lifting AI work from a small mention buried at the bottom to a primary bullet at the top. Treat it as a Pattern 31 lead-verb reframing exercise, not a one-line addition.

**Framing by function — worked examples on the same underlying work:**

Underlying work: candidate architected a HIPAA-eligible AI integration pattern (Citrix → Claude via AWS Bedrock + TrueFoundry AI Gateway), shipped JIRA MCP server adoption across the org, built an automated Python+Snowflake+Power BI reporting pipeline.

| Function | Lead verb cluster | Framing focus | Sample lead bullet |
|---|---|---|---|
| **Solutions/Platform Architect** | Architected, Designed, Established | Architecture decisions, reference patterns, infrastructure design | "Architected a HIPAA-eligible AI reference architecture (Citrix → Claude via AWS Bedrock, governed via TrueFoundry AI Gateway) enabling production-pattern GenAI workflows in regulated PHI environments." |
| **Technical Program Manager** | Drove, Orchestrated, Sequenced, Coordinated | Cross-functional rollout, governance navigation, program-execution scope | "Drove enterprise rollout of HIPAA-eligible AI architecture — coordinating security, compliance, IT, and AWS infrastructure teams from concept through working test deployment in PHI-constrained environments." |
| **Customer Success / Account Leader** | Eliminated, Reduced (friction), Improved, Accelerated | Customer-facing outcome, friction reduction, renewal-cycle impact | "Shipped AI-driven delivery automation (JIRA MCP, automated reporting pipelines) eliminating 3–4 recurring client questions per week and ~4 hours of weekly ad-hoc reporting effort — directly improving customer experience and reducing renewal-cycle friction." |
| **Engineering Manager** | Built, Shipped, Led adoption of | Engineering throughput, team capability, technical-debt reduction | "Led team adoption of MCP-based AI integration patterns, eliminating ~4 hours/week of manual reporting effort across the engineering org." |
| **Sales / Pre-Sales** | Demonstrated, Positioned, Closed with | Deal influence, customer credibility, competitive differentiation | "Positioned and demonstrated HIPAA-eligible AI architecture in pre-sales engagements, accelerating customer adoption decisions on AI-augmented workflows." |
| **Data Scientist / ML Engineer** | Operationalized, Productionized, Tuned, Evaluated | Model behavior, eval rigor, production characteristics | "Operationalized Claude-based workflows via AWS Bedrock with TrueFoundry governance, designing the prompt/response audit pipeline for compliance-traceable inference." |

**Where AI should appear in each variant (recommended placements):**

- **Summary**: At least one pipe segment (Pattern 1) or one sentence (Pattern 23) must surface AI work. Generic "AI orchestration" mention in the summary is not enough — name the specific platform/pattern/outcome.
- **Core Competencies**: At least one competency block that names specific AI tools and patterns the candidate has actually used (MCP, AWS Bedrock, Azure OpenAI, Vertex AI, specific LLM providers, AI Gateway tooling, RAG patterns, agent frameworks, etc. — validated per Pattern 27).
- **Experience bullets**: At least one bullet group that frames AI work for the target audience per the table above. For Architect/TPM variants, this is typically one of the top three bullet groups; for CSM/Sales variants, it is typically positioned alongside customer-outcome content.

**Anti-patterns this pattern guards against:**
- **Buried AI** — listing "AWS Bedrock" in a stack-line on page 2 when the candidate actually shipped a Bedrock-based production pattern. The mention is there but the work is invisible.
- **Generic AI boilerplate** — repeating the same "AI Orchestration & Automation" competency block verbatim across all variants without reframing the actual work for each audience.
- **Fabricated AI** — claiming AI capabilities or projects the candidate has not actually done. Hiring managers probe AI claims in technical screens; fabrication fails immediately. See Pattern 27 honesty guardrails.
- **AI-as-tool-only** — listing AI tools without describing the work done with them. "Claude, AWS Bedrock, MCP" is a tool inventory; "shipped MCP integration that eliminated X hours/week" is evidence.

**When to skip this rule (rare exceptions):**
- The candidate genuinely has no AI work and the target role explicitly does not value AI capability (rare in 2026; verify via Pattern 28 before assuming).
- The target role is in a regulated function where AI claims invite compliance scrutiny that would slow the candidate's selection (some legal, certain medical, certain defense roles). Even here, the candidate should have an honest answer for "tell me about your AI exposure" — Pattern 35 just relaxes the visual prominence on the resume itself.

**Honesty check:** Every AI bullet must back up to defensible work the candidate can walk through in detail in an interview. The architecture diagram exists, the project shipped, the customer outcome happened. Pattern 35 is about *framing* the work for different audiences (see Pattern 31), not inventing AI experience.

**Combines with:** [[pattern-29-dual-positioning-via-resume-variants]] (each variant gets its own AI framing), [[pattern-30-identity-preserving-variation]] (the underlying AI work is invariant across variants; the framing is variant), [[pattern-31-lead-verb-reframing-of-shared-bullets]] (the mechanic for reframing the same AI work per audience), [[pattern-24-domain-functional-vocabulary]] (AI vocabulary is currently being standardized; use Pattern 27 to validate the specific terms in use at the target employer).

**Conflicts with:** None directly. Watch for Anti-Pattern 13 (Buzzword Replacement of Specifics) — vague AI language ("AI-powered solutions," "leveraging machine learning") signals weakness rather than capability. Always name the specific platform, pattern, and outcome.

### Pattern 36: Cross-Industry Dejargonization [OBSERVED]

**Translate domain-specific terminology into industry-agnostic language when the candidate is targeting roles outside their current industry — while preserving scope numbers, AI tooling, and cross-industry credentials unchanged. Keep the domain-specific terms accessible in one labeled "Regulated-Industry" context line so in-domain readers can still find them.**

Distinct from Pattern 29 (Dual-Positioning for Function-Adjacent Role Families) — that pattern is "same person, different role family." Pattern 36 is "**same person, same role family, different industry audience**." A TPM applying to TPM roles across industries needs their TPM work to read for an out-of-healthcare recruiter without losing depth for an in-healthcare recruiter who reaches the document.

**When to apply:**
- Candidate is applying to roles in a different industry than their current one (healthcare-tech IC → consumer-tech, fintech → defense, energy → retail, etc.)
- The target recruiter, hiring manager, and ATS will not recognize the candidate's industry-specific terminology
- The candidate's work is genuinely transferable but reads as opaque without translation
- The candidate is maintaining a parallel in-industry variant — Pattern 36 builds the cross-industry counterpart

**The translation move:**

Replace domain-specific terms with industry-agnostic equivalents while preserving the underlying claim. The scope numbers, dollar figures, and quantified outcomes stay precise per Pattern 33; only the *vocabulary* shifts.

**Translation rules (illustrative — healthcare-IT to general):**

| Domain-specific (in-industry) | Industry-agnostic (cross-industry) |
|---|---|
| "health plan members" | "patients" or "customers" |
| "payer" / "payer client" | "insurance" / "insurance client" |
| "CMS audits + state Medicaid audits" | "regulatory audits" |
| "MA Plan Finder HPMS submission" | "Medicare submission" |
| "CRD/DTR/PAS endpoints" | "standards-based API endpoints" |
| "HL7 Da Vinci reference architecture" | (moved to context parenthetical) |
| "payer-to-payer data exchange" | "insurer-to-insurer data exchange" |
| "PHI environments" | "sensitive data environments" |
| "GovCloud / data-residency-constrained Medicaid" | "government cloud / data-residency-constrained government programs" |
| "100M+ claims" | "100M+ records" |
| "clinical and claims data integration" | "data integration" |
| "EHR systems" | (moved to Healthcare Domain context parenthetical) |
| "FWA detection" | "fraud, waste & abuse detection" |
| "federal mandate delivery" | "regulatory deadline delivery" |
| "state Medicaid deployments" | "state government deployments" |

The translation principle generalizes: identify the domain-specific noun, find the closest industry-agnostic noun that preserves the underlying claim, and substitute. The same principle applies to any industry-pair (finance: "FIX/SWIFT messages" → "trading messages"; defense: "ATO/RMF" → "federal security accreditation"; energy: "NERC CIP" → "grid security compliance").

**What NEVER gets translated (preserve as-is):**

1. **Scope and financial numbers** — $7.35M ARR stays $7.35M; 2.2M+ population scope stays 2.2M+; 99.99% uptime stays 99.99%. The translation is vocabulary, not figures.
2. **Cross-industry-recognized credentials and tools** — AWS Bedrock, Snowflake, Python, Power BI, Kubernetes, MCP, FHIR (when surfaced as an API standard, not as a healthcare-specific marker) — these are universal tech-stack signals.
3. **AI tooling and frameworks** — 2026 cross-industry signal; AI vocabulary stays exactly as in the in-domain variant per Pattern 35.
4. **Universal compliance frameworks** — SOC 2, ISO 27001, GDPR — recognized across industries.
5. **Pattern 21 bold theme prefixes** — translate the body of the bullet, not the prefix when the prefix is already industry-agnostic. ("Enterprise Portfolio Ownership & Growth" stays; "Federal Compliance Program Delivery (CMS-9115-F)" becomes "Federal Compliance Program Delivery" with the regulation citation in the body.)

**The context-parenthetical technique:**

Don't strip domain-specific terms entirely — surface them in one dedicated competency block as parenthetical context so an in-domain reader who reaches the resume can still find the industry-specific credibility signals. This is the elegant move that makes a single resume work across both audiences.

**Example:** In the "Regulated-Industry Delivery" competency block of the dejargonized variant:
```
Regulated-Industry Delivery: Federal Compliance Mandates · Standards-Based Integration · Data Privacy & Security (HIPAA, PHI) · Audit Readiness · Government Cloud (AWS GovCloud) — healthcare context: CMS-9115-F, CMS-0057-F, USCDI v3, HL7 Da Vinci (CRD, DTR, PAS), FHIR, EDI X12
```

The lead text is industry-agnostic ("Federal Compliance Mandates," "Standards-Based Integration"); the em-dash sets off the healthcare-specific anchors as supplementary context. An out-of-healthcare recruiter scans past the em-dash; an in-healthcare recruiter reads the parenthetical and recognizes the depth.

**Apply to:**
- Title (drop function-narrowing suffixes that reference industry-specific role families)
- Summary pipes (translate the audience-narrowing terms; keep the financial and scope figures)
- Competency block bodies (translate prose; use context-parenthetical for domain credentials)
- Experience bullets (translate domain nouns inline; keep numbers and AI vocabulary unchanged)
- Modules / methodologies described in the time-to-value block or similar lists (collapse domain-specific module names into generic categories: "core data integration," "advanced analytics," "risk-scoring modules")

**Skip when:**
- Candidate is applying within their current industry — Pattern 36 destroys the in-domain signal density and disqualifies vs. an in-domain candidate who kept the specifics
- The target role explicitly requires domain expertise the dejargonization removes — if a healthcare-IT product company is hiring a TPM specifically because they need someone who has shipped CMS-9115-F, dejargonizing the CMS-9115-F mention is self-defeating
- The candidate has only one industry of experience and is applying broadly without a specific cross-industry target — apply Pattern 26 first to confirm the target industry; Pattern 36 needs an audience

**Honesty check:** Dejargonization is translation, not reduction. The candidate must still be able to describe the underlying domain-specific work in interview detail. If asked "what's CMS-9115-F?" the candidate answers with the spec; if asked "what does 'patients' mean here?" the candidate answers with the health-plan-member specifics. The resume's job is to be readable; the conversation handles the precision.

**Pattern 36 vs. Anti-Pattern 13:** Anti-Pattern 13 warns against "Buzzword Replacement of Specifics" — replacing concrete domain terminology with abstract consultant-speak ("Regulatory Systemization," "Process Improvement"). Pattern 36 is the legitimate cross-industry alternative: replace domain-specific *nouns* with industry-agnostic *nouns* that still describe the work concretely. "Federal mandate delivery" is concrete; "regulatory transformation excellence" is buzzword-stuffed. The test: would a hiring manager in the target industry recognize the verb-object pair as describing real work? If yes, Pattern 36; if no, Anti-Pattern 13.

**Combines with:** [[pattern-26-title-research-and-selection-methodology]] (Pattern 36 may require a title revision when the in-domain title is industry-anchored), [[pattern-29-dual-positioning-via-resume-variants]] (a cross-industry variant is one more variant in the candidate's stable), [[pattern-30-identity-preserving-variation]] (scope numbers, employer, dates, and credentials stay invariant; vocabulary varies), [[pattern-33-multiplier-ceil-rule-for-growth-metrics]] (the multiplier-ceil rule applies; dejargonization doesn't change number conventions), [[pattern-35-ai-highlight-per-job-function]] (AI vocabulary stays untranslated; AI is the 2026 cross-industry signal).

**Conflicts with:** None directly. The risk is *over-dejargonization* — translating to the point where the resume reads as generic and loses the depth signal. The context-parenthetical technique mitigates this.

---

## Function Pattern Library Scaffold

*This section provides structural placeholders for function-specific tactical patterns. Each function family below lists the **categories of patterns** that practitioners in that field typically need. Pattern 28 (Industry and Role Inference) will adapt the skill to each candidate's function via web research at runtime; contributors are invited to fill these scaffolds with validated patterns over time.*

### How to Read This Scaffold

For each function family, you'll see:
- **What this function typically requires:** the categories of evidence/positioning that matter most for this kind of work
- **Common credentials to surface:** licensure, certifications, professional society memberships
- **Domain vocabulary to validate:** the technical terms recruiters in this field expect to see (Pattern 27 will validate the specific ones the candidate uses)
- **What's missing here:** explicit acknowledgment that no validated tactical patterns exist yet for this function in this skill

If you have validated resume evidence from one of these function families, see CONTRIBUTING.md to add patterns.

### Function Family: Software Engineering (Tech)

**Coverage status:** ✅ Well-covered by existing patterns (1, 2, 4, 5, 7, 10, 11, 12, 16, 18).

### Function Family: Technical Program Management (Tech)

**Coverage status:** ✅ Well-covered by existing patterns (1, 3, 19, 20, 21, 22, 23, 24).

### Function Family: Product Management (Tech)

**Coverage status:** ✅ Covered by existing patterns (15, 23, 25).

### Function Family: Customer Success Management

**Coverage status:** ⚠️ Partial coverage via tech-adjacent patterns. CSM-specific tactical patterns not yet validated.

**What this function typically requires:**
- Portfolio scale evidence (account count, ARR managed, member/seat count)
- Retention/expansion metrics (NRR, GRR, churn rate, expansion ARR)
- Executive engagement evidence (AVP/VP/Director-level sponsor names, QBR cadence)
- At-risk account recovery stories
- Cross-functional coordination evidence (PM, engineering, sales partnerships)

**Common credentials to surface:** None standardized industry-wide; CSM certifications exist but are less weighted than experience.

**Domain vocabulary to validate:** NRR/GRR, churn rate, expansion motion, QBR, executive sponsor, account health score, time-to-value, adoption metrics, customer journey, success plan.

**What's missing:** Tactical patterns for structuring CSM-specific bullets (e.g., the canonical CSM bullet structure, retention storytelling conventions, at-risk-recovery framing). Open invitation for contributions.

### Function Family: Engineering (Non-Software)

**Subfamilies:** Mechanical, Civil, Electrical, Chemical, Aerospace, Biomedical, Industrial, Materials, Environmental

**Coverage status:** ❌ No function-specific tactical patterns validated. Universal patterns and methodology patterns (26, 27, 28) apply.

**What this function typically requires:**
- Project portfolio evidence (specific projects shipped, scale of designs, certifications achieved)
- Technical specialty depth (specific tools, methods, analysis frameworks)
- Regulatory/standards compliance work (industry-specific safety, quality, environmental standards)
- Cross-discipline collaboration evidence (multi-engineering-discipline integration)
- Licensure status (PE, FE/EIT, EI in many jurisdictions)

**Common credentials to surface:**
- Professional Engineer (PE) licensure — state-issued, requires exam + experience
- Fundamentals of Engineering (FE / EIT) — pre-PE certification
- ABET-accredited degree institution
- Discipline-specific specializations (Structural, Mechanical, Electrical PE, etc.)
- Specialist credentials (CWI for welding inspection, LEED for sustainable design, PMP if PM-adjacent)
- Professional society memberships (ASME, ASCE, IEEE, AIChE, AIAA, ASHRAE, NSPE)

**Domain vocabulary to validate (varies by subfamily):**
- *Mechanical:* FEA (ANSYS, Abaqus, NASTRAN), CFD, CAD (SolidWorks, Creo, NX), GD&T, ASME standards, ISO 9001, AS9100 (aerospace), tolerance stack-up, DFMA
- *Civil:* AASHTO, ACI, AISC, IBC, ASCE 7, LRFD, geotechnical analysis, hydraulic modeling, AutoCAD Civil 3D, Bentley OpenRoads
- *Electrical:* IEEE standards, NEC, IEC, hardware design (Altium, KiCad, OrCAD), FPGA/ASIC design, power systems, signal integrity, EMI/EMC
- *Aerospace:* MIL-STD, DO-178C, DO-254, AS9100, TRL levels, flight test certifications, ITAR/EAR compliance, NASA Class A/B/C

**What's missing:** Tactical patterns for non-software engineering resumes — how to structure a project portfolio bullet, how to surface PE licensure prominently, how to communicate cross-discipline integration work, how to handle defense/aerospace clearance signals without overstating. Open invitation for contributions.

### Function Family: Legacy Software / Mainframe

**Coverage status:** ❌ No function-specific tactical patterns validated. Tech-resume patterns partially apply but vocabulary is dated relative to modern-tech bias of existing samples.

**What this function typically requires:**
- Specialty depth (COBOL, JCL, CICS, IMS, DB2, MQ, REXX, Assembler)
- Modernization/migration work evidence (mainframe-to-cloud, Java/microservices integration)
- Performance and reliability metrics (batch window optimization, SLA achievement, daily transaction volume)
- Domain knowledge (banking, insurance, government — where legacy systems are concentrated)

**Common credentials to surface:**
- IBM certifications (z/OS, DB2, CICS — vendor-specific)
- Industry-specific (banking-specific certifications, government clearances)

**Domain vocabulary to validate:** z/OS, JCL, CICS, IMS, DB2, MQ, COBOL/PL/I/REXX/Assembler, IBM Mainframe Open Application Platform, RACF security, batch processing, transaction processing, mainframe modernization (often vendor-named: AWS Mainframe Modernization, Micro Focus, etc.)

**What's missing:** Tactical patterns for positioning legacy-systems work as a strength (rather than a limitation) — how to communicate modernization leadership, how to bridge to cloud-native vocabulary without losing mainframe-specialty credibility. Open invitation for contributions.

### Function Family: Healthcare Clinical (Nursing, MD, Allied Health)

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Patient census / acuity / setting (ICU, ED, OR, ambulatory, etc.)
- Procedure / case counts (relevant for surgical, procedural, diagnostic roles)
- Patient outcome metrics (mortality rates, readmission rates, complication rates — where ethically reportable)
- Care quality and safety initiatives (HCAHPS, patient safety event reduction, quality measure improvement)
- Specialty certifications and continuing education

**Common credentials to surface:**
- For nursing: RN/LPN/NP/CRNA license + state, BLS/ACLS/PALS, specialty certs (CCRN, CEN, OCN, CMSRN, RNC, etc.), BSN/MSN/DNP degrees
- For MDs: MD/DO, board certifications, state medical license, DEA registration, hospital affiliations, ABMS specialty/subspecialty boards
- For allied health: PT/OT/SLP/PA/etc. specific licensure and specialty certifications

**Domain vocabulary to validate:** EHR systems (Epic, Cerner, Athena, Meditech), CPOE, clinical pathways, evidence-based practice protocols, Joint Commission, CMS reporting (HEDIS, MIPS, MACRA), value-based care frameworks, ACO participation, specialty-specific clinical terminology.

**What's missing:** Tactical patterns for clinical resumes — how to surface clinical excellence within HIPAA-compliant framing, how to communicate impact without disclosing individual patient information, how to position clinical leadership work, how to handle the credentials-heavy resume format common in healthcare. Open invitation for contributions.

### Function Family: Legal

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Bar admissions and licensure status (state and federal courts)
- Practice area specialty (litigation type, transactional type, regulatory specialty)
- Matter portfolio (deal sizes, settlement amounts, trial outcomes, case types — within confidentiality limits)
- Publication and speaking record (articles published, CLEs delivered, bar association leadership)

**Common credentials to surface:** JD degree + institution, bar admissions (state + federal courts), specialty certifications (e.g., bankruptcy specialist certification), LLM degrees, judicial clerkships.

**Domain vocabulary to validate:** Practice-area-specific (M&A, securities, IP, employment, tax, etc.); Federal Rules of Civil Procedure, specific regulatory bodies (SEC, FTC, DOJ, etc.), bar association acronyms.

**What's missing:** Tactical patterns for legal resumes — how to communicate matter portfolio within confidentiality limits, how to position litigation track record, how to surface deal sheet credibility, formatting conventions for law-firm vs in-house vs government attorney resumes. Open invitation for contributions.

### Function Family: Finance / Accounting

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Quantitative depth (deal sizes, AUM, portfolio scale, P&L scope)
- Regulatory framework experience (SOX, GAAP, IFRS, Basel III/IV, Dodd-Frank)
- Audit/compliance/risk credentials
- Industry vertical (banking, asset management, insurance, corporate finance)

**Common credentials to surface:**
- CPA, CFA (all three levels), CAIA, FRM, CMA, CIA
- Securities licenses (Series 7/63/65/79/24)
- Industry certifications (Bloomberg, FactSet, specific platform proficiency)

**Domain vocabulary to validate:** GAAP, IFRS, SOX, FASB pronouncements, audit standards (PCAOB, AICPA), specific instruments (derivatives, fixed income, equity, structured products), risk frameworks (VaR, CECL, IFRS 9), regulatory reporting (CCAR, DFAST, Basel reporting).

**What's missing:** Tactical patterns for finance resumes — how to structure deal-list portfolios, how to communicate quantitative achievement without overstating, how to handle confidentiality around specific client/deal details. Open invitation for contributions.

### Function Family: Sales

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Quota and attainment history (consistent over-quota performance, multi-year track record)
- Deal size and complexity (largest deals, average deal size, sales cycle length)
- Territory and segment evidence (geography, segment, named accounts)
- President's Club / Top Performer recognition

**Common credentials to surface:** Industry-specific certifications generally less critical than performance metrics; some methodology certifications (MEDDIC, Challenger, Sandler) signal training but don't replace performance.

**Domain vocabulary to validate:** ACV, ARR, MRR, quota, attainment, pipeline coverage, deal velocity, win rate, average deal size, sales motion type (PLG, enterprise, mid-market, SMB), specific sales methodology vocabulary.

**What's missing:** Tactical patterns for sales resumes — how to structure quota attainment bullets credibly, how to handle the "give credit but not breach confidentiality" tension around named accounts, how to format the quota-vs-attainment-by-year table that's standard in enterprise sales resumes. Open invitation for contributions.

### Function Family: Marketing

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Campaign portfolio (campaigns shipped, audience size, engagement metrics)
- Marketing function specialty (demand gen, content, brand, product marketing, growth, lifecycle, partnerships)
- Pipeline and revenue attribution (MQL/SQL/Opportunity volumes, pipeline contribution, marketing-sourced revenue)
- Tooling proficiency (Marketo, HubSpot, Salesforce, segment platforms)

**Common credentials to surface:** Platform certifications (HubSpot, Marketo, Google Ads, Meta Blueprint); general marketing certifications less weighted than portfolio.

**Domain vocabulary to validate:** MQL, SQL, opportunity, pipeline, ABM, demand gen, lifecycle, attribution (first-touch, multi-touch, etc.), CAC, LTV, brand equity, share of voice.

**What's missing:** Tactical patterns for marketing resumes — how to attribute marketing impact to revenue without overclaiming, how to balance brand/creative work with quantitative metrics, how to handle the specialty-vs-generalist tension. Open invitation for contributions.

### Function Family: Operations / Supply Chain

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Operational scale (volume, throughput, geographic footprint, headcount managed)
- Efficiency improvement work (cost reduction, cycle time reduction, defect rate reduction)
- Process improvement methodology (Lean, Six Sigma, Kaizen)
- Cross-functional vendor and supplier relationship management

**Common credentials to surface:** APICS (CPIM, CSCP, CLTD), Six Sigma (Green Belt, Black Belt, Master Black Belt), PMP, Lean certification.

**Domain vocabulary to validate:** OTIF, fill rate, perfect order, lead time, cycle time, inventory turnover, DSO, COGS, S&OP, MRP, ERP (SAP, Oracle, NetSuite specifically), specific 3PL or carrier vocabulary.

**What's missing:** Tactical patterns for operations resumes. Open invitation for contributions.

### Function Family: Education / Academic

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires (varies significantly by track):**
- *Tenure-track faculty:* publication record (peer-reviewed journals, conference proceedings, books), grant funding history, teaching evaluations, doctoral students mentored
- *K-12 / Higher Ed administration:* program/institution metrics (enrollment, graduation rates, budget managed, fundraising totals)
- *Industry/government researcher:* publication record + project impact

**Common credentials to surface:** PhD/EdD + institution + advisor (early career), professional licensure for K-12 teachers, specific specializations.

**Domain vocabulary to validate:** Discipline-specific publication tier vocabulary, funding agency acronyms (NSF, NIH, DOE, DARPA, etc.), academic society memberships, specific pedagogical or research method frameworks.

**What's missing:** Tactical patterns for academic resumes (note: academic CVs are structurally different from industry resumes — that distinction needs explicit guidance). Open invitation for contributions.

### Function Family: Skilled Trades

**Coverage status:** ❌ No function-specific tactical patterns validated.

**What this function typically requires:**
- Trade license and journeyman/master status
- Project portfolio (sites worked, scale of work, specialty work)
- Safety record (OSHA training, days without incident, safety certifications)
- Specialty endorsements (welding certifications, code-specific work)
- Union membership (where relevant)

**Common credentials to surface:** Trade-specific licensure (Master Electrician, Master Plumber, certified welder per AWS/ASME), OSHA 10/30, specific code certifications.

**Domain vocabulary to validate:** Trade-specific code references (NEC for electrical, IPC for plumbing, AWS for welding), specific manufacturer training, union local affiliations.

**What's missing:** Tactical patterns for skilled trades resumes. Open invitation for contributions.

### Other Function Families Not Yet Scaffolded

The function families above are illustrative, not exhaustive. Other significant families include: design (UX, industrial, graphic), data science / ML / AI research, human resources, executive assistant / administrative, hospitality, transportation / logistics drivers, agriculture, public service / government civilian, military-to-civilian transitions, and many more. Contributions adding scaffolds (and eventually validated patterns) for any of these are welcomed.

### Honest Principle for This Scaffold

This scaffold is **structural**, not prescriptive. The categories listed for each function family reflect general professional knowledge about what those functions require — they are not validated tactical patterns. Pattern 28 (Industry and Role Inference) provides the runtime adaptation; this scaffold provides the contributor roadmap. Until validated patterns exist for a function, treat this scaffold as a starting point for the assistant's web research, not as authoritative guidance.

---

## Anti-Patterns: What Hurts Resumes (Even Strong Ones)

*Weaknesses commonly observed in real resumes. Some are universal; others are software-engineer-specific or context-dependent. Each anti-pattern is tagged with its scope.*

### Anti-Pattern 1: Self-Description Over Win Listing [UNIVERSAL]

**Detection patterns (red flags in summary paragraphs):**
- Buzzword chains: "results-driven," "passionate," "innovative," "impactful," "ever-expanding," "robust"
- Passive credit-claiming: "Acknowledged for...", "Recognized as...", "Known for..."
- Vague leadership claims: "Strong leader," "proven track record," "history of accolades"
- Self-description that the experience section already proves: a strong experience section makes the summary's leadership claims redundant

**Why it hurts:**
- Buzzwords ("impactful," "innovative," "ever-expanding") replace evidence
- "Acknowledged for" / "history of promotions and accolades" — passive, vague
- "Strong leader" is the weakest possible self-claim
- The actual experience section already proves all of this — the summary undermines it

**Fix:** Replace with pipe-separated headline (Pattern 1) or remove entirely.

### Anti-Pattern 2: Tools-as-Skills at Senior Level [SOFTWARE ENGINEER]

**Detection patterns (red flags in senior+ resumes):**
- A "Skills" or "Technical Skills" section listing operating systems (any OS — Windows/macOS/Linux)
- A "Skills" section listing IDEs or code editors (any of them)
- A "Skills" section listing universal collaboration/ticketing tools (Jira, Confluence, Slack, etc.)
- Generic competencies like "Problem-Solving," "Communication," "Teamwork" listed as skills

**Why it hurts:**
- IDEs and OSes at Principal level = junior signal
- Confluence and Jira are universal — listing them = padding
- Takes visual real estate that could go to bullets

**Fix:** Delete the section entirely. Move uncommon/specialized tools into per-role Technologies sub-lines (Pattern 10).

### Anti-Pattern 3: Routine Responsibilities as Achievements [SOFTWARE ENGINEER]

**Detection patterns (red flags):**
- Bullets that describe expected job responsibilities rather than differentiated achievements
- On-call rotation listed as an accomplishment at senior+ levels (it's table stakes)
- Stakeholder communication listed as a bullet (expected at every level)
- Code reviews listed as a bullet (expected at every level)
- Multi-year duration applied to routine responsibilities (signals stagnation, not seniority)

**Why it hurts:**
- On-call is table stakes for engineers — featuring it implies the bar is low
- "12 years of on-call rotation" reads as "I'm still doing on-call" (career stagnation)
- Communicating with stakeholders is expected at this level

**Fix:** Delete the bullet. If on-call ownership genuinely needs mention, compress to "Maintained on-call ownership across [system] for [duration]" — and only if it's a differentiator.

### Anti-Pattern 4: Burying the Biggest Number [UNIVERSAL]

**Detection patterns (red flags):**
- The role with the strongest quantified outcomes has those outcomes at positions 4-5 in its bullet list, not position 1
- Tactical/technical bullets (library upgrades, codebase rewrites, refactoring work) appear above strategic/impact bullets within the same role
- The first bullet of the most recent role is not the strongest bullet of the resume

**Why it hurts:**
- Recruiters scanning fast may stop after the first 2-3 bullets
- The best evidence of impact never gets seen
- Sequencing signals self-awareness about what matters

**Fix:** Reorder bullets in each role so the highest-impact, most-quantified bullet leads. Apply this to every role.

### Anti-Pattern 5: Wordy Bullets with Back-Loaded Numbers [UNIVERSAL]

**Detection patterns (red flags):**
- Bullet exceeds 40 words while still being a single-bullet, single-idea item
- The quantified outcome (number) appears past word 30 of the bullet
- Multiple semicolons within a single bullet (3+ semicolons = multiple ideas crammed together)
- Filler adverbs ("extensively," "significantly," "substantially") that add words without information
- Pre-amble clauses ("Worked closely with...", "Was responsible for...") consume the first 5-10 words before the bullet's actual content begins

**Why it hurts:**
- A number buried past word 30 is functionally invisible to a 10-second recruiter scan
- Semicolon-stacked bullets read as if the candidate couldn't pick what to lead with
- Filler adverbs signal verbose writing, not content depth

**Fix:** Apply Pattern 4 formula. Front-load the number. Cap at 30 words.


### Anti-Pattern 6: Generic Mid-Level Competencies on Senior-Level Resume [SOFTWARE ENGINEER]


**Why it hurts:**
- "Object-Oriented Programming" — table stakes for any engineer
- "Problem-Solving" — meaningless filler
- "Testing & Quality Assurance" — every engineer does this
- At Principal level, these aren't competencies; they're job prerequisites

**Fix:** Either remove entirely, or replace with Principal-level competencies (Distributed Systems, Platform Architecture, Technical Strategy, Cross-Team Technical Leadership, Performance at Scale, etc.).

### Anti-Pattern 7: Recent Thin Roles That Weaken the Top [UNIVERSAL]

Current role (new employer, 5 months): only 2 bullets, both task-level ("Collaborated with senior team members to support testing efforts...", "Led the update of the logging library dependency...")

**Why it hurts:**
- This is the FIRST thing recruiters read
- "Collaborated to support testing" reads as junior IC work
- Updating a library version is not Principal-level work
- Sets a weak tone that the rest of the resume has to overcome

**Fix:** Either compress to 1-2 strategic bullets (omitting task-level work), or reframe with broader scope context ("Joined as Principal Engineer to lead [area]; early focus on X and Y while [larger initiative] ramps").

### Anti-Pattern 8: First-Person Pronouns [UNIVERSAL]


**Why it hurts:**
- Standard resume convention strips first-person pronouns ("I," "my," "me")
- The structure "I [verb]" doubles word count and weakens the verb
- "I authored the incident review document" → "Authored the incident review document" reads stronger
- Recruiters notice the convention break (even subconsciously)

**Why it survives in practice:**
This anti-pattern sometimes survives despite the candidate getting callbacks, suggesting some employers tolerate it (possibly because their internal writing cultures use "I" heavily in operational documents). But "tolerated" ≠ "preferred." Other recruiters will downgrade.

**Fix:** Find/replace all instances of "I [verb]" → "[Verb]" throughout. Easy win.

**Exception:** First-person is acceptable in the summary section if you're using a narrative voice (rare; most summaries should still avoid it). Never in bullets.

### Anti-Pattern 9: Broken PDF Text Encoding [UNIVERSAL — critical]

An incorrectly rendered PDF might contain "iniLatives" (should be "initiatives"), "soBware" (should be "software"), "Lll" (should be "till"), "iniLaLves" (should be "initiatives") — apparently a font ligature substitution issue (ti → L, ff → B) during PDF export.

**Why it's critical:**
- The visual reading looks perfectly fine to humans (the font renders correctly)
- ATS systems extract text from the PDF and would extract "iniLatives" instead of "initiatives"
- This **fails keyword matching silently** — the resume looks great but never matches "initiative" in job description parsing
- Same for "soBware" not matching "software" searches

**How to detect:**
1. Open the PDF
2. Select all text (Cmd-A / Ctrl-A)
3. Copy and paste into a plain text editor
4. Search for obvious corruptions: "L" appearing inside words, "B" inside words, missing characters
5. If you find them, your PDF export is broken

**How to fix:**
- Switch PDF export method (try a different "Save As PDF" path in Word/Google Docs)
- Embed fonts during export (settings vary by tool)
- Test by saving as .docx instead, then converting to PDF via a different tool (e.g., LibreOffice command line)
- Avoid fonts that use unusual ligatures (some serif fonts are worse than sans-serif)

**This is the single highest-leverage anti-pattern to check.** A broken PDF can silently kill an otherwise excellent resume in ATS systems. Always verify text extraction works correctly.

### Anti-Pattern 10: Underselling Significant Detours [UNIVERSAL]

**Detection patterns (red flags):**
- A founding-engineer or founding-team role at a startup is listed without scope context (no team size, no scope, no traction signal)
- An early-stage role with significant scope (founding team, 0-to-1 product launch, exec staff at sub-50-person company) is given the same visual weight as a tactical IC role
- The "detour" reads as a gap rather than a differentiator
A 15-month founding engineer stint at an early-stage startup gets ONE bullet (one paragraph). Roles before and after get extensive detail.

**Why it hurts:**
- Founding engineer at an early-stage well-funded startup is a major credential — most candidates don't have this
- Compressing it to one paragraph signals "this didn't matter" or "this didn't go well"
- Recruiters notice the imbalance and may interpret it as a failure narrative
- The detour deserves the same impact-focused treatment as longer roles, scaled appropriately

**Why this happens:**
Candidates often compress short stints out of self-consciousness ("only 15 months") or fear of seeming like a job-hopper. But significant short stints (founding role, sabbatical with clear outcome, acquisition transition, founder-led venture) deserve appropriate space.

**Fix:** Give significant detours 2-4 bullets minimum, with the same quantification standards:
- ❌ "Was one of the initial engineers, focused on architecting platform infrastructure..."
- ✅ "Joined as Founding Engineer #N, reporting directly to CEO; architected platform infrastructure that onboarded first M paying customers and reached $X ARR before [transition reason]"

**Special case for failed startups:** "Returned to [previous company] to scale impact at larger surface area" is a fine framing. Don't pretend the stint didn't happen, but don't dwell on it either.

### Anti-Pattern 11: Missing Contact Channels in 2026 [UNIVERSAL]

**Detection patterns (red flags):**
- ❌ No LinkedIn URL in the contact block
- ❌ No GitHub URL (especially critical for senior engineering candidates)
- ❌ No phone number
- ❌ Full street address listed (privacy concern in 2026; city/state is sufficient)

**Why it hurts:**
- 2026 recruiters expect LinkedIn URL for instant context
- GitHub is table stakes for senior engineering roles
- Missing online presence signals "I haven't updated my professional brand"
- Full street address adds privacy risk without benefit (city/state is sufficient)

**What's expected on modern resumes (2026 standards):**
- ✅ Email (mailto: hyperlinked)
- ✅ LinkedIn URL (hyperlinked)
- ✅ City, State (no full street address)
- ✅ Phone number (optional but expected for US candidates)
- ✅ GitHub URL (for engineers; required for Principal+)
- ✅ Personal website/portfolio (optional but boosts senior IC candidates)

**Fix:** Replace full street address with city/state. Add LinkedIn and GitHub URLs. Keep contact block to one tight line.

**Format guidance:**
```
email@domain.com | (XXX) XXX-XXXX | linkedin.com/in/handle | github.com/handle | City, State
```

### Anti-Pattern 12: Weak Software Engineer Summary Paragraph [CONFIRMED — SOFTWARE ENGINEER pattern]

**This anti-pattern appears consistently in software engineer resumes.** Software engineers write weaker summary paragraphs than their bullets warrant.



**Common failure modes:**
- "Software professional" / "Senior Software Engineer with" — generic self-description
- "Have built / Have helped / Have experience" — grammatically weak passive constructions
- "Impactful initiatives," "innovative solutions," "robust skill set" — buzzword filler
- **Zero numbers** in either summary, despite bullets being numbers-rich
- Doesn't mention the most differentiating work (publications, multi-hundred-million-dollar risk mitigation, major product launches)

**Why this pattern is specifically about software engineers:**
- SWEs are evaluated on code/systems, so they often deprioritize the summary
- SWE culture sometimes views summaries as "PM/sales fluff"
- Many SWEs treat the resume as a project list, not a positioning document
- Result: bullets are 5x stronger than summary; the summary undersells

**Fix:** Apply Pattern 1 (Pipe-Separated Headline) or rewrite as a tight 3-sentence summary leveraging the strongest 2-3 bullets:


**Cross-function observation [LOW-CONFIDENCE — limited samples]:** Product Manager and TPM resumes tend to have notably stronger summaries than SWE resumes — leading with quantified business outcomes (dollar figures, efficiency gains), using domain vocabulary, and structuring across three paragraphs (Pattern 23).

A defensible interpretation: **PM/TPM work tends to produce metrics and outcomes that are easier to quantify in summary-friendly language** ($X revenue, Y% efficiency, Z accounts) than SWE work (which often centers on system architecture, technical scope, and code-level deliverables that take more contextual framing to surface). This may make PM/TPM summary-writing structurally easier — not necessarily the result of better positioning instincts.

For SWE candidates: the fix is **not** to feel inadequate at summary-writing relative to PMs. The fix is to do the deliberate work of translating technical accomplishments into business-impact language (Pattern 11) — which most SWEs skip, but the strong ones do.

**More data needed:** Additional samples would validate or weaken this observation.

### Anti-Pattern 13: Buzzword Replacement of Specifics [CONTEXT-DEPENDENT]

**Replacing concrete domain terminology with abstract consultant-speak.** This appears both in real resumes (in summary paragraphs) and in well-meaning peer rewrites. The decision to use specific vs. abstract language depends on **whether you're applying in-domain or out-of-domain**.

**Detection pattern (specific-to-abstract drift):**

| Specific (in-domain, strong) | Abstract (generalist override, weak) |
|---|---|
| Industry-canonical standards cited by name (regulations, specs, frameworks) | Generic descriptor ("Industry compliance frameworks") |
| Industry-canonical protocols cited by name (messaging standards, exchange formats) | Generic descriptor ("Communication protocols") |
| Specific federal regulation citations | Coined consultant-speak ("Regulatory Systemization") |
| Industry-canonical methodology terms (Lean, Six Sigma, SPC, Kaizen) | Generic descriptor ("Process improvement") |
| Concrete production deliverable described in technical terms | Coined abstraction with invented vocabulary |

**Why specificity matters for in-domain applications:**
- Domain-specific terminology is **what specialist recruiters look for**
- Industry-canonical standard names match keyword searches in their industries; coined consultant-speak abstractions match nothing in ATS keyword indexes
- Specifics signal expertise to specialists
- Specialist recruiters expect to see the canonical names of regulations and standards their industry uses

**When abstraction is acceptable (out-of-domain applications):**
- Applying to general roles outside your specialty → industry-agnostic framing is fine without listing every standard
- Applying to consulting roles where the resume travels across industries
- Applying to roles where the target audience won't recognize the specifics

**The contextual decision rule:**
- **In-domain application** (candidate's industry = target's industry): Keep specifics. Domain-canonical names are signal-rich keywords.
- **Out-of-domain application** (candidate's industry ≠ target's industry): Abstract slightly, but keep one or two specifics as proof of depth.
- **Cross-industry application**: Lead with abstracted framing, but include the specific terms in parentheses or as examples.

**Fix:**
- Maintain two versions of your resume if you're targeting both in-domain and out-of-domain roles
- For each application, check: would the recruiter recognize this term?
- If yes → use the specific
- If no → apply Pattern 36 (Cross-Industry Dejargonization) — translate domain nouns to industry-agnostic equivalents while preserving scope numbers, AI tooling, and cross-industry credentials; surface domain terms in a context parenthetical so depth signals stay available
- Do NOT replace specifics with abstract consultant-speak ("Regulatory Systemization," "Process Improvement Excellence") — that's Anti-Pattern 13 proper; Pattern 36 is the legitimate alternative

**Caution on peer reviewers:**
When a peer reviewer (especially one outside your domain) suggests abstracting specifics, ask whether the target audience would recognize them. If yes, keep your specifics. The reviewer may be optimizing for a general audience when your audience is actually specialist.

**Related:** [[pattern-36-cross-industry-dejargonization]] is the canonical positive guidance for cross-industry positioning — translate concrete domain nouns to concrete industry-agnostic nouns, never to abstract consultant-speak.

### Anti-Pattern 14: Generalist Voice Override in Specialist Resume [PEER-REVIEW-SOURCED]

**When a generalist reviewer (peer, friend, AI tool, or out-of-domain helper) imposes their own writing voice on your resume, importing vocabulary that clashes with your domain's conventions.**

**Detection pattern (domain-native to generalist-voice drift):**

| Domain-native (strong) | Generalist override (weak) |
|---|---|
| Concrete technical terminology used correctly | Invented compound terms that don't exist in the field |
| Industry-canonical regulatory or compliance terms | Coined abstractions ending in "-ization" or "-ism" |
| Specific industry terminology (code systems, standards) | Generic terms misapplied from adjacent fields |
| Concrete delivery vocabulary | Consultant-speak loops and ecosystem framings |

**Tells that signal generalist voice override:**
- Made-up technical terms that sound plausible but don't exist in the field
- Misused domain terms (a term being applied outside its native domain)
- Consultant-speak with no concrete referent ("velocity loops," "ecosystems," "synergies")
- Vague abstractions where the original had precision

**Why it hurts:**
- A peer who works in consulting writes resumes in consulting voice
- A peer who works in product writes in product voice
- Your target recruiters expect domain-native voice
- Importing the wrong voice weakens domain credibility — specialists notice it immediately
- Made-up terms like "API synthesizations" actively flag you as someone who has *read about* the field, not someone who *works in* it

**How to detect it in your own resume:**
- Read each phrase aloud
- Ask: "Would a specialist in this domain say this in a meeting?"
- If the phrase sounds smart but you can't define it precisely, replace it
- Test on someone who actually works in your field — they'll flag the made-up terms

**Fix when taking feedback from a peer in a different domain:**
- ✅ **Keep their structural suggestions** (formatting, section order, bullet structure, length)
- ✅ **Keep their meta-feedback** (this section is too long, this is buried, this should be quantified)
- ❌ **Reject their vocabulary suggestions** when they're not in your domain
- ✅ **Cross-check terminology** with someone who actually works in your field before accepting changes

**Honest principle:** "If your peer reviewer doesn't recognize a domain term, explain the term to them — don't replace it."

### Anti-Pattern 15: Title Pivoting Without Defensible Evidence [PEER-REVIEW-SOURCED — with important nuance]

**Pivoting your resume title to reflect a different job function (e.g., showing "Senior Customer Success Manager" instead of "Technical Implementation Manager") is legitimate positioning — IF the work backs it. The failure mode is pivoting to a title the underlying work cannot defend. Disclosure of the internal title is a recruiter-conversation matter (when asked), not a document matter (see Pattern 34).**

**The realistic context:**
The job market in 2026 is tough. ATS systems filter by job title. Candidates with hybrid roles legitimately operate across multiple functions (e.g., "Technical Implementation Manager" who does substantial Customer Success work, or "Data Engineering Manager" who is functionally a TPM). Positioning the title to match the role being applied to is standard practice (see Pattern 26 for title selection and Pattern 34 for title display). The anti-pattern is not the pivot itself — it's pivoting beyond what the work supports.

**When title pivoting is acceptable:**
- The pivoted title accurately reflects significant work the candidate actually did
- The candidate can defend the pivot with concrete examples (specific dollar amounts in account growth, executive QBRs run, retention metrics owned — describing actual CSM work if pivoting to a CSM title)
- The pivoted title is the title the market currently uses for that function (validated per Pattern 26's web search)
- The candidate would answer truthfully if asked about the internal title in a recruiter conversation

**Detection patterns (red flags — when the pivot is overreach):**
- ❌ The pivoted title doesn't reflect work the candidate actually did (e.g., "Customer Success Manager" when the candidate has zero retention/expansion work in their bullets)
- ❌ The pivoted title implies seniority beyond the candidate's scope evidence (e.g., "Director of Engineering" when the bullets describe Senior Engineer scope — no team-size, budget, or org signal)
- ❌ The pivoted title implies a function the candidate has no defensible bullet content for
- ❌ The candidate cannot map ≥3 of the target role's major responsibilities to evidence in their own resume bullets

**Why this matters:**
- Title pivots beyond what the work supports get caught in interviews — the moment the hiring manager asks for specifics, the candidate has nothing to point to
- Pivots that overstate seniority signal poor judgment about scope, not just title; that judgment failure spreads doubt across the rest of the resume
- The honest fix is not to *avoid pivoting* but to *pivot honestly* — match the title to what the work actually supports

**Fix:**
- Apply Pattern 26 (Title Research) to identify the title the market uses for the candidate's actual function
- Apply Pattern 34 (Job-Function Title Selection) for how to display the chosen title on the resume
- Verify defensibility: list the top 5 responsibilities of the target role, then map specific resume bullets to each. ≥3 mapped = defensible. <3 mapped = pull back to a less-stretched title
- The resume shows the job-function title only (per Pattern 34) — no parenthetical internal-title disclosure
- If asked about the internal title in a recruiter conversation, answer truthfully (script in Pattern 34); do not volunteer

**What changed from earlier guidance:**
Earlier versions of this anti-pattern prescribed showing the internal title in italics or parentheses underneath the pivoted title. That guidance has been retracted. Field feedback from many hiring managers confirms: the parenthetical internal-title disclosure reads as anxiety, splits the recruiter's 10-second scan, and pre-defends against a question that almost never gets asked. The resume shows one title per role — the job-function title that matches the target role (Pattern 34). Disclosure happens in conversation if and when it comes up, never on the document.

**Honest principle:** "Pivot the title to what the work supports; show only that title on the document; answer truthfully in conversation if asked."

**Related:** [[pattern-26-title-research-and-selection-methodology]] (governs which title to pick), [[pattern-34-job-function-title-selection]] (governs how to display the chosen title).

### Anti-Pattern 16: Unquantified Soft-Skill Bullets [UNIVERSAL]

**Bullets that describe soft-power work (stakeholder management, workshops, alignment, change management) without any numbers — even though numbers are available.**

**Detection patterns (red flags):**
- A bullet describes stakeholder work, workshops, alignment, or change management with no quantification
- Verbs like "led," "drove," "managed," "aligned" appear without scale numbers attached
- A resume that quantifies aggressively elsewhere has 1-3 conspicuously unquantified soft-power bullets

**Why it hurts:**
- Zero numbers in a resume that otherwise quantifies aggressively
- "Recurring planning workshops" — how many? How often?
- "Stakeholders" — how many? At what level?
- "Drove decisions" — how many? What value?
- Soft-skill work is **often more impressive when quantified** because it shows scale of influence

**Why this happens:**
Candidates often quantify their hard deliverables (products, features, $) but describe their soft-power work qualitatively ("led workshops," "aligned stakeholders," "managed change"). The implicit assumption is that soft-power work is hard to quantify. It usually isn't.

**Quantifiable dimensions of soft-skill work:**

| Soft skill | Quantifiable dimensions |
|---|---|
| Stakeholder management | # of stakeholders, seniority level (VP, Director, etc.), geography, function count |
| Workshops / meetings | Frequency (weekly/monthly/quarterly), attendee count, duration of program |
| Executive influence | # of decisions driven, $ value of decisions, # of QBRs presented |
| Change management | # of teams adopting, % adoption rate, time-to-adoption |
| Cross-functional coordination | # of functions, # of teams, # of dependencies, geographic spread |
| Mentorship / coaching | # of mentees, # of direct reports, retention rate, promotion rate of mentees |

**Quantification template:** A previously unquantified bullet should, after the fix, contain at minimum: a frequency or count, a scale or scope, and an impact metric.

**Detection check:** Scan your resume for bullets that don't contain any numbers. For each one, ask: *could I have quantified this?* If yes, do it.

**Exception:** Some bullets genuinely don't need numbers (one-line older role compressions, factual statements about scope). The anti-pattern applies when the work could be quantified and isn't.

### Anti-Pattern 17: Inconsistent Title Capitalization and Formatting [UNIVERSAL]

**Mixed capitalization patterns across role headers signal template/conversion artifacts and lack of polish.**

**Detection patterns (red flags):**
- Mixing lowercase, Title Case, and ALL-CAPS across role titles within the same resume
- Mixing full words and abbreviated forms across roles (e.g., "Manager" in one role, "MGR" in another)
- Mixing proper noun capitalization and lowercase for company names across roles
- Mixing separator characters between title and company (`|`, `–`, `,`) across roles
- Mixing date formats across roles (e.g., "Jan" in one role, "JAN" in another)

**Why it hurts:**
- Looks like a template conversion artifact (e.g., docx auto-formatting gone wrong)
- Signals carelessness — if the candidate didn't catch this, what else did they miss?
- Recruiters scan role headers in 1-2 seconds; visual inconsistency catches the eye for the wrong reason
- Particularly damaging on senior/executive resumes where polish is expected

**Standardization rules:**
- **Job titles:** Title Case — NOT all-caps, NOT all-lowercase
- **Company names:** Match company's own preferred capitalization (proper-noun branding with internal-caps stays as the company uses it; standard-caps stays standard-caps)
- **Abbreviations:** Spell out unless universally understood
- **Punctuation:** Use consistent separators across roles (e.g., always `" | "` between title and company)
- **Date formatting:** Match style across roles (consistent month abbreviation, consistent en-dash)

**Detection check:** Look at just the role headers down the left edge of the resume. Do they read consistently? If your eye snags anywhere, fix it.

**This is the lowest-effort, highest-ROI polish.** Takes 5 minutes; signals attention to detail across the whole document.

### Anti-Pattern 18: Client Name Disclosure in Vendor-Side Resumes [UNIVERSAL — confidentiality risk]

**Naming specific client organizations on a resume when working in vendor, consulting, agency, or SaaS-implementation roles.** Client names typically can't appear on a resume because of confidentiality obligations: explicit NDAs, master service agreement clauses, employer policy, and basic professional hygiene. Even when a client engagement is publicly known (e.g., the work was announced in a press release), naming the client in your resume is usually a contract violation by the employer, not a fact you have permission to disclose individually.

**Detection pattern:** Any bullet that names a specific client organization by its actual name (proper noun, brand, agency, institution) in a vendor/consulting/agency/SaaS-implementation role context.

**Why it hurts:**
- Potential breach of confidentiality clauses in your employment agreement or client MSA
- Background check or reference check may surface the disclosure to your current employer
- Signals poor judgment about confidentiality to the hiring manager (especially in healthcare, finance, government, defense, or any regulated industry)
- Recruiters in vendor-side roles know the convention; naming clients reads as a junior mistake
- Can disqualify you from roles at competitors of the named client, who fear similar disclosure if hired

**The convention: use functional, scale, and vertical descriptors instead of client names.** See Appendix A.12 (*Tier Descriptors for Sanitized Client/Employer References*) for the canonical list. Sample substitution table below illustrates the convention; the appendix is the authoritative source.

**Substitution rules by client category (illustrative — see Appendix A.12 for full list):**

| Client category | Substitute with |
|---|---|
| Specific commercial bank | "regional commercial bank" OR "$[X]-billion-asset bank" |
| Specific state/government agency | "state agency client" OR "federal agency engagement" OR "state-level program engagement" |
| Specific manufacturer | "Tier-1 industrial manufacturer" OR "global [vertical] supplier" |
| Specific retailer | "Fortune [N] retailer" OR "global retail enterprise" |
| Specific investment bank | "Tier 1 global investment bank" OR "Fortune [N] financial services client" |
| Specific healthcare provider | "top-[N] academic medical center" OR "regional integrated delivery network" |
| Specific federal healthcare agency | "large federal healthcare agency" |
| Specific defense contractor | "Tier-1 aerospace prime contractor" OR "DoD prime contractor" |

**Categories of safe descriptors** (see Appendix A.12 for the canonical groupings — scale tiers, funding tiers, functional/vertical descriptors, geographic descriptors):

1. **Functional/vertical descriptors** — see Appendix A.12, third bullet
2. **Scale descriptors** — see Appendix A.12, first bullet
3. **Funding tier descriptors** — see Appendix A.12, second bullet
4. **Geographic descriptors when generic enough** — see Appendix A.12, fourth bullet

**The numbers and scope carry the credibility; the names don't add information a recruiter actually needs.** "Anchor multi-region client, scaled from $[X] to $[Y] over [N] renewal cycles" tells a recruiter everything they need to assess the work. The client identity adds nothing the recruiter would act on differently.

**Exceptions — when client names ARE appropriate:**
- **Direct employment roles** (not vendor-side): If you were a full-time employee at the named company, naming your employer is required, not a disclosure
- **Publicly-credited published work:** Conference talks, case studies, or whitepapers where the client publicly co-authored or co-presented — and the publication is itself the credential
- **Open-source / public domain projects:** If the work is open-source under the client's name, citing the project (not the client engagement) is fine
- **Where the client has explicitly granted resume-use permission in writing:** Rare, but happens at some consulting firms

**Detection check:** Before sending the resume, scan for:
- Specific company names that are clients rather than employers
- Specific product names that are client-owned (not your employer's products)
- Specific project codenames that are client-internal
- Geographic specificity that effectively identifies a client (e.g., "the only large hospital in [small city]")

**For vendor-side candidates targeting roles at the *target company's competitors* of a former client:** Be especially careful. A target company is more likely to disqualify a candidate who appears willing to disclose competitor information than to value the specific client knowledge.

**Honest principle:** "If a recruiter could screenshot your resume and forward it to your former client's legal team as evidence of breach, the resume needs editing."

### Anti-Pattern 19: Same-Bullet, Same-Verb Across Variant Resumes [OBSERVED — VARIANT-RESUME GUARDRAIL]

**When a candidate maintains variant resumes per Pattern 29 (Dual-Positioning) but the shared bullets across variants use identical lead verbs and identical phrasing, the variants fail to differentiate — the second resume incurs maintenance cost without earning audience-specific signal.**

**Detection patterns (red flags):**
- Two variant resumes targeting different role families both open the lead bullet in the most recent role with the same verb (e.g., both say "Owned…" or both say "Led…")
- Side-by-side diff of the two variants shows that shared bullets are byte-for-byte identical across more than ~85% of the bullet text
- The two variants differ only in the summary paragraph and the competencies block — the experience section is unchanged
- The candidate cannot articulate which audience each variant is for, or why a specific bullet is framed the way it is in each variant

**Why it hurts:**
- Variant resumes only earn their maintenance cost if the reframing actually changes what the reader's eye lands on first — same lead verb means same identity signal, regardless of summary tweaks
- A recruiter for the secondary role family sees a resume that reads like the primary role family with a different summary glued on top — the framing feels inauthentic
- The candidate ends up maintaining two stale resumes instead of one well-maintained primary plus a deliberately reframed secondary
- The dual-positioning illusion is broken the moment a reader scans the experience section and sees the primary identity reasserting itself bullet by bullet

**Why this happens:**
Building a second variant resume from scratch is intimidating, so candidates default to copy-paste with only the summary swapped. The summary feels like the "hard" part (because it's narrative), but the experience section is where the reader spends the most time — and is therefore where the reframing has to actually land.

**Fix:**
- For each shared bullet in the variant resume, apply Pattern 31 (Lead-Verb Reframing) — choose a verb cluster that signals the variant's target identity (architect / steward / operator / influencer / people-leader)
- Apply Pattern 30's invariant/variant split — confirm that scope numbers, employer, dates, and credentials are bit-for-bit identical, but lead verbs and modifier phrases are deliberately differentiated
- For at least the top 3 bullets in the most recent role and the top 1–2 bullets in each prior role, the lead verb should differ between variants
- If the candidate genuinely cannot find a defensible alternate lead verb for a given bullet, that's a signal the bullet doesn't reframe — leave it identical, but make sure other bullets carry the reframing load

**Detection check:** Open both variants side-by-side. Read down just the lead verbs of every bullet. If the verb columns are >70% identical between variants, Anti-Pattern 19 is present.

**Honest principle:** "If your two variant resumes are 90% identical in body text, you don't have two variants — you have one resume with two summaries. Either commit to the reframing or stop maintaining the second variant."

**Related:** [[pattern-29-dual-positioning-variants]], [[pattern-30-invariant-variant-split]], [[pattern-31-lead-verb-reframing]].

---

### Status of These Patterns

**Source:** Patterns above are extracted from observation of real resumes with verified positive outcomes (interview callbacks and offers). They represent **observed practices** with varying confidence levels marked by tags:

- **[CONFIRMED]** — repeats across 2+ callback/offer-winning resumes
- **[OBSERVED]** — single-source pattern, observed in working resumes but not yet cross-validated
- **[CONTEXT-DEPENDENT]** — works in specific scenarios, not universally
- **[PEER-REVIEW-SOURCED]** — recommended by a peer reviewer (lower confidence than directly-validated patterns; reviewer opinion rather than verified outcome)

**Sample sources analyzed:**
- Sanitized and deidentified data from many senior-level resumes across TPM, SWE, PM, Data Engineer, Customer Success, and Tech Lead job functions (8–15 years experience each)
- Candidates span multiple large technology employers and Series A–F startups
- Callback-validated, offer-validated, and peer-reviewed sources included
- Examples throughout are illustrative and created by LLM

**Sample composition orientation:**
The source material reflects senior-level tech recruiting cultures. The skill is most reliable for senior IC and program-management roles at large technology employers; less validated for non-tech industries and non-senior levels. Pattern 28 (Industry and Role Inference) mitigates this via runtime adaptation. For any target market, prioritize the universal patterns and methodology patterns (26, 27, 28); patterns explicitly labeled as culture-specific should be applied only when the target matches that culture.

**How to use the patterns now:**
- Treat **[CONFIRMED]** patterns (2, 4, 5, 6, 7, 8, 9, 21, 24, 29, 30, 31, 32, 33, 34) as reliable principles to apply broadly
- Treat **[OBSERVED]** patterns (1, 10, 11, 12, 13, 14, 15, 16, 17, 18, 25, 35, 36) as candidate techniques — apply when they fit
- Treat **[CONTEXT-DEPENDENT]** patterns (3) as situational — evaluate fit per candidate
- Treat **[PEER-REVIEW-SOURCED]** patterns (19, 20, 22, 23) as reviewer-recommended techniques — apply with honest guardrails (Pattern 23 has confirmed-outcome backing)
- Treat **[METHODOLOGY]** patterns (26, 27, 28) as required upstream procedures — Pattern 28 (Industry and Role Inference) must run first at Step 1 before any tactical pattern is applied; Pattern 26 (Title Research) runs second as part of Step 1; Pattern 27 (Business Context Validation) runs throughout before drafting any bullet with domain-specific terms
- Treat **dual-positioning patterns (29, 30, 31)** as a cluster — apply together when building variant resumes for adjacent role families; Pattern 32 is a senior-platform specialization of Pattern 16 (External Credibility Markers)
- Anti-patterns 1-18 are confirmed weaknesses; address them when present (Anti-Pattern 12 is SWE-specific; Anti-Pattern 13 is context-dependent per its tag; Anti-Pattern 18 is universal but applies most to vendor-side/consulting/SaaS-implementation roles). Anti-Pattern 19 is the variant-resume guardrail — apply it whenever Patterns 29–31 are in use
- Don't apply every pattern to every resume — choose based on candidate level, function (TPM, SWE, PM, EM, CSM, etc.), and target role

**Summary format choice (Pattern 1 vs Pattern 23):**
Both validated formats. Use Pattern 1 (pipe-separated headline) for TPM, Program Manager, Engineering Manager, Operations Leader. Use Pattern 23 (3-paragraph structured) for Product Manager, cross-functional roles, and consulting backgrounds. See Pattern 23 for the full decision matrix.

**How they'll evolve:**
- More callback/offer-winning examples will validate or weaken existing patterns
- Patterns unique to a single example may be person-specific and should be deprioritized
- New patterns observed in additional examples will be added
- Anti-patterns will be expanded as more weakness examples accumulate
- [PEER-REVIEW-SOURCED] patterns may graduate to [OBSERVED] or [CONFIRMED] as they appear in additional validated resumes

**What Experienced Reviewers Rewrite First (meta-observation):**

When experienced peers rewrite a resume from scratch, they tend to spend rewrite energy in this priority order. This pattern reveals what high-leverage reviewers consider most important when they have limited time:

1. **Professional Summary** — almost always rewritten wholesale; treated as the highest-leverage section
2. **Core Competencies** — consolidated from many narrow categories into 3-5 broader, scannable groupings
3. **Bullet structure** — restructured with thematic prefixes (Pattern 21) and consistent quantification scaffolding
4. **Awards / Recognition section** — added or expanded with translated names (Pattern 20)
5. **Education** — usually preserved with minor refinements
6. **Section ordering** — sometimes reordered to put strongest content earlier

**Implication for self-review:** If you have limited time to improve your own resume, attack in the same priority order. The Summary is where the highest-leverage improvements live; tweaking older role bullets is the lowest-leverage activity per minute spent.

**Critical reminder:** Strong quantified content can carry a resume despite weak verbs, weak summaries, or dated design. Software Engineer IC resumes often demonstrate this — their business attribution and technical scope survive buzzword summaries, first-person pronouns, and other formatting flaws. But that's not a license to neglect the patterns; it's evidence that **strong numbers buy forgiveness for other weaknesses, while weak numbers cannot be rescued by good verbs or pretty design**.

**Most consistent cross-resume insights (from 4 callback/offer samples + 1 peer-review sample):**
1. **Numbers dominate everything** — quantification is the universally strongest signal across TPM, SWE, and PM tracks
2. **SWE summaries tend to be weaker than SWE bullets** (Anti-Pattern 12). PM and TPM summaries tend to be stronger. A defensible interpretation: PM/TPM metrics (revenue, accounts, efficiency %) are easier to surface in summary form than SWE metrics (system scope, architecture decisions), making PM/TPM summary-writing structurally easier — not necessarily proof that PMs/TPMs are inherently better positioners.
3. **Career progression visibility matters** — all callback/offer resumes make tenure and promotion clear
4. **Some employers have writing-culture-specific rules** — for employers with documented narrative-writing cultures, Variant B narrative bullets, tenure as strength signal, and culture-vocabulary signaling all become high-leverage
5. **Tier-1 employer recognition is real** — recognizable employer names on a resume buy attention from recruiters; the strongest resumes leverage that recognition with clear progression evidence
6. **Reviewers rewrite the Summary first** — confirming Summary as the highest-leverage section
7. **Domain-functional vocabulary signals expertise** — every function has its own native vocabulary (PM, SWE, CSM, program management, data science, etc.); using 5+ function-specific terms naturally throughout a resume signals discipline fluency. See Pattern 24 for the vocabulary table by function.


## ATS-Friendly Formatting Guidelines

### Critical Format Requirements

**What ATS Systems Can and Cannot Parse:**

✅ **ATS-Friendly:**
- Standard section headers: "Professional Experience", "Education", "Skills"
- Simple bullet points (•) or hyphens (-)
- Standard fonts: Arial, Calibri, Georgia, Times New Roman (10-12pt)
- Bold and italics for emphasis
- Clear date formats: "Mar 2021 - Present" or "03/2021 - Present"
- .docx or .pdf files with actual text (not scanned images)

❌ **ATS-Hostile:**
- Tables, text boxes, columns with complex layouts
- Headers and footers (info gets lost)
- Graphics, logos, photos, charts
- Special characters or decorative fonts
- Underlining (use bold instead)
- Multiple columns of text
- Text in images

### Modern ATS-Optimized Layout Structure

```
[FULL NAME - 16-18pt, bold]
[Professional Title/Positioning Line - 11-12pt]
[Email] | [Phone] | [LinkedIn URL] | [City, State]

PROFESSIONAL SUMMARY
[3-4 line executive summary highlighting leadership value, quantified impact, and core expertise]

CORE COMPETENCIES (Optional but ATS-helpful)
[2-3 columns of keyword-rich technical/domain expertise]
Examples vary by industry — illustrative:
*(Healthcare: Healthcare Interoperability • FHIR/HL7 Standards • CMS Compliance •*
*Data Platform Architecture • Value-Based Care • Population Health Analytics)*
*(Industrial: Manufacturing Operations • ISA-95 Architecture • OPC UA Integration •*
*Data Platform Architecture • Lean/Six Sigma • Production Analytics)*

PROFESSIONAL EXPERIENCE

[Company Name] | [City, State] | [Month Year - Month Year]
[Job Title]
• [Impact-driven bullet leading with result, including metrics]
• [Impact-driven bullet showing scope and achievement]
• [Impact-driven bullet with business outcome]

[Previous Company] | [City, State] | [Month Year - Month Year]
[Job Title]
• [Bullets following same format]

EDUCATION
[Degree], [Major] | [University Name] | [City, State] | [Year]

CERTIFICATIONS & PROFESSIONAL DEVELOPMENT (if relevant)
[Certification Name] | [Issuing Organization] | [Year]
```

### ATS Keyword Optimization Strategy

**Where ATS Systems Look:**
- Job titles (match them when truthful)
- Skills section keywords
- Throughout experience bullets (naturally integrated)
- Certifications and education
- Acronyms spelled out on first use, then abbreviated

**Keyword Types to Include (illustrated across industries; use what applies to YOUR target role):**
- *Technical skills:* programming languages, platforms, tools, databases relevant to the target role
  - *(Healthcare-tech: FHIR, HL7, Epic, Snowflake, AWS)*
  - *(SWE: Python, Java, AWS, Kubernetes, Postgres)*
  - *(Industrial: SCADA, OPC UA, ISA-95, MES)*
  - *(Finance: FIX, SWIFT, Bloomberg Terminal, kdb+)*
- *Methodologies:* Agile, Scrum, SDLC, Lean, Six Sigma, DMAIC, PRINCE2
- *Certifications:* PMP, PE, CPA, CFA, AWS Certified, Six Sigma Black Belt, Epic Certified, etc. (specific to your function/industry)
- *Regulatory:* industry-specific compliance frameworks
  - *(Healthcare: HIPAA, CMS-9115-F, CMS-0057-F, USCDI v3)*
  - *(Finance: SOX, Dodd-Frank, GLBA)*
  - *(Aerospace: DO-178C, AS9100, ITAR)*
- *Domain terms:* function-specific vocabulary validated per Pattern 27
  - *(Healthcare: Population Health, Value-Based Care, Interoperability)*
  - *(Finance: AUM, Alpha, Risk-Adjusted Return)*
  - *(Manufacturing: OEE, Cycle Time, Throughput)*

### Executive Chronological Format Requirements

**Why Chronological Matters for Executive Roles:**

Executive search firms and hiring managers need to see clear career progression to assess:
- Leadership trajectory and growth rate
- Company quality and industry experience
- Tenure stability and commitment
- Promotion velocity and recognition
- Strategic vs. tactical experience evolution

**Chronological Format Rules:**

✅ **Required Structure:**
```
PROFESSIONAL EXPERIENCE

[Most Recent Company] | [Location] | [Start Date - End Date or "Present"]
[Most Recent Title] | [Promotion Date if applicable - Present/End]
• Leadership-focused bullets with enterprise-scale metrics
• Platform ownership and architecture decisions
• Strategic transformation initiatives

[Previous Title at Same Company] | [Start Date - Promotion Date]  
• Progression in scope and responsibility visible
• Growing team size, budget, or organizational impact

[Previous Company] | [Location] | [Start Date - End Date]
[Title]
• Continue reverse chronological order
```

✅ **Showing Promotions Within Same Company:**
```
[Company Name] | [City, State] | Mar 2021 - Present

Data Engineering & Customer Success Manager | Jan 2023 - Present
• [Leadership and strategic bullets for current role]

Technical Implementation Manager | Mar 2021 - Dec 2022
• [Shows progression and increasing scope]
```

❌ **What NOT to Do:**

**Functional Format (Obscures Timeline):**
```
LEADERSHIP EXPERIENCE
• Led teams across multiple companies...
• Managed programs for various organizations...

TECHNICAL EXPERIENCE  
• Implemented systems at different companies...
```
*Problem: Can't see career progression, tenure, or growth trajectory*

**Hybrid Format (Confuses Chronology):**
```
CORE COMPETENCIES
[Long skills section taking up space]

SELECTED ACHIEVEMENTS
[Bullets without company/date context]

EMPLOYMENT HISTORY
[Just company names and dates]
```
*Problem: Achievements disconnected from roles and timeline*

**Handling Career Transitions:**

✅ **Promotions - Highlight Them:**
- List each title separately with dates
- Show increasing scope in bullets
- Quantify team/budget growth

✅ **Lateral Moves - Provide Context:**
"Transitioned to [target sector] to drive [target initiative type] following [external trigger event, e.g., regulatory shift, market opening, technology shift]"

✅ **Gaps - Address Briefly:**
"Consulting Projects | 2020 - 2021" or "Professional Development" or "Career Transition"

✅ **Company Acquisitions:**
"[Current Company] (acquired [Original Company] Division) | Mar 2021 - Present"

**Executive Progression Indicators:**

Show growth across dimensions:
- **Team Size**: 3 → 8 → 13 → 25 people
- **Budget**: $500K → $2M → $5M
- **Scope**: Single product → Platform → Enterprise
- **Geography**: Local → Regional → National → Multi-state
- **Seniority**: Manager → Senior Manager → Director
- **Impact**: Project → Program → Transformation

## When to Use This Skill

Trigger this skill when the user:
- Asks to "optimize," "improve," or "rewrite" their resume
- Mentions preparing for job applications or interviews
- Wants to tailor their resume for a specific role or company
- Requests feedback from a "recruiter perspective"
- Needs help with professional summaries or positioning statements
- Wants to align their resume with a job description
- Mentions ATS optimization or keyword alignment
- Requests help quantifying achievements or adding metrics
- Wants executive-level language refinement
- Mentions LinkedIn profile improvements (same principles apply)

## The 6-Step Framework

## Career Level Positioning Framework

**Critical First Step: Identify the Correct Career Level**

Different career levels require fundamentally different resume approaches. Misaligned positioning is one of the top reasons resumes fail - a senior leader positioned as a mid-level professional underwhelms, while a mid-level professional positioned as an executive lacks credibility.

### The 5 Career Levels

---

#### **Level 1: Entry-Level**
*Recent graduates and early-career professionals (0-3 years experience)*

**Resume Focus:**
- Academic achievements (GPA if 3.5+, honors, relevant coursework)
- Internships and co-op experiences
- Transferable skills from part-time work, volunteering, projects
- Core competencies and technical skills
- Certifications and relevant training
- Strong professional foundation positioning

**Length:** 1 page maximum

**Key Sections:**
- Education (prominent placement)
- Internships/Projects
- Skills (technical + soft skills)
- Certifications
- Extracurricular leadership

**Tone:** Eager, learning-oriented, foundation-building

**Avoid:**
- Inflating short experiences into senior-level impact
- Claiming leadership of large teams or budgets
- Strategic-level language without backing

**Entry-level bullet formula:**
`[Verb: Contributed/Built/Supported] [team/project context], [specific deliverable] that [outcome with quantification]`

---

#### **Level 2: Mid-Level**
*Established professionals (3-8 years experience)*

**Resume Focus:**
- Career progression and growth trajectory
- Industry contributions and domain expertise
- Measurable achievements showing consistent performance
- Cross-functional collaboration
- Project leadership and ownership
- Technical depth and specialization

**Length:** 1-2 pages

**Key Sections:**
- Professional Experience (prominent)
- Technical Skills (relevant to domain)
- Certifications
- Education (less prominent than entry-level)
- Notable Projects or Achievements

**Tone:** Confident, contribution-focused, growth-oriented

**Avoid:**
- Junior language ("helped", "assisted", "learned")
- Listing every project (curate to most relevant)
- Missing quantification of contributions

**Mid-level bullet formula:**
`[Tier-1 or Tier-2 verb] [project ownership scope] [delivering quantified outcome], [demonstrating cross-functional or technical depth]`

---

#### **Level 3: Senior-Level**
*Experienced professionals in leadership or specialist roles (8-15 years experience)*

**Resume Focus:**
- Leadership scope (team size, budget, geographic reach)
- Strategic contributions and decisions
- Team management and talent development
- Measurable business impact
- Domain expertise and thought leadership
- Cross-functional influence
- Higher organizational positioning

**Length:** 2 pages

**Key Sections:**
- Professional Summary (3-4 lines)
- Core Competencies
- Professional Experience (detailed)
- Leadership Achievements
- Technical Expertise
- Education & Certifications

**Tone:** Authoritative, strategic, results-driven

**Avoid:**
- IC-level task descriptions
- Missing leadership scope quantification
- Tactical execution focus without strategic context

**Senior-level bullet formula:**
`[Tier-1 verb] [team scope: N-person + geographic spread] through [project portfolio: N+ initiatives], delivering [quantified business outcome] while [quality/reliability metric]`

---

#### **Level 4: Executive-Level**
*Directors, Senior Directors, Heads of Function, Vice Presidents (12-20+ years experience)*

**Resume Focus:**
- Strategic leadership and vision
- Enterprise-wide impact and influence
- Operational ownership and P&L responsibility
- Career progression into senior decision-making
- Industry recognition and thought leadership
- Board-level and C-suite interaction
- Multi-million dollar budget management
- Cross-functional and cross-business-unit leadership

**Length:** 2 pages (edit ruthlessly)

**Key Sections:**
- Executive Summary (powerful 4-line opening)
- Areas of Expertise / Core Competencies
- Professional Experience (chronological, detailed)
- Board & Advisory Roles (if applicable)
- Strategic Achievements
- Education & Executive Development
- Speaking Engagements / Publications (if relevant)

**Tone:** Confident, visionary, transformational

**Required Signals:**
- ✅ P&L responsibility
- ✅ Multi-functional leadership
- ✅ Enterprise-scale transformation
- ✅ C-suite advisory or partnership
- ✅ Industry influence beyond own company
- ✅ Talent development and succession planning
- ✅ Strategic planning and execution

**Avoid:**
- Hands-on technical implementation details
- Project-level metrics (use program/portfolio level)
- Junior leadership scope (single small team)

**Executive-level bullet formula:**

`[Verb: Led/Drove/Spearheaded] [enterprise-scope initiative] as [title], managing [$ budget] and [N-person org] across [N functions] to deliver [named deliverable] serving [scale metric]—generating [$ revenue/savings outcome] and [strategic positioning outcome]`

**Required elements at VP+:**
- Budget ownership (annual $ figure)
- Organization size (headcount, function count)
- Scale of deliverable (users, members, revenue, geographic reach)
- Business outcome (revenue, cost savings, strategic positioning)
- Enterprise scope signal (multi-function, multi-region, multi-year)

---

#### **Level 5: C-Suite Level**
*CEO, COO, CFO, CIO, CTO, CMO, and other Chief-level roles*

**Resume Focus:**
- Enterprise-wide leadership and accountability
- Board-level communication and governance
- Organizational transformation at scale
- Revenue and growth strategy
- M&A activity and strategic partnerships
- High-impact decision-making
- Investor relations (for public companies)
- Long-term vision and strategy execution
- Talent strategy and culture building
- Crisis management and turnaround experience

**Length:** 2-3 pages acceptable

**Key Sections:**
- Executive Profile (powerful narrative opening)
- Core Leadership Competencies
- Professional Experience (strategic narrative)
- Board Memberships & Affiliations
- Notable Transformations / Exits
- Education & Executive Programs
- Awards & Recognition
- Publications & Speaking Engagements

**Tone:** Visionary, strategic, transformational, authoritative

**Required Signals:**
- ✅ Revenue/EBITDA ownership (large-dollar)
- ✅ Organization size (hundreds to thousands)
- ✅ Board interaction and governance
- ✅ M&A leadership (acquisitions, integrations, exits)
- ✅ Investor relations experience
- ✅ Industry recognition (awards, publications, keynotes)
- ✅ Crisis or transformation leadership
- ✅ Strategic partnerships and ecosystem building
- ✅ Cultural transformation and talent strategy

**Avoid:**
- Tactical execution details
- Single-function leadership focus
- Team-level metrics (use enterprise level)
- Implementation specifics (delegate-able work)

**C-Suite bullet formula:**
`[Tier-1 verb] [company/division] from [starting state] to [ending state: revenue/scale/strategic position] as [C-title], scaling [organization size or scope multiplier] across [strategic initiatives: M&A, acquisitions, geographic expansion], establishing [enterprise capability], and delivering [strategic outcome that increased shareholder value]`

---

### How to Determine Your Career Level

**Ask these diagnostic questions:**

1. **Scope of Influence:**
   - Single project/team? → Mid-Level
   - Multiple teams/department? → Senior-Level
   - Function/business unit? → Executive-Level
   - Enterprise/company-wide? → C-Suite

2. **Decision-Making Authority:**
   - Execute decisions? → Mid-Level
   - Make tactical decisions? → Senior-Level
   - Make strategic decisions? → Executive-Level
   - Set enterprise direction? → C-Suite

3. **Financial Responsibility:**
   - No budget ownership? → Entry/Mid
   - Project budgets ($100K-$1M)? → Senior-Level
   - Department budgets ($1M-$10M)? → Executive-Level
   - P&L/Enterprise budgets ($10M+)? → C-Suite

4. **Team Leadership:**
   - Individual contributor? → Entry/Mid
   - Direct team (5-15)? → Senior-Level
   - Organization (20-100)? → Executive-Level
   - Function/Enterprise (100+)? → C-Suite

5. **Stakeholder Engagement:**
   - Peer/manager level? → Mid-Level
   - Director/VP level? → Senior-Level
   - C-Suite/Executive team? → Executive-Level
   - Board/Investors/Industry? → C-Suite

**When diagnostic signals conflict (resolution rule):**

The five diagnostic questions may point to different levels for the same candidate. Apply the following resolution rules in order:

1. **Financial Responsibility is the primary signal.** Budget ownership is the hardest signal to inflate and the most unambiguous to a recruiter. When signals conflict, the Financial Responsibility answer sets the floor: the candidate cannot be positioned above the level their budget evidence supports.

2. **Scope of Influence is the secondary signal.** If Financial Responsibility and Scope of Influence agree → use that level. If they disagree → use Financial Responsibility (the lower signal), and note the gap to the candidate as positioning work needed.

3. **Team Leadership and Stakeholder Engagement are supporting signals.** They confirm or question the primary/secondary signals but do not override them. An IC-track candidate (no direct reports) can still be Senior-level on Financial and Scope signals; Team Leadership = "Individual contributor" doesn't force a downgrade if the other signals are Senior.

4. **When no financial signal exists** (no budget data in the resume): use Scope of Influence as primary, Stakeholder Engagement as secondary. Flag the absence of financial signals to the candidate — it is a positioning gap that Pattern 19 (Worksheet Method) should address.

5. **The diagnostic determines current level; the target level is one level higher maximum.** Stretching one level up is achievable with strong evidence across the five signals. Stretching two levels is rarely credible and should be flagged explicitly to the candidate.

**Output:** State the inferred current level, the evidence that supports it, any conflicting signals and how they were resolved, and the recommended target positioning level.

### Common Positioning Mistakes

**Under-Positioning (Selling Yourself Short):**
- Senior leader using mid-level language
- Executive presenting tactical achievements
- C-Suite leader focusing on functional details
- *Result:* Recruiters dismiss you as "not ready" for higher roles

**Over-Positioning (Lacking Credibility):**
- Mid-level professional claiming enterprise transformation
- Senior leader claiming C-Suite scope
- Inflated team sizes or budget figures
- *Result:* Recruiters detect inflation and reject for credibility issues

**Misaligned Positioning (Wrong Tier):**
- Technical specialist positioned as people leader
- Generalist positioned as deep specialist
- Operator positioned as strategist
- *Result:* Resume doesn't match the role recruiters are filling

---

### Step 1: Resume Mode Activation (Strategic Positioning)

**Purpose:** Set the context and treat the resume as a positioning document, not just a job history.

**Process:**

1. **Industry and Role Inference with Vocabulary Validation Gate** (RUNS FIRST — see Pattern 28 for full methodology):

   Before any pattern from this skill is applied, the assistant must establish who the candidate actually is (industry, role family, seniority, functional responsibilities, specialty) and validate that understanding against current industry vocabulary using the five-check binary gate (see Pattern 28).

   a. **Pass 1 — Inference:** From the resume, conversation, and any provided JD, infer the candidate's industry, role family, seniority, functional responsibilities, technical specialty (if applicable), and target market context. Document each inference explicitly.

   b. **Pass 2 — Validation:** Web-search current industry vocabulary, titles, and frameworks for the inferred industry+role+specialty. Map the candidate's described work to industry-standard terminology.

   c. **Inference Validation Gate:** Run the five binary checks from Pattern 28. All five must return YES before proceeding (see Pattern 28 for full checklist and stop conditions). The gate output — an explicit apply/skip pattern list — must be produced before any pattern is applied.

   **Why this runs first:** Most of the patterns in this skill were extracted from senior-level tech samples. Applying them blindly to a non-tech background (mechanical engineering, COBOL/mainframe, nursing, legal, etc.) produces a resume that sounds wrong to recruiters in those fields. Pattern 28 ensures the skill auto-adapts per candidate, per industry — instead of assuming tech-flavored context.

2. **Identify Career Level** - Use the Career Level Positioning Framework above to determine:
   - Current career level (where you actually are)
   - Target career level (where you want to be positioned)
   - Required signals for the target level
   - Gaps between current resume and target positioning

3. **Gather Context** - Ask the user to identify (if not already established in Step 1.1):
   - **Target role**: Specific position title (e.g., "Director of Healthcare Interoperability", "Senior Technical Program Manager")
   - **Target industry/sector**: Healthcare tech, consulting, payer/provider, SaaS, etc.
   - **Target company** (if specific): Company culture and values to align with
   - **Current resume**: Their existing resume content
   - **Seniority level**: IC, Manager, Senior Manager, Director, Senior Director, VP, C-Suite

4. **Research and Suggest Authentic Titles** (see Pattern 26 for full methodology):

   The candidate's internal title often does not communicate externally. Before optimizing the resume, work with the candidate to determine the right title(s) to use. **This step is research-driven, not assumption-driven**, and is scoped by the industry/role inference established in Step 1.1.

   a. **Audit actual work and responsibilities:**
      - From the candidate's existing resume bullets and conversation, identify the **functions** they actually perform (not the title they hold)
      - A candidate's work may map to one function cluster (e.g., Customer Success: portfolio ownership, renewals, QBR cadence, revenue retention) regardless of what their internal title says

   b. **Web-search current title conventions in the target industry/role:**
      - Search for the specific function + target industry combination (e.g., "Customer Success Manager healthcare SaaS responsibilities 2026")
      - Search current job postings on LinkedIn, Indeed, and target-company career pages for titles attached to similar function descriptions
      - Note title variations across industries and seniority levels
      - **Always use web search for this — don't rely on stale assumptions about title conventions**

   c. **Suggest title(s) that authentically reflect the work:**
      - Match the verbal description of the work to titles currently in use
      - Prefer titles the target market would recognize over internal titles
      - Validate that the candidate can defend the title with concrete work examples (Anti-Pattern 15)
      - Offer 2-3 title options when the work spans multiple functions

   d. **Customize for the specific JD when one is provided:**
      - If a specific job description is available, mirror the JD's title closely (matching for ATS, recognizability, and recruiter scan)
      - Note any required scope/seniority differences and flag for the candidate
      - Disclose any pivot in the recruiter conversation (Anti-Pattern 15)

   e. **Build a versatile vs targeted strategy:**
      - **Versatile resume**: A pivoted but defensible title that fits the broadest set of target roles (e.g., "Senior Technical Program Manager — Platform Programs")
      - **Targeted variants**: Per-application title adjustments for specific high-priority roles (e.g., "Senior Customer Success Manager — Healthcare Tech" for a specific CSM application)

5. **Adopt Level-Appropriate Mindset:**
   - **Entry/Mid**: Show progression and contribution
   - **Senior**: Demonstrate leadership and strategic impact
   - **Executive**: Show enterprise-scale transformation and influence
   - **C-Suite**: Demonstrate vision and organizational leadership

6. **Set Success Criteria:**
   - What makes a candidate compelling for this specific level?
   - What metrics matter most for this tier?
   - What keywords signal correct seniority?
   - What level of strategic vs. tactical content is expected?

**Output:** Validated industry/role inference (Step 1.1), confirmed career level positioning, target role context, and strategy before proceeding to optimization steps.

---

### Step 2: Recruiter 10-Second Test

**Purpose:** Simulate how recruiters actually read resumes - scanning for key qualifications and immediate red flags.

**The Reality of Resume Screening:**
- Recruiters spend 6-10 seconds on initial screen
- They scan top-to-bottom for recognizable signals
- They're looking for reasons to disqualify before reasons to advance
- First impression is formed before reading any bullet points

**Process:**

1. **Simulate the Scan** (10 seconds or less):
   - Top-to-bottom for role titles and company names
   - Quick check of dates for gaps or job-hopping patterns
   - Scan for recognizable keywords and certifications
   - Note immediate impression of seniority/impact level
   - Check if formatting is clean and professional

2. **Provide Honest Assessment:**
   - **First impression**: What signals does the resume send in 3 seconds?
   - **What jumps out positively**: Strong qualification signals
   - **What gets missed**: Important qualifications buried in text
   - **Red flags or confusion**: Anything that raises questions
   - **Positioning accuracy**: Does it read as target role level?
   - **ATS compatibility**: Will it parse correctly?

3. **Specific Feedback Categories:**
   - Visual hierarchy and scannability
   - Job title progression and career trajectory
   - Presence/absence of metrics and quantification
   - Technical credibility signals
   - Leadership scope indicators

**Output format — structured assessment with explicit prioritization:**

Produce exactly 3-5 findings, ordered by the following priority:

1. **ATS disqualifiers first** — anything that causes the resume to be filtered out before a human reads it (broken PDF encoding, missing standard section headers, date format errors, no quantification at all)
2. **10-second scan failures second** — anything a recruiter would misread or miss in a fast scan (buried employer names, weak/missing headline, no numbers visible above the fold, seniority mismatch in first visible role)
3. **Positioning gaps third** — anything that correctly positions the candidate for the wrong role or level (title mismatch, function vocabulary absent, seniority signals contradictory)
4. **High-leverage improvements last** — improvements that would materially strengthen an otherwise-passing resume (weak summary, buried strongest bullets, missing domain vocabulary)

Each finding must state: (a) what the problem is, (b) where on the resume it appears, (c) what the fix is. Vague findings ("summary could be stronger") without a specific location and fix are not acceptable output.

---

### Step 3: Achievement Rewrite (Impact-Driven Bullets)

**Purpose:** Transform responsibility descriptions into achievement statements with measurable impact and strategic positioning.

**MANDATORY pre-step — Business Context Validation (Pattern 27):**

Before drafting or rewriting any bullet that contains domain-specific terms (regulations, standards, implementation guides, frameworks, certifications, products, or quantitative claims about industry scope), web-search to validate every such term. This is not optional. Plausible-sounding domain language that's actually wrong is the most common failure mode of LLM-assisted resume drafting, and it disqualifies candidates the moment a domain expert reads the resume.

For each bullet about to be drafted:
1. Identify domain-specific terms (regulations, specs, IGs, products, certifications, organizations, quantitative-scope claims)
2. Web-search each one to confirm exact name, category, scope, current status, and relationship to other terms
3. Reconcile any quantitative claims (member counts, state lists, scale figures) against the candidate's actual provided data
4. Only then draft the bullet

See Pattern 27 for the full methodology, examples, and the failure mode this defeats.

**Coaching technique — apply Pattern 19 (Worksheet Method) here:**
When reviewing a candidate's existing bullets, scan for missing quantification and insert placeholder brackets with "Tip" callouts that explain what kind of number to find. This converts vague bullets into a worksheet the candidate can systematically complete. See Pattern 19 for the full technique, metric category prompts, and guardrails. **Remember:** the worksheet output is a draft state — all brackets must be filled before submission.

**Formula for Each Bullet:**
1. Lead with impact/result (not action or responsibility)
2. Include specific numbers demonstrating scale/scope
3. Show what was accomplished and how
4. Highlight business outcome or strategic value
5. Maintain technical credibility appropriate to seniority

**Quantification Framework - Add Metrics For:**

| Category | Examples |
|----------|----------|
| **Scale** | Users, members, patients, records, systems, data sources, locations, states |
| **Financial** | Revenue generated, costs saved, budget managed, ROI delivered, incentives enabled |
| **Team** | Direct reports, team size, cross-functional partners, stakeholders coordinated |
| **Time** | Projects delivered, speed improvements (% faster), deadlines met ahead of schedule |
| **Quality** | Accuracy improvements, error reduction, compliance rates, quality scores |
| **Efficiency** | Process improvements, automation gains, time saved per task, throughput increases |

**Positioning Key Wins — explicit ranking procedure:**

For each role, rank all bullets by impact strength and place them in ranked order. Use the following priority hierarchy (highest priority first; when two bullets tie on a criterion, apply the next criterion as tiebreaker):

1. **Dollar magnitude** (highest absolute dollar amount wins) — a bullet attributing $5M in revenue impact outranks a bullet about a 60% efficiency gain
2. **Relevance to target role** (most directly relevant to the specific role or function being targeted wins) — a retention metric outranks a delivery metric when targeting a CSM role, regardless of scale
3. **Scope of influence** (largest cross-functional, geographic, or organizational scope wins) — a program spanning 8 teams outranks a project within a single team
4. **Recency** (most recent role's wins outrank older role's wins, all else equal)
5. **Measurability** (measured outcomes outrank projected outcomes — see Pattern 14)

**Tie-breaking rule:** When two bullets tie across all five criteria, lead with the one that contains the highest-tier verb (Tier 1 > Tier 2 > Tier 3 per Pattern 5).

**Output:** For each role, produce an explicit ordered list of bullets (1, 2, 3...) before placing them — don't sort implicitly. This makes the ranking auditable and reversible if the candidate disagrees.

**Transformation Examples:**

❌ **Before (Weak):**
"Managed data integration projects for healthcare clients"

✅ **After (Strong):**
**Before/after transformation formula:**

❌ **Weak bullet pattern:** `"Responsible for [task description]"` — task-focused, no metrics, no outcome, no scale

✅ **Strong bullet formula:** `"[Tier-1 verb] [specific deliverable] serving [scale metric], delivering [technical scope] [speed metric]—enabling [business outcome] and [risk/cost avoidance metric]"`

**Key Wins Positioning Rule:**

Order bullets within each role using the explicit ranking hierarchy from the bullet ranking procedure above (dollar magnitude → target relevance → scope → recency → measurability → verb tier). Apply the same tiebreaker rules. Do not use subjective "feel" for ordering — apply the hierarchy and document the rationale if the candidate might question the ordering.

**Canonical three-tier structure per role:**
1. **Lead bullet** — the highest-ranked bullet per the hierarchy; the one a skimming recruiter will read first and use to form their impression of this role
2. **Secondary bullet(s)** — the next 2-3 ranked bullets, providing reinforcing evidence across different dimensions (a financial win, a scale win, a delivery win, a leadership win)
3. **Supporting bullets** — operational wins, process establishment, efficiency improvements; provide credibility but should not compete with the lead bullet for first position

**Process:**
1. Review each bullet in experience section
2. Identify missing elements: numbers, scope, outcomes, strategic value
3. Rewrite to lead with impact
4. Add quantification across relevant categories
5. Ensure technical depth remains for credibility
6. Position strongest 1-2 bullets first in each role
7. Verify authenticity - never fabricate metrics

**Platform Ownership Signals (Critical for Executive Roles):**

Executive-level positions require evidence of platform ownership, not just project delivery. Show:

**Architecture Authority:**
- "Architected" vs "Implemented"
- "Designed end-to-end platform" vs "Built features"
- "Established technical standards" vs "Followed best practices"
- "Defined data model" vs "Created schemas"

**Critical Distinction: Building vs. Driving Adoption**

One of the most common resume mistakes is conflating "building something" with "driving its adoption" - or worse, claiming to have built something that already existed. Both are valuable, but they signal different roles:

| Activity | Engineering Signal | TPM/Program Signal | Executive Signal |
|---|---|---|---|
| Wrote the integration code | ✅ Strong | ⚠️ Weak | ⚠️ Weak |
| Drove org-wide rollout | ⚠️ Weak | ✅ Strong | ✅ Strong |
| Designed the architecture | ✅ Strong | ✅ Strong | ✅ Strong |
| Coordinated security/IT/compliance approval | ⚠️ Weak | ✅ Strong | ✅ Strong |
| Enabled cross-team adoption | ⚠️ Weak | ✅ Strong | ✅ Strong |
| Selected the vendor/platform | ⚠️ Weak | ✅ Strong | ✅ Strong |
| Negotiated procurement and licensing | ❌ N/A | ✅ Moderate | ✅ Strong |
| Established governance and standards | ⚠️ Weak | ✅ Strong | ✅ Strong |

**Honest TPM/Executive Framing for Adopting Existing Tools:**

❌ **Inflated (Dishonest):**
"Built JIRA MCP integration for ticket reporting" 
*(Implies you wrote what Atlassian already publishes)*

✅ **Accurate TPM Framing:**
"Drove enterprise adoption of Atlassian's JIRA MCP server within [Company], navigating security review, IT governance, and cross-instance configuration (cloud + on-prem) to unify ticket reporting and accelerate RCA communication"

✅ **Accurate Executive Framing:**
"Championed enterprise adoption of AI-native developer tooling, selecting Atlassian MCP from competitive evaluation and orchestrating security, IT, and compliance alignment to roll out across cloud and on-prem environments — delivering unified ticket intelligence and reducing mean-time-to-resolution"

**Verbs That Signal Adoption Leadership (Not Building):**
- "Drove adoption of..."
- "Championed enterprise rollout of..."
- "Orchestrated cross-functional deployment of..."
- "Led organizational change to integrate..."
- "Selected, deployed, and operationalized..."
- "Negotiated procurement and led implementation of..."

**Why This Matters for TPM and Executive Roles:**
Building software is often IC engineering work. **Making organizations adopt software** - across security boundaries, compliance reviews, IT change management, and team enablement - is TPM and executive work. For senior roles, the adoption story is often more compelling than the build story.

**Honesty Check:**
Before using "built" or "developed" in a bullet, ask:
1. Did I write the code/design from scratch? → If yes, "built" is fair
2. Did I configure/deploy something that already existed? → Use "deployed", "integrated", "rolled out", "adopted"
3. Did I drive the cross-functional work to make it real in the org? → "Drove adoption", "Championed rollout"
4. Did I make the buy decision? → "Selected", "Evaluated and chose"

Choose the verb that's both accurate AND aligned with the level you're positioning for. Often, the *adoption* framing is stronger than the *building* framing for senior roles.

**Technology Decisions:**
- "Selected Snowflake over Redshift after evaluating 3 platforms"
- "[Verb] adoption of [specific standard/technology] as organizational standard"
- "[Verb] [specific technology] as enterprise [scope] strategy"

**Platform Accountability Examples:**




**Strategic Roadmap:**
- "Defined multi-year platform strategy"
- "Built technical roadmap aligned with business objectives"
- "Established platform governance model"
- "Created center of excellence for data engineering"

**Enterprise-Scale Transformation Indicators:**

Show you've led large-scale change, not just projects:

**Magnitude Signals:**
- Member/user base: "[N]M+ members", "[N]M lives"
- Systems integrated: "[N]+ data sources", "[N] EHR systems"
- Geographic scope: "6 U.S. states", "11-state deployment"
- Financial impact: [$ savings], [$ incentives/revenue enabled]
- Data volume: "[N]M+ transactions", "[N]TB daily processing"

**Complexity Indicators:**
- "Multi-state Medicaid compliance across varying regulations"
- "Payer-provider data exchange spanning 3 health plans and 47 provider organizations"
- "Real-time clinical decision support with sub-100ms latency requirements"
- "HIPAA-compliant data lake supporting analytics, ML, and real-time APIs"

**Transformation Duration:**
- "3-year enterprise platform modernization"
- "18-month regulatory compliance program"
- "Multi-year analytics infrastructure overhaul"
- "Sustained 2-year reduction in implementation timelines"

**Organizational Change Management:**
- "Led adoption across 12 healthcare organizations"
- "Trained 200+ clinicians on new platform capabilities"
- "Managed stakeholder alignment across 8 executive sponsors"
- "Drove cultural shift from waterfall to agile delivery"

**Multi-Stakeholder Coordination:**
- "Collaborated with CMS, state agencies, and health plans"
- "Partnered with C-suite to align platform strategy with business goals"
- "Coordinated across Product, Engineering, Clinical, and Compliance teams"
- "Advised Board of Directors on technology investment decisions"

**Executive Transformation Example:**

❌ Before (Project-level):
"Implemented data integration solution for healthcare company"

✅ After (Transformation-level):

This bullet shows:
- ✅ Magnitude (5M members, 200+ integrations)
- ✅ Duration (3-year program)
- ✅ Leadership (25-person team)
- ✅ Platform ownership (architected)
- ✅ Business impact ($4.2M savings)
- ✅ Technical transformation (legacy → cloud-native)
- ✅ Organizational capability (30 days → 24 hours)

**Output:** Rewritten experience section with every bullet following impact-first formula, key wins prominently positioned, comprehensive quantification, and clear platform ownership/transformation signals for executive evaluation.

---

### Step 4: Summary That Positions

**Purpose:** Create a powerful 3-4 line opening that positions the candidate for the target role without buzzwords or generic language.

**Characteristics of Strong Executive Summaries:**
- Concrete and specific (not generic or vague)
- Quantified impact where possible (numbers, scale, scope)
- Role-relevant technical expertise mentioned explicitly
- Leadership scope indicated (team size, org size, budget)
- No buzzwords like "results-driven," "team player," "detail-oriented"
- No first-person pronouns ("I," "my")
- Reads like executive-level introduction

**3-Line Structure:**

**Line 1: Core Identity + Years + Primary Domain**
"[Role/Title] with [X+] years [primary achievement area/domain]..."

**Line 2: Signature Achievements + Quantified Impact**
"[Specific accomplishments with numbers], serving [scale/scope]..."

**Line 3: Technical Expertise + Strategic Value**
"Deep expertise in [relevant technical areas] and [strategic capabilities]..."

**Process:**
1. Extract most impressive quantifiable achievements from resume
2. Identify 2-3 technical/domain areas most relevant to target role
3. Determine appropriate seniority signals (team size, budget, scope)
4. Craft 3-4 lines that flow naturally without jargon
5. Ensure every claim is backed up by bullets in experience section
6. Read aloud to check for natural, confident tone
7. Verify it matches seniority level of target role

**Common Mistakes to Avoid:**
- Starting with "I am a..." (no first person)
- Generic phrases: "proven track record," "results-oriented"
- Vague claims without quantification
- Skills list instead of achievement summary
- Too long (more than 4 lines)
- Technical jargon not explained

**Output:** 3-4 line professional summary ready to place at top of resume, with quantified impact and executive positioning.

---

### Step 5: ATS Alignment (Keyword Optimization)

**Purpose:** Weave in missing keywords from the job description naturally, without making the resume sound stuffed or robotic.

**Process:**

**1. Keyword Extraction (from JD):**

Before comparing, extract keywords from the JD using the following explicit method:

a. Extract every **noun phrase** that describes a required or preferred qualification (tools, technologies, methodologies, certifications, regulatory frameworks, domain terms)
b. Extract every **verb phrase** that describes a required activity (e.g., "led delivery of," "architected," "managed portfolio of")
c. Categorize each extracted term into: Technical Skill | Methodology | Certification | Regulation/Standard | Domain Term | Seniority Signal
d. Mark each as Required (appears in "Required" section or used 2+ times) vs. Preferred (appears once in "Preferred" section)

**2. Resume Coverage Check (term-by-term):**

For each extracted JD keyword, locate it in the resume and mark:
- ✅ **Exact match** — the term appears in the resume using identical or near-identical phrasing
- ⚠️ **Implied match** — the concept is present but with different terminology (e.g., JD says "FHIR API integration"; resume says "HL7 standards implementation" — related but not an ATS keyword match)
- ❌ **Missing** — the term is absent from the resume entirely

**3. Gap Analysis — three types:**
- **Type A (❌ Missing, Required):** Highest priority — the candidate likely has the skill but it's absent from the resume. Add it via Methods A-D below.
- **Type B (⚠️ Implied, Required):** Medium priority — the terminology needs to be aligned to match what the ATS indexes against.
- **Type C (❌ Missing, Preferred):** Lower priority — add if authentic; skip if fabricating would be required.

**Honesty gate before proceeding:** For each Type A and Type B gap, verify the candidate actually has the skill before adding terminology. Do not add terms the candidate cannot defend in an interview.

**3. Strategic Integration Methods:**

**Method A: Add to existing bullets (preferred)**
Before: "Led data platform implementation"
After: "Led [domain-specific systems] data platform implementation using [domain-specific APIs/standards]"
*(Example for finance: "Led Bloomberg/Reuters market data platform implementation using FIX 4.4 and SWIFT MT messages")*

**Method B: Add Core Competencies section**
Create keyword-rich section after summary:
```
CORE COMPETENCIES
[Domain Area #1] • [Domain Standards & Versions] • [Regulatory Compliance References]
[Major Systems/Tools] • [Cloud/Data Platforms] • [Programming Languages]
[Analytics/Specialized Capabilities] • [Methodology] • [Leadership Scope]
```

**Method C: Spell out acronyms strategically**
First mention: "[Full term spelled out] ([ACRONYM])"
After: "[ACRONYM]" throughout
*(Example: "Statistical Process Control (SPC)" first, then "SPC")*

**Method D: Natural context integration**
"...led implementation of [regulatory framework] compliance initiative, including [specific sub-framework #1] and [specific sub-framework #2] within the [parent industry-standard project] framework..."

**4. Keyword Categories to Address:**

| Category | Examples (illustrative across industries — use what applies to YOUR target role) |
|----------|----------|
| **Technical Skills** | Programming languages, platforms, tools, databases relevant to the target function |
| **Standards** | Industry-specific data standards (e.g., FIX/SWIFT in finance, ISO 20022 in payments, IFC in construction, FHIR/HL7 in healthcare, MIL-STD in defense, ISA-95 in manufacturing) |
| **Regulations** | Industry-specific regulatory frameworks (SOX/Dodd-Frank/Basel in finance, HIPAA/CMS in healthcare, ITAR/DFARS in defense, FDA in biotech/pharma, FERC/NERC in utilities) |
| **Methodologies** | Agile, Scrum, Waterfall, SDLC, Lean, Six Sigma, Kaizen, DMAIC, PRINCE2 |
| **Systems / Platforms** | Industry-major systems (ERP, CRM, EHR, MES, LMS, etc. — use what's standard in your target industry) |
| **Certifications** | Function/industry-specific (PMP, PE, CPA, CFA, CISSP, AWS Certified, RN, JD, etc.) |
| **Domain Terms** | Industry-specific vocabulary validated per Pattern 27 |

**5. Quality Control Checks:**
- Read entire resume aloud — does it sound natural?
- Would a human find it readable and compelling?
- Are keywords used in proper context?
- Did you add any keywords you don't actually possess?
- Are acronyms spelled out on first use?

**Critical Rules:**
- **Never sacrifice clarity for keywords**
- **Never add skills you don't have**
- **Human readability comes first**
- **Keywords must be authentic and contextual**
- **ATS optimization should be invisible to human readers**


### Step 6: Final Polish (Executive-Level Pass)

**Purpose:** Ensure the entire resume reads as a senior candidate from the first line with consistent voice, clarity, and visual hierarchy.

**Polish Checklist:**

### Voice & Tone

**Consistency:**
- Past tense for previous roles, present tense for current role
- Active voice throughout (avoid passive constructions)
- Authoritative but not arrogant tone
- Industry-appropriate formality level

**Executive Tone Refinement:**

Transform passive/junior language into confident leadership voice:

❌ **Avoid (Passive/Junior):**
- "Responsible for managing..." → ✅ "Led" or "Directed"
- "Helped with implementation..." → ✅ "Delivered" or "Drove"
- "Assisted in developing..." → ✅ "Architected" or "Designed"
- "Worked on team to..." → ✅ "Collaborated across X teams to..."
- "Was involved in..." → ✅ Specific action verb
- "Participated in..." → ✅ "Led", "Contributed", or "Drove"
- "Duties included..." → ✅ Delete and rewrite with impact

✅ **Executive Action Verbs by Category:**

**Strategic Leadership:**
- Architected, Spearheaded, Pioneered, Transformed, Established
- Championed, Orchestrated, Steered, Envisioned

**Team Leadership:**
- Directed, Led, Managed, Supervised, Mentored
- Built, Scaled, Developed, Cultivated

**Delivery & Execution:**
- Delivered, Executed, Implemented, Launched, Deployed
- Drove, Completed, Achieved, Accomplished

**Impact & Results:**
- Generated, Achieved, Accelerated, Reduced, Improved
- Increased, Optimized, Enhanced, Streamlined

**Innovation & Creation:**
- Designed, Developed, Created, Engineered, Built
- Innovated, Invented, Conceptualized

**Confident Leadership Tone Examples:**





### Clarity

**Eliminate Ambiguity:**
- No unclear pronouns or vague antecedents
- Technical terms used correctly and consistently
- Acronyms spelled out on first use (where appropriate)
- Numbers formatted consistently (5M vs 5 million vs 5,000,000)

**Readability:**
- Bullets scannable in 2-3 seconds each
- Each bullet makes one clear point
- Complex concepts explained simply
- Jargon minimized (but technical credibility maintained)

### Visual Hierarchy

**Prioritization:**
- Most important information first (recency + impact)
- Strongest bullets at top of each role
- Most relevant experience detailed more thoroughly
- Older/less relevant roles condensed

**Formatting:**
- Clear section breaks with descriptive headers
- Consistent bullet formatting throughout
- Appropriate white space (not too cramped, not too sparse)
- Dates aligned consistently (right or left aligned, pick one)
- Job titles and company names visually distinct
- Bold and italics used purposefully (not excessively)

**Page Length Guidelines:**
- Early career (0-5 years): 1 page
- Mid-career (5-15 years): 1-2 pages
- Senior (15+ years): 2 pages maximum
- Executive (20+ years): 2 pages (edit ruthlessly)

### Executive-Level Signals

**Scope Indicators:**
- Team size: "Led 13-person global team"
- Budget: "[Verb] $[X]M [type] budget"
- Population/users: "Serving [N]M+ [members/users]"
- Geographic scope: "Across 6 U.S. states and territories"
- Systems/data scale: "[N]+ data feeds", "[N]M+ transactions"

**Strategic Framing:**
- Business outcomes emphasized over technical details
- Cross-functional leadership mentioned
- Regulatory compliance and risk mitigation highlighted
- ROI and financial impact quantified
- Strategic initiatives vs. tactical tasks

### Final Checks

**Accuracy:**
- No typos or grammatical errors (run spell check)
- Company names spelled correctly
- Job titles accurate
- Dates add up correctly (no gaps or overlaps unexplained)
- Contact information current and working
- LinkedIn URL functional (if included)

**ATS Compatibility:**
- File saved as .docx or text-based .pdf
- No tables, text boxes, or complex layouts
- Standard fonts used throughout
- All text is actual text (not images)

**Authenticity:**
- Every claim can be substantiated in interview
- Numbers are accurate (not inflated)
- No fabricated achievements or responsibilities

**Output:** Final, polished resume ready for submission with a summary of changes made in this pass, broken down by category (tone, clarity, hierarchy, signals).

---

## Workflow Integration

### Full Optimization (All 6 Steps)

When user requests comprehensive resume optimization:

1. **Start with Step 1** (Positioning) to set strategic context
2. **Run Step 2** (Recruiter Test) for diagnostic assessment
3. **Execute Step 3** (Achievement Rewrite) for content transformation
4. **Create Step 4** (Summary) for opening positioning
5. **Apply Step 5** (ATS Alignment) if job description provided
6. **Finish with Step 6** (Final Polish) for quality assurance

**Timeline:** Present work in stages, getting user feedback after Steps 2, 3, 4, and 6.

### Targeted Optimization

When user has specific needs, jump to relevant step:

- "Is my resume strong?" → **Step 2** (Recruiter Test)
- "Help me rewrite my bullets" → **Step 3** (Achievement Rewrite)
- "Write a professional summary" → **Step 4** (Summary)
- "Tailor this to a job description" → **Step 5** (ATS Alignment)
- "Final review before submitting" → **Step 6** (Final Polish)
- "Make my resume ATS-friendly" → **Format guidelines + Step 5**
- "Add more metrics" → **Step 3** (Quantification Framework)
- "Improve my executive tone" → **Step 6** (Tone Refinement)

### Iterative Approach

**Best Practices:**
- Show work in stages, not all at once
- Get user feedback before proceeding to next step
- Allow user to focus on specific sections if overwhelmed
- Provide rationale for major changes
- Preserve user's authentic voice while elevating impact

---

## Best Practices

### Do's

✅ **Be honest but constructive** - If resume has significant gaps, address them tactfully
✅ **Preserve authenticity** - Never fabricate achievements or exaggerate scope
✅ **Consider industry context** - Healthcare tech emphasizes compliance, scale, integration complexity
✅ **Calibrate to seniority** - IC vs Manager vs Director vs VP have different expectation levels
✅ **Context is king** - A bullet impressive for one role might be table stakes for another
✅ **Lead with impact** - Results first, then how you achieved them
✅ **Quantify everything possible** - Numbers = credibility at executive level

### Don'ts

❌ **Missing metrics** - No numbers = no credibility at senior levels
❌ **Buried lede** - Important achievements hidden in middle of long bullets
❌ **Inconsistent depth** - Some bullets hyper-detailed, others vague
❌ **Keyword stuffing** - ATS optimization that makes resume unreadable
❌ **Acronym overload** - Assuming reader knows niche abbreviations
❌ **Responsibilities lists** - What job required vs what you achieved
❌ **Wall of text** - Long paragraphs instead of scannable bullets

---

## Common Pitfalls & Solutions

### Pitfall 1: Resume is a Job Description
**Problem:** Lists responsibilities instead of achievements
**Solution:** Apply Step 3 formula - lead with impact, add metrics, show business outcome

### Pitfall 2: No Quantification
**Problem:** All bullets are qualitative statements
**Solution:** Use Quantification Framework - scale, financial, team, time, quality, efficiency

### Pitfall 3: Inconsistent Seniority
**Problem:** Some bullets sound junior, others senior
**Solution:** Apply Executive Tone Refinement throughout - consistent action verbs, strategic framing

### Pitfall 4: ATS Incompatible Format
**Problem:** Beautiful design that ATS can't parse
**Solution:** Follow ATS Format Guidelines - simple formatting, standard sections, .docx file

### Pitfall 5: Generic Summary
**Problem:** Generic self-description ("Results-driven professional with proven track record...") — buzzword-laden, no specifics, no numbers
**Solution:** Use Step 4 structure - specific role, quantified impact, technical expertise

### Pitfall 6: Keywords Stuffed Unnaturally
**Problem:** Reads like a dictionary, not a resume
**Solution:** Step 5 integration methods - add to existing bullets, use Core Competencies section

### Pitfall 7: Strongest Wins Buried
**Problem:** Best achievements are 4th or 5th bullet
**Solution:** Position Key Wins first in each role

---

## Output Format

For each step completed, provide:

1. **What changed**: Clear before/after or summary of improvements
2. **Why it matters**: Brief explanation of the strategic value
3. **Suggested next step**: Guide user through the workflow
4. **Request feedback**: Ensure user agrees before proceeding
5. **Preserve context**: Keep track of target role and positioning strategy

---

## Additional Use Cases

This skill can also help with:

### LinkedIn Profile Optimization
- Same principles, different format
- Headline = Professional Summary condensed
- About section = Expanded summary + personality
- Experience bullets = Same impact-driven formula
- Skills section = Keyword optimization

### Cover Letter Alignment
- Use resume content to inform cover letters
- Draw from Key Wins for opening paragraph
- Demonstrate culture fit using same tone
- Reference specific quantified achievements

### Interview Preparation
- Practice explaining resume achievements in detail
- Prepare STAR method examples from resume bullets
- Anticipate questions about gaps or transitions
- Prepare to expand on quantified metrics

### Promotion Packets
- Internal career advancement documentation
- Emphasize strategic contributions and business impact
- Show progression and increasing scope
- Document ROI and cost savings

### Executive Bios
- Condense resume into 150-250 word narrative
- Lead with biggest career achievement
- Include current role and 2-3 signature accomplishments
- Close with expertise and leadership philosophy

---

## Industry-Specific Guidance

### Healthcare Technology Roles

**What matters most:**
- Regulatory compliance (CMS mandates, HIPAA)
- Scale (members served, data volume)
- Integration complexity (number of systems/sources)
- Quality scores and compliance rates
- Cost savings and ROI
- Federal mandate deadlines met

**Key terminology:**
- Interoperability, FHIR, HL7, USCDI
- Value-based care, population health
- CMS-9115-F, CMS-0057-F, Da Vinci
- Epic, Cerner, Athena EHR systems
- HEDIS, risk adjustment, quality measures

**Emphasize:**
- Data platform architecture at scale
- Cross-functional technical leadership
- Regulatory deadline performance
- Member/patient impact
- Quality and compliance metrics

---

## Final Notes

**Remember the Goal:**
Resumes don't get jobs; they get interviews. A resume should:
- Pass the 10-second recruiter scan
- Survive ATS screening
- Position candidate at right seniority level
- Open doors to conversations where candidate can elaborate

**The Standard:**
Every bullet should pass this test:
- Does it lead with impact?
- Does it include quantification?
- Does it show scope?
- Does it demonstrate business value?
- Does it sound like an executive wrote it?

**The Process:**
1. Understand positioning strategy
2. Diagnose current state
3. Transform content
4. Optimize opening
5. Align with requirements
6. Polish to executive level

**Success Metrics:**
- Resume passes 10-second test with clear value proposition
- ATS systems parse correctly (test with Jobscan or similar)
- Keywords naturally integrated without stuffing
- Every bullet quantified with at least one metric
- Tone consistently executive-level throughout
- User confident submitting to target roles

---

## Appendix A: Named Entity Reference Lists

*This appendix consolidates the named companies, analyst firms, regulatory bodies, and platforms referenced throughout the skill. Patterns and anti-patterns that need a "Tier-1 employer" or "industry analyst" anchor should reference the relevant list here rather than hardcoding a single name, so the assistant can choose the closest match for the candidate's industry, geography, and seniority.*

### How to use this appendix

1. When a pattern says "see Appendix A.N," scan that list for the entity that best fits the candidate's context (industry, geography, employer tier, target role).
2. Lists are **illustrative, not exhaustive.** If the candidate's actual employer, vendor, regulator, or platform is not listed, that is **not** a signal to omit the entity — apply Pattern 27 (Business Context Validation) to confirm the correct named entity and use it.
3. **Sanitization rule:** These lists exist so the skill can name landmarks for orientation, not so candidates name clients. Pattern/Anti-Pattern usage of these names describes a *category* the candidate's work falls under. Candidate-side resume content still follows the confidentiality rules in Anti-Pattern 18.
4. **Currency:** Industry landmarks shift. Lists below reflect a 2026 snapshot. Apply Pattern 27 to validate that a given entity is still current and named as listed.

---

### A1. Tier-1 / High-Bar Tech Employers

*Used by: Pattern 9 (Specific Company Identifiers), Pattern 16 (External Credibility Markers), Pattern 17 (Tenure as Strength Signal).*

Recognizable global employers whose name on a resume carries pattern-recognition weight in tech recruiting:

- **US hyperscalers / megacaps:** Google (Alphabet), Meta, Microsoft, Amazon (incl. AWS), Apple, Netflix, Nvidia, Tesla
- **High-bar enterprise software:** Salesforce, Oracle, Adobe, ServiceNow, Workday, Atlassian, Snowflake, Databricks, MongoDB, Stripe, Shopify, Block (Square), Twilio, Cloudflare, Datadog, HashiCorp, Palantir
- **High-bar consumer / marketplace tech:** Airbnb, Uber, DoorDash, Lyft, Pinterest, Snap, Spotify, Reddit
- **Top-tier AI labs / research-heavy employers:** Anthropic, OpenAI, Google DeepMind, Meta AI / FAIR, Microsoft Research, Apple ML Research
- **Top-tier semiconductor / hardware:** Nvidia, AMD, Intel, Qualcomm, Broadcom, ASML, TSMC, ARM
- **Top-tier APAC tech:** Tencent, Alibaba (incl. Ant Group), ByteDance, Baidu, Samsung Electronics, Sony, Rakuten, Coupang, Mercado Libre
- **Top-tier European tech:** SAP, Spotify, ASML, Klarna, Adyen, Revolut, Bolt

### A2. Cloud Hyperscalers and Major Cloud Platforms

*Used by: Pattern 16 (Architect-role examples), Pattern 18 (Verifiability hosts for cloud docs), Function Scaffold: Software Engineering.*

- **Hyperscalers:** AWS (Amazon Web Services), Microsoft Azure, Google Cloud Platform (GCP)
- **Second-tier global cloud:** Oracle Cloud Infrastructure (OCI), IBM Cloud, Alibaba Cloud, Tencent Cloud, Huawei Cloud
- **Specialty / regional cloud:** DigitalOcean, Linode (Akamai), Vultr, Hetzner, OVHcloud, Scaleway
- **Sovereign / regulated cloud:** AWS GovCloud, Azure Government, Google Public Sector Cloud, Oracle Government Cloud, OVHcloud Sovereign, T-Systems / Bleu (EU sovereign), Gaia-X aligned providers

### A3. Industry Analyst Firms

*Used by: Pattern 32 (Analyst-Influence Bullets).*

Analyst firms whose reports influence enterprise buying decisions and whose engagement signals senior-platform credibility:

- **Top-tier generalist IT analysts:** Gartner, Forrester, IDC
- **Specialty / second-tier IT analysts:** 451 Research (S&P Global Market Intelligence), Constellation Research, RedMonk, Omdia (formerly Ovum), GigaOm, ISG, Everest Group, HFS Research, Nucleus Research
- **Vertical/specialty analysts:** KLAS Research (healthcare IT), Celent (financial services), Aite-Novarica (financial services), Chartis Research (risk/finance), Frost & Sullivan (cross-industry)
- **Equity/sell-side analyst houses that move enterprise narrative:** Morgan Stanley, Goldman Sachs, JPMorgan, Barclays, UBS technology research teams — when a candidate has briefed equity analysts in addition to industry analysts, this is a distinct and rarer signal

### A4. Analyst Report Brand Names (Recognizable Frameworks)

*Used by: Pattern 32 (Analyst-Influence Bullets).*

Named analyst-report formats are recognizable shorthand for category-leader positioning:

- **Gartner:** Magic Quadrant (MQ), Critical Capabilities, Hype Cycle, Peer Insights, Market Guide
- **Forrester:** Wave, New Wave, Now Tech, Tech Tide, Total Economic Impact (TEI)
- **IDC:** MarketScape, MarketShare, FutureScape
- **Everest Group:** PEAK Matrix
- **ISG:** Provider Lens
- **HFS Research:** Horizons
- **KLAS Research:** Best in KLAS, Category Leader rankings (healthcare IT)
- **GigaOm:** Radar reports

### A5. Major Consulting Firms and Systems Integrators

*Used by: Anti-Pattern 18 (Client Name Disclosure context — these are the employer types where vendor-side confidentiality rules apply most strictly).*

- **MBB strategy consulting:** McKinsey & Company, Boston Consulting Group (BCG), Bain & Company
- **Big Four consulting / audit-adjacent:** Deloitte, PwC (PricewaterhouseCoopers), EY (Ernst & Young), KPMG
- **Tier-2 strategy / management consulting:** Oliver Wyman, A.T. Kearney (Kearney), Roland Berger, L.E.K. Consulting, Strategy& (PwC), AlixPartners, FTI Consulting
- **Global systems integrators:** Accenture, IBM Consulting, Capgemini, Cognizant, Infosys, TCS (Tata Consultancy Services), Wipro, HCLTech, Tech Mahindra, NTT Data, DXC Technology, Atos, Genpact
- **Federal / regulated-market integrators:** Booz Allen Hamilton, Leidos, CACI, SAIC, ManTech, GDIT (General Dynamics IT), Peraton, MITRE (FFRDC — not a contractor but frequently named)
- **Healthcare/life-sciences specialist consulting:** ZS Associates, IQVIA, McKinsey Health Institute, Trinity Life Sciences

### A6. Developer Tooling and Platform Vendors

*Used by: Pattern 24 (Domain-Functional Vocabulary), Anti-Pattern 13 (Buzzword Replacement of Specifics — when "evaluated platforms" should name them).*

- **Source control / DevEx:** GitHub, GitLab, Bitbucket (Atlassian), Azure DevOps
- **Issue tracking / project mgmt:** Jira (Atlassian), Linear, Asana, Monday.com, Trello, ClickUp, Shortcut
- **Wiki / docs:** Confluence (Atlassian), Notion, Coda, GitBook
- **CI/CD:** GitHub Actions, CircleCI, Jenkins, GitLab CI, Buildkite, Argo CD, Spinnaker
- **Observability / monitoring:** Datadog, New Relic, Splunk, Dynatrace, Grafana, Honeycomb, Sentry, AppDynamics
- **Data warehousing / lakehouse:** Snowflake, Databricks, BigQuery (Google), Redshift (AWS), Synapse (Microsoft), ClickHouse
- **Data orchestration / transformation:** dbt (Labs), Airflow, Dagster, Prefect, Fivetran, Airbyte
- **ML platforms / MLOps:** SageMaker (AWS), Vertex AI (GCP), Azure ML, Databricks MLflow, Weights & Biases, Hugging Face
- **Container / orchestration:** Kubernetes, Docker, OpenShift (Red Hat), Rancher (SUSE), Nomad (HashiCorp)
- **Infrastructure-as-code / config:** Terraform (HashiCorp), Pulumi, Ansible, Chef, Puppet, CloudFormation (AWS), Bicep (Azure)

### A7. Enterprise SaaS Platforms by Category

*Used by: Pattern 24 (Domain-Functional Vocabulary), Function Scaffolds.*

- **CRM:** Salesforce, HubSpot, Microsoft Dynamics 365, Zoho, Pipedrive, SugarCRM
- **ERP:** SAP (S/4HANA, ECC), Oracle (NetSuite, Fusion, JD Edwards, PeopleSoft), Workday, Microsoft Dynamics 365 F&O, Infor, Epicor
- **HCM / payroll:** Workday, SAP SuccessFactors, Oracle HCM Cloud, ADP, UKG, Rippling, BambooHR, Gusto
- **ITSM / ESM:** ServiceNow, Atlassian Jira Service Management, BMC Helix, Freshservice, Ivanti, Cherwell
- **Marketing automation:** Marketo (Adobe), HubSpot, Salesforce Marketing Cloud, Eloqua (Oracle), Pardot, Braze, Iterable, Klaviyo, Customer.io
- **Customer success platforms:** Gainsight, ChurnZero, Totango, Catalyst, Vitally, Planhat
- **Collaboration / messaging:** Slack (Salesforce), Microsoft Teams, Zoom, Google Workspace, Webex
- **Document / e-signature:** DocuSign, Adobe Sign, Dropbox Sign, PandaDoc
- **Customer support:** Zendesk, Salesforce Service Cloud, Freshdesk, Intercom, Front, Help Scout

### A8. Verifiability Hosts for Pattern 18 (Embedded Hyperlinks on Named Projects)

*Used by: Pattern 18 (Embedded Hyperlinks on Named Projects).*

External platforms where senior IC contributions can be independently verified:

- **Code:** GitHub, GitLab, Bitbucket — repos, contributions, commit history
- **Patents:** USPTO (United States Patent and Trademark Office), EPO (European Patent Office), JPO (Japan), CNIPA (China), Google Patents (aggregator), Lens.org (aggregator)
- **Academic publications:** ACM Digital Library, IEEE Xplore, arXiv, Google Scholar, Semantic Scholar, ResearchGate, SSRN (social sciences/finance), PubMed (life sciences), DBLP (computer science bibliography), DOI.org links
- **Conference talks:** Conference site session pages, YouTube official conference channels, InfoQ, SlideShare/Speaker Deck (slides)
- **Standards / spec authorship:** W3C, IETF (RFC), ISO, IEEE Standards Association, OASIS, Linux Foundation (CNCF, OpenJS, etc.)
- **Open-source ecosystem:** Apache Software Foundation project pages, CNCF landscape, npm/PyPI/crates.io/Maven Central (package ownership)
- **Cloud platform docs (for features candidate owned):** AWS docs / what's-new pages, Azure docs / updates, Google Cloud docs / release notes

### A9. Job-Search Infrastructure and ATS Platforms

*Used by: ATS-Friendly Formatting Guidelines, Anti-Pattern 11 (Missing Contact Channels), Workflow Integration.*

- **ATS / recruiting platforms:** Workday Recruiting, Greenhouse, Lever, iCIMS, SmartRecruiters, Taleo (Oracle), SAP SuccessFactors Recruiting, Jobvite, Ashby, BambooHR ATS, Rippling ATS
- **Job boards / aggregators:** LinkedIn, Indeed, Glassdoor (Indeed-owned), ZipRecruiter, Monster, Built In, AngelList Talent (Wellfound), Otta (Welcome to the Jungle), Dice, Hired
- **Resume scanning / ATS-check tools:** Jobscan, Resume Worded, Teal, Enhancv, Rezi, Skillsyncer
- **Professional networks for recruiter reach:** LinkedIn (dominant in NA/EU), Xing (DACH region), Wellfound (startups), Lunchclub, Polywork

### A10. Healthcare EHR and Clinical Information Systems

*Used by: Function Scaffold: Healthcare Clinical, Pattern 27 (Business Context Validation — healthcare).*

- **Major EHRs (US):** Epic, Oracle Health (formerly Cerner), MEDITECH, athenahealth (Athena), Allscripts/Veradigm, NextGen, eClinicalWorks
- **Major EHRs (Global):** InterSystems TrakCare, ChipSoft (HiX, NL/EU), Dedalus (EU), Philips Tasy (LATAM)
- **VA / DoD systems:** VistA (legacy VA), MHS GENESIS (DoD, Oracle Health-based)
- **Specialty clinical platforms:** Pyxis (BD, dispensing), GE Centricity, Sectra (imaging), Change Healthcare (claims/payments — now Optum)
- **Healthcare data / interoperability:** Redox, 1upHealth, Innovaccer, Health Gorilla, Particle Health, Datavant, Health Catalyst

### A11. Regulatory Bodies and Frameworks by Industry

*Used by: Pattern 27 (Business Context Validation), Pattern 28 (Industry/Role Inference), Function Scaffolds (all regulated families).*

- **US healthcare:** HHS, CMS (Medicare/Medicaid), FDA, HIPAA, HITECH, CLIA, Joint Commission, HEDIS, MIPS/MACRA, USCDI, HL7/FHIR (standards); CMS-9115-F, CMS-0057-F (specific rules); Da Vinci Project (implementation guide accelerator)
- **US financial services:** SEC, FINRA, OCC, Federal Reserve, FDIC, CFTC, CFPB, FASB, PCAOB; SOX, Dodd-Frank, GLBA, FCRA, Reg E/Z, Basel III/IV, CCAR, DFAST, IFRS 9, CECL
- **US defense / federal:** DoD, NSA, DISA, GSA, NIST (SP 800-53, 800-171, CSF), FedRAMP, FISMA, CMMC, ATO/RMF, ITAR, EAR, DFARS, FAR; clearance levels (Public Trust, Secret, TS, TS/SCI)
- **US energy / utilities:** NERC, FERC, NRC (nuclear), DOE; NERC CIP, FERC Order 2222
- **US aviation / aerospace:** FAA, NASA; DO-178C, DO-254, ARP4754A, AS9100, MIL-STD; FAA Part 23/25/27/29
- **EU:** GDPR, NIS2, DORA (financial), DMA, DSA, AI Act, EU MDR (medical devices), eIDAS, PSD2/PSD3
- **UK:** FCA, PRA, ICO; UK GDPR
- **Cross-border data:** APEC CBPR, Standard Contractual Clauses (SCCs), Adequacy Decisions
- **Industry-agnostic security/privacy:** ISO/IEC 27001, 27017, 27018, 27701; SOC 2 (Type I/II); PCI DSS; CSA STAR
- **Telecom:** FCC (US), Ofcom (UK), 3GPP (standards), ETSI, ITU-T

### A12. Tier Descriptors for Sanitized Client/Employer References

*Used by: Anti-Pattern 18 (Client Name Disclosure), CONTRIBUTING.md sanitization checklist, peer-review-sourced bullet templates.*

Generic tier descriptors that replace specific named clients in vendor-side, consulting, agency, or SaaS-implementation resume bullets:

- **Scale tiers:** "Fortune [N] enterprise" (10/50/100/500/1000), "Global 2000," "FTSE 100/250," "Nikkei 225," "DAX 40," "$[X]-billion-revenue enterprise"
- **Funding tiers:** "Series [A–F] startup," "growth-stage startup," "publicly-traded enterprise," "PE-backed portfolio company," "unicorn-tier (>$1B valuation) private company"
- **Functional / vertical descriptors:** "Tier-1 global investment bank," "regional commercial bank," "money-center bank," "global asset manager," "national health insurer," "academic medical center," "integrated delivery network (IDN)," "Fortune 500 retailer," "global CPG manufacturer," "Tier-1 automotive OEM," "state agency client," "federal civilian agency," "DoD systems integrator," "intelligence community customer"
- **Geographic descriptors:** "multi-region engagement," "EMEA-headquartered enterprise," "APAC-headquartered telecom," "LATAM-based fintech"

---

## Quick Reference Card

**For Users:** When requesting optimization, provide:
1. Target role title
2. Industry/sector
3. Current resume
4. Job description (if targeting specific role)
5. Specific concerns or focus areas

**For the assistant (Claude, Gemini, or other LLM):** Follow this sequence:
1. Confirm positioning (Step 1)
2. Assess current state (Step 2)
3. Transform bullets (Step 3)
4. Create summary (Step 4)
5. Optimize keywords (Step 5)
6. Final polish (Step 6)

Always show work in stages and get feedback between steps.
