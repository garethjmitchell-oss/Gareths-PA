# Tool 4: Estimator

## Purpose
Provides realistic time estimates for tasks, specifically adjusted for ADHD brains.

## Why It Matters for ADHD
Time blindness is one of the defining features of ADHD. People with ADHD consistently underestimate how long things take, forget to account for transitions, and don't plan for the "getting started" friction. This tool gives honest, padded estimates that actually match reality.

## Triggers
`4`, `estimate`, `how long`, `time`

## Input
A task or activity description.

## Output Format
- **Focused time:** the realistic range if fully focused (e.g., "30-45 min")
- **With breaks:** adds ~10 min per 30 min of focused work
- **Context-switching cost:** "Add 15 min if you're switching from something else"
- **ADHD-adjusted note:** accounts for getting-started friction, transition time, and hyperfocus risk
- **Energy level:** low / medium / high cognitive load
- **Best time to do it:** "Peak focus task — tackle it in the morning if possible" or "Low-stakes — good for an afternoon slump"
- **Relatable comparison:** "About the length of a TV episode" or "Roughly two songs"

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | Just the time range, one line |
| Default | Time range + with-breaks + energy level + comparison |
| More detail | Breakdown by sub-activity with individual time estimates |

## ADHD Adaptations
- Always give TWO times: focused and with-breaks (ADHD users will take breaks whether planned or not)
- Round to friendly numbers: "about 45 min" not "43 minutes"
- Flag hyperfocus risk: if a task is the kind that can swallow hours (research, organising, creative work), warn about it
- Use relatable comparisons instead of abstract time (a movie, a commute, a lunch break)
- Account for "startup cost" — the 5-15 minutes it takes an ADHD brain to actually begin

## Example

**Input:** `4 clean the bathroom`

**Output:**

- **Focused:** 20-30 min
- **With breaks:** 35-45 min
- **Energy:** Medium cognitive load
- **About the length of** a TV sitcom episode

**Note:** Add 5-10 min startup time if you're dreading it. Put on music or a podcast to make it easier to begin.

*Want me to break this into steps?*

## Follow-up Line
*Want me to break this into steps?*
