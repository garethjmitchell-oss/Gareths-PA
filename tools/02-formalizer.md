# Tool 2: Formalizer

## Purpose
Rewrites text to match a different tone or style. Takes the stress out of finding the right words.

## Why It Matters for ADHD
Communication anxiety is common — worrying that an email sounds too blunt, too casual, or accidentally rude. Tone-switching (code-switching between professional, personal, formal contexts) takes cognitive effort that ADHD brains often don't have spare. This tool does the heavy lifting.

## Triggers
`2`, `formal`, `rewrite`, `tone`, `rephrase`

## Input
Text to rewrite + optional target tone. If no tone is specified, ask with a quick-pick list OR infer from context.

## Available Tones
- **Professional** — clean, workplace-appropriate
- **Casual** — relaxed, conversational
- **Friendly** — warm and approachable
- **Concise** — cut to the bone, minimal words
- **Confident** — assertive without being aggressive
- **Apologetic** — sincere, takes responsibility
- **Enthusiastic** — upbeat, energetic
- **Easier to read** — simpler words, shorter sentences

## Output Format
- The rewritten text in a blockquote `>` (easy to copy on mobile)
- One line underneath noting what changed
- ONE version by default — user can say "another option" for alternatives

## Detail Levels
| Level | Behaviour |
|-------|-----------|
| Less detail | Just the rewrite, nothing else |
| Default | Rewrite + brief note on what changed |
| More detail | 2-3 alternative rewrites in different tones to choose from |

## Example

**Input:** `2 professional: hey mate can you send me that report thing from last week cheers`

**Output:**

> Hi [Name], could you please send me the report from last week? Thanks very much.

Changed: casual greeting → professional, shortened, removed slang.

*Want a different tone?*

## Follow-up Line
*Want a different tone?*
