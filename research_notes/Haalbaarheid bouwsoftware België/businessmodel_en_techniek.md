# Businessmodel en techniek: haalbaarheid van custom bouwsoftware (vertical SaaS) door een solo developer in Vlaanderen, stand eind 2026

Method note for the report writer: research was done 14 Nov 2026 via web search only. Direct page fetches of vendor and government sites (robaws.com, vlaio.be, recommand.eu, bryntum.com) were blocked by the session's network allowlist, so all figures below come from search-result extracts of those pages or from third-party pages. Every price should be re-checked on the vendor page before it goes into a budget. Items marked "ESTIMATE" are my own arithmetic or judgement, not published numbers.

## 1. Vertical SaaS economics and Belgian/Dutch construction SaaS benchmarks; break-even for a solo founder

### Takeaway
Published data points suggest Belgian SME construction SaaS earns roughly €25-50 per user per month, or about €200-500 per company per month, so a solo founder needs on the order of 25-50 paying companies to replace a €100-150k/year freelance income (ESTIMATE). The incumbents are well funded (Vertuoza: €4M+ ARR, €10M Series A; Bouwsoft: Visma-owned, 10,000+ users; Robaws: 700+ customers), so the market is proven but not empty.

### Cited Findings
- Vertuoza (Belgian construction ERP for SMEs) reached €1M ARR in early 2022 after tripling in a year, with "more than 3,000 users" active at the time of its €4M pre-Series A (Oct 2022) — [tech.eu](https://tech.eu/2022/10/14/belgiums-vertuoza-raises-eur4-million-in-pre-series-a/)
- Vertuoza closed a €10M Series A (2023) at a stated ARR of €4M with 72 employees in three countries; goal was to double ARR and finish "V2" of its software — [Fortino Capital](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series)
- A French trade outlet describes Vertuoza as having more than €4M ARR and targeting €10M the next year (article date not visible) — [CFNEWS](https://www.cfnews.net/L-actualite/International/Operations/Capital-innovation/Vertuoza-se-construit-avec-ses-historiques-462232)
- Robaws: "over 700 satisfied customers" according to a quote from a BouwInfosys director (undated, third party) — [vsk.nl](https://vsk.nl/en/?p=11756)
- Robaws pricing (third-party, conflicting, not confirmed on robaws.com): Starter €29/month base + €24/month per extra user; Go €59/month base + €49/month per extra user, billed annually — [Spendbase listing](https://test-partneway.prod.spendbase.co/?p=39455); a different listing gives a Pro plan at €199/month billed yearly (€239 monthly) with two users included — [SaaSworthy](https://www.saasworthy.com/product/robaws)
- Bouwsoft (Use It Group, Bruges; also Groensoft, Archisoft) was acquired by Visma in July 2021; Use It Group had about 30 staff; price undisclosed; it was Visma's fourth Belgian acquisition after Yuki, Syneton and Admisol — [Dutch IT Channel](https://dutchitchannel.nl/677424/visma-koopt-belgische-useitgroup-bouwsoft.html)
- Bouwsoft claims "more than 10,000 construction professionals" and 25 years of history — [Visma press release via Cision](https://publish.ne.cision.com/v2.2/Release/ViewReleaseHtml/76CCD26C800636F0)
- Exact acquired Dutch construction SaaS Bouw7 in 2019 — [Accountancy Vanmorgen](https://www.accountancyvanmorgen.nl/2019/06/04/exact-breidt-aanwezigheid-in-de-bouwsector-uit-met-de-overname-van-bouw7/); Exact's Belgian construction product page lists tiers at €126 and €339 per month (unclear whether per company or per user) — [Exact Bouw](https://www.exact.com/benl/producten/bouw)
- Consolidation continues in Benelux construction software: Pro4all acquired STA Software (Jan 2025) — [Emerce](https://www.emerce.nl/wire/pro4all-neemt-sta-software-bouwt-verder-positie-toonaangevende-europese-leverancier-bouwsoftware); Brink sold its software division to Aceve (July 2025) — [Dutch IT Channel](https://www.dutchitchannel.nl/news/659437/brink-verkoopt-softwaredivisie-aan-aceve)
- SMB SaaS churn: aggregator pages citing ChartMogul 2025 give 11-13% median annual gross churn for SMB customers (top quartile 7-8%); other aggregators citing KeyBanc 2025 give 20-25% for SMB-focused SaaS. The two are not reconciled — [We Are Founders](https://www.wearefounders.uk/saas-churn-rates-and-customer-acquisition-costs-by-industry-2025-data/), [Prospeo](https://prospeo.io/s/saas-industry-benchmarks) (secondary sources; I could not open the primary reports)
- SMB CAC: OpenView 2025 (n=519) as relayed by a secondary source: median CAC $1,100-1,400 at ACV $1,000-10,000, payback 9-15 months; other secondary sources cite 16-24 months median payback for B2B SaaS — [SaaS Hero](https://www.saashero.net/uncategorized/gtm-saas-metrics-2026/)
- A Tidemark/Stripe "Vertical & SMB SaaS Benchmark Report 2025" exists but its figures were not accessible — [Stripe](https://stripe.com/en-be/lp/vertical-saas-benchmark-2025)
- Freelance rate context: Securex advises a full-time Belgian freelancer never to charge below €45/hour — [Securex](https://www.securex.be/nl/inspiratie/ondernemerschap/starten/freelancer-prijs-bepalen). No reliable published Belgian average developer day rate was found; the €600-900/day in the brief stays an assumption.

### Inferences
- ESTIMATE, revenue per user: Vertuoza's €1M ARR over roughly 3,000 users implies about €28 per user per month as a floor (ARR and user count are from slightly different dates in 2022). The Robaws third-party figures give €24-49 per extra user per month. A working assumption of €30-50 per office user per month, with cheaper or free field users, is consistent with both.
- ESTIMATE, revenue per company: a 10-25 person contractor with 4-8 office users lands at about €200-450 per month, i.e. €2,400-5,400 ARR per customer. Robaws at 700+ customers and Vertuoza at €4M ARR fit an average in the low thousands of euros per customer per year.
- ESTIMATE, break-even: a solo founder billing 200 days at €600-900 earns €120-180k per year as a freelancer. To match €120k from subscriptions at €3,500 ARR per customer needs about 35 customers; at €5,000 it needs 24; at €2,400 it needs 50. Adding €10-20k per year of running costs (hosting, component licences, Peppol, accountant, insurance) adds 3-8 customers. A lower "ramen" target of €60k needs 12-25 customers.
- ESTIMATE, time to get there: with 11-25% annual churn and a founder who also builds and supports, signing 10-15 new SME contractors per year is already ambitious, so subscription-only break-even is plausibly 2.5-4 years out. This is why a paid bespoke first project plus implementation fees matters for cash flow.
- Gross margin for this kind of product is not hosting-limited; the real cost is the founder's support and onboarding time (ESTIMATE: 1-3 days of onboarding per customer for data import, templates and training, which should be charged as a setup fee).

### Gaps
- No published revenue, ARPU or churn for Robaws, Bouwsoft, Hero, Gripp, Bouw7, KYP or Ed Controls was found. NBB annual accounts (Robaws, Vertuoza, Use It Group) would give revenue or gross margin and were not consulted.
- No official price list could be opened for Robaws, Vertuoza, Bouwsoft, Hero, Gripp, KYP or Ed Controls; most quote on request.
- Sales-cycle length and CAC specific to Belgian construction SMEs: no source found.
- Primary benchmark reports (ChartMogul, KeyBanc, OpenView, Tidemark) were not read directly; the churn range of 11-25% is wide because the secondary sources disagree.

## 2. "Custom build for one client first, then productise": patterns, pitfalls and Belgian legal points

### Takeaway
The model works only if the developer keeps the copyright and gives the first client a licence; under Belgian (and Dutch) law the developer owns the code unless a written contract says otherwise, so the default is favourable but must be confirmed in writing. Liability caps and one-sided terms are constrained by the Belgian B2B unfair-terms law (in force since 1 Dec 2020).

### Cited Findings
- Software copyright arises automatically in Belgium at creation if the work is original; no registration is needed. It covers source code, object code, interfaces and preparatory material, and any transfer must be arranged by contract — [LexGO, leidraad bescherming van apps](https://www.lexgo.be/en/news-and-articles/1782-leidraad-bij-de-bescherming-van-apps), [Unizo](https://www.unizo.be/ondernemersgids/juridisch/intellectuele-eigendom/bescherming-van-software)
- For employees the rule is reversed: the employer is presumed to hold the economic rights to software written in the course of employment, unless the contract says otherwise. This matters once the founder hires — [Unizo](https://www.unizo.be/advies/wie-heeft-de-rechten-ingeval-van-ontwikkeling-van-computerprogrammas-door-het-personeel)
- Without a contractual transfer the client does not become owner and gets at most a usage right, even when the client paid the full development cost and the software is bespoke (Dutch source, same principle) — [Dirkzwager](https://www.dirkzwager.nl/kennis/artikelen/it-contracten-deel-14-intellectuele-eigendom)
- Advice aimed at Belgian clients is to demand the transfer, the source code and documentation, and to check open-source components; so the first client's adviser may ask for exactly what the developer needs to keep — [K law via LegalNews](https://legalnews.be/it-ip/softwareontwikkeling-enkele-tips-voor-de-klant-opdrachtgever-k-law/)
- Agency practice: assign IP only in purely bespoke deliverables, keep ownership of pre-existing code, modules and frameworks ("background IP"), and prefer a licence over an assignment — [Sprintlaw, licensing agreements](https://sprintlaw.co.uk/articles/licensing-agreements-for-uk-software-development-agencies/), [Sprintlaw, client IP checklist](https://sprintlaw.co.uk/articles/client-ip-ownership-checklist/) (UK law firm, general principle only)
- Known trap: most agency contracts transfer IP to the client on payment, which blocks productisation of that work — [CoderCops](https://blog.codercops.com/blog/agency-ip-productization-2026) (blog)
- Belgian B2B law: clauses that create a manifest imbalance between businesses are void; there is a black list and a grey list; it applies to IT service contracts — [LexGO](https://www.lexgo.be/nl/nieuws-en-publicaties/5997-onrechtmatige-bedingen-nu-ook-in-b2b-relaties), [Jubel](https://www.jubel.be/het-beperken-van-aansprakelijkheid-in-b2b-relaties/)
- The B2B regime cannot be contracted out of when Belgian law governs the contract — [CMS expert guide](https://cms.law/en/int/expert-guides/limitations-and-exclusions-of-liability-in-b2b-contracts/belgium)
- New Belgian contract law (Book 5 Civil Code, art. 5.52) adds a general unfair-terms rule for non-negotiated clauses; the B2B law covers all clauses, negotiated or not — [Timelex](https://www.timelex.eu/en/blog/new-belgian-law-contracts-impact-it-contracts)
- Fiscal side note: the favourable tax regime for copyright income is reported to apply to software developers again from 1 Jan 2026 — [LexGO](https://www.lexgo.be/nl/nieuws-en-publicaties/14992-auteursrechtvergoeding-voor-software-opnieuw-fiscaal-voordelig-vanaf-2026), [Jubel](https://www.jubel.be/softwareontwikkelaars-maken-comeback-in-het-gunstig-auteursrechtenstelsel/)

### Inferences
- Recommended contract shape (ESTIMATE, to be reviewed by a Belgian IT lawyer): (1) developer keeps all IP; client gets a perpetual, non-exclusive, non-transferable licence for own use; (2) client gets "launching customer" benefits instead of ownership: a discounted build price, a long price lock on the later subscription, roadmap influence, possibly a sector or regional exclusivity window of 6-12 months; (3) source-code escrow or a continuity clause (access to source if the developer stops trading or is incapacitated); (4) a separate maintenance and hosting agreement with a monthly fee and response times; (5) a liability cap (commonly the annual fee) drafted to stay off the B2B grey list; (6) a data-processing agreement for employee data (hours, check-in).
- Pricing the bespoke MVP: charging the full freelance rate for client-specific analysis and data migration, and a reduced rate for generic product features the developer keeps, is the usual compromise. ESTIMATE: 40-70 billable days (€25-60k at €600-900) for a first slice, plus €300-800 per month for hosting and maintenance.
- Avoiding forks: one codebase, one database schema, tenant-level settings and feature flags from day one; client-specific output (offerte and vorderingsstaat layouts) as templates, not code. Anything only this client wants is either configurable or declined.
- The first client being a concrete contractor is a risk for productisation: bekisting, wapening and beton quantities, pump and mixer planning are niche. Keep those as a module on top of a generic contractor core.

### Gaps
- I did not retrieve the text of WER art. XI.294-XI.304 (computer programs) or a Belgian source confirming the written-form requirement for transfers by a self-employed developer; the principle is standard but needs a lawyer's confirmation.
- No Belgian-specific sources on escrow practice or typical SLA terms for small SaaS vendors were found (no Sirius Legal, Timelex or deJuristen article on escrow surfaced).
- No founder post-mortems on a first client holding the roadmap hostage were found; the fork-avoidance advice is my own judgement.

## 3. Realistic MVP effort with AI-assisted development; smallest valuable slice

### Takeaway
Evidence on AI coding agents is mixed: large gains in code volume (commits up 40-180%) but smaller gains in finished output (around 20-30%), and one RCT found experienced developers 19% slower on mature codebases. For a greenfield solo build the gain is probably real but should be budgeted as "somewhat faster", not "ten times faster"; the bottleneck stays domain analysis, testing and onboarding.

### Cited Findings
- METR RCT (Feb-Jun 2025): 16 experienced open-source developers, 246 real tasks on large repositories they knew; with AI tools they took 19% longer, while believing they were about 20% faster; they accepted under 44% of generations. Authors stress it is setting-specific — [TechCrunch](https://techcrunch.com/2025/07/11/ai-coding-tools-may-not-speed-up-every-developer-study-shows), [InfoQ](https://www.infoq.com/news/2025/07/ai-productivity)
- NBER working paper (May 2026), telemetry from 100,000+ GitHub developers: autocomplete, interactive agents and autonomous agents raised commits by a cumulative 40%, 140% and 180%; the paper discusses that later human steps limit final output — [NBER w35275](https://www.nber.org/system/files/working_papers/w35275/w35275.pdf)
- Harvard working paper (718 firms): after adopting coding agents, lines of code +30%, commits +20%, pull requests +23%, but time from PR to merge +49% (review becomes the bottleneck) — [Let's Data Science summary](https://letsdatascience.com/news/harvard-study-finds-ai-coding-agents-raise-code-volume-not-o-ea78729b) (secondary)
- Microsoft 2026 field study of agentic command-line tools: about 24% more merged PRs — [Larridin summary](https://larridin.com/blog/microsoft-study-ai-coding-agent-roi) (secondary)
- A Cursor-linked study across about 1,000 organisations claims large output gains; methodology is thin and vendor-linked — [LeadDev](https://leaddev.com/ai/cursor-claims-its-tools-are-a-massive-productivity-hack-for-devs)
- MVP scoping advice: keep to 3-5 core features; settle the hard-to-reverse decisions first, of which multi-tenancy is the biggest; do not trim so far that the first use is not useful — [Aloa](https://aloa.co/ai/resources/deep-dive/scope-a-saas-mvp) (agency guide)
- Since 1 Jan 2026 B2B invoices between Belgian VAT payers must be structured e-invoices in Peppol BIS format over the Peppol network; the tolerance period covered the first three months of 2026 and has ended — [Unizo](https://www.unizo.be/ondernemersgids/financieel/factuur/e-facturatie-correct-werken-met-peppol-en-je-digitale), [Banqup](https://www.banqup.com/nl-be/resources/blog/e-invoicing-grace-period-2026-belgium)

### Inferences
- No study covers a solo developer on a greenfield business app. That setting avoids the review bottleneck and the "large legacy repo" penalty, so it is the favourable case, but the studies do not quantify it. ESTIMATE: plan with a 1.5-2.5x speed-up on implementation work and no speed-up on analysis, client workshops, data migration, testing with real users and support.
- ESTIMATE of effort for a solo developer using agents (person-days, including testing, excluding sales):
  - Foundation (auth, tenants, roles, customers, projects, article and price lists, PDF engine, hosting, backups): 15-25 days
  - Slice A, field to office: werfbonnen and urenregistratie on mobile, materials and machines per werf, approval, export to payroll and nacalculatie per project: 25-40 days
  - Slice B, money flow: offerte with posts and meetstaat, vorderingsstaat (cumulative, with previous states, meerwerken), invoice and creditnota via a Peppol API, export to accounting: 30-50 days
  - Planning board (drag and drop crews and equipment per werf): 15-25 days with a commercial scheduler component
  - Purchasing (bestelbonnen, delivery notes, incoming invoice matching): 20-35 days
  - Full first product (A + B + planning + purchasing): roughly 100-175 days, i.e. 6-10 months solo
- Smallest valuable slice for a concrete contractor (ESTIMATE): Slice A. Reasons: hours and materials per werf are the data nobody else has, labour is the largest cost in ruwbouw and betonwerken, it runs alongside the existing invoicing package so there is no risky switch, and it yields nacalculatie within weeks. Slice B is the better commercial hook later because invoicing is mandatory-Peppol and replaces a paid tool, but it carries legal correctness risk (BTW medecontractant, 6% renovation, inhoudingsplicht) and competes head-on with incumbents.
- Order suggested: A (8-10 weeks) → nacalculatie dashboards → B → planning → purchasing.

### Gaps
- No published effort figures for comparable Belgian construction MVPs. All day counts above are my estimates and should be validated against the first client's actual process.
- I did not find a 2026 DORA report or a METR follow-up with newer tools.

## 4. Technology choices in 2026

### Takeaway
A boring monolith on PostgreSQL with a responsive web app plus PWA for the werf is the lowest-risk route; the main paid component worth buying is a scheduler, where licence terms for SaaS use differ sharply (DHTMLX Commercial excludes SaaS, Bryntum has separate OEM/ISV licensing, Syncfusion is free under $1M revenue). Building on Odoo or ERPNext speeds up accounting-adjacent features but brings per-user fees or copyleft questions that hurt a product business.

### Cited Findings
- Bryntum: licences are per developer; listed "from" prices are $680 per developer (Scheduler) and $1,100 (Scheduler Pro) for small teams of 3+; the Bryntum Complete page shows $2,150 per developer per year (Business) and $4,455 (Enterprise), which suggests a move to annual pricing; a separate OEM & ISV licensing page exists for embedding in products sold to customers — [Bryntum OEM pricing](https://bryntum.com/oem-pricing/), [Bryntum Complete store](https://bryntum.com/store/complete). The same search extract claims a free MIT "Community tier" per Bryntum product; I could not verify this and it should be checked.
- DHTMLX: perpetual licences; Standard editions of Gantt, Scheduler and Suite are GPL v2; the Scheduler Commercial licence covers 5 developers and 1 project with "no use in SaaS" (SaaS needs the Enterprise tier); a startup programme lists Scheduler at $539 instead of $1,799 for one year, up to 3 developers — [DHTMLX licences](https://dhtmlx.com/docs/products/licenses), [DHTMLX Scheduler Commercial](https://dhtmlx.com/docs/products/dhtmlxScheduler/commercial), [DHTMLX startups](https://dhtmlx.com/docs/startups/)
- Syncfusion: Scheduler SDK $959 per developer per year with a 5-developer minimum ($4,795 per year); the Community Licence is free for organisations with under $1M annual gross revenue and fewer than 5 developers — [Syncfusion products](https://www.syncfusion.com/sales/products), [Syncfusion community licence](https://www.syncfusion.com/blogs/post/milestone-syncfusion-s-community-license)
- Offline sync: PowerSync syncs an in-app SQLite database with a Postgres (or MongoDB, MySQL) backend and positions itself as the engine with first-class offline support; ElectricSQL leaves client-side persistence to the developer — [PowerSync blog](https://powersync.com/blog/electricsql-vs-powersync) (vendor source, biased). A 2026 comparison reports ElectricSQL with the highest adoption, PowerSync with the fastest release cadence and Triplit stalled since Jan 2026 — [pistack.xyz](https://www.pistack.xyz/posts/2026-10-21-local-first-sync-engines-electricsql-powersync-triplit/) (single blog)
- Odoo: Community edition is LGPL-3.0, Enterprise is proprietary and priced per user; the Belgian pricing page shows the Standard plan at US$31.10 and the Custom plan (Odoo.sh or on-premise, Studio, multi-company, external API) at US$61.00 per user per month in the search extract (currency and billing period should be re-checked) — [Odoo pricing BE](https://www.odoo.com/nl_BE/pricing)
- A partner blog reports a 25% surcharge in 2026 for Odoo Enterprise on Odoo.sh or on-premise and for older versions (unofficial) — [WeSolved](https://wesolved.com/blog/odoo-2/odoo-25-toeslag-in-2026-betaal-jij-straks-meer-en-hoe-voorkom-je-dat-214)
- Odoo states it offers free Peppol sending and receiving — [Odoo e-invoicing Belgium](https://www.odoo.com/electronic-invoicing/belgium)
- ERPNext is GPLv3; Frappe Framework is MIT; Frappe says customisations do not inherit the licence and obligations arise mainly on redistribution, but a forum answer warns a custom app may be a derivative work that needs GPL licensing and advises legal opinion — [Frappe docs](https://docs.frappe.io/customer-guide/about-frappe/what-open-source-mean-for-you), [Frappe licence page](https://docs.frappe.io/legal/others/license-and-trademark.md), [Frappe forum](https://discuss.frappe.io/t/licensing-of-app-made-using-frappe-erpnext/9836)
- Multi-tenancy is the hardest early decision to reverse — [Aloa](https://aloa.co/ai/resources/deep-dive/scope-a-saas-mvp)

### Inferences
- Stack recommendation (ESTIMATE, based on general engineering judgement, not on a cited comparison): pick the stack the developer already knows best among Laravel, Django, Rails, .NET or TypeScript (Next.js/NestJS); all are adequate. PostgreSQL with a tenant_id column on every table plus row-level security is the simplest multi-tenant design for tens to hundreds of customers. Host in the EU (a managed Postgres plus one app server costs roughly €50-200 per month at this scale).
- Mobile: start with a PWA (installable, camera, offline cache of today's werven and a queue of unsent werfbonnen). Full offline sync engines (PowerSync and similar) are only worth it if werven regularly lack coverage; in Flanders an "offline queue" usually suffices. Go native (React Native/Expo or Flutter) only if push notifications, background GPS or app-store presence become sales requirements.
- PDF: render HTML templates to PDF with a headless browser (Playwright/Chromium, Gotenberg) or a library such as WeasyPrint; offertes and vorderingsstaten need precise tables, page breaks and client branding, so template-per-tenant matters more than the engine.
- Scheduler: for a solo developer under $1M revenue, Syncfusion's Community Licence is the cheapest legal route; Bryntum is widely regarded as the strongest scheduler UI but SaaS embedding goes through OEM pricing (quote); DHTMLX requires the Enterprise tier for SaaS. Budget ESTIMATE: €0-5,000 per year.
- Odoo as a base: fastest route to accounting, purchasing and invoicing, and Peppol is built in; but (a) Enterprise costs about €30-60 per user per month, which consumes most of the achievable ARPU, (b) Community lacks Studio, multi-company and bank sync, (c) Belgian construction specifics (vorderingsstaten, meetstaat, Checkinatwork) must still be built as modules, and (d) the product becomes "an Odoo implementation", which is a services business rather than own SaaS. It is a reasonable choice if the goal is to be an integrator for 5-15 clients, a poor one for an independent product.
- ERPNext: no per-user fee, but GPLv3 and a smaller Benelux ecosystem; legal position of closed custom apps offered as SaaS is disputed. Dolibarr, Directus, Supabase and Budibase are tools to speed up admin screens and auth rather than a construction base.

### Gaps
- No pricing or evaluation retrieved for Dolibarr, Directus, Supabase or Budibase, and nothing on existing Odoo construction modules for Belgium (vorderingsstaat). Not researched for lack of tool budget.
- Bryntum OEM/ISV price is quote-only; exact SaaS terms not seen.
- No independent PWA-versus-native comparison for field apps was found.

## 5. Build-versus-buy components and prices

### Takeaway
Peppol, bank feeds, OCR and accounting sync should all be bought: Peppol costs about €0.10-0.30 per document via an API provider, bank feeds about €1-4 per account per month, invoice OCR about €0.05-0.10 per page. Accounting integration is the expensive one: aggregator pricing (Chift) is quote-only, so the MVP should start with one or two direct exports.

### Cited Findings
- Recommand (Belgian Peppol API): free tier with 25 documents per month then €0.30 per document; Starter €29/month including 200 documents then €0.20; Professional €99/month including 1,000 documents then €0.10; Enterprise custom — [Media Atelier overview](https://www.mediaatelier.com/en/Posts/E-Invoices-Belgium/) (third-party page, not recommand.eu itself)
- e-invoice.be: Pro at €0.25 per invoice with packages from €350; an Enterprise rate of €0.18 per invoice also appears — [Media Atelier overview](https://www.mediaatelier.com/en/Posts/E-Invoices-Belgium/)
- Digiteal Peppol for integrators: one-time setup €365, pay per document, €85 monthly minimum — [Digiteal pricing](https://www.digiteal.eu/pricing/), [European Purpose listing](https://europeanpurpose.com/tool/digiteal)
- Billit runs a certified Peppol access point with a REST API, sandbox and production — [Billit](https://www.billit.eu/llms.txt); Storecove offers a 30-day sandbox and volume-based pricing, rates unpublished — [e-invoice.app](https://www.e-invoice.app/vendors/storecove)
- Chift (Belgian unified accounting API) lists connectors for Exact Online, Octopus, Yuki and Winbooks; Winbooks has no API and is reached through an on-premise bridge — [Chift connectors](https://docs.chift.eu/unified-apis/accounting/connectors), [Chift Winbooks](https://www.chift.eu/tools/winbooks), [Chift Octopus](https://chift.eu/tools/octopus)
- Chift pricing is quote-only — [Apideck comparison](https://www.apideck.com/alternatives/chift) (competitor source)
- Ponto (Isabel): fee per bank account added to the integration, billed monthly; with a software partner the cost can be included in the partner's subscription — [Ponto support](https://pontosupport.isabel.eu/knowledgebase/article/KA-02513); indicative amounts: €4 per month per account (old Odoo documentation and Informer) and €1 per month per active bank link at one partner — [Informer](https://www.informer.nl/ponto)
- CodaBox is now part of Wolters Kluwer; no price found — [Wolters Kluwer CodaBox](https://www.wolterskluwer.com/nl-be/solutions/codabox)
- Mindee invoice OCR: $0.10 per page pay-as-you-go on one page, "from $0.05" per extra page on another; a Starter plan at €44 per month for 500 pages is cited — [Mindee invoice page](https://mindee.com/l/invoice), [Mindee pricing blog](https://www.mindee.com/blog/ocr-api-pricing-free-vs-paid)
- Checkinatwork web service: the supplier's software connects to the NSSO web service; steps are requesting a GlobalSign certificate and creating a technical user; a simulation environment exists — [socialsecurity.be, how](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/general/how.htm)
- The NSSO does not certify suppliers' solutions, and using a supplier's solution does not remove the employer's legal liability — [socialsecurity.be, Checkinatwork](https://www.socialsecurity.be/foreign/working_in_belgium/en/checkinatwork.html)

### Inferences
- ESTIMATE of variable third-party cost per customer per month for a 15-person contractor: Peppol 60-150 documents (€6-30), OCR 100-200 pages (€5-20), bank feed 1-2 accounts (€2-8), hosting share (€3-10): about €15-70, i.e. gross margin of 80-93% at €300-450 ARPA before support time.
- LLM-based extraction of purchase invoices and leverbonnen is now a realistic alternative to Mindee or Klippa for line items, and since incoming B2B invoices arrive as structured Peppol UBL from 2026, OCR is mainly needed for delivery notes and foreign or older PDFs. This reduces the value of buying a specialised OCR product (ESTIMATE).
- Accounting: start with a generic export (Peppol UBL sales invoices plus a CSV or Octopus/Exact file) and add one direct API for the first client's accountant. Add Chift once 3-4 different packages are requested.
- Checkinatwork and inhoudingsplicht checks are differentiators for Belgian contractors that foreign tools lack; the web service route appears open to any software supplier via a certificate and technical user, with no certification barrier.

### Gaps
- No prices found for Billit API/partner plans, Storecove, Banqup or Dokapi; CodaBox; Klippa; Azure Document Intelligence; itsme, Connective or Dioss e-signature; Codat; Silverfin.
- KBO/VIES lookup and the Inhoudingsplicht web service (onboarding steps, whether a technical user under the client's name is required) were not researched.
- Whether Chift has a startup tier or a minimum monthly fee is unknown.

## 6. Subsidies and fiscal incentives (developer side and customer side)

### Takeaway
For the developer the VLAIO ontwikkelingsproject (25-50% of accepted costs, minimum €25,000 subsidy) is the only sizeable grant, but it requires real innovation risk and the procedure changes on 1 Jan 2027. The kmo-groeisubsidie has been abolished and the kmo-portefeuille digitalisation theme now covers only cybersecurity, so customers have little Flemish subsidy left for buying or implementing this software.

### Cited Findings
- VLAIO ontwikkelingsproject: subsidy of 25% to 50% of accepted costs (60% for interregional or international cooperation), minimum subsidy €25,000; base 25%, +10 points for medium-sized and +20 points for small enterprises, capped at 50% — [VLAIO ontwikkelingsproject](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/ontwikkelingsproject-subsidie-voor-innovatie), [VLAIO financiële steun](https://www.vlaio.be/nl/subsidies-financiering/ontwikkelingsproject/financiele-steun-voor-een-ontwikkelingsproject)
- From 1 Jan 2027 VLAIO changes the application and evaluation process for research and development projects — [VLAIO nieuw proces 2027](https://www.vlaio.be/nl/subsidies-financiering/ontwikkelingsproject/aanvraag-en-evaluatieprocedure/nieuw-proces-onderzoeks-en-ontwikkelingsprojecten-2027), [PNO](https://www.pnoinnovation.com/be/insights/nieuwe-aanvraagprocedure-vlaio-oo-projecten-vanaf-2027/)
- Kmo-groeisubsidie: no new applications; the November 2025 call was cancelled; the Flemish government ended the scheme as a budget measure; pending applications are still handled — [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/kmo-groeisubsidie-strategisch-adviesaanwerving-bij-groeitraject), [VLAIO wijziging](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/wijzigingen/291), [Forum for the Future](https://blog.forumforthefuture.be/nl/article/stopzetting-van-de-kmo-groeisubsidie/28941)
- Kmo-portefeuille: since 1 Feb 2026 the digitalisation theme covers only cybersecurity advice, at 45% for small and 35% for medium-sized enterprises — [VLAIO kmo-portefeuille digitalisering](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/wat-is-de-kmo-portefeuille/digitalisering), [VLAIO kmo-portefeuille](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille)
- Innovatieaftrek: 85% of net income from qualifying IP is exempt from corporate tax; copyright-protected software qualifies only if it results from an R&D project or programme validated by BELSPO; software already on the market is not eligible even if new to the company — [VLAIO innovatieaftrek](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/innovatieaftrek), [Deloitte](https://www.deloitte.com/be/en/services/tax/blogs/innovation-income-deduction-for-copyrighted-software-new-belspo-guidelines.html)
- Whether BELSPO advice is legally required or only strongly recommended is described differently by advisers — [Forvis Mazars](https://www.forvismazars.com/be/en/services/tax/belgium-innovation-incentives-overview)
- Partial exemption from remitting withholding tax for R&D staff: 80% need not be remitted; projects must be notified to BELSPO before they start — [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/vrijstelling-doorstorting-bedrijfsvoorheffing-voor-onderzoekers), [Securex](https://www.securex.be/nl/lex4you/werkgever/nieuws/aanmelding-en-advies-o-o-projecten-nieuwe-richtlijnen-vanaf-2025); Cassation confirmed on 2 Apr 2026 the importance of a correct and complete notification — [EY](https://www.ey.com/nl_be/technical/alerts/de-belspo-aanmeldingen-onder-de-loep)
- Tax shelter for starting companies: a small company can raise up to €500,000; investors get a 30% to 45% tax reduction, capped at €100,000 per person per year — [VLAIO tax shelter](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/tax-shelter-voor-startende-ondernemingen), [Spreds](https://www.spreds.com/en/tax-shelter)
- Winwinlening (Flanders): the lender receives a yearly tax credit of 2.5% on the average outstanding amount; registered through PMV — [VLAIO winwinlening](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/winwinlening)
- VLAIO has a page on training and software packages for mandatory e-invoicing that includes a section on fiscal advantages — [VLAIO e-facturatie](https://www.vlaio.be/nl/nieuws/verplichte-e-facturatie-voor-bedrijven-vanaf-2026-opleiding-en-softwarepakketten)

### Inferences
- A VLAIO ontwikkelingsproject implies a project budget of at least about €50,000-100,000 (€25,000 minimum subsidy at 50% or 25%). A "me-too" contractor ERP is unlikely to pass the innovation test; a credible angle would need real technical uncertainty (for example AI-based meetstaat extraction from plans, automatic nacalculatie from werf data). ESTIMATE: low to moderate chance, several weeks of application work.
- The 80% withholding-tax exemption only helps once there are employees with qualifying degrees doing R&D; it does nothing for a one-person company where the founder is a self-employed director.
- The innovatieaftrek is relevant only once the product makes taxable profit, and needs the BELSPO notification filed before development starts; it is cheap to file early.
- For customers, the remaining arguments are fiscal (e-invoicing cost deductions and the investment deduction for digital investments) rather than subsidies; the sales pitch should not promise kmo-portefeuille support for implementation.

### Gaps
- Not confirmed from a primary source: the 120% cost deduction for e-invoicing software and the investeringsaftrek for digital investments (rates, end dates), Startlening (PMV) ceilings and Winwinlening maximum amount, the exact 45% tax-shelter condition (micro-enterprise), and whether a VLAIO Startersbeurs-type instrument exists in 2026.
- Constructiv or other sector-fund support for software purchase: not researched.
- The search extract of the innovatieaftrek mixed in a €77,220 figure that belongs to the copyright-income regime; I could not verify it and have left it out.

## 7. Go-to-market in Belgian construction SME

### Takeaway
The addressable base is large (about 134,000 VAT-registered construction businesses in Belgium in 2022, most without staff) but fragile, and incumbents sell through accountants and sector federations; a newcomer's realistic channel is referrals from the first client, local accountants and a narrow niche (ruwbouw and betonwerken) rather than trade fairs.

### Cited Findings
- Belgium counted 134,355 VAT-registered businesses in construction in 2022, out of 732,478 private businesses — [Embuild, Kerncijfers 2023](https://cms.embuild.be/election/media/_Users/Kerncijfers%20van%20de%20Belgische%20bouw%20-%202023.pdf)
- 1,749 companies went bankrupt in Flanders in Q1 2025; two in three bankrupt construction firms were Flemish, which Embuild links partly to the high number of starters — [VRT NWS](https://www.vrt.be/vrtnws/nl/2025/04/18/faillissementen-vlaanderen-eerste-kwartaal/)
- Buildwise's 2024 Digital Construction document points to a lack of digital support for SMEs and limited interoperability between software applications — [Buildwise](https://www.Buildwise.be/media/mlwkxudc/pt-2024-digital-construction-short-nl_v1.pdf)
- Mandatory Peppol e-invoicing since 1 Jan 2026 means every contractor already has (or just bought) an invoicing tool — [Unizo](https://www.unizo.be/ondernemersgids/financieel/factuur/e-facturatie-correct-werken-met-peppol-en-je-digitale)
- Incumbents have deep distribution: Bouwsoft is part of Visma alongside accounting brands (Yuki, Admisol), Bouw7 is part of Exact — [Dutch IT Channel](https://dutchitchannel.nl/677424/visma-koopt-belgische-useitgroup-bouwsoft.html), [Accountancy Vanmorgen](https://www.accountancyvanmorgen.nl/2019/06/04/exact-breidt-aanwezigheid-in-de-bouwsector-uit-met-de-overname-van-bouw7/)
- Vertuoza used venture funding to expand across three countries, showing NL and FR coverage is the norm for scaled players — [Fortino Capital](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series)

### Inferences
- Target segment (ESTIMATE): contractors with 5-50 employees doing ruwbouw, betonwerken, funderingen and industriebouw in Flanders. Firms without staff will not pay €300 per month; firms above 50 buy Bouwsoft, Robaws or a full ERP with an implementation partner.
- The Peppol mandate cuts both ways: the 2025-2026 buying wave is over, so "invoicing" is no longer an entry point, and switching costs are fresh (article lists, templates, accounting link). Entering alongside the existing invoicing tool with werfbonnen, hours and nacalculatie avoids the switch.
- Channels ranked by fit for a solo founder (ESTIMATE): (1) referrals and case study from the launching customer, including its subcontractors and peers; (2) two or three local accountancy firms with construction clients; (3) Bouwunie or Embuild local chapters and their member magazines; (4) content and search in Dutch on specific pains (vorderingsstaat, nacalculatie beton); (5) fairs such as Matexpo, Batibouw or Digital Construction Brussels are expensive for one person and better visited than exhibited at.
- Language: Dutch only is enough for the first 30-50 customers; French is needed for Brussels and Wallonia and for Flemish contractors with French-speaking crews, so build i18n into the code from the start but translate later. Field app languages for workers (Polish, Romanian, Portuguese) may matter sooner than French for the office.
- Sales cycle (ESTIMATE, no source): 1-3 months for owner-led firms of 5-20 people, driven by a demo, a trial on one werf and the winter low season; 3-9 months when replacing an incumbent.

### Gaps
- No data found on software adoption rates among Flemish SME contractors, on partnership programmes of Embuild or Bouwunie for software vendors, or on fair costs.
- The number of Flemish construction firms with 5-50 employees (the real target count) was not found; Statbel or NSSO tables would give it.

## 8. Main failure risks for a newcomer and mitigations

### Takeaway
The biggest risks are not technical: single-client dependency, the support and legislative-upkeep burden on one person, and buyers' reasonable fear of a one-person vendor. They are mitigated by contract structure (licence not transfer, escrow or continuity clause, paid maintenance), ruthless scope limits and buying regulated components instead of building them.

### Cited Findings
- Incumbents are being bought by large groups (Visma-Bouwsoft 2021, Exact-Bouw7 2019, Pro4all-STA 2025, Brink-Aceve 2025), which raises their distribution power but also shows an exit route for niche products — [Dutch IT Channel](https://dutchitchannel.nl/677424/visma-koopt-belgische-useitgroup-bouwsoft.html), [Emerce](https://www.emerce.nl/wire/pro4all-neemt-sta-software-bouwt-verder-positie-toonaangevende-europese-leverancier-bouwsoftware), [Dutch IT Channel, Brink](https://www.dutchitchannel.nl/news/659437/brink-verkoopt-softwaredivisie-aan-aceve)
- Vertuoza needed 72 employees to reach about €4M ARR, i.e. roughly €55,000 ARR per employee, which shows how labour-intensive sales, onboarding and support are in this segment — [Fortino Capital](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series) (the per-employee ratio is my arithmetic)
- Legislative upkeep is real and recurring: mandatory Peppol since 2026, with e-reporting planned for 2028 — [Banqup](https://www.banqup.com/nl-be/resources/blog/e-invoicing-grace-period-2026-belgium), [Unizo](https://www.unizo.be/ondernemersgids/financieel/factuur/e-facturatie-correct-werken-met-peppol-en-je-digitale)
- Liability cannot be freely excluded: the B2B unfair-terms regime applies to IT contracts and cannot be contracted out of — [CMS](https://cms.law/en/int/expert-guides/limitations-and-exclusions-of-liability-in-b2b-contracts/belgium), [Jubel](https://www.jubel.be/het-beperken-van-aansprakelijkheid-in-b2b-relaties/)
- Clients are advised to secure source code and documentation in the contract — [K law via LegalNews](https://legalnews.be/it-ip/softwareontwikkeling-enkele-tips-voor-de-klant-opdrachtgever-k-law/)
- The employer stays legally liable for Checkinatwork registrations even when a supplier's tool is used, so errors in such integrations create client exposure — [socialsecurity.be](https://www.socialsecurity.be/foreign/working_in_belgium/en/checkinatwork.html)
- AI assistance raises code output more than finished, reviewed output, so a solo developer can generate more code than one person can properly verify — [Harvard study summary](https://letsdatascience.com/news/harvard-study-finds-ai-coding-agents-raise-code-volume-not-o-ea78729b)

### Inferences
- Risk table (ESTIMATE, own judgement):
  - Single-client dependency: cap the first client at under 50% of revenue within 18 months; sign 2-3 further design partners before building beyond Slice A/B; keep freelance income alongside in year 1.
  - Scope creep into "a full ERP": no own bookkeeping, payroll or bank payments; integrate with the accountant's package and the sociaal secretariaat.
  - Legislative upkeep: buy Peppol, accounting sync and bank feeds from providers who track the rules; keep VAT logic in one tested module.
  - Support burden: fixed onboarding package, in-app help, support by ticket with stated hours; price support into the subscription. ESTIMATE: beyond about 30-40 customers a solo founder needs a part-time support or implementation person.
  - Bus factor: source-code escrow or a continuity agreement with a second developer or small agency who has repository access and a runbook; automated backups with documented restore; data export for the client at any time; business-continuity and professional-liability insurance. These are also the items larger contractors and their advisers ask for.
  - Competition and consolidation: stay in a niche the generalists serve poorly (concrete and ruwbouw specifics: bekisting, wapening, betonleveringen, pompplanning) and treat acquisition by a larger vendor as a legitimate outcome.
  - Quality risk from AI-generated code: automated tests on money logic (vorderingsstaten, VAT, rounding), staged rollouts, and one external code review per year.
- Go/no-go reading (ESTIMATE): "go" as a paid bespoke project with retained IP and a maintenance contract, since it is cash-positive from the start; "conditional go" for productisation, gated on signing 3-5 additional paying contractors on the same codebase within about 12 months of the first go-live. A pure speculative SaaS build without the paying first client would be a "no-go" given the funded incumbents.
- Phased roadmap (ESTIMATE):
  - Phase 0 (4-6 weeks): process analysis at the client, contract (licence, maintenance, continuity), BELSPO notification if an innovation angle exists, stack and tenant model.
  - Phase 1 (8-12 weeks): Slice A live on real werven; weekly feedback.
  - Phase 2 (3-4 months): nacalculatie dashboards, offerte → vorderingsstaat → Peppol invoice, accounting export.
  - Phase 3 (months 9-15): planning board, purchasing, second and third customer, pricing page, setup-fee package.
  - Phase 4 (year 2+): French, Checkinatwork and inhoudingsplicht checks, accounting aggregator, first hire or partner at 30-40 customers.

### Gaps
- No Belgian founder write-ups or post-mortems of small construction SaaS vendors were found, so mitigations are judgement rather than documented precedent.
- Typical escrow costs in Belgium and what Belgian contractors actually demand contractually from small vendors were not found.
- Professional-liability (BA beroepsaansprakelijkheid IT) insurance premiums were not researched.
