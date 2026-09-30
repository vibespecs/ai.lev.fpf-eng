# Engineering DPF Suite {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Engineering DPF Suite* (28 September 2026), `Engineering DPF Suite/README.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. The document, carried whole. See LICENSE.md for the list of changes.

# Engineering DPF Suite {#root-2}

> Methods for difficult engineering decisions, explained as patterns you can use with your colleagues and AI assistants.

- **Author:** Anatoly Levenchuk, with AI-assisted development and review
- **Version:** 28 September 2026
- **Status:** Eternal alpha: already used in project analyses and development programmes, and revised as the methods and their evidence improve.
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for original framework content; third-party material retains its own terms.
- **Publication:** [FPF repository](https://github.com/ailev/FPF)

You may be choosing an architecture, trying to make a working method reproducible, reorganizing a team, or deciding what to develop next. The Suite helps you find a useful way to tackle that particular difficulty and produce an answer you can act on.

A **DPF**, or **Domain Principle Framework**, collects methods for a field as a language of patterns. Each pattern explains a recurring difficulty, a way to address it, the result to obtain, and the conditions that affect its use. The methods are connected: one can help you discover or supply what another needs.

[FPF Core](spec://ai.lev/fpf-spec/pub/TOC#root) supplies the common concepts used across fields. The DPFs bring in the field's methods, competing approaches, examples and source evidence. This combination lets a team discuss technical choices, ways of working and organizational consequences in a shared language.

Using a DPF also means finding its place in the work you must actually perform. Which constituent abilities and resources are needed, what larger work is being done through the selected action, and what changes if that whole's conditions change? The [Method-vertical examples](spec://ai.lev/fpf-eng/pub/reference/combine-results-and-handle-a-missing-input#what-must-be-available-through-the-method-vertical) show how a missing intermediate capability or shared resource changes the next move. A described Method can cover only part of what successful performance requires.

## Start with the problem in front of you {#start-with-the-problem-in-front-of-you}

Describe the situation in ordinary words. For example:

> “We can buy a controller, commission one, or build it ourselves. How do we compare the alternatives, including the work and cost that each leaves to us?”

Open [SYSE.24 - Choose How the Project Will Obtain a Needed Engineering Result](spec://ai.lev/fpf-eng-syse/contract/SYSE-24#root). It helps you compare complete ways to obtain the result: equipment alone, integration work, operating support, capability, access and eventual replacement can all change the choice. Your first useful result may be a defensible comparison or a precise question to put to a supplier.

Use a pattern's **Problem frame** to check that it fits. Its **Solution** gives the working moves; the example shows how they fit a case, and the checklist helps inspect your result. Bring in another pattern when you need its answer. You can begin from a result your project already has.

You can read this way yourself, use a pattern in a working meeting, or ask an AI assistant to help apply it. You do not need to read every framework before starting.

You can ask an assisting agent to explain an answer or give feedback in ordinary language, without FPF terminology. For example: “Explain this and comment on my proposal without FPF jargon; use the language of my work.” The patterns can guide the reasoning while the answer uses familiar words.

## Choose a DPF {#choose-a-dpf}

The public folder contains twenty-six published DPFs with 414 pattern bodies. Start with the working question nearest to yours. Each linked publication provides its full searchable pattern index.

### Published DPFs {#published-dpfs}

| What you are trying to do | Published DPF | A result it can help you obtain |
| --- | --- | --- |
| Bring about or change an engineered system, from its intended use to working integration and continued development. | [Systems Engineering](spec://ai.lev/fpf-eng-syse/pub/TOC#root) - 52 patterns | A system boundary, architecture decision, comparison of ways to obtain a result, integration plan, or justified release decision. It also covers general Platform Engineering, a substantial software delivery and reliability profile, and eleven Methods for engineering agent work and support, with human and technical realizations. |
| Choose, explain, test or improve a way of working, or develop a pattern language from source knowledge. | [Method Engineering](spec://ai.lev/fpf-eng-me/pub/TOC#root) - 26 patterns | An explicit method, a mathematical comparison or construction of a changed way of working, a useful description or support arrangement, evidence about fit, transfer and practical value, or a source-based contribution to a method description in pattern-language form. |
| Change how an organization contributes, assigns work and enables people and other performers to act. | [Organization Change Engineering](spec://ai.lev/fpf-eng-oce/pub/TOC#root) - 17 patterns | A compared organizational arrangement, clarified assignments and authority, a supported change, or a decision about its consequences. |
| Work out what the problem is, compare possible directions, or prepare a recommendation. | [Problem Structuring and Decision Support](spec://ai.lev/fpf-eng-psd/pub/TOC#root) - 17 patterns | Several useful problem formulations, decision alternatives, a comparison under uncertainty, or a recommendation with its grounds and limits. |
| Find a worthwhile contribution or an obtaining way, and relate direction, options and bounded commitments under uncertainty. | [Strategy](spec://ai.lev/fpf-eng-str/pub/TOC#root) - 15 patterns | A qualified or provisional problem/contribution account, conditional direction, explained options with their support and gaps, comparison, recommendation or authorized commitment; a decision about conflicting work, changed assumptions or strategic practice. A sufficient answer can finish without an experiment or a new commitment. |
| Create, perform, teach or develop music and dance practices. | [Music and Dance Practice Engineering](spec://ai.lev/fpf-eng-mdpe/pub/TOC#root) - 22 patterns | A performance or practice design, a useful observation, a transmission method, or a choice about the practice's next development. |
| Recognize, represent, vary, perform, teach or observe rhythmic relations. | [Embodied Rhythmics](spec://ai.lev/fpf-eng-rhy/pub/TOC#root) - 14 patterns | A specific rhythmic correction, usable representation or variant, coordinated performance, representative exercise, bounded capability probe or observation. Its connected uses obtain cultural transmission and development contributions from the relevant MDPE methods. |
| Understand and change the bodily contribution to a familiar human movement. | [Somatic Movement Modeling](spec://ai.lev/fpf-eng-som/pub/TOC#root) - 5 patterns | A model and correction attempt connecting experience, regulation and result; a needed bodily distinction, controllable change, coordination or support transition. Movement technique and suitable physical demands remain prerequisites. |
| Keep an operation working while demand, queues, capacity, commitments and evidence change. | [Operations Management](spec://ai.lev/fpf-eng-ops/pub/TOC#root) - 26 patterns | A bounded admission or continuation decision, queue or constraint treatment, capacity and service account, operating-method improvement, quality response, simultaneous-work reconciliation, or cultural-continuation decision. |
| Explain how work uses resources and how that use appears in money, forecasts and performance accounts. | [Management Accounting](spec://ai.lev/fpf-eng-ma/pub/TOC#root) - 9 patterns | A resource and cost model, capacity account, cost allocation, reconciliation, forecast, margin explanation or assessment of accounting incentives. |
| Establish whose financial position is described, what can change it and how a financial service contributes to a participant's result. | [Financial Domain Modeling](spec://ai.lev/fpf-eng-fdm/pub/TOC#root) - 5 patterns | A model of parties, rights and obligations; conditional contractual flows; an established financial effect; or a connection between a service and its use. |
| Value investments, arrange finance, preserve liquidity or manage financial exposure. | [Corporate Finance](spec://ai.lev/fpf-eng-fin/pub/TOC#root) - 22 patterns | An investment valuation, financing comparison, liquidity response, hedge, treasury action or financial recommendation. |
| Connect economic plans, form feasible exchanges and commitments, or change resource-use and institutional arrangements. | [Economic Reasoning and Coordination](spec://ai.lev/fpf-eng-eco/pub/TOC#root) - 10 patterns | A grounded calculation, price response, exchange proposal, commitment or adaptation arrangement, shared-resource rule, institutional change or total-use comparison after an efficiency gain. |
| Explain dependence, spread, competing variants and the consequences of protective action. | [Defense and Transmission Modeling](spec://ai.lev/fpf-eng-dtm/pub/TOC#root) - 9 patterns | A participant comparison, transmission or interaction model, selection decomposition, or protective-action comparison grounded in the work and its available capabilities. |
| Establish corporate rights and powers, make a governing decision, protect a right or improve governance practice. | [Corporate Governance](spec://ai.lev/fpf-eng-cgov/pub/TOC#root) - 17 patterns | An authority answer, usable disclosure or review, a corporate act, a rights-protection result, an effective arrangement or a supported change to governance methods and culture. |
| Handle an administrative request, resolve a difficult case, or improve the arrangement providing the service. | [Organization Administration](spec://ai.lev/fpf-eng-adm/pub/TOC#root) - 15 patterns | Usable provision, a resolved exception, reconciled obligations and records, or a choice about controls, provider contributions and administrative burden. |
| Preserve or restore required equipment functioning, and manage the policies, support and programme that make maintenance useful. | [Maintenance Engineering and Management](spec://ai.lev/fpf-eng-mnt/pub/TOC#root) - 16 patterns | A qualified condition account, supported policy or intervention recommendation, feasible protected work and return to use, or a justified information, programme, Method or practice decision. Advice can be complete before repair. |
| Compare continued use, renewal, replacement or other changes for one asset, an interacting system or a portfolio. | [Engineering Asset Management](spec://ai.lev/fpf-eng-eam/pub/TOC#root) - 16 patterns | An applicable asset account, supported alternatives or programme recommendation, feasible timing, an asset decision, or a choice about improving asset-management arrangements, methods or culture. |
| Develop a person's capability, design learning for a future audience, or evaluate instructional material. | [Human Capability Development](spec://ai.lev/fpf-eng-hcd/pub/TOC#root) - 29 patterns | A supported demand, target or profile; a compared personal programme or whole learning-product design; feasible individual and group practice; performance, transfer or retention evidence; a continuing-development decision, or an instructional-material evaluation. |
| Develop a useful cultural or community contribution, with participation suited to its purpose. | [Community Building](spec://ai.lev/fpf-eng-cb/pub/TOC#root) - 16 patterns | A useful offer or exchange, workable participation and organising, an agreed continuation with the work it needs, a usable mandate for shared decisions, maintained repertoire, connection between practices or represented position. Independent carriers of a practice remain a possible route. |
| Understand a customer's situation, develop an offer, and organise the work needed to fulfil it. | [Marketing](spec://ai.lev/fpf-eng-mkt/pub/TOC#root) - 14 patterns | An answer to a customer question, an understandable and feasible choice, help suited to the customer's use, or a programme for selected organisations with evidence about cost, contribution and repeatability. |
| Construct a useful development opportunity, or advise a person, organization or other developing subject. | [Development Opportunity Construction and Development-Direction Advising](spec://ai.lev/fpf-eng-doca/pub/TOC#root) - 9 patterns | A bounded inquiry, characterized change, candidate direction with its supports, joint-reachability result, retained opportunity, or qualified advising engagement. PSD supplies the actual comparison and recommendation when those are needed. |
| Decide whether research is needed, conduct it, examine its conclusions or improve its methods. | [Research Method Practice](spec://ai.lev/fpf-eng-rmp/pub/TOC#root) - 9 patterns | An answer from existing evidence or a justified research plan; a protocol and record of research performed; an analysis, credibility judgement or corpus synthesis with its limits; a revised claim or question for another practice; or a choice to retain or improve the research method. |
| Connect separately governed meanings for a receiving use, qualify a model, handle semantic change or maintain shared modules. | [Semantic Integration Engineering](spec://ai.lev/fpf-eng-sie/pub/TOC#root) - 12 patterns | A bounded integration result, adequate model reuse or construction, affected-use repair or revalidation, or a sufficient interface agreement or modular-commons arrangement. |
| Help someone follow why an outcome occurred, how a calculation works, or why a recommendation follows. | [Explanation Design](spec://ai.lev/fpf-eng-exd/pub/TOC#root) - 6 patterns | A useful explanatory question, an account with its grounds, a worked example, coordinated text and diagrams, a repaired exchange, or a supported choice about improving an explanation. Includes instructional, technical and advisory, and human–AI profiles. |
| Notice consequential omissions, preserve answer meanings and coordinate checks in human, AI or mixed work. | [Checklist](spec://ai.lev/fpf-eng-chk/pub/TOC#root) - 6 patterns | Useful questions, an interpretable form, a workable occasion, grounded answers, a shared conclusion, or a bounded judgement about a criterion and its checking means. |

The word *engineering* includes physical equipment, factories, laboratories, buildings, robots and software, as well as the means needed to develop them. A platform can be a manufacturing or laboratory platform. The software profile addresses its particular delivery and reliability difficulties.

When your question crosses fields, open the [Suite Reference](spec://ai.lev/fpf-eng/pub/REFERENCE#root). It provides a detailed question index and worked cases, including [direct software-platform questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#resolve-a-software-platform-difficulty) for measurement, alerts, release exposure, recovery and repetitive work. The [instructional-material questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#evaluate-instructional-material-for-its-intended-use) lead to evaluation-specification construction and material evaluation; the [research preparation and trace questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#make-research-executable-and-inspect-its-course) lead to the RMP publication's operationalization and research-trace methods. When combining methods, match the result one supplies to what another needs and check their conditions of use. It also gives direct entries for [settling an HCD Method's supported use](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#develop-a-practice-or-a-person-s-capability) and [analyzing a research claim or choosing a relevant credibility examination](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#analyze-a-claim-or-examine-its-credibility). For retaining or changing a research Method and returning its consequences, use [the research-Method entry](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#retain-or-improve-a-research-method).

For preserving or restoring equipment functioning, use the [maintenance question index](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#maintain-equipment-and-manage-maintenance) or the [PS17 advice-to-selected-work example](spec://ai.lev/fpf-eng/pub/reference/can-we-recommend-a-repair-before-it-is-ready-to#root). To compare continued use, renewal, replacement or withdrawal by value, cost, risk and service, use the [asset-management question index](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#choose-how-to-use-and-change-engineered-assets). EAM provides both a [single-asset comparison](spec://ai.lev/fpf-eng-eam/pub/README#eam-asset-compare-continued-use-and-change-for-one-asset) and a [programme choice under shared constraints](spec://ai.lev/fpf-eng-eam/pub/README#eam-combination-choose-asset-work-under-shared-constraints). Choose by the result your question needs; either practice can concern one asset or many.

For a cost model, operating forecast or reconciliation of profit and cash, use the [management-accounting questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#explain-resource-use-costs-and-operating-accounts). For parties, rights, contractual events or the effects of financial actions, use the [financial-modeling questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#model-financial-positions-and-effects). For valuation, funding, liquidity or treasury action, use the [corporate-finance questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#value-investments-arrange-finance-and-manage-liquidity).

For economic plans that need to work together, use the [economic-coordination questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#coordinate-economic-plans-exchanges-and-shared-resources). The [venture example](spec://ai.lev/fpf-eng-eco/pub/README#eco-venture-turn-a-useful-idea-into-a-feasible-service) connects exchange discovery, calculation, commitments and adaptation; the shared-resource and efficiency examples show different combinations and stopping points.

For corporate authority, rights, board and committee work, disclosure or a decision, use the [corporate-governance questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#make-corporate-decisions-and-sustain-governing-contributions). The [interested-party transaction](spec://ai.lev/fpf-eng-cgov/pub/README#cgov-conflicted-matter-bring-an-interested-party-transaction-to) connects several contributions without treating an expert opinion as the corporate act.

For a rhythmic difficulty, use the [rhythm questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#work-with-rhythmic-relations-in-performance-and-learning). The [partnered-variation example](spec://ai.lev/fpf-eng-rhy/pub/README#rhy-card-01-make-a-variation-work-with-a-partner) connects recognizing a difficulty, preserving continuing movement, arranging cues and returning to the whole performance.

For a bodily correction that must work during a whole movement, use the [somatic modeling questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#model-and-change-the-bodily-contribution-to-movement). They distinguish an unclear bodily relation, an unavailable adjustment and a combination that breaks during changing support. The [connected SOM entries](spec://ai.lev/fpf-eng-som/pub/README#root) lead back to the receiving action and its concurrent demands.

For an explanation that someone must understand and use, start with the [explanation questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#make-an-explanation-understandable-and-usable). They distinguish the grounds for an account, its expression, the help a recipient needs and whether further repair is worthwhile.

For a practice whose spread or protective response changes the work, use the [dependence and protection questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#model-dependence-spread-and-protective-action). The [review-capacity example](spec://ai.lev/fpf-eng/pub/reference/can-protective-review-work-with-the-capacity-we#root) connects a modeled protective effect to the operating capacity and other commitments needed to obtain it.

For a checklist that misses a consequential question or yields reassuring entries without adequate grounds, use the [checklist questions](spec://ai.lev/fpf-eng/pub/reference/find-a-starting-pattern#select-and-use-checklists-without-losing-the-work-question). The [Checklist applications](spec://ai.lev/fpf-eng-chk/pub/applications#root) connect local checking with shared work, change and Method improvement.

For a person or technical agent choosing how to obtain a result, open the [agent engineering family](spec://ai.lev/fpf-eng-syse/pub/README#syse-llm-path-choose-and-use-a-way-to-complete-the-task). Its first use compares complete ways to calculate 347 × 6 and reaches the used answer; repeated assistance, input or control failures enter their corresponding constructors. The [connected Reference answer](spec://ai.lev/fpf-eng/pub/reference/make-an-available-contribution-work-in-the#root) then works support-selection diagnostics and a comparison of manual, rule and learning arrangements, alongside prediction, timely bodily action and reusable calculation. Its bounded structure descriptions and separate demonstrations explain conditional availability after those practical uses.

## Looking for development recommendations? {#looking-for-development-recommendations}

Open [Development Opportunity Construction and Development-Direction Advising](spec://ai.lev/fpf-eng-doca/pub/TOC#root) for the development-specific question. Its two branches can be used independently.

If useful opportunities are missing, start with [DOCA.1](spec://ai.lev/fpf-eng-doca/contract/DOCA-1#root) or the first missing construction result in its pattern index. To establish the terms of help from an adviser, use [DOCA.7](spec://ai.lev/fpf-eng-doca/contract/DOCA-7#root). When the inputs and service boundary are already adequate, go directly to the missing comparison or recommendation method: [PSD.13](spec://ai.lev/fpf-eng-psd/contract/PSD-13#root) may be enough. [DOCA.8](spec://ai.lev/fpf-eng-doca/contract/DOCA-8#root) helps requalify opportunities after their premises change.

For a particular person's programme comparison, use [HCD.2](spec://ai.lev/fpf-eng-hcd/contract/HCD-2#root) once the relevant demand, starting performance, support and candidate programmes are available. Use [HCD.28](spec://ai.lev/fpf-eng-hcd/contract/HCD-28#root) to construct or revise a learning product for a future audience. The Reference shows [how this construction contributes to advice for the programme author](spec://ai.lev/fpf-eng/pub/reference/how-do-we-recommend-a-development-direction#recommend-a-programme-before-the-learners-are-known).
For example, “What should our engineering team learn or change over the next four months?” calls for evidence about the work it needs to perform, present limits, feasible alternatives and opportunity costs. A course is one possible response. The inquiry can also reveal a method, tooling or organizational change that would help more. The Reference explains [how to connect advice with those domain results](spec://ai.lev/fpf-eng/pub/reference/how-do-we-recommend-a-development-direction#root).

## Work with an AI assistant {#work-with-an-ai-assistant}

Give the assistant access to FPF Core and the relevant DPF files. Tell it about the actual project, the decision you face, your constraints and the evidence available. Ask it to read the patterns it uses.

A useful starting request is:

> Help me work through this situation using FPF and the relevant Engineering DPFs: [describe the situation]. Identify the question we need to answer now, select the pattern that fits it, and help produce the next usable result. Explain the reasoning in ordinary engineering language, show the PatternIDs you used, and say which missing facts could change the answer.

Inspect the answer against the pattern and your project evidence. You and the other participants supply observations, specialist judgement and the authority to make real decisions. The assistant can help search, compare, draft and question the reasoning.

## What to read next {#what-to-read-next}

| You need... | Use... |
| --- | --- |
| A quick introduction and a first attempt with the Suite | This README. |
| A precise starting pattern, or a worked example involving several fields | [Engineering DPF Suite Reference](spec://ai.lev/fpf-eng/pub/REFERENCE#root). |
| The method itself, its example, checks and source discussion | The selected DPF's pattern body. Its Readme gives examples within that field. |
| An explanation of a shared FPF concept or general reasoning method | [FPF Core](spec://ai.lev/fpf-spec/pub/TOC#root). |
| A programme of study, exercises and feedback to build your abilities | An instructional Guide or a separately designed development programme. The Reference is organized for lookup while you work. |

The README introduces the Suite. The Reference helps you find and combine methods. Full pattern bodies remain the place to inspect what a method asks you to do.

## Suite scope and membership {#suite-scope-and-membership}

Engineering DPF Suite brings together domain pattern languages for developing engineered systems and the work, organizations and capabilities needed for them. It serves practitioners choosing and improving methods across these fields, using FPF's shared concepts.

**Current scope.** Under this purpose, the Suite includes the DPF series named in [Published DPFs](spec://ai.lev/fpf-eng/pub/README#published-dpfs), together with the [Engineering DPF Suite Reference](spec://ai.lev/fpf-eng/pub/REFERENCE#root) series. This section and the declared list are the current Suite identity and membership account. Each product keeps its own field boundary, readers, methods and dated editions. The list links available editions; the ecosystem catalogue describes the same products alongside the other FPF publications.

Include a DPF when its accepted product boundary and published pattern language supply a useful contribution to this common purpose, its relevant FPF dependencies are stated, and readers can reach its admitted edition and conditions of use. Record inclusion by updating this declared list when that product decision takes effect. A first accepted publication can implement the product and Suite-inclusion decisions together. Subsequent editions are admitted under the product's own rules; changing an edition or its availability leaves the product's Suite membership in place.

Review the scope when new practitioner needs, changed foundations or a product's limitations alter its contribution. A limitation calls for an explicit warning and a decision to repair, remove or replace the affected contribution. A dated removal ends membership; preserve the earlier fact for readers of older editions. If a product series ends or changes identity, its former membership ends and the replacement needs an inclusion decision.

Adding, removing or revising products preserves this Suite while its common purpose, inclusion rules and identity conditions remain. A change outside that scope identifies another Suite. If the shared purpose can no longer be served, decide whether to restore the collection or retire it; an empty or one-product interval needs an explicit restoration or retirement decision. State any continuing maintenance or future-availability commitment separately from this scope decision.

## Publication scope {#publication-scope}

The [FPF repository's Suite table](https://github.com/ailev/FPF#engineering-dpf-suite) gives the ecosystem view of these publications. When an available pattern does not cover a result your project needs, obtain that result from the relevant practice. The date at the start of each DPF identifies the publication you are using.

## Sources, revisions and citation {#sources-revisions-and-citation}

The DPFs bring together useful research and practitioner approaches, including disagreements and known limits. Source discussions explain what an approach contributes and where its evidence stops. The methods continue to change as better answers become available.

For consequential decisions, keep the publication date and the evidence behind the result you used. Revisit the affected conclusion when the situation or a relied-on source changes.

Cite the collection as: Anatoly Levenchuk. *Engineering DPF Suite*. [FPF repository](https://github.com/ailev/FPF). Include the date shown at the start of this file.

For a particular method, cite its DPF, PatternID, title and the date shown in that publication.

## License and reuse {#license-and-reuse}

The original FPF and DPF content by Anatoly Levenchuk, including the Engineering DPF Suite and Narrativization DPF, is available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): you may share and adapt it, including commercially, with attribution, a license link and an indication of changes. See the [licensing scope](https://github.com/ailev/FPF/blob/main/LICENSING.md) for the full notice and third-party and software boundaries.

You choose the license for your own original DPF or LPF. Using FPF methods or its publication form does not impose CC BY on your work. When sharing licensed FPF or DPF text under CC BY 4.0, preserve its attribution and comply with the license. Where your use needs no copyright permission, including under an applicable exception, these conditions do not apply. The license has no ShareAlike requirement.
