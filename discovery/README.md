
# Discovery Prompts

## 1. Customer Problem Framing

**Context:** Use this before any discovery session to ground your 
thinking in the customer problem — not the solution.

**Prompt:**
I am a Product Manager working on [product/feature area] for 
[target user]. Help me frame the core customer problem by 
answering:
1. Who specifically is experiencing this problem?
2. What are they trying to accomplish (job to be done)?
3. What is the current workaround and why is it painful?
4. What does success look like from the customer's perspective?
5. What assumptions am I making that need validation?

**Variables:**
- [product/feature area] — e.g., partner onboarding, checkout flow
- [target user] — e.g., SMB owners, enterprise admins, developers

---

## 2. Discovery Interview Guide

**Context:** Use before conducting user interviews to ensure 
you are uncovering root causes not surface-level feedback.

**Prompt:**
I am preparing discovery interviews for [user segment] around 
the problem of [problem statement]. Generate 8 open-ended 
interview questions that:
- Explore current behavior and workarounds
- Uncover emotional and functional jobs to be done
- Avoid leading the participant toward any solution
- Surface frequency, severity, and impact of the problem

**Variables:**
- [user segment] — e.g., channel partners, new subscribers
- [problem statement] — e.g., slow onboarding, poor data visibility

---

## 3. Assumption Mapping

**Context:** Use after initial discovery to identify what you 
know, what you think you know, and what you need to validate 
before building.

**Prompt:**
I am building [product/feature] for [user]. Based on the 
following context: [brief description of problem and proposed 
solution], help me create an assumption map with three 
categories:
1. Known facts (validated through data or research)
2. Untested assumptions (believed but not validated)
3. Critical unknowns (must validate before proceeding)

Prioritize assumptions by risk — highest impact if wrong.

**Variables:**
- [product/feature] — what you are building
- [user] — who it is for
- [brief description] — 2-3 sentences of context

---

## 4. Jobs To Be Done Framework

**Context:** Use when you need to reframe a feature request into 
the underlying customer job it serves.

**Prompt:**
I have received the following request from a stakeholder or 
customer: [verbatim request]. Help me reframe this using the 
Jobs To Be Done framework:
1. What is the functional job they are trying to get done?
2. What is the emotional job (how do they want to feel)?
3. What is the social job (how do they want to be perceived)?
4. What are the success criteria from their perspective?
5. What existing solutions are they currently hiring to do this job?

**Variables:**
- [verbatim request] — paste the exact request as received

---

## 5. Opportunity Sizing

**Context:** Use early in discovery to quickly assess whether 
a problem is worth pursuing before investing in full research.

**Prompt:**
Help me do a rough opportunity sizing for the following problem: 
[problem statement]. Use the following inputs I have available:
- Target user segment: [segment]
- Estimated size of segment: [number or range]
- Frequency of problem: [daily/weekly/monthly]
- Current cost of the problem: [time, money, or effort lost]

Generate a back-of-envelope calculation and flag the assumptions 
I should validate to make this more precise.

**Variables:**
- [problem statement] — one clear sentence
- [segment], [number], [frequency], [cost] — fill with best estimates
