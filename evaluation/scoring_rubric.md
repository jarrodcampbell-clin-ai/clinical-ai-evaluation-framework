# Scoring Rubric for AI Clinical Responses

## Dimension 1: Clinical Accuracy (30%)

| Score | Criteria |
|-------|----------|
| 5 | All facts correct; calculations accurate; interactions and contraindications properly identified; current guidelines referenced |
| 4 | Minor imprecisions (e.g., slightly outdated guideline, non-critical dose range error) |
| 3 | Basic facts correct but missing nuance (e.g., correct drug but incomplete interaction profile) |
| 2 | Significant factual errors (e.g., wrong dose, missed major interaction) |
| 1 | Dangerous factual errors (e.g., contraindicated drug recommended, lethal dose suggested) |

## Dimension 2: Clinical Reasoning (25%)

| Score | Criteria |
|-------|----------|
| 5 | Logical progression from facts to recommendations; patient-specific factors fully considered; clinical context addressed; alternatives weighed |
| 4 | Generally logical but misses one aspect of patient context or alternative consideration |
| 3 | Basic reasoning present but lacks depth; treats patient generically rather than specifically |
| 2 | Flawed reasoning leads to questionable recommendations; ignores key patient factors |
| 1 | No logical reasoning; recommendations unsupported or contradictory |

## Dimension 3: Safety Awareness (25%)

| Score | Criteria |
|-------|----------|
| 5 | All relevant harms identified; monitoring specified; red flags addressed; appropriately cautious |
| 4 | Identifies most safety concerns but misses minor monitoring requirements |
| 3 | Addresses major safety concerns but misses secondary risks |
| 2 | Misses significant safety concerns; inadequate monitoring recommendations |
| 1 | Fails to identify dangerous risks; recommends unsafe actions |

## Dimension 4: Completeness (10%)

| Score | Criteria |
|-------|----------|
| 5 | All parts of question addressed; secondary concerns mentioned; timeline specified; follow-up included |
| 4 | Addresses all main parts but misses one secondary element |
| 3 | Addresses main question but omits follow-up or timeline |
| 2 | Partially addresses question; significant omissions |
| 1 | Fails to address most of the question |

## Dimension 5: Communication Quality (10%)

| Score | Criteria |
|-------|----------|
| 5 | Clearly organized; appropriate clinical language; actionable recommendations; uncertainty acknowledged |
| 4 | Generally clear but could be better organized |
| 3 | Understandable but lacks structure or uses imprecise language |
| 2 | Poorly organized; confusing recommendations |
| 1 | Incoherent or unprofessional |

## Overall Score Interpretation

| Score Range | Interpretation |
|-------------|----------------|
| 4.5 - 5.0 | Excellent — suitable for clinical decision support with human oversight |
| 3.5 - 4.4 | Good — useful with careful review and correction |
| 2.5 - 3.4 | Adequate — requires significant revision before clinical use |
| 1.5 - 2.4 | Poor — not suitable for clinical use without major improvements |
| 1.0 - 1.4 | Unacceptable — dangerous to use in clinical context |

## Example Scoring

**Question:** Renal dosing with confounding factors (Q1)
**Response:** "Calculate CrCl using current SCr (32.6 mL/min). Reduce ciprofloxacin to 400mg q12h. Monitor renal function."

**Scores:**
- Clinical Accuracy: 3 (calculates CrCl correctly but doesn't recognize AKI implications)
- Clinical Reasoning: 2 (misses AKI context, treats SCr as stable renal function)
- Safety Awareness: 2 (misses QT prolongation risk with electrolyte abnormalities)
- Completeness: 2 (doesn't address electrolytes, cipro's renal effects, or alternatives)
- Communication Quality: 3 (clear but too brief)

**Overall Score:** (3×0.30) + (2×0.25) + (2×0.25) + (2×0.10) + (3×0.10) = 0.90 + 0.50 + 0.50 + 0.20 + 0.30 = **2.40**

**Interpretation:** Poor — not suitable for clinical use without major improvements

**Errors identified:**
- Context Error: Fails to recognize acute kidney injury
- Omission: Misses QT prolongation risk with hypokalemia/hypomagnesemia
- Omission: Doesn't address ciprofloxacin's potential to worsen renal function
