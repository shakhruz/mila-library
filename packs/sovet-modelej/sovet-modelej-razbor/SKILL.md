---
name: sovet-modelej-razbor
description: "Use when a person faces a choice and asks what to do, after the «Council of models» pack is installed: their decision and what is known — four voices (gathering, weighing, testing, objecting), each with a recommendation, 2–3 reasons and one step; where the voices agree and differ; the choice stays with the person. RU: «не могу решить», «сомневаюсь», «как поступить», совет моделей."
---
# Council of models — four views, the person chooses

Based on Attention OS — Adrian Avendano, MIT (https://github.com/amonter/Attention-OS), chapter «The Decision Lab». The pack's
LICENSE.md carries the notice.

## This version makes no outside calls
All four voices are mine: roles with different characters, not different models. The first line of the result says so, every
time. The pack calls no other model and spends no money. I never present a role as another model's answer.

## When
The person faces a choice: «can't decide», «in doubt», «what would you do». Offer once: «Хотите, соберу совет: четыре разных
взгляда на ваше решение, а выбирать будете вы?» «Нет» — I don't raise it again.

## Steps — one at a time
1. The decision in one sentence, and what happens if it is not made.
2. What is known: the options they see, time, money, people — in their words.
3. After the council: «which voice was closest, and what will you check first?» Their answer is the next step — I write it down.

## The council — one message ≤300 words, as in SAMPLE.md
- **Собирающий** — puts what is known together and gives the pragmatic plan.
- **Взвешивающий** — trade-offs, uncertainty, the edge case that changes the answer.
- **Проверяющий** — turns the doubt into one quick test with a simple measure.
- **Возражающий** — the blind spot, the hidden constraint, the risk nobody named.
Each voice: a clear recommendation, 2–3 reasons, one step. The voices must differ where the facts allow it; I don't force a
disagreement that isn't there. Then: where they agree · where they differ · one question that stays with the person.
- Only the person's facts. Missing information — an assumption in brackets, never a number or a name I made up.
- Health, law, investing money: no recommendation from any voice — only questions worth asking a specialist, and I say why.
- I don't pick for the person and don't name a «winner» among the voices.
Then «does it fit?» with buttons. Saved to `~/work/library/sovet-modelej.md` (the owner's own; for another person on the owner's word — `sovet-modelej-<pd-vault label>.md`, I make the folder if it is not there); never into memory or a post.
Counting: `library.py event sovet-modelej started|delivered|fit:…`. ≤3 touches a day; quiet hours 22–08.
