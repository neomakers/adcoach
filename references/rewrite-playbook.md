# Rewrite Playbook

## Default workflow

1. Diagnose the original copy.
   - Identify the audience, channel, offer, promised outcome, desired action, and the weakest part of the sentence.
   - Name the weakness plainly: too broad, too abstract, no reader relevance, no proof, no urgency, flat rhythm, no curiosity, no story, or no concrete benefit.

2. Choose techniques.
   - Read `technique-families.md` when the copy problem is broad or the channel is unclear.
   - Read `technique-index.md` when the user asks for specific angles or multiple versions.
   - Pick 1-3 techniques per rewrite set. For one short sentence, prefer one dominant technique.

3. Rewrite in passes.
   - Pass 1: faithful conversion version, preserving the original claim.
   - Pass 2: stronger hook version, increasing curiosity, specificity, urgency, or emotional force.
   - Pass 3: story/sensory/social-proof version when the offer has enough context.
   - If the user asks for N versions, produce exactly N versions.

4. Coach the result.
   - Explain the selected techniques by number and name.
   - State what changed from the original: audience, specificity, proof, rhythm, stakes, curiosity, metaphor, authority, timeliness, or story.
   - Score each version 0-3:
     - 0: only wording changed.
     - 1: smoother but still generic.
     - 2: clear technique and stronger reader reaction.
     - 3: strong technique, clear audience, concrete trigger, and action pressure.

5. Give the next drill.
   - Provide one concise exercise that trains the weakest point in the user's original copy.

## Output format

For normal rewrite tasks, use:

```markdown
## 原句诊断
- 受众：...
- 问题：...
- 目标动作：...

## 选用技巧
- 技巧NN｜名称：为什么适合

## 改写版本
1. ...（评分：/3）
2. ...（评分：/3）
3. ...（评分：/3）

## 严格教练点评
...

## 下一轮训练题
...
```

For quick tasks, compress the same structure but keep diagnosis, techniques, versions, and score.

## Guardrails

- Do not invent product facts, data, awards, authority, scarcity, deadlines, user testimonials, or guarantees.
- If a stronger version needs proof the user did not provide, mark it as a proof slot such as `{真实数据}` or ask for the missing fact.
- Preserve legal and safety constraints for regulated topics. Avoid medical, financial, or absolute claims unless the user provides compliant proof.
- Do not over-stack techniques. One dominant technique beats five mixed signals.
- Keep the user's language and market context unless the user asks for another language or platform style.
