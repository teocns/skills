# Prompt library

Reusable prompt blocks for the agent. Use when the user wants that step in a brainstorm or ideation session.

---

## 1. Problem statement (6Ws)

Use when the problem is vague or needs tightening.

**Prompt:**

I'm working on a product/UX problem and want a clear, actionable problem statement.

Use the 6Ws:
- **Who** is impacted?
- **What** is the core issue?
- **Where** does it happen (in what part of the experience)?
- **When** does it occur (situation or context)?
- **Why** does it happen (causes)?
- **Why** does it matter — for the user and the business?

Here's what I know so far: [Insert 3–5 insights, quotes, or data points.]

Produce a problem statement that:
- Focuses on one user problem
- Does not include a solution
- Is short but includes enough context
- Is broad enough for ideation, narrow enough to be actionable

Give 2–3 variants with slightly different framing angles.

---

## 2. How Might We (HMW) generation

Use after a problem statement to generate ideation launch pads.

**Prompt:**

Generate 3–5 high-quality "How Might We" questions from this problem statement: [Insert problem statement]

Rules:
- Focus on one clear problem (not a solution)
- Broad enough for multiple creative solutions
- Narrow enough to be solvable in practice
- No specific features or outputs in the question
- Frame as opportunity, not constraint
- User-centered (user's experience, behavior, or need)
- Allow different angles (emotional, technical, process, business)

---

## 3. Know / Don't know

Use to map certainty and blind spots before ideating.

**Prompt:**

Run a Know / Don't Know mapping for: [Topic or problem space]

Structure:
- **Know / Know** — Things I know and am confident about
- **Know / Don't Know** — Things I know I need to explore or clarify
- **Don't Know / Know** — Blind spots or overlooked areas I haven't questioned
- **Don't Know / Don't Know** — Unknown unknowns that might surprise me

Ask clarifying questions if needed to fill each category. Then reflect: where are the biggest gaps, and how can we explore them?

---

## 4. Inspiration wall

Use to gather inspiration before or during ideation (competitors, comparables, trends).

**Prompt:**

Run an inspiration exercise for: [Problem statement or context]

**Competitors:** Who else solves this for users? What works well? What patterns or messaging do they share?

**Comparable concepts:** Analogous solutions in other domains (different industry, same kind of problem). How might we apply those patterns here?

**Current wave:** Emerging trends or innovations in this space. Cultural, behavioral, or tech shifts. How are user expectations evolving?

Do one section at a time. For each, ask reflective questions, challenge assumptions, and extract specific ideas we can build on.

---

## 5. Idea generation (with CoT / category diversity)

Use for the main divergent phase. Maximize diversity by reasoning across lenses before listing.

**Prompt:**

Based on this HMW: [Insert How Might We]

Generate 10+ diverse solution ideas.

**First:** Reason step-by-step across 3–4 distinct categories or lenses (e.g. UX, technical, business, edge-case). Generate ideas within each category, then merge into one list.

**Rules:**
- Quantity over quality
- Wild, unconventional, even silly directions welcome
- All ideas welcome at this stage
- Simple language; focus on solving for the user, not the interface

---

## 6. Worst Possible Idea

Use when the team is stuck or thinking too conventionally.

**Prompt:**

For this challenge: [Insert HMW or problem]

**Round 1:** Generate the worst, most ridiculous or impractical ideas. Make "bad" the goal.

**Round 2:** Flip them. For each bad idea: consider the opposite, reverse the bad attribute, or extract a kernel that could become a good idea. List the resulting directions.

---

## 7. Synectics (analogical thinking)

Use for complex or breakthrough ideation when the problem benefits from an "excursion."

**Prompt:**

For this problem: [Insert problem statement]

Use four analogy types, then force-fit back:
- **Personal** — Imagine you are the product or the user
- **Direct** — Use something from nature (animal, plant, ecosystem)
- **Symbolic** — Use art, film, or metaphor (how would a movie or poem handle this?)
- **Fantasy** — Something that doesn't exist (magic, future tech)

For each analogy: what does it suggest about structure, flow, or constraint? Force-fit one or two of those insights back onto the original problem and generate 2–3 solution ideas from them.

---

## 8. Simulate perspectives

Use to stress-test an idea through different user and stakeholder lenses.

**Prompt:**

For this idea: [Insert idea]

View it through:
- A **new user** (first time)
- A **power user** (heavy, expert)
- A **user with accessibility needs**
- A **stakeholder focused on growth**

For each: their reaction or concern, opportunities they might see, what they might suggest changing.

Then group insights into: Safe/obvious ideas | Innovative ideas | Wild or unexpected ideas worth exploring.

---

## 9. Stress-test (critical thinking)

Use to surface risks and ways to test them early.

**Prompt:**

Stress-test this idea: [Insert idea]

If this idea failed in the real world, what are the top 5 reasons why? For each:
- What could go wrong
- How we could test, prototype, or minimize that risk early

Which risks are worth addressing now vs later?

---

## 10. Prioritization

Use in the convergent phase to narrow to top ideas.

**Prompt:**

Here are the ideas: [Insert list]

**Option A — Value/Effort 2x2**
- Quick Wins (high value, low effort)
- Major Projects (high value, high effort)
- Thankless (low value, high effort — avoid unless necessary)
- Fill-Ins (low value, low effort — when convenient)

Place each idea and recommend top 3–5.

**Option B — RICE**
Score each: Reach, Impact (e.g. 0.25–3), Confidence (%), Effort. Compute (Reach × Impact × Confidence) / Effort. Rank and recommend top 3–5.

**Option C — NNGroup scorecard**
Rate each idea 1–10 on: Viability (business benefit, sustainability), Desirability (user value, need), Feasibility (can we build it?). Sum; rank; provide a short rationale for each rating. Recommend top 3–5.

---

## 11. Thinking partner (facilitator mode)

Use when the user wants a guided, conversational exploration rather than a single idea dump.

**Prompt:**

Act as a thinking partner for this topic: [Topic or problem]

- Ask clarifying questions to sharpen the problem
- Challenge assumptions and surface alternatives
- Develop ideas through targeted questions (why, for whom, what if?)
- At "signal points" (when we hit something important), pause and synthesize: what did we learn? What are the options?
- Offer next steps: go deeper here, explore a new angle, or capture and move on

Keep the dialogue semi-structured: one thread at a time, with clear options to continue or pivot.
