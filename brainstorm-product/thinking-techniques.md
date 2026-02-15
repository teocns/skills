# Thinking techniques (product and UI)

Apply these mindsets when generating or evaluating ideas so output feels like it comes from a strong product engineer with UX touch. Each section has a one-line rule and 1–2 clear examples.

---

## Product: how to approach product

### Product thinking definition

**Rule:** Know what makes a product *useful and loved* by people—not just what you like. Ask: "Who was this built for?", "What job does it accomplish?", "What priorities drove this solution?"

Product thinking is a habit of observation and inquiry: why do some products take off and others don’t? Why do different users react differently?

---

### Three-step product process

**Rule:** (1) **User** — Who are they? Details that set them apart (context, habits, constraints). (2) **Job to be done** — What outcome are they trying to reach? (3) **Solution** — What to build; evaluate by business value and user impact.

**Example (JTBD):** Sonic milkshakes sold heavily before noon. The job wasn’t "a snack"—it was "a snack that lasts the morning commute without making a mess." A banana was gone in a minute; a bagel made a mess. The milkshake was "hired" for that job.

**Example (JTBD):** For an 11-year-old who plays a lot, a video game’s job might be "interactive entertainment that connects me with friends, gives me challenges, and helps me express myself"—not just "fun."

---

### Observation + inquiry

**Rule:** Observe yourself (when delighted or annoyed), others (what they gush or complain about), and the world (reviews, differentiators). Then ask *why*—don’t take surface requests at face value.

**Example:** Users asked Facebook for a "dislike" button. The team didn’t ship it because "dislike" is ambiguous: dislike the team? The sentiment? The person? They shipped Reactions (love, anger, sadness, etc.) so people had expressive options without increasing negativity or misunderstanding. Data from early markets helped pare down to the five most distinct, popular reactions.

---

### Good vs great product process

**Rule:** Great processes: (1) Produce new, novel features at the edge of innovation; (2) Continuously improve how they solve core needs; (3) Prioritize outcomes over output. Think at each step: Vision → Strategy → Discovery → Specification → Test → Roll-Out, with questions per step (e.g. Vision: "Who are the user groups that matter?" Spec: "What tradeoffs did the feature make?").

Use these questions to sharpen ideas: not just "what should we build?" but "what problem do we solve?", "how do people’s problems differ?", "what would we measure?", "how would we roll this out to pressure-test?"

---

### Product = design + technology + business

**Rule:** Product thinking integrates design thinking with **technology thinking** (can we build it? scale? effort?) and **business thinking** (profits, metrics, fit). When brainstorming, briefly sanity-check ideas against feasibility and value in the convergent phase—not to kill ideas in the divergent phase.

---

### First principles

**Rule:** Break the problem to basic truths (Five Whys, Socratic questioning: "What do you mean by…?", "What could we assume instead?", "What would be an alternative?"), then rebuild a solution from those truths.

**Example:** Airbnb didn’t copy hotels. First principles: people need a place to stay when traveling; not everyone has a spare room to offer; people value unique experiences. That led to a platform connecting travelers with hosts and unique stays, not a hotel clone.

---

### Outcome over output

**Rule:** Measure success by user and business outcomes, not features shipped. A North Star Metric is a single metric that captures the value users get from the product.

**Example:** Instead of "total free trial accounts," a product might use "trial accounts with more than 3 users active in week 1"—an outcome that signals real value and future revenue, not just signups.

---

### User story framing

**Rule:** "As a [type of user], I want [goal/capability], so that [reason/benefit]." Keeps who, what, and why in one line.

**Example:** "As a small business owner, I want to collect emails automatically, so each customer gets my marketing material."

Use when describing an idea or a feature to keep the user and benefit explicit.

---

### JTBD forces

**Rule:** Four forces influence switching: **Push** (dissatisfaction with current situation), **Pull** (attraction of the new solution), **Anxiety** (fears about the new), **Habit** (inertia of current). A switch happens when Push + Pull outweigh Anxiety + Habit.

**Example:** Mid-afternoon energy slump. Push = important meeting with senior management; Pull = alertness. Habit = drinking coffee. If the coffee line is too long (situational push), the person might try 5-Hour Energy—unless Anxiety (taste, availability, "weird") blocks the switch. When brainstorming adoption or retention, map these four forces to see what to strengthen or weaken.

---

## UI: how to approach user interfaces

### Mental models

**Rule:** Users have beliefs about how the system works (from past experience). Match the UI to their mental model; don’t force them to learn the system’s model. Follow platform and industry conventions (Jakob’s Law: people spend more time on other products than yours).

**Example (Norman door):** If a door says "push" but you have to pull, the design failed—the affordance and label didn’t match the user’s expectation. Good design makes the right action obvious.

---

### Design for the edges

**Rule:** "Solve for one, extend to many." Design for people at the margins (disability, temporary limitation, age); solutions often improve the experience for everyone.

**Example:** A bed with integrated armrests designed for accessibility also helps anyone recovering from surgery or with aches. In a usability study, a single red dot indicating an error caused a neurodivergent user to abandon the task; when that friction was fixed, the flow became calmer and clearer for all users.

---

### Design for failure (beyond the happy path)

**Rule:** Five layers: (1) **Happy path** — core flow the product exists to provide. (2) **Edge cases** — less common needs built into the design. (3) **Customer support** — handles what design can’t. (4) **Engineering** — handles what support can’t. (5) **Oblivion** — what falls through (minimize). Error messages: plain language + precise problem + constructive next step that gives the user agency.

**Example:** Instead of "Your account must be authorized," use "You must confirm your email before this action. Click here to resend confirmation to me@example.com." The second tells the user what went wrong and what to do next.

---

### 10 usability heuristics (Nielsen)

**Rule:** Use as a quick UI checklist when evaluating or generating interface ideas.

| # | Heuristic | One line | Example |
|---|-----------|----------|---------|
| 1 | Visibility of system status | Keep users informed | Progress bar, "You are here" on a map |
| 2 | Match system and real world | User’s language and conventions | Stovetop controls match burner layout |
| 3 | User control and freedom | Emergency exit, undo | Cancel button, Undo |
| 4 | Consistency and standards | Platform/industry conventions | Hotel check-in at front |
| 5 | Error prevention | Prevent before they happen | Guardrails, good defaults |
| 6 | Recognition over recall | Visible options, not memory | "Is Lisbon the capital of Portugal?" vs "What is the capital?" |
| 7 | Flexibility and efficiency | Shortcuts for experts | Keyboard shortcuts, personalization |
| 8 | Aesthetic and minimalist design | No irrelevant info | Ornate teapot that’s hard to use = bad |
| 9 | Help recognize, diagnose, recover from errors | Plain language + solution | "Wrong way" sign with what to do |
| 10 | Help and documentation | Easy to search, concrete steps, in context | Kiosk at airport right where needed |

---

### Empathy map

**Rule:** Four quadrants to ground ideas in a specific user: **Says** (quotes), **Thinks** (unvoiced concerns), **Does** (actions), **Feels** (emotions). Use when refining an idea or checking if it fits a persona.

**Example (food delivery app):** Says "I want more healthy options"; Thinks "Am I doing this wrong?"; Does "Compares prices across apps"; Feels "Frustrated by limited choices." This shifts the team from generic "users want healthy food" to a concrete picture for design and copy.
