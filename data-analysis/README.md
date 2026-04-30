# Data Analysis Prompts

## 1. Defining a Metrics Framework

**Context:** Use when launching a new product or feature and 
you need to establish a complete measurement framework before 
writing a single line of code.

**Prompt:**
I am launching [product/feature] for [user segment]. The core 
value we deliver is [value proposition]. Help me build a 
complete metrics framework with:
1. North star metric — the single metric that best captures 
   customer value delivered
2. Primary metrics — 3-4 metrics that directly measure success
3. Secondary metrics — leading indicators that predict the primary
4. Guardrail metrics — what we must not sacrifice in pursuit 
   of growth
5. Counter metrics — signals that would tell us we are 
   optimizing the wrong thing

For each metric include: definition, measurement method, 
target direction, and update frequency.

**Variables:**
- [product/feature] — what you are measuring
- [user segment] — who it serves
- [value proposition] — core value in one sentence

---

## 2. Diagnosing a Metric Drop

**Context:** Use when a key metric has declined unexpectedly 
and you need to structure a systematic root cause investigation.

**Prompt:**
My [metric name] dropped by [percentage] over [timeframe] 
for [product/feature]. Before this drop, the trend was 
[describe baseline]. Help me build a structured diagnosis 
framework that:
1. Identifies clarifying questions to ask before hypothesizing
2. Segments the drop by user type, geography, platform, 
   and acquisition channel
3. Separates internal causes from external factors
4. Lists the top 5 hypotheses ranked by likelihood
5. Defines the data queries or experiments needed to 
   confirm or eliminate each hypothesis

Do not jump to conclusions — walk through elimination 
systematically.

**Variables:**
- [metric name] — e.g., DAU, conversion rate, retention
- [percentage] — size of the drop
- [timeframe] — when it started
- [product/feature] — context
- [describe baseline] — what normal looked like before

---

## 3. Experiment Design and A/B Testing

**Context:** Use when designing an experiment to validate 
a product hypothesis before full rollout.

**Prompt:**
I want to test the following hypothesis: [hypothesis statement] 
for [product/feature] targeting [user segment]. Help me design 
a rigorous A/B test that includes:
1. Control and treatment group definitions
2. Primary success metric and minimum detectable effect
3. Required sample size and estimated runtime
4. Guardrail metrics to monitor during the test
5. Pre-defined criteria for ship, iterate, or kill decision
6. Risks that could invalidate the test results

Flag any confounding variables I should control for and 
whether this hypothesis is even testable with an A/B test 
or requires a different approach.

**Variables:**
- [hypothesis statement] — what you believe will happen and why
- [product/feature] — what you are testing
- [user segment] — who is in the experiment

---

## 4. Funnel Analysis and Conversion Optimization

**Context:** Use when analyzing where users are dropping off 
in a product flow and identifying the highest-impact 
optimization opportunities.

**Prompt:**
Here is my current product funnel for [user journey]: 
[list each step with current conversion rate]. The biggest 
drop-off is at [specific step]. Help me:
1. Identify the most likely reasons for drop-off at this step
2. Segment the drop-off by user type, device, and acquisition 
   source to find patterns
3. List qualitative research methods to understand the why
4. Suggest 3-5 testable interventions ranked by expected impact
5. Define success criteria for each intervention

Prioritize interventions that address root causes not just 
surface symptoms.

**Variables:**
- [user journey] — e.g., onboarding, checkout, activation
- [list each step with conversion rate] — your funnel data
- [specific step] — where the biggest drop occurs

---

## 5. Communicating Data Insights to Non-Technical Audiences

**Context:** Use when you need to translate complex data 
findings into a clear narrative that drives executive decisions.

**Prompt:**
I have the following data findings from [analysis type]: 
[paste key findings in raw form]. My audience is [describe 
stakeholders — their role and technical level]. Help me 
transform these findings into a clear executive narrative that:
1. Leads with the single most important insight
2. Provides only the context needed to understand it
3. Connects the finding to a business decision or action
4. Anticipates the top two questions the audience will ask
5. Ends with a clear recommendation and next step

Avoid jargon. Every number should have a so-what attached 
to it. If a finding does not drive a decision, cut it.

**Variables:**
- [analysis type] — e.g., cohort analysis, funnel analysis
- [paste key findings] — your raw data or bullet points
- [describe stakeholders] — who is in the room and their background
