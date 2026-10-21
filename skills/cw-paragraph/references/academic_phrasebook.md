# Academic Phrasebank — Reference

A structural meta-guide for using the Manchester Academic Phrasebank (John Morley, University of Manchester) as a Pass 2 resource. **The phrasebook itself remains the user's personal copy** — this file does not reproduce its phrase entries. Instead, it catalogs the rhetorical functions the phrasebook covers and gives decision rules for when to draw on those functions during editing.

Load this file during Pass 2 whenever scientific or academic mode is active. Skip otherwise.

---

## The override rule (read first)

When humanizer constraints (`humanizer.md`) conflict with phrasebook conventions, **humanizer wins**. The phrasebook codifies what academic readers expect; the humanizer codifies what reads as AI-generated. Many high-frequency phrasebook entries (especially in sections like *Introducing Work*, *Discussing Findings*, *Being Cautious*) overlap heavily with AI-vocabulary tells because LLMs were trained on academic prose that uses them.

How the override works in practice:

1. Pass 2 identifies a place where a phrasebook function would help (e.g., signaling a transition, hedging a claim, naming a contrast).
2. The skill picks the plainest, shortest, most concrete instantiation of that function.
3. The skill checks the candidate against humanizer patterns 1, 3, 4, 7, 8, 9, 14, 23, 27.
4. If the candidate triggers a humanizer pattern, the skill falls back to a plainer alternative or restructures without the phrasebook phrase.

Default bias: shorter and more direct beats longer and more formal, even in academic prose. The phrasebook offers a menu; the humanizer removes the dishes that read as AI.

---

## Phrasebook section taxonomy

The phrasebook organizes phrases under 28 functional categories in four groups. Use this taxonomy to locate the right function when editing.

### Major sections (research-paper-specific)

These cover the canonical research-paper structure. Most relevant when editing introductions, methods, results, discussion, and conclusion paragraphs.

1. **Introducing Work** — establishing the territory, identifying a niche, occupying the niche (Swales' CARS model). Subcategories: establishing importance of topic, indicating gaps, stating aims, outlining structure, defining terms, giving background.
2. **Reviewing the Literature** — general comments on the field, referring to previous research, summarizing source material, identifying limitations of previous work.
3. **Describing Methods** — describing materials, samples, procedures, instruments, analytical methods, ethical considerations, justifying choice of method.
4. **Reporting Results** — referring to data, presenting numerical/qualitative findings, comparing results, identifying patterns or trends.
5. **Discussing Findings** — restating main findings, explaining their significance, comparing with previous research, explaining unexpected results, acknowledging limitations.
6. **Writing Conclusions** — restating aims, summarizing main findings, suggesting implications, recommending further research.

### General functions (cross-cutting rhetorical moves)

These appear throughout academic writing regardless of paper section.

7. **Being Cautious** — hedging claims, qualifying assertions, expressing tentative interpretation. *(High humanizer overlap: see warning below.)*
8. **Being Critical** — evaluating other work, identifying weaknesses in arguments, expressing disagreement.
9. **Classifying and Listing** — grouping items by category, presenting taxonomies, enumerating types.
10. **Comparing and Contrasting** — naming similarities, drawing contrasts, identifying differences in degree or kind.
11. **Defining Terms** — formal definitions, informal definitions, technical definitions, narrowing scope.
12. **Describing Trends** — increase/decrease, magnitude, rate of change over time.
13. **Describing Quantities** — proportions, fractions, statistical relationships.
14. **Explaining Causality** — naming cause, effect, mechanism, contributing factors.
15. **Giving Examples as Support** — illustrative examples, representative cases, supporting evidence.
16. **Signalling Transition** — moving between ideas, sections, or phases of an argument. *(High humanizer overlap.)*
17. **Indicating Shared Knowledge** — referring to commonly accepted ideas in the field.
18. **Writing about the Past** — historical context, prior events, narrative chronology.
19. **Writing Abstracts** — condensed summaries with all major moves represented.
20. **Writing Acknowledgements** — gratitude conventions.

### Notes on academic writing (style guidance)

Conceptual guidance rather than phrase lists. The first of these — Academic Style — is summarized below because the principles inform Pass 2 and Pass 3 behavior directly.

21. **Academic Style** — seven principles (see below).
22. **Style in Presentations** — not usually relevant to paragraph editing.
23. **British and US Spelling** — preserve whichever the source uses.
24. **Punctuation** — basic conventions.
25. **Using Articles** — *a*, *an*, *the* in academic contexts.
26. **Sentence Structure** — common sentence-level problems.
27. **Paragraph Structure** — topic sentences, supporting sentences, transitions (overlaps directly with Pass 1).
28. **Tips on the Writing Process** — process advice.

### Useful lists

Reference word lists.

29. **Connecting Words** — coordinators, subordinators, transition adverbs.
30. **Commonly Confused Words** — *affect/effect*, *imply/infer*, etc.
31. **Commonly Used Verbs** — reporting verbs (*argues, suggests, demonstrates*), analytical verbs (*examines, considers, posits*).

---

## The seven principles of academic style

Summarized from the phrasebook's "Note on Academic Style" section. These inform what Pass 2 should preserve when editing academic prose.

1. **Evidence-based.** Claims are supported by attribution to other work. Preserve attribution phrases and citation patterns; do not let Pass 3 cut them as "vague attributions" if specific sources are present.

2. **Classical-origin vocabulary.** Academic English favors Greek and Latin-derived words over Anglo-Saxon synonyms (*considerable* over *a lot of*, *insufficient* over *not enough*, *eradicate* over *get rid of*). When editing academic prose, do not "simplify" technical vocabulary unless the original was inflated for its own sake.

3. **Cautious.** Hedging is genuine, not decorative. Statements like *some studies suggest* or *appears to* reflect epistemic care, not AI hedging. Pass 3 should preserve hedging that maps to real uncertainty in the evidence.

4. **Impersonal.** Academic writing typically avoids first- and second-person pronouns. Exceptions: some humanities disciplines accept first person; lab-science papers using *we* for collaborative work. Pass 3's "Add Voice" section stays off by default in academic mode.

5. **No contractions.** *Cannot*, not *can't*. *Does not*, not *doesn't*.

6. **Nominalization.** Verbs are often turned into noun phrases (*the opening of the railway* rather than *the railway opened*). This is conventional but can be overused; Pass 1 should flag noun-phrase pile-ups that bury action.

7. **Avoid rhetorical questions** except for stating research questions explicitly. Pass 2 should restrict Pattern 19A (short questions) in academic mode.

---

## When Pass 2 should consult the phrasebook

The skill should reach for phrasebook functions selectively, not as a default. Specific triggers:

- **Pass 1 identifies a missing or weak transition** between sentences or between paragraph sections. → Look at section 16 (Signalling Transition) for the function, then choose the plainest connector.
- **Pass 1 identifies a topic sentence that names a topic but lacks a controlling idea.** → Look at section 1 (Introducing Work) for ways to state aims or claims, then phrase plainly.
- **A claim is presented as certain when the evidence supports only an association.** → Look at section 7 (Being Cautious) for hedging conventions, then choose minimal hedging that fits the evidence.
- **A causal claim needs explicit signaling** that the evidence is causal, not correlational. → Look at section 14 (Explaining Causality) for vocabulary that distinguishes mechanism from correlation.
- **A comparison or contrast is implied but not named.** → Look at section 10 (Comparing and Contrasting).
- **The paragraph has weak attribution to prior work** in a context that requires it. → Look at section 2 (Reviewing the Literature).

When Pass 2 reaches for a phrasebook function, it consults the user's PDF copy or its memory of the phrasebook structure. It does not insert phrases unless the function is genuinely missing in the original. Adding phrasebook phrases for decorative effect produces AI-sounding prose.

---

## Sections with high humanizer overlap (use with extra caution)

These sections of the phrasebook are most likely to produce phrases that the humanizer will override. The skill should still use them when the function is missing, but should pick the shortest, plainest entries and check against humanizer patterns afterward.

**Being Cautious (section 7).** Conflicts with humanizer Pattern 24 (excessive hedging). Rule: keep one hedge per claim, not stacked hedges (*it could potentially possibly be argued that...*). Hedging matched to real uncertainty stays; decorative hedging gets cut.

**Signalling Transition (section 16).** Conflicts with humanizer Pattern 28 (signposting) and Pattern 7 (AI vocabulary — *moreover, furthermore, additionally, in light of*). Rule: prefer no transition word when sequence is obvious. When a transition is needed, prefer plain coordinators (*but, and, so*) or specific connectives (*because, after, when*) over heavy transition adverbs.

**Introducing Work (section 1).** Conflicts with humanizer Pattern 1 (undue emphasis on significance) and Pattern 23 (filler phrases like *it is worth noting that, it is important to consider*). Rule: state the topic and claim directly; skip preamble.

**Discussing Findings (section 5).** Conflicts with humanizer Pattern 25 (generic positive conclusions). Rule: state specific implications, not generic significance claims.

**Connecting Words (section 29).** Use the simple end of the list (*and, but, so, because*); the heavy end (*moreover, furthermore, consequently, in addition*) often triggers Pattern 7.

---

## Sections that rarely conflict with the humanizer

These sections of the phrasebook are mostly safe — the functions are concrete and the phrases tend to be technical rather than decorative.

- **Describing Methods (section 3)** — procedural language is genre-specific and earns its place.
- **Reporting Results (section 4)** — most phrasing names actual data.
- **Defining Terms (section 11)** — definitional phrasing is structurally necessary.
- **Describing Trends and Quantities (sections 12, 13)** — quantitative language is precise.
- **Explaining Causality (section 14)** — when a real causal mechanism is being named, the vocabulary earns its place. Watch only for *plays a crucial role in* (Pattern 1 humanizer flag).

---

## How the phrasebook reference is used in practice

In Pass 2, when the skill identifies a place where a phrasebook function would help:

1. Identify the function (e.g., "signal transition," "hedge claim," "name causal mechanism").
2. Pick the plainest instantiation of that function — typically a single conjunction, verb, or short phrase.
3. Check the candidate against humanizer patterns. If it triggers a pattern, fall back to a plainer alternative or restructure without the phrase.
4. Document the choice in the Pass 2 section of the analysis file (which function, which instantiation, why).

The user's PDF copy of the phrasebook remains the canonical source for specific phrase examples. This reference catalogs the menu; the user's copy contains the entrées.

---

## Reference

Morley, J. (2021). *Academic Phrasebank: A compendium of commonly used phrasal elements in academic English* (enhanced PDF edition). University of Manchester. http://www.phrasebankresearch.net

The phrasebook draws on John Swales' genre analysis framework (1981, 1990), particularly the CARS (Create A Research Space) model for research-article introductions. The skill uses this same framework when analyzing the structure of academic paragraphs.
