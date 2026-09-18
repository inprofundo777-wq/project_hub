# In Profundo — Development Map

**Тип:** Living Development Map  
**Статус:** 🟢 Active Working Map  
**Базовая проверка направлений:** 2026-09-05  
**Полная project-level сверка:** 2026-09-18 — weekly Delta Review + Parallel Branch Convergence  
**Назначение:** карта зрелости, движения и связей основных capabilities In Profundo

---

# 1. Как читать карту

Development Map отвечает на три вопроса:

> **Что уже существует?**

> **Насколько каждая capability способна выполнять свою функцию?**

> **Какой следующий переход должен быть доказан практикой?**

Карта не является:

- календарём публикаций;
- полным backlog Owner;
- Strategic Snapshot;
- заменой permanent documentation;
- полным реестром материалов;
- вторым Content Portfolio.

## Зрелость capability

- 🟢 — capability существует и подтверждена практикой;
- 🟡 — capability существует, но формируется, проверяется или нормализуется;
- 🔴 — существенная capability отсутствует или заблокирована;
- ⚪ — направление предусмотрено / видно на горизонте, но сейчас не активировано.

## Шаги развития

- `●` — завершено / подтверждено;
- `◐` — текущий переход / частично пройдено;
- `○` — следующий возможный шаг.

Количество `●` и `○` не определяет цвет математически.

## Связи

- `→` — передача;
- `↔` — feedback loop;
- `⛓` — dependency.

## Текущая активность

`СЕЙЧАС →` показывает текущий переход.

Зрелость и активность — разные координаты. Capability может быть зрелой и находиться на паузе либо быть незрелой и активно развиваться.

---

# 2. Карта проекта сверху

Карта показывает зрелость больших capabilities. Для 🟡 / ⚪ блоков рядом указаны только незавершённые переходы; завершённые внутренние шаги не разворачиваются повторно.

| Большой блок | Зрелость | Незавершённый переход |
|---|---:|---|
| Fundamental Layer | 🟡 | ◐ оставшиеся reviews → ○ интеграционная редакция |
| Project Overview / Continuity | 🟡 | ◐ повторяемость Convergence → ○ long-term re-entry |
| Publication Master | 🟡 | ◐ Candidate validation debt → ○ operational repeatability |
| Notion / Content Intelligence | 🟡 | ◐ selective Portfolio 02 update → ○ research-card lifecycle |
| Far Content Horizon | 🟢 | |
| Content Portfolio | 🟢 | |
| Editorial System / VIA | 🟡 | ◐ первый полный production cycle после role stabilization → ○ Product Quality verdict |
| Publication | 🟢 | |
| Distribution | 🟢 capability / 🟡 channels | ◐ lightweight Telegram + Facebook experiment → ○ external reach evidence |
| Audience / Discovery / SEO | 🟡 | ◐ live evidence → ○ encounter/value distinction |
| Research Lab | 🟡 | ◐ TP-RL-001 execution → ○ route gate / repeatability verdict |
| Books | 🟡 | ⛓ mature Research evidence |
| «Взгляд» | ⚪ | ○ smallest meaningful experiment |
| GitHub / Archive / Automation | 🟡 | ◐ one-link Run Record practice → ○ repeatability |
| External Orchestration | ⚪ | paused |

### Основная рабочая связка

```text
Portfolio 🟢
→ Coach / Editorial cycle 🟡
→ Publication 🟢
→ Distribution / Audience evidence 🟡
↔ Notion / Strategy 🟡

Research Lab 🟡
→ bounded research output
→ отдельный Owner gate
→ возможный Knowledge Transfer
```

Зрелость блока не равна его текущей активности: зелёная capability может быть на паузе, а жёлтая — находиться в активной проверке.

---

# 3. OWNER

**Ответственность:** направление проекта и стратегические решения.

● Owner определяет направление.  
● Owner утверждает существенные стратегические решения.  
● ясная задача может идти непосредственно в соответствующую capability.  
● Publication Master не является обязательным gate.  
● Project Overview не является supervisor систем.  
● Owner не должен становиться ручным integration layer между системами.

**Текущий project-level выбор:**

> после периода интенсивной нормализации вернуть основной фокус к публикационной работе и проверять уже созданные capabilities практикой.

**Критерий развития:**

> Если capability работает только потому, что Owner вручную помнит и соединяет её части, capability ещё не полностью доказана.

---

# 4. FUNDAMENTAL LAYER — 🟡

**Функция:** удерживать идентичность, authority и фундаментальную архитектуру проекта.

### Подтверждено

● DNA rev 3.1: часть I — основание; часть II — открытое развитие.  
● ARC-001 — утверждённая карта подготовки корпуса, не готовая Конституция или полный мандат ролей.  
● различены Constitution / Framework / Policy / Workflow.  
● Mission 0.2, Core Principles 0.2 и Editorial Philosophy 0.2 сформированы как рабочий candidate corpus.  
● межсистемная проверка candidate corpus завершена.  
● Theological Review завершён 9 сентября 2026 и интегрирован в три документа.  
● фундаментальный корпус сохраняет различие между Писанием как первичным основанием, исторической христианской традицией, разумным исследованием, опытом и ограничениями собственных утверждений.

### В развитии

◐ Mission: Strategic, Reader и Literary Reviews.  
◐ Core Principles: Strategic, Research и Editorial Reviews.  
◐ Editorial Philosophy: Literary, Reader, Research и Strategic Reviews + проверка применения в role packages.  
○ интеграционная редакция после оставшихся reviews.  
○ окончательное размещение project-level Foundation документов.

### Дальнейший нормативный корпус

○ Constitution 1.0.  
○ FRM-001 Architecture and Authority Framework.  
○ POL-001 Documents, Decisions and Archive Policy.  
○ FRM-002 Research, Scripture and Editorial Integrity Framework.  
○ WF-001 Fundamental Decision Workflow.  
○ REG-001 Transfer Register.  
○ POL-002 Automation and Tool Governance Policy — позже.

### Граница

Mission и Core Principles остаются project-level conceptual drafts без нормативной силы; Editorial Philosophy остаётся system-level applied philosophy draft. Их зрелость выросла, но завершённые reviews не превращают документы автоматически в нормативную Конституцию.

**СЕЙЧАС → не ускорять Foundation ради административной завершённости; оставшиеся reviews проводить без вытеснения publication focus.**

---

# 5. PROJECT OVERVIEW & CONTINUITY — 🟡

**Функция:** удерживать развивающееся целое, continuity понимания, связи и точки возврата.

### Подтверждено

● пакет v0.4 Candidate действует как Working Candidate.  
● Audit Correction, DS-01, DS-02 и DS-04 завершены.  
● Role Activity Log и Parallel Branch Convergence Gate действуют как Working Pilot.  
● несколько реальных межветочных передач сведены без повторения уже выполненной работы.  
● weekly Delta Review 18 сентября свёл Research Lab, Editorial System, Portfolio / VIA и Notion в актуальную Background Map.  
● Project Overview сохраняет основную роль при Owner и не становится управляющим центром систем.

### Открытая validation

◐ повторяемость Parallel Branch Convergence и one-link re-entry.  
○ real Temporary Role Exit / DS-03 при естественной задаче.  
○ Long-term Re-entry после реального интервала.  
○ новый project-level Snapshot после закрытия ближайших production / research gates.

**СЕЙЧАС → использовать актуальные `Project_Map.md` и `MASTER_ROADMAP.md` как две разные координаты: первая хранит области и границы, вторая — зрелость и переходы.**

---

# 6. PUBLICATION MASTER — 🟡

**Функция:** архитектурная связность Publication System и ограниченные system-level / cross-role вопросы.

### Закрыто

● пакет Publication Master v0.1 Candidate пересобран.  
● Fresh-context Recovery — PASS.  
● Leadership Continuity targeted stabilization — VERIFIED.  
● Publication Role Readiness закрыт: PASS WITH VALIDATION DEBT; blocking debt отсутствует.  
● границы Master / Coach / Longform / Strategist восстановлены однозначно.  
● Master завершает bounded assignment через Handoff и Role Exit, не удерживая следующий VIA.

### Осталось доказать

◐ non-blocking validation debt накапливает evidence в реальной работе, без нового redesign.  
○ повторяемость system-level handoff в следующем естественном случае.

**СЕЙЧАС → не запускать новую нормализацию Master; использовать роль только при реальном архитектурном вопросе Publication System.**

---

# 7. NOTION / CONTENT INTELLIGENCE — 🟡

**Функция:** долговременная структурированная память содержания и карта будущих редакционных решений.

### Закрыто

● capability test `VIA-2026-012–019 → Notion Content Intelligence` — PASS.  
● подтверждена граница: GitHub хранит durable artifact / evidence, Notion — structured content intelligence.  
● 26 существующих карточек фактически синхронизированы: 15 публикаций 2025 года и 11 публикаций первой половины 2026 года.  
● проверены VIA, VIA URL, Blogger URL, дата, публикационный статус и канал; дубли не создавались.  
● Notion не превращён во второй production tracker.

### Текущий переход

◐ selective update package для Queue, Reserve и research cards второго Portfolio.  
○ минимально различить publication status и research lifecycle.  
○ продолжать возвращать только отфильтрованное durable learning, а не весь VIA / Far Horizon.

**СЕЙЧАС → выполнить выборочное обновление Portfolio 02; не запускать массовое content enrichment 26 карточек без отдельного решения.**

---

# 8. ДАЛЬНИЙ СОДЕРЖАТЕЛЬНЫЙ ГОРИЗОНТ — 🟢

Capability подтверждена закрытием второго Content Portfolio: Near Publication Queue, Reserve, research-led candidates и Far Development Horizon различены без превращения всего будущего в production plan.

---

# 9. CONTENT PORTFOLIO — 🟢

Capability подтверждена двумя циклами: Portfolio сохраняет готовую очередь, границы и readiness, а Owner может передать Coach одну ссылку на закрытый handoff. `Content-Portfolio-2026-02` закрыт; первый следующий handoff подготовлен для «Литургии обычного дня». Новая тема не активируется автоматически до отдельного Owner / Coach перехода.

---

# 10. EDITORIAL SYSTEM / VIA — 🟡

**Функция:** проводить выбранный материал через достаточный редакционный цикл до стабильного Final Text, публикации и learning.

### Закрыто

● VIA Protocol и stage / lifecycle boundaries существуют.  
● Publication Role Readiness — PASS WITH VALIDATION DEBT; blocking debt отсутствует.  
● Publication Master Fresh-context Recovery — PASS.  
● Editorial Coach stabilization и Fresh-context Recovery — PASS WITH NON-BLOCKING FINDINGS.  
● Longform Editor v0.2 Fresh-context Recovery — PASS WITH NON-BLOCKING FINDINGS.  
● Longform удерживает цельное авторство Draft / Revised Draft; Coach интегрирует независимые findings; Master не управляет отдельным VIA.  
● `VIA-2026-018` и `VIA-2026-019` дали live protocol evidence.

### Текущий переход

◐ `VIA-2026-020 — После сотого падения`: Blogger Placement / Publication / Close.  
○ отдельным Owner gate активировать Closed Portfolio 02 → Coach → новый VIA.  
○ пройти полный evidence chain: Draft → independent Findings → Coach Integration → Revised Draft → Final Text.  
○ вынести Editorial Product Quality verdict; сейчас он остаётся VALIDATION PENDING.

**СЕЙЧАС → завершить VIA-2026-020, затем проверить стабилизированные роли на одном реальном цикле; не подменять product-quality evidence новой документацией.**

---

# 11. EXTERNAL / ADDITIONAL EDITORIAL CAPABILITIES — 🟡

### External Literary Editor

● Recovery завершён.  
● Working Core сохраняет восстановленную capability.  
● capability использовалась в live work.  
◐ permanent role stabilization остаётся будущей задачей после достаточного evidence.

Переходный принцип сохраняется:

> Working Core = capability.  
> VIA = конкретная задача и material context.

### Modular Editorial

🟡 Full Capability + Minimal Invocation остаётся рабочей гипотезой.

○ продолжать проверять селективные вызовы практикой.  
○ не создавать модульную архитектуру только ради полноты.

**СЕЙЧАС → не активировать отдельную нормализацию External Literary Editor, пока publication cycle не создаёт реального запроса.**

---

# 12. PUBLICATION — 🟢

Capability подтверждена несколькими реальными переходами Final Text → Publication Preparation → Blogger / Public Publication. Текущая активность — завершение Blogger Placement / Publication для `VIA-2026-020`; это operational work, а не незакрытая зрелость capability.

---

# 13. DISTRIBUTION — 🟢 capability / 🟡 текущая модель каналов

**Функция:** адаптировать опубликованные материалы под каналы и создавать точки входа.

### Подтверждено

● platform-native adaptation.  
● Telegram и Facebook production capability.  
● предыдущие DIST cycles дали evidence структуры, Owner load и литературной повторяемости.  
● Distribution capability ≠ external discovery.

### Текущий operational выбор

#### Telegram — 🟢 MAINTAIN / lightweight

● Telegram остаётся рабочим каналом.  
● материалы можно готовить непосредственно в рабочей ветке по готовому Final Text статьи.  
● полный formal DIST для каждой публикации временно не требуется.

◐ проверить, сохраняет ли lightweight режим качество при меньшей административной нагрузке.

#### Facebook — 🟡 EXPERIMENT

● существующая страница и опубликованный корпус используются как экспериментальная база.  
◐ исследовать форматы: короткий текст, визуальный постер, цитата, вопрос, самостоятельный entry point и другие platform-native варианты.  
○ собирать сравнительный evidence вместо преждевременного процесса.

#### Microformats — ⚪ WATCH

● capability и прошлый опыт существуют.  
○ не являются текущим operational priority; возвращаться при конкретной channel need.

### Не доказано

○ устойчивый external reach.  
○ acquisition.  
○ meaningful exposure среди релевантных незнакомых людей.

**СЕЙЧАС → Telegram поддерживать облегчённо; Facebook тестировать как отдельную экспериментальную ветку; не возвращать formal DIST по умолчанию.**

---

# 14. BLOG ARCHITECTURE / NAVIGATION — 🟡

**Функция:** помочь уже пришедшему читателю двигаться внутри корпуса In Profundo.

● Navigation ≠ Distribution.  
● публичная страница «Темы» существует как real pilot.  
◐ usefulness observation.  
○ следующий structural decision только после evidence.

**СЕЙЧАС → наблюдать, не расширять архитектуру преждевременно.**

---

# 15. AUDIENCE / DISCOVERY / SEO — 🟡

**Функция:** понять, встречается ли In Profundo с релевантными незнакомыми людьми и что происходит при этой встрече.

### Подтверждено

● internal maturity ≫ external validation.  
● publication ≠ distribution.  
● distribution ≠ discovery.  
● SEO capability встроена в publication work.  
● Discovery / Acquisition Capability Gap существует.  
● Discovery как единственный primary project constraint пока не доказан.

### Текущий переход

◐ собирать live evidence через реальную публикацию и channel experiments.  
○ meaningful exposure.  
○ различить encounter problem и value problem.  
○ использовать SEO Review нового Portfolio как отдельный тип evidence, не как замену Reader Review.

**СЕЙЧАС → evidence before positioning conclusions; не строить новый Discovery system до достаточного внешнего сигнала.**

---

# 16. RESEARCH LAB — 🟡

**Функция:** формировать, выполнять и независимо проверять исследовательскую работу до возможного Knowledge Transfer / application.

### Закрыто за неделю

● Role System v0.1 реализован: Director → Project Lead → Researcher; Auditor независим от operational ownership.  
● Director / Project Lead / Researcher / Auditor имеют статус Candidate Active / Validation Pending.  
● Packages A/B/C, Modes, Role Configuration Lock, authority / escalation и independence standards введены.  
● Wave 1 Fresh-context Recovery пройден четырьмя ролями.  
● Formation `RQ-RL-001 — Generosity, Trust and Entrusted Resources` прошла independent audit.  
● route исправлен: FULL PROJECT → LIMITED PROBE.  
● Existing Research Coverage Review завершён.  
● Narrowed Bounded Limited Review завершён; specific textual uncertainty локализована.  
● `TP-RL-001` установлен и получил Owner execution authorization.

### Текущий переход

◐ Researcher выполняет `TP-RL-001` только по Мф. 6:19–34 и Лк. 12:13–34.  
○ Project Lead принимает / возвращает Probe по OC1.  
○ Director проводит route re-evaluation; следующий route требует отдельного Owner gate.  
○ Wave 2 формирует evidence повторяемости Role System, Handoff, Role Exit и one-link Run Record.

### Граница

2 Кор. 8–9 остаётся comparative literature context, не primary corpus. Corpus expansion, Full Project, downstream application и следующий route не разрешены. `IP-001` не перезапускался и не изменялся.

**СЕЙЧАС → завершить bounded Textual Probe и только затем определить следующий Research gate.**

---

# 17. BOOKS — 🟡

### «Тот, Кто остаётся»

● архитектура книги сформирована.  
● основной manuscript существует.  
● Reader Arc сформирован.  
● Workbook direction сформирован.

### Dependency

    Book
      ↓
    Part IV evidence problem
      ↓
    IP-001
      ↓
    mature Research evidence
      ↓
    selective Book Transfer

⛓ часть дальнейшей стабилизации книги зависит от IP-001.

### Активность

⚪ сознательная пауза относительно текущего publication focus.

**СЕЙЧАС → не считать книгу просроченным долгом и не подменять исследование заранее желаемым выводом.**

---

# 18. ВЗГЛЯД — 🟡

**Функция:** практическая лаборатория внимания и восприятия.

● направление различено.  
● первый Strategic Snapshot существует.  
● photography признана возможным входом, но не определением направления.  
● practice before architecture.

⚪ сейчас не operational priority.  
○ smallest meaningful experiment при естественном окне.

**СЕЙЧАС → сохранять как emerging direction, не превращать в курс, школу или production system.**

---

# 19. PROJECT MEMORY / CONTINUITY — 🟡

### Подтверждено

● Snapshot package и Snapshot Index существуют.  
● Post-Audit Snapshot 2026-09-07 сохранён как HISTORICAL / INSUFFICIENT CANDIDATE.  
● Audit Correction Control Point 2026-09-08 — текущий Snapshot Project Overview.  
● Project-level Snapshot 2026-08-30 остаётся CURRENT PROJECT BASELINE, но предшествует текущему operational transition.  
● CURRENT / CURRENT PROJECT BASELINE / CONCEPT / RECOVERY / HISTORICAL различены.  
● Development Map существует и является living map.  
● Decision Memory и Role Activity Log имеют отдельные функции.  
● отдельный постоянный список «Созревшие ветки» не требуется.

### Правило

> **Слепок хранит понимание.**

> **Карта развития хранит движение.**

> **Текущая работа не должна превращаться в отдельный постоянный реестр только ради видимости.**

### Следующая контрольная точка

◐ новый project-level Snapshot содержательно назревает из перехода `system-building → publication-centered operational validation`.  
○ предпочтительная точка фиксации: после `VIA-2026-020 Close` + `Content Portfolio 2026-02 Strategy Close`.

**СЕЙЧАС → не создавать Snapshot до закрытия этих двух близких переходов без отдельного решения Owner.**

---

# 20. GITHUB / ARCHIVE / AUTOMATION — 🟡

**Функция:** durable source-of-truth и техническая среда воспроизводимой работы.

### Подтверждено

● GitHub является permanent archive / source-of-truth.  
● старый Master Roadmap архивирован как `ARH-001-MASTER_ROADMAP.md`.  
● текущий `MASTER_ROADMAP.md` является Living Development Map.  
● permanent-doc cycle сформирован.  
● Project Overview Document Stewardship показал практическую ценность архива, read-back и Correct Stop.  
● Role Activity Log и Parallel Branch Convergence снижают риск расхождения нескольких экземпляров одной роли.

### Validation debt

◐ безопасная запись более чем в одном типе процесса.  
○ real Correct Stop.  
○ temporary-role write + Role Exit.  
○ повторяемость Convergence Gate.  
○ автоматизация только после доказательства governance behavior.

### Archive hygiene

○ selective sweep только реальных stale states.  
○ не строить дополнительную архивную инфраструктуру без необходимости.

**СЕЙЧАС → использовать GitHub в живых процессах и проверять governance практикой, а не расширять automation layer заранее.**

---

# 21. EXTERNAL ORCHESTRATION — ⚪ PAUSED

**Функция-кандидат:** внешний orchestration / automation layer для повторяющейся работы и публикационных операций.

● концепция и варианты изучались.  
● экономическая и operational необходимость пока не доказана.  
● внутренний chat-based workflow остаётся достаточным для текущих VIA / Portfolio процессов.

**СЕЙЧАС → пауза. Возвращаться только при реальном repetitive workload, ясной экономике и стабилизированном внутреннем процессе.**

---

# 22. БЛИЖАЙШИЙ ГОРИЗОНТ

## NOW

### Publication

```text
VIA-2026-020
→ Blogger Placement / Publication
→ Close
```

### Research Lab

```text
TP-RL-001 execution
→ Project Lead OC1 acceptance
→ Director route re-evaluation
→ Owner gate
```

## NEXT

```text
Closed Content Portfolio 02
→ Owner activation
→ Editorial Coach
→ new VIA
→ Longform + independent Editors
→ Final Text
→ Editorial Product Quality verdict
```

И:

```text
Portfolio 02 selective update
→ Notion Queue / Reserve / research cards
→ no wholesale Far Horizon transfer
```

## MAINTAIN / EXPERIMENT

- Telegram → lightweight channel production.
- Facebook → experimental platform-native formats.
- Project Overview → one-link re-entry and repeated Convergence Gate.

## PAUSED / WATCH

- `IP-001` → не разморожен текущим Research route.
- Book → зависит от mature Research evidence.
- External Orchestrator → paused до доказанной нагрузки и экономики.
- «Взгляд» → концепция сохранена, production system не строится.

---

# 23. ГЛАВНЫЙ ПЕРЕХОД ПРОЕКТА

Предыдущий период:

> **восстановить → различить → спроектировать → нормализовать capability**

Текущий период:

> **использовать стабилизированные роли в реальной работе → собирать evidence результата → закрывать gates без ручной реконструкции Owner**

Три ближайших доказательства:

1. Research Lab завершает `TP-RL-001` и корректно проходит следующий gate.
2. Editorial System проводит первый полный цикл после стабилизации Master / Coach / Longform и получает Product Quality evidence.
3. Portfolio → VIA → Notion работает через закрытые handoff и выборочное learning, без превращения Owner в ручной integration layer.

Главный риск:

> спутать завершённость документации с доказанной зрелостью capability — либо, наоборот, продолжать разворачивать уже зелёный блок вместо перехода к следующему реальному результату.

Главный критерий:

> **зелёный блок больше не требует внутреннего development checklist; жёлтый блок обязан показывать конкретный текущий переход и следующий проверяемый шаг.**
