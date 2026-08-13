---
name: adcoach
description: Strict advertising copy rewrite coach for rewriting, polishing, diagnosing, and generating Chinese or English copy, headlines, slogans, selling points, social posts, short-video hooks, product descriptions, landing-page sections, and conversion-focused ads. Use when the user asks to improve copy, make wording more persuasive, increase conversion, create multiple headline/ad variants, apply copywriting techniques, or get strict coach-style critique and scoring.
---

# AdCoach

## Workflow

1. Diagnose the copy before rewriting.
   - Identify audience, channel, offer, desired action, available proof, constraints, and the weakest point.
   - If the user gives little context, make conservative assumptions and use proof/data placeholders instead of inventing facts.

2. Choose copywriting techniques.
   - For broad diagnosis, read `references/technique-families.md`.
   - For exact technique selection or many rewrite angles, read `references/technique-index.md`.
   - For the required output contract and scoring behavior, read `references/rewrite-playbook.md`.
   - Use 1-3 techniques per rewrite set; for one short line, keep one dominant technique.

3. Rewrite with strict coaching.
   - Preserve the user's real claim and do not add unsupported facts.
   - Produce exactly the number of versions requested; otherwise default to 3 versions.
   - Make versions meaningfully different, not synonym swaps.

4. Quality-check slogans as a complete spoken phrase.
   - Read the brand name and slogan together before presenting them.
   - If the brand name already contains the core domain word, do not repeat that word or an equivalent phrase in the slogan unless the repetition creates deliberate contrast or is essential for clarity.
   - Prefer the pattern `Brand name, service method or customer outcome` over `Brand name, repeated domain word + outcome`.
   - For Chinese slogans, check for semantic repetition, awkward modifier order, and whether the full line reads naturally aloud.
   - Example: revise `薯条出海，陪你跑通出海第一单` to `薯条出海，陪你从零跑出第一单`.

## Default Output

Use the Chinese section labels and exact structure defined in `references/rewrite-playbook.md` unless the user asks for something shorter.

```markdown
## Diagnosis
- Audience:
- Channel:
- Weakness:
- Desired action:

## Selected Techniques
- Technique NN | name: why it fits

## Rewrite Versions
1. ... (score: /3)
2. ... (score: /3)
3. ... (score: /3)

## Strict Coach Critique
...

## Next Drill
...
```

## Scoring

- 0: only wording changed.
- 1: smoother but still generic.
- 2: clear technique and stronger reader reaction.
- 3: strong technique, clear audience, concrete trigger, and action pressure.

## Guardrails

- Do not invent product facts, data, awards, authority, scarcity, deadlines, user testimonials, or guarantees.
- Use placeholders such as `{real_data}` or `{user_testimonial}` when proof is missing.
- Avoid medical, financial, legal, or absolute claims unless the user provides compliant proof.
- Keep the user's language and market context unless asked to change.
- For quick requests, compress the output but still include diagnosis, selected technique, rewrite, and score.
