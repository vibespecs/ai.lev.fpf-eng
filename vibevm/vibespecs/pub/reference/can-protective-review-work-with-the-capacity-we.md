# Can protective review work with the capacity we have? {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Engineering DPF Suite Reference* (29 September 2026), `Engineering DPF Suite/ENGINEERING-DPF-SUITE-REFERENCE.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. One section of the Suite Reference. See LICENSE.md for the list of changes.

A service uses an automated method whose outputs can contain errors. In this constructed case, its operators are considering fewer automated runs and a review of the remaining results. The question is whether the combined action can reduce erroneous deliveries without consuming capacity needed for other work. All rates and times below are stipulated for the example, not measured performance.

[DTM.1](spec://ai.lev/fpf-eng-dtm/contract/DTM-1#root) separates dependence on automation from its useful and harmful consequences. Reducing its use must preserve the required service; an error count alone cannot establish that. [DTM.8](spec://ai.lev/fpf-eng-dtm/contract/DTM-8#root) then separates reducing established activity from intercepting its consequences.

After halving the original 200 runs, 100 remain per week. With a 0.25 error probability, they generate 25 expected errors. Assume that each detected error is kept out of delivery; any needed replacement result must be supplied separately. Reviewing all 100 results with 80% detection would leave 5 expected erroneous deliveries. This conclusion requires that capacity and detection performance be available together.

Suppose each review requires two minutes and the reviewers have only 100 usable minutes after their other commitments. [OPS.10 - Qualify Operating Capacity Under Variability](spec://ai.lev/fpf-eng-ops/contract/OPS-10#root) exposes a necessary capacity bound: at most 50 reviews fit, even before variability, rework or additional constraints. Even if all 50 reviews can be completed, uniform selection and the same conditional detection rate would remove 50 × 0.25 × 0.8 = 10 expected errors, leaving 15. The five-error result is therefore unavailable under this capacity limit.

The next move depends on what can change. [OPS.19 - Reconcile Simultaneous Operating Work Across Cases and Scales](spec://ai.lev/fpf-eng-ops/contract/OPS-19#root) compares obtaining more usable capacity, changing admission or retaining another arrangement while preserving other commitments. The service's responsible practice supplies the required output and acceptable consequence; neither DTM nor this arithmetic chooses them. If reviews create delay, consume learning opportunities or change subsequent behavior, [DTM.9](spec://ai.lev/fpf-eng-dtm/contract/DTM-9#root) adds those effects when they can change the choice.

Reading an output, detecting a fault and protecting the service can be constituent contributions to the same review work. Operating coordination also considers other work that competes for those minutes. This distinguishes a Method vertical from concurrent resource use. A plan to add reviews establishes neither the needed capability nor the later effect; evidence about the error and detection mechanisms can require returning to the subject model.
