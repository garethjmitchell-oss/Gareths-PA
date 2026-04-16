# Tool 8: Chef

## Purpose
Suggests recipes based on available ingredients, dietary needs, or cravings.

## Why It Matters for ADHD
Meal planning combines every ADHD weak spot: decision-making, sequencing, time estimation, and sustained attention. "What should I eat?" becomes paralysing. The Chef removes the decision fatigue by working with what you have and giving step-by-step instructions where each step is a single action.

## Triggers
`8`, `chef`, `recipe`, `cook`, `ingredients`, `what can I make`

## Input
Available ingredients, dietary restrictions, a craving, or some combination.

## Output Format

**Phase 1 — Suggestions:**
- 2-3 recipe suggestions
- Each has: name + one-line description + time estimate
- User picks one

**Phase 2 — Instructions (after user picks):**
- Numbered steps
- Each step is a **single action** — never compound
  - Wrong: "Chop the onions and mince the garlic while heating oil in a pan"
  - Right: Step 1: Chop the onions. Step 2: Mince the garlic. Step 3: Heat oil in a pan over medium heat.
- Timer reminders inline: "Set a timer for 10 min"
- Flag steps where user must stay present: "Stay by the stove for this one"

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | Just recipe names to pick from, minimal instructions |
| Default | Names + descriptions + times, then steps when picked |
| More detail | Full recipes with exact measurements, tips, and substitution ideas |

## ADHD Adaptations
- Single-action steps prevent the "wait, what was I supposed to do at the same time?" confusion
- Timer reminders prevent "I forgot it was in the oven" disasters
- "Stay by the stove" flags prevent wandering off mid-cook
- Suggestions are limited to 2-3 to avoid decision paralysis

## Example

**Input:** `8 I have chicken, rice, broccoli, soy sauce, and garlic`

**Output:**

Here's what you can make:

1. **Quick chicken stir-fry** — saucy, savoury, done in 20 min
2. **Chicken and rice bowl** — simple comfort food, 30 min
3. **Garlic chicken with steamed broccoli** — clean and easy, 25 min

*Pick a number and I'll walk you through it.*

---

**User picks 1:**

### Quick Chicken Stir-Fry (20 min)

- [ ] 1. **Cut the chicken** into bite-sized pieces
- [ ] 2. **Mince the garlic** (2-3 cloves)
- [ ] 3. **Chop the broccoli** into small florets
- [ ] 4. **Heat oil** in a pan or wok over high heat
- [ ] 5. **Cook the chicken** — spread it out, don't move it for 3 min per side
- [ ] 6. **Add the garlic** — stir for 30 seconds (stay by the stove, it burns fast)
- [ ] 7. **Add the broccoli** — stir-fry for 3-4 min until bright green
- [ ] 8. **Pour in soy sauce** (2-3 tablespoons) and toss everything together
- [ ] 9. **Serve over rice**

*Want the rice instructions too?*

## Follow-up Line
*Pick a number and I'll walk you through it.* (suggestions phase)
*Want to cook something else?* (after recipe is given)
