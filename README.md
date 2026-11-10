# Mila Library

Free packs for [Mila Agent](https://github.com/shakhruz/mila-agent) — small sets of skills Mila offers one at a time and installs only when her owner presses «Install».

**English** · [Русский](#русский) · [Oʻzbekcha](#oʻzbekcha)

## Packs

| Pack | For whom | Category |
|---|---|---|
| `biznes-profil` — Business profile | You have a business and want Mila to know it as well as you do | business |
| `proforientatsiya` — Career direction | You are not sure what to do, or are thinking of changing jobs | getting acquainted |
| `audit-vnimaniya` — Attention audit | Your attention goes everywhere except your main project | warm-up |
| `sovet-modelej` — Council of models | You face a decision and want four different views on it — all four voiced by Mila herself, no other models | warm-up |

Every pack is text only: skills, a three-step tutorial and a sample result with an invented person. Nothing in a pack is executed on install.

## How Mila uses it

You don't install anything from here by hand. Ask Mila «what packs are there?» — she shows the catalog; after you get acquainted she may offer one pack that fits what you told her. She installs it only after you press the button; «Not now» — she doesn't offer again.

## How trust works

1. Each Mila Agent release carries the sha256 of `library.json` at the library tag made for that release (`core-vX.Y.Z`).
2. `library.json` carries the sha256 of every archive in `dist/`.
3. Each archive's `manifest.json` carries the sha256 of every file.

An index or an archive that does not match is refused. A change here reaches Milas only with the next core release.

## Layout

```
packs/<id>/        pack.json, README.md, TUTORIAL.md, SAMPLE.md, <skill>/SKILL.md
dist/              built archives and their manifests
library.json       the index (built, not edited by hand)
```

Build (from a Mila Agent checkout): `python3 tools/build_library.py <this checkout>` — prints the sha256 for the core's `skills/library/library.lock`.

A pack's `for_whom` and title are one plain line: no links, no commands, no imperatives — the build stops otherwise.

## Credits and licence

Apache-2.0 — see [LICENSE](LICENSE). The packs `audit-vnimaniya` and `sovet-modelej` are based on [Attention OS](https://github.com/amonter/Attention-OS) by Adrian Avendano (MIT); each carries the MIT notice in its `LICENSE.md`. See [NOTICE](NOTICE).

---

## Русский

Бесплатные паки для Mila Agent — небольшие наборы навыков. Мила предлагает их по одному и ставит только по нажатию хозяина.

- **Бизнес-профиль** — если у вас есть дело и вы хотите, чтобы Мила знала его так же хорошо, как вы.
- **Профориентация** — если вы не знаете, чем заняться, или думаете сменить работу.
- **Аудит внимания** — если внимание расходится на всё, кроме главного дела.
- **Совет моделей** — если стоите перед решением и хотите четыре разных взгляда; все четыре ведёт сама Мила, без других моделей.

Руками отсюда ничего ставить не нужно: спросите Милу «какие есть паки?». В паке только тексты — при установке ничего не исполняется. Каждый выпуск Mila Agent несёт сумму индекса библиотеки, индекс — суммы архивов, архив — суммы файлов; несовпадение — отказ.

Лицензия Apache-2.0. «Аудит внимания» и «Совет моделей» написаны по мотивам Attention OS (Adrian Avendano, MIT).

## Oʻzbekcha

Mila Agent uchun bepul paketlar — kichik koʻnikmalar toʻplami. Mila ularni bittadan taklif qiladi va faqat egasi tugmani bosgandan keyin oʻrnatadi.

- **Biznes profili** — ishingiz boʻlsa va Mila uni siz kabi yaxshi bilishini xohlasangiz.
- **Kasb tanlash** — nima bilan shugʻullanishni bilmasangiz yoki ishni almashtirmoqchi boʻlsangiz.
- **Diqqat auditi** — diqqatingiz asosiy ishingizdan boshqa hamma narsaga ketayotgan boʻlsa.
- **Modellar kengashi** — qaror oldida tursangiz va toʻrt xil nazar kerak boʻlsa; toʻrttasini ham Milaning oʻzi yuritadi, boshqa modellarsiz.

Bu yerdan qoʻlda hech narsa oʻrnatish shart emas: Miladan «qanday paketlar bor?» deb soʻrang. Paketda faqat matn bor — oʻrnatishda hech narsa ishga tushmaydi.

Litsenziya: Apache-2.0. «Diqqat auditi» va «Modellar kengashi» Attention OS (Adrian Avendano, MIT) asosida yozilgan.
