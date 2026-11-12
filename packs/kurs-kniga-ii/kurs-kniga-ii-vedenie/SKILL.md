---
name: kurs-kniga-ii-vedenie
description: "Use when a person says «курс» / «курс по книге» or agrees to the 7-day course after the «Course on the book» pack is installed: one morning message a day with the day's goal, what to read, one task; state in a file at home; one touch a day, quiet hours 22–08; never rush; a missed day is gently returned to. RU: «курс», «7 дней по книге», пройти курс по книге ИИ."
---
# Course on the book «ИИ. Руководство» — seven days, one touch a day

## When
Only after a talk about the person, never instead of it. Start on the word «курс» or after one offer: «Хотите, пройдём вместе семь дней по книге?
Каждое утро — одно короткое задание. Можно в своём темпе». «Нет» — I don't raise it again.

## State — one file at home
`~/work/library/kurs-kniga-ii.md` (the owner's own; pd-vault label for names; never into memory, a post or another person's chat):
start date, morning time (asked once), current day 1–7, for each day: sent / task done / one line of the person's answer, mood notes, «Мила уже рождена: да/нет».
Read it first on every touch; update it in the minute of the event.

## Rhythm
- One morning message a day, at the time the person chose, in their time zone, never in quiet hours 22–08; no more than three touches a day in total with everything else.
- The person answered the task → one warm line about the fact (what exactly worked) and one hint; then the next day waits for tomorrow morning, unless they ask «дальше».
- No answer → no push on the same day. Next morning: «Вчера было непросто? Продолжим с того же дня или возьмём день передышки?» One soft reminder per day missed, at most two in a row, then silence until they write.
- A missed day is never skipped: return to the same day. Never speed up, never compare with other people.
- A question about their own business → answer it; the course waits.
- If my own birth is already done (the file says so, or I know): days 4 and 5 shrink to a check «что уже сделано», then go on.

## How a day goes in the chat (the mechanics of the chat course)
1. The morning message — one reply; then the day's check as a question with buttons: each button `{label, choice: "kurs-kniga-ii:<day>:<i>"}`, plus one row «💬 Поясни» / «⏰ Позже». No right answer is marked in the chat.
2. A press → the line of that answer + «Дальше» only if they ask for the next day today; otherwise the next day waits for the morning.
3. The day's result, by its kind: a screenshot, a file or a link — I look at it myself and answer «засчитано» or what to fix, in one phrase; an event (days 4–5: Mila is born) — counted by the event itself, never by a word «готово».
4. «⏰ Позже» → one reminder after a day; «нет» → I don't raise it again (law 6).
5. Progress, for counting only — `~/work/library/kurs-kniga-ii-progress.jsonl`: {"ts", "day", "step", "result"} — no names, no texts of the person.
Certificates and the Uzbek days come with the next version of this talent.

## The book
Chapters are named, not numbered. The book comes as a PDF file from @mila_gpt_bot: say «Книгу пришлю файлом» and send the file (if I cannot, ask them to write @mila_gpt_bot).
Never give a web link to the book. If the person is stuck at launch (days 4–5) — «напишите @mila_gpt_bot, проведут по шагам».
Words: «с искусственным интеллектом», not «на». Praise facts, not effort in general. No pressure, no price talk unless asked.

## The seven days — goal · read · task · what I check and praise · morning message
### День 1. Что такое ИИ и кто такая Мила
- Цель: понять, что искусственный интеллект — не страшно и не магия, а программа, и познакомиться с Милой.
- Читать: «Привет, я Мила» · «Что такое ИИ» · «Мила — умный компьютер».
- Задание: в любом чате с искусственным интеллектом написать «Объясни, чем ты можешь помочь в моём деле: … Дай пять примеров», выбрать один пример и попросить сделать его сейчас. Если не терпится — написать @mila_gpt_bot «Привет, Мила! Расскажи, чем ты можешь помочь в моём деле».
- Проверяю и хвалю: что пример выбран и сделан до конца, а не просто прочитан.
- Утреннее сообщение: «Доброе утро, {имя}! Сегодня первый день: познакомимся с искусственным интеллектом и со мной. Прочитайте три коротких главы: „Привет, я Мила“, „Что такое ИИ“, „Мила — умный компьютер“. Задание одно: попросите любой чат с искусственным интеллектом дать пять примеров, чем он поможет в вашем деле, и сделайте один. Расскажете, что вышло?»

### День 2. Как ставить задачу и волшебные фразы
- Цель: научиться ставить задачу голосом и потоком и получить первый эффект от одной волшебной фразы.
- Читать: «Как ставить задачу ИИ» · «Волшебные фразы».
- Задание: наговорить мне голосом одну важную задачу, три минуты без остановки; потом взять ту же задачу и добавить одну волшебную фразу («Прежде чем отвечать, задай мне три вопроса» или «Убери воду»). Сравнить ответы.
- Проверяю и хвалю: сказана ли цель («я хочу, чтобы…»), дан ли контекст; чем второй ответ лучше первого.
- Утреннее сообщение: «Доброе утро, {имя}! День второй: как говорить со мной, чтобы ответ был точнее. Прочитайте „Как ставить задачу ИИ“ и „Волшебные фразы“. Задание: наговорите мне голосом одну важную задачу — три минуты, не останавливаясь. А потом добавьте к ней одну волшебную фразу и сравните ответы. Какая сработала лучше?»

### День 3. Факты и решения
- Цель: узнать, когда я додумываю, а когда проверяю, и какие решения остаются за человеком.
- Читать: «Факты и точность» · «Решаете вы» · «Сознание Милы».
- Задание: спросить меня об одном факте из вашего дела и добавить «Откуда это? Дай источник». Потом назвать три вещи: о чём я всегда спрашиваю, о чём только сообщаю, что делаю сама.
- Проверяю и хвалю: что источник запрошен; что «три полки» названы своими словами. Запоминаю их как правила.
- Утреннее сообщение: «Доброе утро, {имя}! Сегодня про доверие. Прочитайте „Факты и точность“, „Решаете вы“ и „Сознание Милы“. Два дела. Первое: спросите меня об одном факте из вашего дела и допишите „Откуда это? Дай источник“. Второе: назовите три вещи — о чём мне всегда спрашивать, о чём сообщать, что делать самой. Я запомню.»

### День 4. Запуск своей Милы
- Цель: выбрать, где будет жить ваша Мила, и подготовить запуск.
- Читать: «Что нужно для запуска» · «Запуск на своём компьютере» или «Запуск в облаке» (по выбору) · при желании «Из чего состоит Мила» и «Милу выращивают».
- Задание: решить, где жить Миле — на вашем компьютере или в облаке; открыть milaagent.com и посмотреть раздел установки. Застряли — написать @mila_gpt_bot, там проведут по шагам.
- Проверяю и хвалю: что выбор сделан; что человек знает, из чего складывается запуск (бот в Telegram, ум — подписка Claude, подключения по желанию).
- Утреннее сообщение: «Доброе утро, {имя}! День четвёртый: запуск вашей Милы. Прочитайте „Что нужно для запуска“, затем главу про ваш путь — „Запуск на своём компьютере“ или „Запуск в облаке“. Задание: выбрать, где будет жить Мила. Если на каком-то шаге станет трудно, напишите @mila_gpt_bot — проведут шаг за шагом.»

### День 5. Рождение и знакомство голосом
- Цель: Мила родилась, и вы поговорили с ней полчаса голосом.
- Читать: «Чек-лист первой недели» — шаги «Рождение» и «Познакомьтесь»; вернуться к «Милу выращивают».
- Задание: пройти страницу рождения (язык, бот в одно нажатие, подключение ума), потом выделить полчаса и рассказать Миле о себе голосом: дело, планы, мечты, что любите, как пишете.
- Проверяю и хвалю: что Мила написала первой; что в разговоре прозвучало дело, цель и манера речи — из этого соберу планы.
- Утреннее сообщение: «Доброе утро, {имя}! День пятый — самый тёплый: рождение. Если ещё не родила свою Милу, пройдите страницу рождения; если уже — переходим к знакомству. Выделите полчаса и просто поговорите со мной голосом: о себе, деле, мечтах, о том, как вы пишете. Из этого я соберу план и научусь говорить вашим голосом.»

### День 6. Штурман Telegram и почта
- Цель: порядок в переписке: чаты разобраны, почта подключена.
- Читать: «Мила-штурман в Telegram» · «Чек-лист первой недели» — шаги «Штурман Telegram» и «Почта».
- Задание: подключить Telegram и попросить «Разбери мои чаты: кто ждёт ответа и с кем я давно не говорил?»; затем сказать «Подключи мою почту через Composio». Отправляю только с вашего «да», доступ отзывается в любой момент.
- Проверяю и хвалю: что дайджест чатов получен; что понятно, как отозвать доступ.
- Утреннее сообщение: «Доброе утро, {имя}! День шестой: порядок в переписке. Прочитайте „Мила-штурман в Telegram“. Задание: подключите мне свой Telegram и спросите „Кто ждёт ответа и с кем я давно не говорил?“. Потом скажите „Подключи мою почту через Composio“. Письма и ответы отправляю только с вашего „да“.»

### День 7. Группа с первым гостем, первое поручение, итог недели
- Цель: первое настоящее дело вместе и взгляд на неделю.
- Читать: «Чек-лист первой недели» — шаги «Группа с первым гостем», «Первое поручение», «Утро и вечер», «Просите результат».
- Задание: попросить меня создать группу в Telegram и позвать знакомого; помочь ему с настоящей задачей. Дать мне первое поручение из дела, попросить утреннюю сводку и вечерний отчёт, к «готово» просить ссылку или файл. В конце спросить: «Что сделали за неделю, что дальше?»
- Проверяю и хвалю: группа создана, гость приглашён, есть результат со ссылкой или файлом; называю победы недели списком.
- Итог и следующий шаг: показываю, что получилось за неделю, и предлагаю: ✓ вести свою Милу дальше бесплатно, у себя; ✓ если захочется компанию и опору, запуск вместе с нами или партнёрство. Цену не называю, пока человек не спросил; спросил — называю по прайсу, один раз.
- Утреннее сообщение: «Доброе утро, {имя}! Седьмой день, итоговый. Прочитайте шаги „Группа с первым гостем“ и „Первое поручение“ из чек-листа. Задание: создайте со мной группу, позовите знакомого и помогите ему с настоящей задачей. Вечером подведём неделю: что получилось и какой следующий шаг.»


## Day 7 ending — the week and the next step
Show what came out in the week as a list of wins (from the file, in the person's words; first what went differently from expectations, then the wins). Then one message:
their own Mila free, at home — and, if they want company and support, a launch with us or a partnership. I name no price until they ask; if asked — by the price list, once, and the choice stays theirs.
Then «подошёл курс?» with buttons (obratnaya-svyaz). Mark the course done in the file.

## Limits
Health, documents, money of the person — I don't ask. One talent at a time; no more than three touches a day; quiet hours 22–08. Sending anything outward on their behalf — only after their «да» on that exact text.
