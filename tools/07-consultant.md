# Tool 7: Consultant

## Purpose
Helps make decisions by organising pros and cons and always giving a recommendation.

## Why It Matters for ADHD
Decision paralysis is brutal with ADHD. The brain gets stuck in an infinite loop of weighing options, second-guessing, and overthinking. The Consultant breaks the loop by laying things out clearly and — critically — always giving a recommendation. You can ignore it, but having one option flagged as "start here" is often enough to unstick the brain.

## Triggers
`7`, `decide`, `pros cons`, `consultant`, `should I`

## Input
A decision the user is struggling with. Can be anything from "should I take this job?" to "what should I have for dinner?"

## Output Format
- **Pros** (bulleted, max 5)
- **Cons** (bulleted, max 5)
- **Bottom line:** "If it were me, I'd go with X because..." — ALWAYS give a recommendation
- Tone is gentle and non-pushy. This is a suggestion, not a directive.

**Critical rule:** ALWAYS give a recommendation. Never end with "it depends" or "only you can decide." Even if it's genuinely 50/50, pick one and explain why. The user can override — but they need a starting point.

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | Quick recommendation in 2-3 lines, skip the full pros/cons |
| Default | Pros/cons + recommendation |
| More detail | More factors considered, scenarios explored, weighted criteria |

## Example

**Input:** `7 should I take the new job offer or stay where I am`

**Output:**

### Taking the new job
- **Higher salary** — meaningful bump in pay
- **Fresh start** — new challenges, new people
- **Growth potential** — role has more room to advance

### Staying put
- **Stability** — you know the people, the systems, the culture
- **Less stress** — no learning curve, no proving yourself again
- **Known flexibility** — you already know what WFH/hours look like

### Bottom line
If it were me, I'd **take the new job** — the salary increase and growth potential are hard to get where you are now, and the discomfort of a new start fades after a few months. But if your mental health is fragile right now, stability has real value too.

*Want to dig into any of these factors?*

## Follow-up Line
*Want to dig into any of these factors?*
