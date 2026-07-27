# Evaluation Criteria for AI Clinical Responses

## Overview

This document defines the criteria used to evaluate AI-generated responses to clinical questions. Each response is assessed for clinical accuracy, reasoning quality, safety awareness, and communication effectiveness.

## Core Evaluation Dimensions

### 1. Clinical Accuracy (30%)
- Are the facts correct (drug names, doses, mechanisms, guidelines)?
- Are calculations accurate?
- Are drug interactions correctly identified?
- Are contraindications and warnings addressed?

### 2. Clinical Reasoning (25%)
- Does the response demonstrate logical progression from facts to recommendations?
- Are patient-specific factors considered?
- Is the clinical context addressed (e.g., severity of illness, treatment goals)?
- Are alternative approaches considered?

### 3. Safety Awareness (25%)
- Are potential harms identified?
- Are monitoring requirements specified?
- Are red flags and contraindications addressed?
- Is the response appropriately cautious without being paralyzed by rare risks?

### 4. Completeness (10%)
- Are all parts of the question addressed?
- Are relevant secondary concerns mentioned?
- Is the timeline of action specified when relevant?
- Are follow-up steps included?

### 5. Communication Quality (10%)
- Is the response clearly organized?
- Is the language appropriate for a clinical audience?
- Are recommendations actionable?
- Is uncertainty acknowledged when appropriate?

## Scoring Scale

Each dimension is scored 1-5:

- **5:** Excellent — comprehensive, accurate, well-reasoned
- **4:** Good — minor gaps or imprecisions
- **3:** Adequate — covers basics but lacks depth or misses secondary concerns
- **2:** Poor — significant gaps or errors
- **1:** Unacceptable — dangerous or largely incorrect

## Overall Score Calculation

Overall Score = (Clinical Accuracy × 0.30) + (Clinical Reasoning × 0.25) + (Safety Awareness × 0.25) + (Completeness × 0.10) + (Communication Quality × 0.10)

## Error Categorization

Errors are categorized by type:

- **Factual Error:** Incorrect drug information, dosing, or guideline reference
- **Reasoning Error:** Correct facts but wrong clinical conclusion
- **Omission:** Missing critical safety consideration or key recommendation
- **Hallucination:** Fabricated information presented as fact
- **Context Error:** Failing to account for patient-specific factors
- **Overcaution:** Excessive warnings that may lead to undertreatment
- **Undercaution:** Insufficient warnings about real risks

## Evaluation Process

1. Read the question and the AI response
2. Compare to the correct answer and clinical reasoning
3. Score each dimension 1-5
4. Identify and categorize any errors
5. Calculate overall score
6. Write a brief summary of strengths and weaknesses
