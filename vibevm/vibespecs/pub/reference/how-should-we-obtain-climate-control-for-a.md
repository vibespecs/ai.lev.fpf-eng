# How should we obtain climate control for a greenhouse? {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Engineering DPF Suite Reference* (29 September 2026), `Engineering DPF Suite/ENGINEERING-DPF-SUITE-REFERENCE.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. One section of the Suite Reference. See LICENSE.md for the list of changes.

An equipment company needs climate control for a new greenhouse. It could buy a ready controller, commission a custom controller, develop one internally with AI assistance, or combine a ready controller with its own supervisory layer.

**Start with [SYSE.24](spec://ai.lev/fpf-eng-syse/contract/SYSE-24#root).** Compare ways to obtain the same accepted climate-control result. Include the integration and support work, required capability, access and eventual exit as well as the device price.

Identify the real greenhouse, crops, actuators, climate and operating conditions with [SYSE.1](spec://ai.lev/fpf-eng-syse/contract/SYSE-1#root) and [SYSE.16](spec://ai.lev/fpf-eng-syse/contract/SYSE-16#root) where needed. Obtain the actual performance and safety thresholds from the appropriate specialists.

| What could reverse the choice? | Evidence to obtain |
| --- | --- |
| Control performance or fallback fails in the intended configuration. | Configuration-specific control and electrical-safety thresholds, a permitted test, and evidence that the fallback works. |
| The attractive price hides a continuing access or support problem. | The actual offer, funding limit, access and update terms, data arrangements, support duties, remedies and exit costs over the intended period. |
| The receiving team cannot perform the work left to it. | A workable allocation among people, AI and providers, with assignments, authority and capability evidence. Identify any required human development. |
| The arrangement cannot be kept operating. | The maintenance, recovery, reliability and operating results required for the intended service, including capacity where it matters. |

The [GH-2 worked application](spec://ai.lev/fpf-eng-syse/pub/cross-pattern-applications#app-syse-04-worked-application-obtain-climate-control-for-a-new) follows this comparison. Two candidates remain; an interface-and-fallback test and the example's price-and-burden rule favour the ready controller with an internal supervisory layer. It leaves a further question: can the internal integration agent configure the layer and produce commissioning evidence before the need date?

Use the example to understand the comparison. For procurement, substitute your offers, configuration and evidence; have the responsible chooser record the resulting decision. [A.15.9](spec://ai.lev/fpf-spec/contract/A-15-9#root) helps request a missing specialist result when it could change the choice.

After selection, obtain the realization result through [SYSE.3](spec://ai.lev/fpf-eng-syse/contract/SYSE-3#root), configuration identity through [SYSE.13](spec://ai.lev/fpf-eng-syse/contract/SYSE-13#root), and the required evidence and release decision through [SYSE.10](spec://ai.lev/fpf-eng-syse/contract/SYSE-10#root), [SYSE.4](spec://ai.lev/fpf-eng-syse/contract/SYSE-4#root) and [SYSE.14](spec://ai.lev/fpf-eng-syse/contract/SYSE-14#root) as those questions arise. If the integration or commissioning method is itself inadequate, use [ME.1](spec://ai.lev/fpf-eng-me/contract/ME-1#root) to investigate it. Once the arrangement and operating conditions are established, OPS.5-OPS.7 in the complete Operations Management DPF address admission, exceptional-case continuation and local priority or commitment revision.

Pause only the decision that depends on a missing input. Keep the conclusions whose grounds still hold.
