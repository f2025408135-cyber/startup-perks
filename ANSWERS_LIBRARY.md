# ANSWERS_LIBRARY.md — Copy-Paste Application Text (build once, reuse everywhere)

> Fill the `[PLACEHOLDERS]` once with your partner. Every application then takes ~15 minutes. Consistency across applications is the pass condition — reviewers and bots check that your website, deck, and form answers match word-for-word.

---

## 1. Company description — three lengths

**50 words (forms, dropdowns):**
> [COMPANY] is an [CATEGORY, e.g. "AI-native operations platform"] that [ONE-SENTENCE WHAT] for [CUSTOMER]. Founded in [YEAR] by [PARTNER NAME] ([DE/AT-based, ex-…]) and Moiz ([PK-based, …]). Bootstrapped, pre-seed, incorporated in [COUNTRY]. Building on [PRIMARY AI STACK, e.g. "Claude/GPT-4.1 via Azure OpenAI + Bedrock"].

**100 words (AWS/Microsoft):**
> [COMPANY] helps [ICP] achieve [OUTCOME] by [MECHANISM]. Unlike [INCUMBENT], we [DIFFERENTIATOR]. Our product is live at [DOMAIN]; current traction: [METRIC 1], [METRIC 2], [METRIC 3 with dates]. We are raising [no funding / pre-seed] and project [12-month spend plan — see §4]. Planned workloads on your platform: [SERVICE LIST].

**200 words (Google/Anthropic/accelerator short forms):**
> Problem: [2 sentences with numbers]. Solution: [2 sentences + demo link]. Why now: [1 sentence]. AI architecture: [model pipeline — inference workload, fine-tuning, data flywheel — name the provider's stack]. Traction: [3 metrics + links]. Team: [partner bio 1 line], [Moiz bio 1 line]. Why [PROGRAM]: [1 sentence naming their specific services you'll consume].

## 2. Traction statement (Google requires public links)

> Traction (all verifiable via public links): [X] waitlist signups ([link]), [Y] GitHub stars / commits ([link]), [N] LOIs / pilot conversations ([attachment]), demo video ([YouTube link]), press/launch post ([link]).
> Funding status: **Bootstrapped / self-funded** — we are [raising / not yet raising] a pre-seed round of [amount].

⚠️ Never dress grants or F&F money up as a "round" — Google explicitly excludes angel/F&F/crowdfunding from Scale-tier eligibility.

## 3. "Why [provider] / how will you use the credits" — per program

**AWS:** "We will run [PRODUCT] on EC2/EKS, RDS [engine], S3, CloudFront, and consume LLM inference via **Amazon Bedrock** ([models]) — approx [X]M tokens/month. Credits cover [12-month ramp: dev → production]. Expected services count: [8-10] distinct workloads. Spend projection attached from the AWS Pricing Calculator: [link]."
**Microsoft:** "[9] workloads: App Service, AKS, Azure SQL, Blob, Functions, Service Bus, Application Insights, Container Registry, **Azure OpenAI/Foundry** ([models]). Milestone plan: 5 workloads live within 30 days of incorporation, 10+ by day 90, ~$3k/mo sustained by month 4."
**Google:** "Gemini [model] is the foundation of our primary product (not a bolt-on): [architecture detail]. Workloads: Cloud Run, Cloud SQL, BigQuery, Vertex AI, Memorystore, Pub/Sub, GCS, Cloud Build, Artifact Registry. AI-first justification: [inference/fine-tuning/data-flywheel detail]."
**Anthropic:** "Claude [model] powers [core loop: e.g. 'the analysis agent that …']. Projected [X]M tokens/month by month 6. We use the first-party API (not Bedrock/Vertex) for [reason]."

## 4. 12-month credit-spend projection (the table reviewers want)

| Month | Workloads live | Projected spend | Credit drawdown | Cash |
|---|---|---|---|---|
| M1-2 | Dev/staging: compute, managed DB, storage, CI, observability (4-6) | €400-800 | 100% credit | €0 |
| M3-4 | + inference/API, queue, vector DB (7-8) | €1,500-3,000 | 100% credit | €0 |
| M5-8 | Production: autoscaled inference + model API spend (10+) | €3,000-6,000 | ~90% credit | €0-500 |
| M9-12 | Scale + enterprise pilots; credit tail | €4,000-8,000 | 60-70% credit | €1,000-2,500 |

Rules: name services + units; generate the numbers in the vendor's own pricing calculator and paste the link; state "credits fully consumed by month [20-22], before expiry."

## 5. Security & compliance paragraph

> [COMPANY] processes customer data on [EU regions — eu-central-1 (Frankfurt) / westeurope]. GDPR-compliant DPA available; data residency EU by default; least-privilege IAM; audit logging enabled; SOC 2 roadmap begins [quarter]. Security contact: security@[domain].

## 6. Team bios (1 line each, with matching LinkedIn URLs)

- [PARTNER]: [ROLE] — [credential/track record], based [CITY, DE/AT].
- Moiz [LAST NAME]: [ROLE] — [credential], based Lahore/Karachi, PK.

## 7. Referral-hunt outreach template (Week 2-4 org hunt)

> Subject: Pre-seed AI startup — Activate Provider Org ID / Investor Network code?
> Hi [NAME], we're [COMPANY] — [1-line description], incorporated in [COUNTRY], pre-seed, building on [stack]. We're applying to AWS Activate Portfolio and Microsoft for Startups and understand [ORG] is an Activate Provider / Investor Network member. Could you share your Org ID / referral code and confirm our association on the provider side? Happy to share the deck ([link]). Thanks — [PARTNER].

## 8. Deck outline (NVIDIA requires upload; accelerators expect ≤15 slides)

1 Problem · 2 Solution + demo · 3 Why now / AI-first architecture · 4 Market · 5 Business model · 6 Traction (numbers + links) · 7 GTM · 8 Team · 9 12-month roadmap incl. cloud-spend projection · 10 The ask / use of credits

## 9. Gotcha cheatsheet

- Never create a **Datadog** account before the referral application
- Microsoft sign-in = **personal** MSA + **personal** LinkedIn (company-domain emails fail)
- Google: email domain = website domain = billing domain; don't subscribe to paid Workspace within 31 days before applying
- Anthropic credits: first-party API only; gated on institutional funding; **one shot per company**
- AWS Portfolio: Org ID is confidential & case-sensitive; re-awards pay the difference; keep the same provider
- Kiro free offer: excludes Germany — don't plan on it
- Credits expire (1-2 yrs AWS / 2 yrs MS / 2 yrs Google) — under-consumption blocks future top-ups
- Declare AI-generated text in Austrian aws grant applications (external-source rule)