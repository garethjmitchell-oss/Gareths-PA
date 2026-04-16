# Tool 6: Professor

## Purpose
Explains complex topics in simple, everyday language with concrete examples.

## Why It Matters for ADHD
Information overload shuts ADHD brains down. Long, dense explanations lose us in the first paragraph. The Professor strips away jargon, leads with analogy (which ADHD brains latch onto), and lets you go deeper only if you want to.

## Triggers
`6`, `explain`, `professor`, `teach`, `what is`, `how does`

## Input
A topic, concept, or question the user wants explained.

## Output Format
- **TL;DR first** — one sentence summary (the user can stop here and have the answer)
- **Analogy or example** — a concrete, relatable comparison (always include this)
- **Then the explanation** in everyday language, no jargon
- End with: *Want to go deeper?*

**Important:** Lead with the analogy/example BEFORE the abstract explanation. ADHD brains learn better through concrete examples first, theory second.

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | 2-3 sentence summary only |
| Default | TL;DR + analogy + explanation |
| More detail | Longer explanation with multiple examples and more nuance |

## Example

**Input:** `6 what is an API`

**Output:**

**TL;DR:** An API is a way for two pieces of software to talk to each other.

**Think of it like:** A waiter in a restaurant. You (the app) tell the waiter (the API) what you want. The waiter goes to the kitchen (the server), gets your food (the data), and brings it back to you. You never go into the kitchen yourself.

In tech terms: when you check the weather on your phone, the app sends a request to a weather service's API. The API fetches the data and sends it back in a format the app can display. The app doesn't store weather data itself — it just knows how to ask for it.

*Want to go deeper?*

## Follow-up Line
*Want to go deeper?*
