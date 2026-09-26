# Task 1: Adverse Drug Reaction (ADR) Identification Basics

## Objective
To review the given patient case, analyze the reported symptoms against the medication history and timeline, and determine whether the reaction observed is drug-related. If it is, the suspected drug is identified along with the reasoning and recommended next steps.

---

## 1. Patient Case Summary

| Parameter | Detail |
|---|---|
| Patient | Female, 45 years |
| Presenting symptoms | Rash, itching, nausea, dizziness |
| Drug 1 | Amoxicillin – started on Day -5, taken continuously |
| Drug 2 | Paracetamol – taken as needed (PRN), not a fixed schedule |
| Symptom onset | Day -2 (i.e., 3 days after starting Amoxicillin) |
| Current status | Symptoms are persisting on Day 0 |

---

## 2. Timeline Mapping

```
Day -5  →  Amoxicillin started
Day -2  →  Symptoms began (rash, itching, nausea, dizziness)
Day 0   →  Symptoms still present
```

The gap between starting Amoxicillin and the onset of symptoms is 3 days. This window is consistent with how drug hypersensitivity reactions to beta-lactam antibiotics typically present — most cutaneous reactions to amoxicillin show up anywhere from 1 to 14 days after the first dose, especially in a patient with no prior exposure recorded. Paracetamol, on the other hand, was used only intermittently (PRN), so there's no clean, continuous exposure window to match against the symptom timeline in the same way.

---

## 3. Is the Reaction Drug-Related?

Yes — the pattern of symptoms lines up well with a drug-induced hypersensitivity reaction rather than a coincidental illness. Reasoning:

- **Temporal plausibility**: Symptoms began after Amoxicillin exposure had already started and continued for a few days, not before.
- **Symptom cluster fits a known ADR pattern**: Rash + itching (pruritus) together are classic signs of a hypersensitivity/allergic-type reaction to a beta-lactam antibiotic. Nausea and dizziness can accompany this as part of a broader systemic allergic response, or may simply be additive GI/CNS-type effects.
- **Dechallenge/rechallenge data isn't available in this scenario** — we don't know whether symptoms improved after stopping the drug, or whether they returned on re-exposure. This is a limitation, and it's noted below.
- **No stronger alternative explanation** stands out from the information given (no mention of new food, infection, or other illness).

---

## 4. Suspected Drug: **Amoxicillin**

Paracetamol is not ruled out entirely, but it's the weaker candidate here because:
1. It was taken PRN, not on a fixed schedule, so its exposure pattern doesn't map as cleanly onto the Day -2 symptom onset.
2. Amoxicillin (and beta-lactams generally) are far more commonly implicated in rash/pruritus-type ADRs than paracetamol.
3. Paracetamol-induced hypersensitivity exists but is comparatively rare.

---

## 5. Causality Assessment (Naranjo Algorithm)

| # | Question | Answer | Score |
|---|---|---|---|
| 1 | Are there previous conclusive reports of this reaction? | Yes – amoxicillin-associated rash/pruritus is well documented | +1 |
| 2 | Did the adverse event appear after the suspected drug was given? | Yes | +2 |
| 3 | Did the reaction improve when the drug was discontinued/an antagonist given? | Not reported in scenario | 0 |
| 4 | Did the reaction reappear on re-administration? | Not reported | 0 |
| 5 | Are there alternative causes that could explain the reaction? | None mentioned | 0 |
| 6 | Did the reaction reappear with placebo? | Not applicable/unknown | 0 |
| 7 | Was the drug detected in blood/fluid in a toxic concentration? | Not tested | 0 |
| 8 | Was the reaction worse with a higher dose or better with a lower dose? | Not reported | 0 |
| 9 | Did the patient have a similar reaction to the same/similar drug before? | Not mentioned | 0 |
| 10 | Was the event confirmed by any objective evidence? | Clinical presentation only | 0 |

**Total Score: 3 → "Possible" ADR** (Naranjo scale: ≥9 Definite, 5–8 Probable, 1–4 Possible, ≤0 Doubtful)

The score lands in the "Possible" range mainly because several data points (dechallenge, rechallenge, past history) simply aren't available in the case as given — not because the evidence points away from Amoxicillin. With a proper dechallenge (symptoms resolving after stopping the drug), this would likely move up to "Probable."

---

## 6. Recommended Next Steps

1. **Discontinue Amoxicillin** under medical supervision and observe for symptom resolution (dechallenge).
2. **Symptomatic management**: antihistamine for itching/rash, antiemetic if nausea persists, and monitor vitals given the dizziness — mainly to rule out an early systemic/anaphylactoid response.
3. **Do not rechallenge** with the same drug unless clinically necessary and under controlled conditions, since a hypersensitivity reaction can worsen on re-exposure.
4. **Switch to an alternative antibiotic class** (non-beta-lactam) if antimicrobial therapy is still needed.
5. **Document the reaction** in the patient's medical record and flag Amoxicillin/penicillin-class drugs as an allergy for future prescriptions.
6. **Report the ADR** through the pharmacovigilance channel (e.g., PvPI in India) so it's captured in the national ADR database — this is what actually improves patient safety at a population level, not just for this one case.

---

## 7. Conclusion

Based on the timeline, symptom pattern, and standard causality assessment, this case represents a **probable drug hypersensitivity reaction to Amoxicillin**, presenting with rash, itching, nausea, and dizziness roughly 3 days into therapy. Paracetamol is unlikely to be the primary cause given its intermittent use. The case underlines why timeline correlation and a structured causality tool (like Naranjo or WHO-UMC) are essential in pharmacovigilance — a symptom in isolation means little without mapping it against exposure history.
