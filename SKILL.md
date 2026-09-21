---
name: "humanizer"
description: "Run before calling any AI-drafted or AI-edited copy finished: newsletters, emails, blog posts, client and exec documents. Strips AI writing tells, checks house style and voice, reports what it caught."
---

# Humanizer

Run this on any draft before saying it is finished. Every pattern, every time. Spot-checking is how bad copy gets through.

The patterns below come from Wikipedia's "Signs of AI writing", maintained by WikiProject AI Cleanup, drawn from thousands of observed instances. They are what makes text read as machine-written even when nothing in it is factually wrong.

Work through the passes in order. Do not skip pass 2. A draft can be technically clean and still fail, because voiceless writing is as obvious as slop.

## Pass 0: house style

Before anything else, find the style rules that apply. Check, in this order: a style guide or voice profile in the project, the author's global instructions or saved writing preferences, and a recent finished piece by the same author to calibrate against. If none exists, say so and use the defaults below.

Common house rules worth confirming rather than assuming:

- Dashes. Some teams ban em dashes outright. Check before rewriting punctuation either way.
- Straight versus curly quotes and apostrophes.
- Numerals versus spelled-out numbers.
- Sentence case or Title Case for headings.
- Emoji policy, and whether it differs by placement (subject lines and sign-offs versus body prose).
- Whether vendor and product names can be named, or the piece stays tool-agnostic.
- Oxford comma, date format, and how the company and its products are written.

Verify the mechanical ones with a search rather than by eye. Dashes, curly quotes and emoji hide well in long documents and arrive invisibly through copy-paste.

## Pass 1: AI writing tells

### Content

1. Inflated significance. "marks a pivotal moment", "reflects a broader shift", "stands as a testament", "setting the stage for", "evolving landscape", "indelible mark", "deeply rooted". Cut the sentence or replace it with the concrete fact.
2. Notability padding. Listing outlets, follower counts or "independent coverage" instead of saying what someone actually did or argued.
3. Superficial -ing tails. "highlighting the...", "ensuring that...", "reflecting the...", "showcasing...", "contributing to...", "cultivating...". These bolt fake depth onto a finished sentence. Delete the tail.
4. Promotional language. "boasts", "vibrant", "rich" (figurative), "profound", "nestled", "in the heart of", "renowned", "breathtaking", "stunning", "must-visit", "commitment to".
5. Vague attribution. "experts say", "industry reports suggest", "observers have noted", "some critics argue", "several sources". Name the source or cut the claim.
6. Formulaic challenges sections. "Despite these challenges...", "Challenges and future prospects", "Future outlook". Replace with the specific thing that went wrong and what was done about it.

### Language

7. AI vocabulary. however, additionally, furthermore, moreover, delve, dive into, unpack, tapestry, testament, landscape (abstract), showcase, underscore, seamless, robust, leverage (verb), crucial, vibrant, foster, boasts, align with, enhance, garner, interplay, intricate, key (adjective), pivotal, valuable, enduring. These cluster: finding one usually means finding several.
8. Copula avoidance. "serves as", "stands as", "represents", "features", "offers". Use is, are, has.
9. Negative parallelism. "it's not just X, it's Y", "not only... but also", "it's not merely a tool, it's a philosophy". Say the positive thing once.
10. Forced rule of three. Groups of three that exist to sound comprehensive. Cut to two, or to the one that carries the weight.
11. Elegant variation. Cycling synonyms for the same subject across consecutive sentences (the protagonist, the main character, the central figure, the hero). Repeat the noun.
12. False ranges. "from X to Y" where X and Y are not on a real scale.

### Style

13. Em dash overuse. Whatever the house rule, a draft with more than one or two is a tell. Replace with a period, comma, colon or parentheses.
14. Mechanical boldface. Bold at most one key line per section, and only where it earns it.
15. Bolded-header bullet lists. "**Performance:** Performance has been improved...". Turn them into prose or plain bullets.
16. Title Case headings, where house style says sentence case.
17. Decorative emoji on headings and bullets.
18. Curly quotes and apostrophes, where house style says straight.

### Communication artifacts

19. Chatbot residue. "I hope this helps", "Certainly!", "Of course!", "You're absolutely right", "Would you like me to...", "Here is a...".
20. Knowledge-cutoff disclaimers. "as of my last update", "while specific details are limited", "based on available information".
21. Sycophantic tone. "Great question", "That's an excellent point".
22. Filler. "in order to" becomes "to". "due to the fact that" becomes "because". "at this point in time" becomes "now". "has the ability to" becomes "can". "it is important to note that" gets cut.
23. Stacked hedges. arguably, perhaps, potentially, might possibly. Pick one, or commit to the claim.
24. Generic upbeat endings. "exciting times ahead", "a step in the right direction", "the future looks bright".

## Pass 2: does it have a pulse

Removing tells is half the job. Sterile writing is just as obvious.

Signs of soulless copy: every sentence the same length, no opinions, no acknowledgement of uncertainty or trade-offs, no first person where it would fit, no edge. It reads like a press release.

Check for:

- A real position. At least one claim the author would defend and could be wrong about.
- Varied rhythm. Short punchy sentences next to longer ones. If every sentence runs the same length, it is dead.
- Specifics over abstractions. Named sources, real numbers, concrete examples.
- Honest limits. Real people have mixed feelings. "This is impressive and also a bit unsettling" beats "This is impressive."
- Structure that fits the piece. If a story has been flattened into a numbered walkthrough, rewrite it as a narrative.

Match the author, not a generic house voice. If a recent finished piece by them exists, read it before rewriting. Most voice misses come from editing without a reference.

## Pass 3: readability

- Break up walls of text. Short paragraphs.
- At most one bolded key line per section.
- A pull-quote where it earns one.
- Read it aloud. If it sounds like a press release or a tutorial when it should not, it is not done.

## Pass 4: report back

Do not say a draft is clean. Say which passes ran and what each one caught, including the passes that caught nothing, so the author can tell a pass that ran from a pass that was claimed.

A useful report looks like:

- House style: checked against the team style guide. 3 em dashes and 1 curly apostrophe replaced.
- AI tells: caught pattern 3 (two -ing tails) and pattern 9 (one negative parallelism). Nothing else.
- Voice: calibrated against last month's piece. The opening was too neutral, rewritten in the author's own framing.
- Readability: split 2 dense paragraphs, added 1 pull-quote.

## Adapting this for a team

This works out of the box. It gets much better with a voice profile alongside it: a short file naming the author's or team's hard rules, signature phrases, banned words, and one or two finished pieces to calibrate against. Keep that separate from this skill, so style can change without touching the patterns and one humanizer serves everyone.