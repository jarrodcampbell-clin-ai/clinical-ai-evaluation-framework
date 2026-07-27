# Question 3: Vancomycin Pharmacokinetics

## Question

A 65-year-old male (weight 80kg, SCr 1.4 mg/dL) is started on vancomycin 1g IV q12h for MRSA bacteremia. A trough is drawn 30 minutes before the 4th dose and returns at 28 mcg/mL. What is your assessment of this level, what factors could contribute to this result, and what adjustments would you recommend?

## Clinical Domain
- Vancomycin pharmacokinetics
- Therapeutic drug monitoring
- MRSA bacteremia treatment
- AUC vs. trough-based dosing

## Correct Answer and Clinical Reasoning

### Trough Assessment
- Target trough for MRSA bacteremia: **15-20 mcg/mL** (traditional trough-based monitoring)
- Current trough: **28 mcg/mL** — this is **supratherapeutic**
- However, current guidelines (2020 ASHP/IDSA) recommend **AUC-guided monitoring** over trough-based
- A trough of 28 likely corresponds to an AUC24 > 600, which exceeds the recommended 400-600 range

### Contributing Factors to Investigate
1. **Was a loading dose given?** (25-30 mg/kg) — if yes, levels may be higher initially
2. **Was the trough drawn correctly?** — confirm it was truly 30 minutes before the 4th dose, not after
3. **Is the dosing weight appropriate?** — for obese patients, use adjusted body weight
4. **CrCl calculation:**
   - Cockcroft-Gault: [(140-65) × 80] / (72 × 1.4) = 59.5 mL/min
   - This suggests q12h dosing is reasonable, but individual variation exists
5. **Timing of the level:** Was it drawn at steady state? (Vancomycin reaches steady state in ~3-5 half-lives)

### Clinical Context: MRSA Bacteremia
- **Do NOT underdose** — MRSA bacteremia requires adequate exposure
- AUC24 target of 400-600 is critical for efficacy and nephrotoxicity avoidance
- Simply reducing the dose without calculating AUC risks underdosing

### Recommended Actions
1. **Hold the next dose** (trough of 28 is high enough to warrant a hold)
2. **Repeat trough before next dose** to confirm level is trending down
3. **Consider AUC calculation** using Bayesian software or trapezoidal method with a peak and trough
4. **Adjust dosing based on AUC:**
   - If AUC24 > 600: reduce dose or extend interval
   - Target AUC24: 400-600
5. **Monitor renal function** — vancomycin nephrotoxicity risk increases with high troughs
6. **Consider alternative dosing:** q8h or continuous infusion if AUC remains difficult to target

### What NOT to Do
- Don't simply reduce to 750mg q12h without calculating AUC
- Don't continue current dosing — level is supratherapeutic
- Don't switch to an alternative antibiotic solely due to one high level (MRSA bacteremia needs vanc)

## Expected AI Failure Modes

- Simply says "reduce the dose to 750mg q12h" without clinical reasoning
- Doesn't consider whether the trough was drawn correctly
- Doesn't address the clinical context (bacteremia requires adequate exposure)
- Doesn't mention holding the dose
- Ignores AUC-based dosing approach entirely
- Doesn't mention monitoring renal function
- Suggests switching to a different antibiotic

## Scoring Criteria

- **5/5:** Identifies supratherapeutic level, recommends holding dose, mentions AUC-guided approach, addresses MRSA bacteremia context, recommends renal monitoring
- **4/5:** Identifies most elements but misses AUC approach or doesn't mention holding dose
- **3/5:** Recognizes level is high and dose needs adjustment but lacks comprehensive approach
- **2/5:** Provides partial assessment with significant omissions
- **1/5:** Recommends continuing current dosing or gives dangerous advice
