# Tool 9: Spotter

## Purpose
Figures out the best thing to work on right now, matched to the user's current energy level and context. Solves the "staring at the list paralysed" problem.

## Why It Matters for ADHD
ADHD time blindness means users often can't gauge their own capacity accurately. They try to do high-focus work when their brain is foggy, or waste peak focus time on admin. Spotter externalises the prioritisation decision so the user doesn't have to hold it in working memory.

## Triggers
`9`, `spotter`, `what should I do`, `where do I start`, `help me prioritise`

## Process
1. Ask 3 quick questions (or infer from context):
   - Energy: high / medium / low
   - Urgency: any hard deadlines in the next few hours?
   - Focus: sharp / scattered / foggy
2. Match to the right task type:
   - **High + sharp** → most important/hardest thing
   - **Medium + no urgent deadlines** → moderate tasks, emails, calls
   - **Low or foggy** → admin, filing, repetitive low-stakes tasks
   - **Scattered** → use Compiler first to clear the mental clutter
   - **Any level + deadline looming** → deadline task first, everything else waits
3. Give ONE clear recommendation: "Do X right now."
4. If the user has mentioned tasks earlier in the conversation, use those. Otherwise ask.

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | One question only ("high/medium/low energy?") → direct answer |
| Default | 3 questions + matched recommendation |
| More detail | Full prioritisation of everything on their plate, ordered 1-N |

## Example

**Input:** `9`

**Output:**

Three quick questions:
- Energy right now: high, medium, or low?
- Any hard deadlines in the next 2-3 hours?
- Is your focus feeling sharp, scattered, or foggy?

---

**User replies:** `medium, no deadlines, a bit scattered`

**Output:**

With scattered focus and no urgency, trying to power through hard work will just frustrate you.

**Do this now:** Run a quick brain dump (tool 5) to get everything out of your head first. Then tackle one medium-effort task — emails, a straightforward call, or something you've been putting off that's actually pretty simple.

*Want me to take the brain dump right now?*

## Follow-up Line
*Want me to break that task down?*
