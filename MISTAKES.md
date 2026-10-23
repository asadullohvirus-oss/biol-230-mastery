# Mistake Ledger

Last updated: 2026-10-23
Status: ACTIVE

Track meaningful conceptual errors only.

## Status definitions

- NEW — meaningful error observed once
- CONFIRMED — repeated independently or reveals a high-value misconception
- IMPROVING — increasingly correct/self-corrected
- RESOLVED — correct across spaced contexts; still eligible for hidden retest

## Root-cause categories

- missing knowledge
- causal-direction error
- incorrect mechanism
- terminology confusion
- equation error
- graph/data interpretation error
- cross-system integration failure
- incomplete chain
- careless execution

## Entry template

### M000 — Short label
Unit:
Chapter/objective:
Status:
Priority:
Root cause:
Typical error:
Correct model:
Evidence/occurrences:
First observed:
Last observed:
Remediation:
Retest strategy:
Anki needed: Yes / No
Anki card ID:
Resolution evidence:

## Active mistakes

### M001 — Reproductive-system function confused with mitosis
Unit: 1
Chapter/objective: Chapter 1, Lesson 2 — U1-C1-L2-O2
Status: IMPROVING
Priority: Medium
Root cause: incorrect mechanism / terminology confusion
Typical error: States that mitosis is a defining function of the reproductive system.
Correct model: The reproductive system produces gametes, releases hormones that regulate reproduction and other body processes, and associated organs transport and store gametes.
Evidence/occurrences: Repeated twice during closed-book Lesson 2 retrieval on 2026-09-23; after targeted correction, independently retrieved the correct system-level function.
First observed: 2026-09-23
Last observed: 2026-09-23
Remediation: Contrast the system-level function with unrelated cell-division terminology; retrieve the reproductive-system function without prompts.
Retest strategy: Hidden spaced retest in later Chapter 1 mixed-system review.
Anki needed: Yes — one targeted contrast card requested after repeated historical confusion; spaced retest still required.
Anki card ID: batch02, tag m001, prompt "Why is mitosis not the defining function of the reproductive system?"
Resolution evidence: One correct immediate retrieval after remediation on 2026-09-23; not yet spaced, so not resolved.

### M002 — ECF compartment and nutrient-pathway confusion
Unit: 1
Chapter/objective: Chapter 1, Lesson 4 — U1-C1-L4-O2
Status: NEW
Priority: High
Root cause: terminology confusion / incomplete chain
Typical error: Identifies ECF correctly and plasma as one compartment, but names generic 'water' instead of interstitial fluid and cannot trace an absorbed nutrient from plasma through interstitial fluid into the cell.
Correct model: ECF is internal environment; its components are plasma (fluid part of blood) and interstitial fluid (between cells). Absorbed nutrient route: digestive tract → plasma → interstitial fluid → muscle cell (intracellular fluid).
Evidence/occurrences: 2026-10-01 closed-book Chapter 1 targeted retest Q3; earlier 2026-09-24 compartment identification required prompting.
First observed: 2026-10-01
Last observed: 2026-10-01
Remediation: Reconstruct compartment locations and draw/retrieve nutrient route from memory; distinguish ICF from ECF.
Retest strategy: After learning, ask short unfamiliar exchange scenario without diagram/hints and have student name each compartment in order.
Anki needed: Yes — three distinct cards for ECF meaning, compartment locations, and nutrient route after weak independent retrieval; cards do not replace retesting.
Anki card ID: batch01, tag m002, prompts on ECF internal environment, ECF compartments, and nutrient route
Resolution evidence:

### M003 — Ion versus free-radical distinction
Unit: 1
Chapter/objective: Ch. 2 L1, U1-C2-L1-O2
Status: IMPROVING
Priority: Medium
Root cause: terminology confusion
Typical error: Defined a free radical by electron gain/loss rather than an unpaired outer-shell electron.
Correct model: Ion = net charge; free radical = unpaired outer-shell electron. These properties are independent.
Evidence: Repeated error followed by correct prompted retrieval on 2026-10-03.
Remediation: Charge-versus-pairing comparison.
Retest: Spaced classification of novel ion/free-radical examples with explanation.
Anki needed: Yes; pending.tsv batch03 m003.
Resolution evidence: Immediate retrieval correct; spaced retest outstanding.

### M004 — Bicarbonate buffer direction
Unit: 1
Chapter/objective: Chapter 2, Lesson 4 — U1-C2-L4-O3
Status: NEW
Priority: Medium
Root cause: causal-direction error
Typical error: Predicts that bicarbonate concentration increases when excess H+ is added.
Correct model: Bicarbonate (HCO3-) accepts added H+ to form H2CO3, so HCO3- is consumed and initially decreases while the rise in free H+ is limited.
Evidence/occurrences: 2026-10-11 Lesson 4 targeted correction test.
First observed: 2026-10-11
Last observed: 2026-10-11
Remediation: Track which reactant is consumed when H+ + HCO3- forms H2CO3.
Retest strategy: Spaced prediction with added acid and added base conditions.
Anki needed: Yes — one targeted mechanism card in batch04.
Anki card ID: batch04, tag m004
Resolution evidence:

### M005 — Figure 2.11 pH-scale interpretation
Unit: 1
Chapter/objective: Chapter 2, Lesson 4 — U1-C2-L4-O1
Status: NEW
Priority: Medium
Root cause: graph/data interpretation error
Typical error: At pH 6, selects neutral concentrations (H+ and OH- both 10^-7); overlooks that pH 8.41 and 5.59 are equally distant from 7.
Correct model: From required Figure 2.11, at pH 6 H+ is 10^-6 M and OH- is 10^-8 M. A change in pH shifts H+ and OH- in opposite directions. Equal numeric distances above/below pH 7 are equally distant on the pH scale.
Evidence: 2026-10-11 Lesson 4 coverage MCQ audit; 10/14 overall.
Remediation: Interpret new pH values directly from Figure 2.11 and compare distances from pH 7.
Retest: New pH values in straightforward one-best-answer questions; no excluded logarithm calculations.
Anki needed: No — remediate with practice first.
Resolution evidence:

### M006 — Colloid versus suspension
Unit: 1
Chapter/objective: Chapter 2, Lesson 4 — U1-C2-L4-O2
Status: CONFIRMED
Priority: Medium
Root cause: terminology confusion / missing knowledge
Typical error: Classifies a cloudy light-scattering mixture whose particles remain dispersed as a suspension rather than a colloid; initially attributed difference to polarity.
Correct model: Both solutions and colloids remain dispersed; colloids have particles large enough to scatter light. Suspensions contain material that eventually settles.
Evidence: 2026-10-11 initial incorrect mechanism, guessed correctly after correction, then incorrect classification on targeted 5/7 MCQ retest. Follow-up checkpoint quiz 5/6: again missed colloid/suspension distinction, selecting that suspensions always appear clear.
Remediation: Contrast particle size, light scattering and settling; retrieve explanation rather than recognize a label.
Retest: Ask an unfamiliar mixture scenario and require causal explanation without answer choices after a delay.
Anki needed: Existing targeted mixture comparison card in batch04; no duplicate.
Resolution evidence:

### M007 — DNA triplet, RNA codon and base-pairing notation
Unit: 1
Chapter/objective: Chapter 3, Lesson 5 — U1-C3-L5-O1
Status: IMPROVING
Priority: Medium
Root cause: terminology confusion / sequence representation
Typical error: Mistook an mRNA codon for three amino acids and produced a DNA-style complement containing T instead of an mRNA sequence containing U.
Correct model: A DNA base triplet and an mRNA codon each contain three nucleotides; mRNA base pairing with template DNA follows A-U, T-A, C-G, G-C.
Evidence: 2026-10-16 practice MCQ 15/17, missed Q2 and Q3. 2026-10-22 cumulative Q11 and Q12 correct on new RNA complement and codon-change applications; independent explanation not yet tested.
Remediation: Explain the difference and check RNA sequence notation during later spaced/cumulative recall, without immediate redundant retesting.
Retest: Later cumulative application; not a prerequisite to starting Lesson 6.
Anki needed: Not yet; reassess if error recurs.
Resolution evidence:

### M008 — Kinetochore attachment during mitosis
Unit: 1
Chapter/objective: Chapter 3, Lesson 6 — U1-C3-L6-O1
Status: IMPROVING
Priority: Low
Root cause: terminology / structure-function confusion
Typical error: Incorrectly identified the role of the kinetochore on the Lesson 6 MCQ.
Correct model: The kinetochore is a protein complex at a chromosome's centromere where spindle microtubules attach during mitosis.
Evidence: 2026-10-22 practice MCQ 14/17; missed Q9. 2026-10-22 cumulative Q1 correct on novel kinetochore disruption scenario.
Remediation: Contrast centromere (chromosome region) with kinetochore (protein attachment complex).
Retest: Later cumulative review, not immediate repeat.
Anki needed: No card yet; only if recurring.
Resolution evidence:

### M009 — Cyclin–Cdk phosphorylation and division timing
Unit: 1
Chapter/objective: Chapter 3, Lesson 6 — U1-C3-L6-O2
Status: IMPROVING
Priority: Medium
Root cause: missing mechanism / causal prediction
Typical error: Missed Cdk kinase action and effect of insufficient cyclin on mitotic entry.
Correct model: Cyclin binds and activates a specific Cdk, which transfers phosphate from ATP to target proteins. Without sufficient cyclin the relevant Cdk complex remains inadequately active, delaying the subsequent cell-cycle events, including mitotic entry.
Evidence: 2026-10-22 practice MCQ 14/17; missed Q15 and Q16 but Q14 correct. 2026-10-22 cumulative Q2 and Q3 correct on cyclin loss and deficient Cdk kinase activity.
Remediation: Review the regulation paragraph once, then later predict the effect of cyclin changes.
Retest: Later cumulative review, not immediate repeat.
Anki needed: Consider one short mechanism/prediction card if difficulty recurs.
Resolution evidence:

### M010 — Adherens versus desmosome junction function
Unit: 1
Chapter/objective: Chapter 3, Lesson 8 — U1-C3-L8-O2
Status: CONFIRMED
Priority: Medium
Root cause: terminology confusion / structure-function contrast
Typical error: Misidentified the adherens junction (Q14) and the desmosome (Q15) despite correctly classifying tight, gap and hemidesmosome junctions.
Correct model: Adherens junctions link adjacent cells through plaques coupled to actin microfilaments; desmosomes provide spot-like cell-to-cell reinforcement anchored to intermediate filaments. For both, use Figure 3.30; exclude red-struck microscopic details.
Evidence: 2026-10-22 Lesson 8 practice MCQ 13/17; missed Q14 and Q15. 2026-10-22 cumulative Q4 again misidentified adherens as gap; Q6 misidentified hemidesmosome as adherens (Q5 desmosome correct). 2026-10-23 Chat 03 changed-context remediation 0/3: actin-linked adhesion, intermediate-filament spot reinforcement, and basement-membrane-versus-gap-junction pairing all incorrect; remains CONFIRMED.
Remediation: Reviewed contrasting actin-linked adherens, intermediate-filament-linked desmosomes, basement-membrane hemidesmosomes, and communicating gap junctions; corrected the three selected distractors after the 0/3 attempt. Corrected recall not independently demonstrated.
Retest: Chat 02 independent, no-choice changed-context application on/after 2026-10-26 (at least one overnight interval). Distinguish cell-to-cell mechanical adhesion, cell-to-matrix anchoring, and direct communication; no previous stems or excluded microscopic detail.
Anki needed: Yes — two selective nonduplicate comparison cards added to anki/pending.tsv (2026-10-23), tagged m010.
Resolution evidence:

### M011 — Connective tissue collagen, elastic and reticular fibers
Unit: 1
Chapter/objective: Chapter 3, Lesson 8 — U1-C3-L8-O1
Status: CONFIRMED
Priority: Medium
Root cause: terminology confusion / structure-function contrast
Typical error: Confuses fibers giving tensile strength with those providing elasticity or fine structural support.
Correct model: Collagen resists pulling forces; elastic fibers stretch and recoil; reticular fibers form delicate supporting networks.
Evidence: 2026-10-22 Lesson 8 Q8 wrong; cumulative Q7 incorrectly chose elastic for tensile strength and Q9 incorrectly chose collagen for fine supporting network. Cumulative Q8 elastic recoil correct. 2026-10-23 Chat 03 changed-context remediation 0/2: selected elastic rather than collagen for loss of tensile strength, and thick collagen rather than reticular for lost delicate support; remains CONFIRMED.
Remediation: Corrected pulling/tensile force → collagen, stretch/recoil → elastic, and delicate cell-supporting mesh → reticular after unsuccessful application. No independent corrected retrieval yet.
Retest: Chat 02 independent changed-context application on/after 2026-10-26 (at least one overnight interval), using new tissue scenarios and no answer choices; avoid repeats of already-correct elastic recoil question.
Anki needed: Yes — one selective comparative collagen-versus-reticular card, with elastic recall in Extra; tagged m011 in anki/pending.tsv (2026-10-23).
Resolution evidence:

### M012 — Neurons versus neuroglia
Unit: 1
Chapter/objective: Chapter 3, Lesson 8 — U1-C3-L8-O1
Status: CONFIRMED
Priority: Medium
Root cause: missing knowledge / causal application
Typical error: Unreliable recognition of neuroglial support role, despite learning neuron electrical signalling.
Correct model: Neurons primarily generate and conduct electrical signals; neuroglia support, protect and help maintain neurons.
Evidence: 2026-10-22 Lesson 8 Q12 incorrect and Chapter 3 cumulative Q10 again incorrect on consequence of losing supporting cells. 2026-10-23 Chat 03 changed-context remediation 1/2: incorrectly predicted neuronal conversion rather than declining support after selective glial impairment; correctly distinguished direct neuronal loss from neuroglial support loss on the next question. Remains CONFIRMED; one correct prompted-choice application insufficient.
Remediation: Corrected glial impairment → weaker support/protection/maintenance and potentially unreliable neuronal function, rather than transdifferentiation; differentiated neurons as electrical signaling cells. Needs unprompted production.
Retest: Chat 02 independent new-context free-response on/after 2026-10-26 (at least one overnight interval), predict effect of selective support-cell dysfunction with neurons still intact; no old stems.
Anki needed: Yes — one concise prediction card tagged m012 added to anki/pending.tsv (2026-10-23) after repeat mismatch.
Resolution evidence:

### M013 — Enzyme activity versus net reaction energy in a pathway
Unit: 1
Chapter/objective: Chapter 4, Lesson 2 / Lesson 3 — U1-C4-L2-O3, U1-C4-L3-O3, U1-C4-L3-O4
Status: NEW
Priority: Medium
Root cause: incorrect mechanism / causal-direction prediction
Typical error: When an enzyme catalyzing B → C in A → B → C → D is activated with ample B and downstream capacity, selects that activation necessarily changes the net energy difference rather than initially accelerating B use and downstream D formation.
Correct model: Increasing enzyme activity changes the rate/flux of its catalyzed reaction, not the energy difference between reactants and products. Under the specified conditions B initially decreases and D formation can increase.
Evidence/occurrences: 2026-10-23 cross-lesson MCQ Q9 incorrect (D instead of B); rest of set Q1–Q8 correct, including novel blocked-step and feedback inhibition scenarios.
First observed: 2026-10-23
Last observed: 2026-10-23
Remediation: Contrast catalytic rate, activation barrier, and net potential energy. Short correction already supplied after MCQ; later require independent prediction in a new pathway without answer choices.
Retest strategy: First spaced retest due 2026-10-27 (or first Chat 02 session thereafter). Use an unfamiliar pathway with altered enzyme concentration or activation; require a closed-book prediction of intermediate and product changes and whether the reactant–product energy difference changes. Do not repeat the 2026-10-23 Q9 stem or test M013 during the M010–M012 remediation.
Anki needed: No — first occurrence; retest before considering a card.
Anki card ID:
Resolution evidence:
