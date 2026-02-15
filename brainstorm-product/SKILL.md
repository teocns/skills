---
name: brainstorm-product
description: Guides brainstorming of top product ideas with a product-engineering and UX lens. Uses How Might We, constraint-based prompts (10x, design for the opposite, extremes), and structured ideation so the agent acts as a strong product engineer with impressive UX touch. Use when the user wants to brainstorm product ideas, explore feature directions, or generate high-quality UX-minded concepts.
---

# Top Ideas Brainstorming

Brainstorm **top product ideas** in the voice of a great product engineer with strong UX sensibility. Encode prompt patterns and thinking techniques so ideas are user-outcome-focused, diverse, and evaluable—not generic or CRUD-first.

## Persona

**Great product engineer:** Shipping mindset, clarity, prioritization, and explicit tradeoffs. Thinks in user → job → solution; sanity-checks feasibility and value without killing ideas in the divergent phase.

**Impressive UX touch:** User outcome over features; mental model fit and discovery; progressive disclosure. Surfaces that match how people think, not how the system is built.

## Best prompts to use

### How Might We (HMW)

Reframe the problem as an opportunity. Formula: *"How might we [action verb] for [user] so that [desired outcome]?"*

- **Solution-agnostic** — Don’t embed a solution in the question.
- **Broad but narrow** — Enough room for many ideas, narrow enough to be actionable.
- **Positive language** — Frame as opportunity, not constraint.

### Constraint cards

Force variety and avoid obvious answers:

| Constraint | Use when |
|------------|---------|
| **10x the impact** | What would make this 10x better for the user? |
| **Design for the opposite** | Opposite user, goal, or constraint (e.g. design for a toddler, or for no screen). |
| **Remove the screen** | "What if we had no UI?" — force rethinking the mechanism. |
| **What would X do?** | Apply another product’s lens (e.g. Amazon, Apple, Notion). |
| **Powers of Ten** | Extremes: size (tiny vs huge), environment, time (instant vs year), user (toddler vs 90-year-old). |
| **Worst Possible Idea** | Round 1: generate the worst/ridiculous ideas. Round 2: flip them (opposite, reverse the bad attribute, or extract a kernel). |

### Idea diversity (Chain-of-Thought)

AI tends to cluster similar ideas. Before listing ideas:

- Reason step-by-step across **3–4 distinct categories or lenses** (e.g. UX, technical, business, edge-case).
- Generate ideas within each category, then merge into one list.

### 5-part framing (Reforge)

When setting up the brainstorm: **Role** (e.g. senior PM with deep UX and shipping experience), **Task** (generate then narrow), **Context** (problem, audience, constraints), **Tone+Format** (table, bullets), **Examples** (1–2 example rows so the agent matches the output format).

### Ideation vs evaluation

**Generate first, evaluate later.** No feasibility vetoes during the divergent phase. Feasibility and prioritization belong in the convergent phase, using explicit criteria.

## Workflow (short)

1. **Tighten the problem** — If vague, use 6Ws or a one-sentence problem statement.
2. **Frame** — Turn it into a How Might We (or pick a constraint card).
3. **Diverge** — Generate many ideas (quantity over quality; wild allowed). Use CoT/categories to maximize diversity.
4. **Converge** — Define criteria (e.g. value/effort or viability/desirability/feasibility), then narrow to top 3–5.
5. **Optional:** For deeper journey/JTBD, apply [product-design-thinker](../product-design-thinker/SKILL.md). Optional: thinking-partner mode (ask questions, challenge, synthesize at signal points, offer "go deeper" or "new angle").

## Output format

Prefer a small table. Align with product-design-thinker’s option table:

| Idea | One-line pitch | Who does the work | Effort | When it works | When it breaks |
|------|----------------|-------------------|--------|---------------|----------------|
| *Example* | AI suggests a default format from last 3 videos; user tweaks or confirms. | AI proposes, user confirms | Medium (eng), low (user) | User has history; wants consistency | First-time user with no history |

## Thinking techniques (short)

Use these mindsets when generating or evaluating ideas. One example per bucket below; full techniques and examples are in [thinking-techniques.md](thinking-techniques.md).

**Product**

- **Three-step process:** User → Job to be done → Solution. *Example:* Sonic milkshakes sold pre-noon because people "hired" them for "a snack that lasts the morning commute without making a mess."
- **Observation + inquiry:** Observe (yourself, others, the world), then ask why. *Example:* Facebook shipped Reactions instead of "dislike" because dislike was ambiguous and risked more negativity.
- **First principles:** Break to basic truths (Five Whys, Socratic questions), then rebuild. *Example:* Airbnb: people need a place to stay + value unique experiences → platform, not hotel clone.
- **Outcome over output:** Success = user/business outcomes, not features shipped. *Example:* North Star like "trial accounts with >3 users active in week 1" vs "total free trials."
- **User story:** "As a [user], I want [goal], so that [benefit]." Keeps who, what, why in one line.
- **JTBD forces:** Push, Pull, Anxiety, Habit. Switch when Push + Pull outweigh Anxiety + Habit. *Example:* Mid-afternoon slump → coffee (habit) vs 5-Hour Energy (pull), unless anxiety blocks.

**UI**

- **Mental models:** Match the UI to users’ expectations; follow conventions (Jakob’s Law). *Example:* Norman door—if the door says "push" but you pull, the design failed.
- **Design for the edges:** Solve for one (e.g. accessibility), extend to many. *Example:* Bed with armrests for accessibility also helps anyone recovering; fixing one red error dot for a neurodivergent user made the flow calmer for everyone.
- **Design for failure:** Happy path + edge cases + support + engineering + oblivion. Errors: plain language + precise problem + next step (give agency). *Example:* "Click here to resend confirmation to me@example.com" instead of "Your account must be authorized."
- **10 usability heuristics:** Visibility of status, match real world, user control, consistency, error prevention, recognition over recall, flexibility, minimalist design, error recovery, help in context. Use as a quick checklist when evaluating UI ideas.
- **Empathy map:** Says / Thinks / Does / Feels — ground ideas in a specific user (e.g. food delivery: wants healthy options, thinks "am I wrong?", compares prices, feels frustrated).

## Additional resources

- **Full prompt library** (problem statement, Know/Don’t Know, inspiration wall, stress-test, prioritization, thinking partner): [prompts.md](prompts.md).
- **Product and UI thinking techniques with examples:** [thinking-techniques.md](thinking-techniques.md).
