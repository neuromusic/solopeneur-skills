# Solopreneur Skills Library

A Claude Code plugin marketplace of **45 structured playbooks and frameworks for solopreneurs**, covering everything from validating your first idea to scaling beyond yourself.

Each skill is a self-contained playbook with step-by-step frameworks, decision trees, templates, real examples, and common mistakes. The library is split into **nine themed plugins** so you install only the slice you need.

---

## Install

Add the marketplace once:

```
/plugin marketplace add neuromusic/solopeneur-skills
```

Then install whichever plugins you want:

```
/plugin install solo-sales@solopreneur-skills
/plugin install solo-marketing@solopreneur-skills
```

Browse everything on offer with `/plugin` and update later with `/plugin update`.

> **Why nine plugins instead of one?** Every installed skill's description sits in Claude's context all the time. Installing all 45 at once costs roughly 9k tokens of always-on context (`claude plugin details <name>` shows the exact figure per plugin). Pick the two or three plugins that match what you're working on.

**Prefer to do it by hand?** Every skill is still a plain file — copy `skills/<name>/SKILL.md` into your Claude skills directory and it works on its own.

Each skill's frontmatter lists **trigger phrases** — the phrases that tell Claude to reach for that playbook. Asking *"help me validate my idea"* pulls in `idea-validation`.

---

## The Plugins

### `solo-validation` — Idea & Market Validation

Stress-test an idea before investing time or money.

| Skill | Description |
|-------|-------------|
| [Idea Validation](skills/idea-validation/SKILL.md) | Validate a business idea before investing time or money |
| [Market Research](skills/market-research/SKILL.md) | Size a market, map the landscape, and identify trends |
| [Niche Selection](skills/niche-selection/SKILL.md) | Find and score profitable niches worth pursuing |
| [Competitive Analysis](skills/competitive-analysis/SKILL.md) | Deep-dive on specific competitors and find exploitable gaps |
| [Business Model Canvas](skills/business-model-canvas/SKILL.md) | Design how your business creates, delivers, and captures value |

### `solo-brand` — Brand & Positioning

Decide what the business stands for and how it gets described.

| Skill | Description |
|-------|-------------|
| [Brand Identity](skills/brand-identity/SKILL.md) | Build a complete brand identity from scratch or refresh an existing one |
| [Positioning Strategy](skills/positioning-strategy/SKILL.md) | Craft a differentiated market position and translate it into messaging |
| [Naming & Domains](skills/naming-and-domains/SKILL.md) | Choose the right name and secure a matching domain |
| [Business Plan](skills/business-plan/SKILL.md) | Write a business plan adapted for solo operators |

### `solo-product` — Product & Launch

Decide what to build and how to put it in front of people.

| Skill | Description |
|-------|-------------|
| [MVP Planning](skills/mvp-planning/SKILL.md) | Scope your first version and define what "done" looks like |
| [Product Roadmap](skills/product-roadmap/SKILL.md) | Prioritize features using RICE and manage your roadmap sustainably |
| [Product Launch](skills/product-launch/SKILL.md) | Plan a launch from waitlist to week-one momentum |
| [Go-to-Market Strategy](skills/go-to-market/SKILL.md) | Define ICP, choose channels, and execute a 90-day GTM plan |

### `solo-finance` — Pricing & Finance

Set prices and keep the books straight.

| Skill | Description |
|-------|-------------|
| [Pricing Strategy](skills/pricing-strategy/SKILL.md) | Set optimal prices using value-based frameworks |
| [Revenue Model Design](skills/revenue-model-design/SKILL.md) | Design and stack sustainable revenue streams |
| [Unit Economics](skills/unit-economics/SKILL.md) | Calculate CAC, LTV, payback period, and improve each lever |
| [Financial Planning](skills/financial-planning/SKILL.md) | Budget, forecast revenue, and manage cash flow |
| [Bookkeeping Basics](skills/bookkeeping-basics/SKILL.md) | Track income and expenses, reconcile accounts, and prep for tax time |
| [Tax Planning](skills/tax-planning/SKILL.md) | Quarterly taxes, deductions, S-Corp election, and year-end strategy |

### `solo-sales` — Sales & Proposals

Turn strangers into signed contracts without a sales team.

| Skill | Description |
|-------|-------------|
| [Sales Funnel Design](skills/sales-funnel-design/SKILL.md) | Map your funnel, benchmark conversions, and fix drop-off points |
| [Outreach & Prospecting](skills/outreach-and-prospecting/SKILL.md) | Build a prospecting system with cold outreach sequences that get replies |
| [Proposal Writing](skills/proposal-writing/SKILL.md) | Write proposals that win — structure, pricing psychology, and follow-up |
| [Negotiation](skills/negotiation/SKILL.md) | Handle price pushback, stalls, and contract terms with confidence |
| [Closing Deals](skills/closing-deals/SKILL.md) | Move warm prospects to signed contracts with repeatable closing techniques |
| [Grant Writing Framework](skills/grant-writing-framework/SKILL.md) | Write winning grant proposals — research, narrative, budget, and evaluation plans |

### `solo-marketing` — Marketing & Content

Get found and get read on a solo budget.

| Skill | Description |
|-------|-------------|
| [Content Strategy](skills/content-strategy/SKILL.md) | Plan content, choose channels, and build a repurposing workflow |
| [Copywriting](skills/copywriting/SKILL.md) | Write landing pages, emails, and ads using AIDA, PAS, and FAB |
| [Email Marketing](skills/email-marketing/SKILL.md) | Build lists, write sequences, and improve open and click rates |
| [SEO Strategy](skills/seo-strategy/SKILL.md) | Research keywords, optimize pages, and build backlinks |
| [Social Media Marketing](skills/social-media-marketing/SKILL.md) | Choose platforms, grow followers, and drive conversions from social |
| [Paid Advertising](skills/paid-advertising/SKILL.md) | Run and optimize ads on Google, Facebook, and LinkedIn |

### `solo-customers` — Customer Success

Keep the customers you already won.

| Skill | Description |
|-------|-------------|
| [Customer Onboarding](skills/customer-onboarding/SKILL.md) | Design onboarding flows that drive activation and reduce early churn |
| [Customer Retention](skills/customer-retention/SKILL.md) | Measure churn, analyze why it happens, and fix it systematically |
| [Customer Feedback](skills/customer-feedback/SKILL.md) | Collect, organize, and act on feedback without losing focus |
| [Support Systems](skills/support-systems/SKILL.md) | Set up support that scales without consuming your day |

### `solo-operations` — Operations & Systems

Build the machinery so the business doesn't run on memory.

| Skill | Description |
|-------|-------------|
| [Project Management](skills/project-management/SKILL.md) | Organize projects, prioritize tasks, and plan your week effectively |
| [Automation Workflows](skills/automation-workflows/SKILL.md) | Identify, design, and build automations using Zapier, Make, or n8n |
| [Scaling Strategy](skills/scaling-strategy/SKILL.md) | Automate, delegate, build SOPs, and grow beyond solo operations |
| [Legal Essentials](skills/legal-essentials/SKILL.md) | LLC formation, contracts, IP protection, and liability basics |
| [SOP Generator](skills/sop-generator/SKILL.md) | Turn recordings, transcripts, and brain dumps into team-ready SOPs |
| [Spreadsheet Automation](skills/spreadsheet-automation/SKILL.md) | Turn Google Sheets into a database and workflow engine with Apps Script |

### `solo-productivity` — Focus & Wellbeing

Protect the one resource a solo business can't replace: you.

| Skill | Description |
|-------|-------------|
| [Time Management](skills/time-management/SKILL.md) | Time-block your calendar, protect deep work, and avoid burnout |
| [Goal Setting & OKRs](skills/goal-setting-okrs/SKILL.md) | Set and track goals from vision down to weekly priorities |
| [Mental Health Psychoeducation](skills/mental-health-psychoeducation/SKILL.md) | Learn about conditions, therapy modalities, and coping techniques — educational only, not medical advice |
| [Reclaim Your Brain](skills/reclaim-your-brain/SKILL.md) | Turn AI conversations into deep learning via Socratic questioning instead of answer-collecting |

---

## How to Use

Each skill is a self-contained playbook with:

- Clear phases and steps to follow
- Practical frameworks and templates
- Decision trees and worked examples
- Common mistakes to avoid
- Solopreneur-specific adaptations

**Starting a new venture?** Install `solo-validation`, `solo-brand`, and `solo-finance` and work through them in that order.

**Growing an existing business?** Install just the plugin that matches your bottleneck — `solo-sales` if the pipeline is dry, `solo-customers` if churn is the problem, `solo-operations` if you're the bottleneck.

**Not sure which skill you need?** Just describe the problem. The trigger phrases in each skill's frontmatter let Claude pick the right playbook on its own.

---

## Repository Layout

```
.claude-plugin/marketplace.json   # the nine plugin definitions
skills/<skill-name>/SKILL.md      # 45 playbooks, one directory each
```

All nine plugins share this single `skills/` tree — no file is duplicated. Adding a skill means
adding one directory and listing it in one plugin's `skills` array.

Validate changes with:

```
claude plugin validate .
```

---

## License

MIT — see [LICENSE](LICENSE).
