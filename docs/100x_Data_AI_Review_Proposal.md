# Tandem Creative Dev Limited

# Data & AI Review Partner

## Proposal

Project number: 26-004

Document number: 26-004-P01

Client: 100x Impact / London School of Economics

Quote ref: 100x Impact Data & AI Review Partner

Date: 17/06/2026

Status: OPEN

Authors: Jack Casstles-Jones, Maxime Downe

1. # **Who We Are and Why We Fit**

Tandem is a two-person full-stack development and AI engineering agency. We build digital tools for mission-driven organisations: government bodies, educational institutions, charities, and social ventures. Our recent clients include the Department for Education, the University of Warwick, the Department for Work and Pensions, Skills England, the Gatsby Charitable Foundation and the wider Sainsbury Family Charitable Trusts office, the British Red Cross, and UN Ocean Decade-endorsed climate venture OZEAON. We work almost entirely with organisations like this because it is the work we want to be doing.

We are practitioners first. We spend most of our time building and shipping data platforms and AI systems for organisations similar to 100x, and we run hands-on AI training for professional developers. That shapes how we would approach this review: every recommendation we make will be grounded in what is actually implementable, with realistic costs and effort attached, because building these systems is what we do the rest of the week.

We understand ventures. Several of our current clients including OZEAON ([ozeaon.com](http://ozeaon.com)), Amagi Brain Health ([amagibrainhealth.org](http://amagibrainhealth.org)), and ZigZag AI ([zzag.ai](http://zzag.ai)) are actively participating in accelerators, pursuing funding and grant applications, and represent the type of high-impact ventures that 100x supports.

We also understand what this is ultimately for. 100x exists to back the ventures taking on the hardest social problems, and with both the application rate and the portfolio growing, the organisation's data and AI have to keep pace so the team spends its time on ventures, not on wrestling with systems. Better-structured data and well-chosen AI are a means to that end: they are how 100x keeps giving each venture proper attention as it scales.

Four pieces of our recent work map directly onto this brief.

## Data Audit

For OZEAON, we inherited an existing database that had grown incrementally without design oversight. We audited the full estate, cataloguing structural issues across roughly 70 tables, from integrity gaps and undocumented legacy columns to inconsistent data models. We produced a written assessment for the team \- setting out every finding, the options considered, and the rationale for each recommendation. We then carried out the remediation ourselves. This is the same discipline the brief asks for: systematic review of an estate we did not build, documented findings a non-technical stakeholder can act on, and recommendations grounded in what was actually implemented afterwards.

## Data Mapping

We built the UK Skills Explorer for Skills England in partnership with the University of Warwick. We took a national dataset that existed only as database files emailed between researchers and turned it into structured public infrastructure: defining the core data model and entity definitions, ingesting and connecting over 47,000 entities and 170,000 relationships, and publishing it under an Open Government Licence with a documented API.

Between these two projects we have worked from both directions \- auditing and rebuilding an inherited estate, and architecting a new one from first principles. We know what good looks like because we have had to define it, defend it, and run it in production for government and commercial clients.

## AI Review

We work at both ends of the AI adoption journey. For the Gatsby Charitable Foundation we built GatBot, an AI research interview platform used in production. Its outputs were published in Gatsby's Generative AI in Further Education report (October 2025\) and presented to the DfE, Skills England, Jisc, and Innovate UK. For the Sainsbury Family Charitable Trusts we prototyped an internal AI helpdesk over their SharePoint library in under a month, designed to test the value of the use case before any production investment. We have direct, recent experience of which AI use cases create value in these organisations, which don't, and how to differentiate cheaply.

## Working Group Enablement

Between March and July 2025 we designed and delivered a programme of ten full-day workshops on responsible AI adoption for startup founders and professional developers through the Founders and Coders training community. Attendees included the CTO of Policy in Practice and lead engineers from Oak National Academy and Hackney Council. Facilitating structured, practical sessions that build organisational confidence in AI is something we have done repeatedly, for both non-technical audiences and demanding technical participants.

2. # **Proposed Approach and Methodology**

We propose three overlapping phases across the six months. The approach is deliberately bottom-up: the findings are built from what the team and the ventures actually need, drawn out through conversation rather than handed down as a template. The Data & AI Working Group is involved from inception, contributing to discovery and analysis at each stage, and we make a point of hearing from across the organisation so the recommendations carry the voice of the people who will have to live with them.

## Phase 1: Discover (months 1 to 2\)

We start with an inception session with the Chief Insights Officer and Working Group to agree scope, stakeholder list, working rhythms, and what success looks like. Then the discovery work runs across both strands in parallel:

- A first pass at needs and opportunities, covering both data and AI: the data and structures people wish they had, and the routine work they would most like to take off their plate. We identify these in discovery so Phase 2 can assess them properly, rather than arriving at analysis cold.

- Structured interviews and workshops with stakeholders across teams and functions, covering three things: what data they hold and how it flows; how knowledge is captured, shared and retrieved day to day (and where it lives only in people's heads or inboxes); and how they currently use AI, formally and informally.

- Hands-on review of systems, tools and repositories, including the boundary between 100x and LSE systems. We will want to understand the LSE technology environment early, since it constrains what future architecture and AI tooling is realistic.

- An organisational AI usage assessment, capturing current tools, patterns, confidence levels and emerging risks across teams.

Phase 1 outputs:

- Data inventory and asset register (first version)

- AI usage and maturity baseline

- Knowledge management baseline: where organisational knowledge is held, how it moves, and where it is lost

- Confirmed map of stakeholders and systems

- A first list of data and AI needs and opportunities, carried into Phase 2 for assessment

## Phase 2: Analyse (months 3 to 4\)

- Map venture data across the end-to-end venture lifecycle, from application and pipeline through selection and into the active portfolio. As both the application rate and the portfolio grow, the data model has to scale with them, so we design for where 100x is heading, not only where it is today. We also map ecosystem data across its organisational uses.

- Develop the core data model and entity definitions: the shared vocabulary of ventures, programmes, people, organisations and outcomes that everything else hangs off.

- Identify gaps, duplication, inefficiencies and risks, including governance, stewardship, privacy and GDPR considerations, with specific attention to data flowing to third-party AI services.

- Analyse how data and knowledge management interact: where structured data could feed organisational learning, where knowledge practices undermine data quality, and where the two need to be designed together rather than separately. The interdependencies between data, knowledge management and AI are where most of the value in this brief sits, so we treat them as a single system from the analysis stage.

- Assess the data & AI needs and candidate use cases surfaced in Phase 1 against value, feasibility, risk and fit with 100x's capability and values. Many of the highest-value AI use cases in organisations like 100x are knowledge management use cases (retrieval, institutional memory, onboarding) so the two assessments inform each other directly.

- Facilitated Working Group sessions to test emerging findings and build shared ownership of the analysis.

Phase 2 outputs:

- Venture lifecycle data map

- Ecosystem data map

- Core data model and entity definitions

- AI needs and opportunity map, including knowledge management use cases

## Phase 3: Recommend and embed (months 5 to 6\)

- Develop the data roadmap (architecture, governance, ownership, phased implementation) and the AI roadmap (prioritised use case portfolio, governance, training and capability building, with principles for responsible adoption). Knowledge management recommendations are embedded in both rather than treated as a third stream: data architecture choices determine what knowledge is retrievable, and AI use cases determine what knowledge needs to be structured.

- Where it would materially de-risk a priority recommendation, we can build small, time-boxed prototype spikes within the engagement: a day or two proving that a proposed integration or AI use case actually works with 100x's real systems and data. Recommendations that have been validated by real users can be carried forward.

- Synthesis of both strands into an integrated findings report with a prioritisation framework, identifying the interdependencies between data, knowledge management and AI.

- A final presentation and discussion workshop, plus a closing session with the Working Group focused on its future role in implementing and governing the recommendations.

Phase 3 outputs:

- Data roadmap and implementation plan

- AI roadmap and adoption recommendations

- Integrated Data & AI findings report

- Final workshop

Throughout: project management appropriate to a £28.5k engagement. A maintained project plan, a regular check-in with the Chief Insights Officer, short written progress notes at each phase boundary, and documentation produced continuously.

## How we work

We communicate in plain English over technical jargon, choose working sessions over presentations, and share findings as they emerge. We are a two-person partnership, so the people 100x briefs are the people doing the work \- no account managers, no handoffs to junior staff, no layer between you and the people making the calls. Our aim is to leave 100x with something it owns and can run itself, not a dependency on us: our recommendations are vendor-neutral, we have no reseller relationships, and we would rather hand over capability than create a retainer.

3. # **Team Structure and Key Personnel**

Jack Casstles-Jones, Co-founder (engagement lead). Leads stakeholder engagement, interviews, workshop facilitation, and synthesis. Jack co-designed and delivered Tandem's AI adoption workshop programme and leads client relationships across Tandem's government and foundation work. Jack has a background in recruitment and teaching.

Maxime Downe, Co-founder (technical lead). Leads the systems review, data modelling, and AI assessment. Max led the data architecture of the UK Skills Explorer and the engineering of GatBot and the SFCT AI helpdesk prototype. Max has a background in architecture.

Both of us work across both strands; the split above reflects where each of us leads. We can flex additional specialist capacity through our subcontractor network if a specific need emerges (for example, deep Microsoft 365 governance expertise), with any such use agreed with 100x in advance and within the fixed budget.

4. # **Budget Breakdown and Payment Schedule**

Our day rate is £500 excluding VAT. We propose a fixed price of £28,500 excluding VAT for 57 delivery days across the six months, allocated as follows:

| Workstream                                                          | Days   | Cost        |
| :------------------------------------------------------------------ | :----- | :---------- |
| Inception and project management (throughout)                       | 7      | £3,500      |
| Data mapping and planning (discovery, analysis, recommendations)    | 17     | £8,500      |
| AI review (assessment, opportunity identification, recommendations) | 17     | £8,500      |
| Working Group enablement (facilitated sessions throughout)          | 6      | £3,000      |
| Synthesis, final report, prototype spikes, and final workshop       | 10     | £5,000      |
| **Total (excluding VAT)**                                           | **57** | **£28,500** |

Payment schedule: three invoices of £9,500 \- end of Phase 1, end of Phase 2, and on delivery of the final report and workshop. We can adjust to LSE's standard schedule if preferred

5. # **Assumptions, Risks and Dependencies**

The timeline assumes stakeholders are available for interviews and workshops within each phase window, and that we get read access (or guided walkthroughs) of relevant systems early in Phase 1\. We know this work lands on top of everyone's day job, so we will keep our demands on people's time proportionate \- grouping sessions sensibly, coming prepared, and doing the desk-based review ourselves wherever we can. We will agree and protect the interview schedule at inception, since stakeholder availability is the most common cause of slippage in discovery work.

Discovery will involve systems holding personal and commercially sensitive venture data. We will work under NDA, keep material within 100x's own environment wherever possible, and flag GDPR concerns as we find them, not only in the final report. Relatedly, an honest AI usage baseline depends on staff being candid about informal use of AI tools; in our experience that takes a clearly non-judgemental framing, which we will agree with the Chief Insights Officer before interviews begin.

A £28,500 budget across two connected projects demands firm prioritisation. At inception we will agree which areas warrant depth and which warrant breadth, and revisit that at each phase boundary. Prototype spikes are time-boxed and undertaken only where they de-risk a priority recommendation.

Finally, as a two-person team we carry key-person risk. We mitigate it by both working across all strands and documenting continuously, so nothing lives only in one person's head.

---

We would be glad to discuss any element of this proposal. Thank you\!

[image1]: data:image/png;base64,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

