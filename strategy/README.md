
# Strategy Prompts

## 1. Problem Statement to Strategic Opportunity

**Context:** Use when you need to elevate a tactical problem 
into a strategic framing that resonates with leadership.

**Prompt:**
I am working on the following problem: [problem statement] 
for [user segment] at [company/product]. Help me reframe this 
as a strategic opportunity by:
1. Connecting it to a broader market trend or shift
2. Articulating the cost of inaction over 12-24 months
3. Framing the opportunity in terms of business outcomes
   (revenue, retention, efficiency, competitive advantage)
4. Identifying which company strategic priorities this supports
5. Suggesting a north star metric that would define success

**Variables:**
- [problem statement] — one clear sentence
- [user segment] — who is affected
- [company/product] — your specific context

---

## 2. Build vs Buy vs Partner Analysis

**Context:** Use when evaluating how to deliver a capability — 
internally, through a vendor, or via a strategic partnership.

**Prompt:**
I need to evaluate whether to build, buy, or partner for 
[capability/feature] at [company]. Here is my context:
- Current state: [brief description]
- Timeline pressure: [urgency]
- Engineering capacity: [available or constrained]
- Strategic importance: [core differentiator or commodity]

Analyze all three options across:
1. Time to value
2. Total cost of ownership
3. Technical debt and maintenance risk
4. Strategic fit and long-term flexibility
5. Recommendation with clear rationale

**Variables:**
- [capability/feature] — what you are evaluating
- [company] — your context
- Fill in current state, timeline, capacity, and importance

---

## 3. Competitive Positioning

**Context:** Use when defining how your product should be 
positioned against existing alternatives in the market.

**Prompt:**
Help me develop a competitive positioning strategy for 
[product/feature] targeting [user segment]. Here are the 
main alternatives customers currently use: [list competitors 
or workarounds]. For each alternative, identify:
1. Their core strength and why customers choose them
2. Their biggest weakness or unmet customer need
3. Where our product can credibly differentiate

Then suggest a positioning statement using this format:
For [target user] who [need], [product] is the [category] 
that [key benefit] unlike [alternative].

**Variables:**
- [product/feature], [user segment] — your context
- [list competitors or workarounds] — include indirect alternatives

---

## 4. North Star Metric Framework

**Context:** Use when aligning your team around a single 
metric that best captures the value you deliver to customers.

**Prompt:**
Help me define a north star metric framework for [product] 
serving [user segment]. The core value we deliver is 
[value proposition in one sentence]. Generate:
1. Three candidate north star metrics with rationale for each
2. For each candidate — leading indicators that predict it
3. For each candidate — lagging indicators that confirm it
4. The tradeoffs between each option
5. A recommendation with clear reasoning

Flag any metrics that could be gamed or optimized in ways 
that hurt the customer experience.

**Variables:**
- [product] — what you are building
- [user segment] — who it serves
- [value proposition] — one sentence on core value delivered

---

## 5. Roadmap Prioritization Framework

**Context:** Use when you need to prioritize a backlog of 
initiatives against strategic goals and resource constraints.

**Prompt:**
I have the following list of potential initiatives for 
[product/team]: [list initiatives]. Help me prioritize 
them using a structured framework that considers:
1. Strategic alignment — does it support [company priority]?
2. Customer impact — frequency and severity of problem solved
3. Revenue or retention potential — estimated business value
4. Effort and complexity — rough engineering estimate
5. Dependencies and sequencing — what must happen first

Output a prioritized stack rank with a one-line rationale 
for each initiative. Flag any initiatives that are 
strategically important but low ROI in the short term.

**Variables:**
- [product/team] — your scope
- [list initiatives] — paste your backlog items
- [company priority] — your current strategic focus
