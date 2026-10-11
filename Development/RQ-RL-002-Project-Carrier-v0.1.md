# RQ-RL-002 — Parent Project Carrier v0.1

**Исходный запрос:** «Христианское сопровождение депрессии и суицидального кризиса»  
**Статус:** ACTIVE DESIGN CARRIER / WAVE 0  
**Дата открытия:** 11 октября 2026  
**Owner:** Owner In Profundo  
**Steward / continuity:** Project Overview  
**Назначение:** единая точка входа и возврата для project-level RQ-RL-002; удерживает исходный запрос, блоки A–K, capabilities, зависимости, версии, durable outputs, проверки, gates и return routes.  
**Нормативная граница:** carrier не изменяет Конституцию/Методологию Research Lab, постоянные роли или полномочия существующих систем и сам по себе не запускает substantive research.

---

# 1. Канонический вход

## Исходный вопрос Owner

> **Как христианин, семья, пастор/служитель и церковная община могут понимать и сопровождать человека, проходящего депрессию и/или суицидальный кризис, оставаясь верными библейскому свидетельству, честными по отношению к современному профессиональному знанию, безопасными в практическом действии и ясными относительно границ собственной компетенции?**

Исходный запрос не сужается до capability, через которую он вошёл в проект. Research Lab является одним из исследовательских узлов, а не контейнером всего запроса.

## Pinned inputs

1. `Development/RQ-RL-002-Project-Research-Map-v0.1.md` — концептуальная карта A–K.
2. `Development/RQ-RL-002-Capability-Fit-v0.1.md` — первичный Capability Fit и волны.
3. `Development/Brainstorms/Cross-System-Formation-Synthesis-Owner-Decision-Frame-v0.1.md` — принятый архитектурный вход для project-level arrangement.
4. `Development/Cross-Cycle-Carrier-Transition-Principle-v0.1.md` — Discussion Draft; используется как рабочая линза, не как принятая постоянная норма.
5. `FP-RL-002-R2` и `RQ-RL-002-Limited-Review-Installation-Package-v0.1` — существующие child artifacts Research Lab; не считаются substantive execution.

При появлении новой редакции pinned input carrier должен явно указать, какая версия заменила прежнюю и какие downstream outputs требуют impact review.

---

# 2. Языковая граница

Смысловой язык RQ-RL-002 — **русский**. Английский и другие языки допустимы для источников, оригинальных терминов и технических идентификаторов. Задания, аргументы, ограничения, выводы, решения и handoff должны быть полноценно понятны на русском.

---

# 3. Как читать состояние

## Capability Fit

- 🟢 **есть** — подходящая capability существует;
- 🟡 **можно собрать** — функция может быть ограниченно собрана из существующих механизмов/назначений и профильной поддержки;
- 🔴 **нужно получить/создать** — достаточной компетенции или владельца сейчас нет.

`🔴` сохраняет вопрос в проекте, но запрещает считать его исследованным.

## Состояние блока

`○ NOT STARTED` → `◐ FORMING / ASSIGNED / IN WORK` → `◑ RESULT RETURNED / UNDER ACCEPTANCE` → `● ACCEPTED / CLOSED`

Дополнительно: `⛔ BLOCKED`, `↩ RETURNED`, `⏸ HOLD`.

## Визуальный показатель покрытия блока

Покрытие показывает не качество и не истинность вывода, а **насколько требуемый контур блока заполнен принятыми результатами**.

`░░░░░ 0%` — нет принятого покрытия  
`█░░░░ 20%`  
`██░░░ 40%`  
`███░░ 60%`  
`████░ 80%`  
`█████ 100%` — минимально достаточный результат блока принят

Промежуточные значения допускаются кратно 10%, если это помогает точнее показать состояние. Процент меняется только по durable evidence. Source discovery, assignment или наличие участника сами по себе не увеличивают substantive coverage, если требуемый результат ещё не принят.

**Общее покрытие RQ-RL-002** считается только как навигационный показатель по блокам A–J. Блок K (продукты) показывается отдельно, потому что downstream product production не доказывает полноту исследования.

---

# 4. Living Map — текущее состояние

| Блок | Capability Fit | Состояние | Покрытие | Ведущая capability / owner | Ключевая поддержка | Следующий gate |
|---|---|---|---|---|---|---|
| A. Библейское свидетельство | 🟢 + 🟡 | ○ NOT STARTED | `░░░░░ 0%` | Research Lab; конкретный owner назначается child assignment | богословская интеграция; клиническая граница против ретроспективной диагностики | подготовить bounded Research Lab assignment |
| B. Антропология / грех / ответственность / спасение | 🟡 + 🔴 | ⏸ HOLD | `░░░░░ 0%` | богословский synthesis owner — не назначен | A + C/D clinical constraints | ждать достаточных предметных входов и named theological owner/reviewer |
| C. Депрессия | 🔴 + 🟡 | ⛔ BLOCKED | `░░░░░ 0%` | клинический/психиатрический owner — отсутствует | source-review | получить достаточную профильную компетенцию |
| D. Суицидальность / кризис | 🔴 + 🟡 | ⛔ BLOCKED | `░░░░░ 0%` | suicide-prevention / crisis owner — отсутствует | pastoral + biblical/theological | получить профильного владельца безопасности/кризисных выводов |
| E. Пастырское сопровождение | 🟡 + 🔴 | ⏸ HOLD | `░░░░░ 0%` | pastoral/application owner — не назначен | A/B + C/D | назначать после достаточных upstream boundaries |
| F. Семья / церковная община | 🟡 + 🔴 | ⏸ HOLD | `░░░░░ 0%` | pastoral/application owner — не назначен | clinical/crisis + biblical/theological | определить после C/D и pastoral scope |
| G. Эстония / доступность / source map | 🟡 + 🔴 | ○ NOT STARTED | `░░░░░ 0%` | source-review / local-check function — назначить | clinical/crisis interpretation | подготовить child assignment на основе существующего Limited Review design |
| H. Статистика / эпидемиология | 🔴 + 🟡 | ⛔ BLOCKED | `░░░░░ 0%` | statistical/methodological owner — отсутствует | research source mapping | определить, material ли quantitative block; при да — получить methodological review |
| I. Междисциплинарный синтез | 🟡 | ⏸ HOLD | `░░░░░ 0%` | временный synthesis owner — не назначен | все принятые subject owners | открывать только на pinned accepted inputs |
| J. Применение / безопасность | 🟡 + 🔴 | ⏸ HOLD | `░░░░░ 0%` | application owner — не назначен | pastoral + clinical/crisis + biblical/theological + safety reviewer | отдельное application acceptance после subject/synthesis inputs |
| K. Продукты | 🟡 → 🟢 | ⏸ HOLD | `░░░░░ 0%` | Product Formation → Editorial / Publication | accepted upstream results | отдельный Owner product decision после достаточного upstream close |

**Исследовательское покрытие A–J:** `░░░░░ 0%`  
**Продуктовый слой K:** `░░░░░ 0%` / не активирован.

---

# 5. Контракт блока

Ни один substantive блок не стартует только потому, что он появился в Living Map. До `ASSIGNED` для блока должны быть зафиксированы:

1. **Block ID / exact question** — точный вопрос и границы.
2. **Required competence** — какая компетенция действительно нужна.
3. **Lead capability / named owner** — кто владеет профильным результатом.
4. **Supporting capabilities** — кто поддерживает и где заканчивается их authority.
5. **Pinned inputs / versions** — из чего работа исходит.
6. **Expected durable output** — что именно должно быть сохранено.
7. **Canonical path** — точный путь GitHub до начала работы.
8. **Write mode** — по умолчанию `WRITE → VERIFY → COMMIT → LINK IN CARRIER → HANDOFF`; если Owner должен принять до записи, явно `DO NOT WRITE`.
9. **Acceptance type** — contract/documentary, subject-matter, synthesis/linking, application/safety или иной точно названный тип.
10. **Reviewer / accepter** — кто компетентен принять именно этот тип результата.
11. **Dependencies** — какие блоки/версии обязательны.
12. **Stop / Return** — когда участник обязан остановиться и куда вернуть результат/проблему.
13. **Coverage rule** — какой принятый результат изменяет показатель покрытия.
14. **Downstream permitted use** — для чего результат после принятия разрешено использовать.

Если named competent owner или accepter отсутствует, блок остаётся `BLOCKED/HOLD`; координатор не замещает отсутствующую компетенцию.

---

# 6. Реестр child work

| Child ID | Parent block | Carrier / system | Assignment | Durable output | Acceptance | State | Return |
|---|---|---|---|---|---|---|---|
| RL-RQ-002-FORMATION-R2 | project-wide input | Research Lab | Formation R2 | существующий Formation artifact | Formation/contract level | ● EXISTING INPUT | Parent carrier |
| RL-RQ-002-INSTALL-v0.1 | G / project source-review input | Research Lab | Limited Review Installation | существующий Installation Package | Installation/contract level | ● EXISTING INPUT / EXECUTION NOT LAUNCHED | Parent carrier |
| RQ002-A-01 | A | Research Lab | не создано | TBD before assignment | subject-matter + required independent check | ○ | Parent carrier |
| RQ002-G-01 | G | TBD bounded source-review carrier | не создано | TBD before assignment | source-map/documentary; профильные claims отдельно | ○ | Parent carrier |

Новая child work добавляется сюда **до запуска**, а после завершения строка обновляется ссылкой/версией результата, verdict и разрешённым downstream use.

---

# 7. Acceptance Map

Carrier различает минимум четыре класса принятия:

1. **Contract / documentary acceptance** — результат соответствует заданию и документально полон; не доказывает предметную истинность.
2. **Subject-matter acceptance** — профильный вывод принят компетентным предметным reviewer/owner.
3. **Synthesis / linking acceptance** — принято новое утверждение, связывающее уже принятые предметные выводы.
4. **Application / safety acceptance** — принято практическое применение; safety-sensitive рекомендации требуют профильной проверки.

Отдельно **project progression** решает, можно ли переходить дальше; это не epistemic verdict.

Каждый verdict закрепляется за конкретным объектом, версией, видом проверки, компетентным accepter и разрешённым downstream use.

---

# 8. Dependency Map

```text
A ───────────────┐
                 ├──► B ───────┐
C ───────────────┤             │
D ───────────────┘             │
                               ├──► I ───► J ───► K
A/B/C/D ─────────────► E ──────┤
A/B/C/D ─────────────► F ──────┤
C/D ─────► G ──────────────────┤
C/D/H ─────────────────────────┘
```

Схема показывает основные зависимости, а не обязательный линейный pipeline. Блоки могут идти параллельно там, где их contract не требует ещё не принятых upstream conclusions.

---

# 9. Return Routes

## Child → Parent

Каждый child result возвращается в этот carrier с:

- точной ссылкой и immutable version/commit;
- типом результата;
- verdict и типом acceptance;
- ограничениями;
- разрешённым downstream use;
- изменением покрытия блока;
- открытыми вопросами;
- impact note для зависимых блоков.

## Parent → Child

Если входной материал изменён после запуска child task, Project Overview/координатор не молча заменяет input. Сначала фиксируется impact review: `NO IMPACT / RECHECK REQUIRED / RETURN / SUPERSEDED`.

## Owner

Owner получает material gates, а не выполняет технический перенос уже разрешённых результатов между участниками. Если продолжение требует от Owner вручную переносить артефакт, повторно объяснять маршрут или отдельно просить сохранить значимый результат без нового material decision, carrier считается недостаточно настроенным и требует orchestration correction.

---

# 10. Волны

## Wave 0 — carrier / infrastructure — ◐ ACTIVE

- ● parent carrier создан;
- ● Project Research Map pinned;
- ● Capability Fit pinned;
- ● существующие Formation R2 / Installation зарегистрированы;
- ● языковая граница закреплена;
- ● правило substantive start only with named owner + acceptance route закреплено;
- ○ подготовить child contract A;
- ○ подготовить child contract G;
- ○ определить маршрут получения C/D competence.

## Wave 1 — доступные исследовательские блоки — ○

- A — bounded biblical research;
- G — source / Estonia map;
- поиск решения для C/D competence без симуляции её наличия.

## Wave 2 — профессиональные предметные блоки — ⛔ частично BLOCKED

- C — depression;
- D — suicidality/crisis;
- H — statistics if material.

## Wave 3 — integration — ⏸ HOLD

B, E, F, I после достаточных принятых inputs.

## Wave 4 — application / safety — ⏸ HOLD

J с отдельным safety acceptance.

## Wave 5 — products — ⏸ HOLD

K после отдельного Owner product decision.

---

# 11. Owner Gates

### Gate P0 — Carrier opening

**Disposition:** APPROVED / IMPLEMENTED. Owner поручил создать общий carrier.

### Gate P1 — First child assignments

Перед substantive execution должны быть подготовлены точные child contracts A и G с durable paths, owners, inputs, acceptance и return routes. Их подготовка не равна запуску execution, если соответствующая локальная система требует отдельного Owner gate.

### Gate P2 — Professional competence

C/D не запускаются без named competent owner/reviewer. H — аналогично, если количественный блок остаётся material.

### Gate P3 — Synthesis

I не запускается, пока не определены достаточные accepted subject inputs и отдельный synthesis mandate/accepter.

### Gate P4 — Application / Safety

J не активируется без соответствующих subject/synthesis inputs и профильного safety route.

### Gate P5 — Products

Owner отдельно решает, какие продукты действительно нужны. Ни research close, ни synthesis автоматически не создают статью, пособие, семинар или рекомендации.

---

# 12. Current blockers

### 🔴 C/D competence

Главный содержательный blocker полного запроса: клиническая компетенция по депрессии и suicide-prevention / crisis safety.

### 🔴 H competence

Методологическая/статистическая компетенция нужна до substantive quantitative conclusions, если H сохраняется material.

Эти blockers не мешают Wave 0 и подготовке A/G, но блокируют честное закрытие полного RQ-RL-002.

---

# 13. Change / provenance rule

Carrier — living document. Материальное изменение фиксирует:

- дату;
- затронутый блок/контракт;
- предыдущую и новую версию входа/результата;
- причину;
- impact на dependencies;
- кто имеет authority на изменение;
- commit.

Не переписывать принятый historical result так, будто новая редакция существовала изначально. Существенные child outputs сохраняются отдельными durable artifacts и только регистрируются/линкуются здесь.

---

# 14. Close condition

RQ-RL-002 может быть закрыт только с явным disposition по каждому блоку A–J:

- `ACCEPTED`;
- `NOT REQUIRED` с обоснованием Owner;
- `BLOCKED / UNRESOLVED` как честно сохранённый остаток;
- `DEFERRED` с re-entry condition.

Продуктовый K закрывается отдельно по выбранным продуктам.

Полный проект не считается содержательно завершённым только потому, что создан carrier, собраны источники или выпущен отдельный продукт.

---

# 15. Ближайший рабочий переход

```text
PARENT CARRIER — OPEN
        ↓
подготовить RQ002-A-01
        +
подготовить RQ002-G-01
        +
определить route получения C/D competence
        ↓
проверить contracts / local authority gates
        ↓
отдельно активировать разрешённые child tasks
```

Следующая substantive работа должна входить через этот carrier, а не через новый installation prompt как единственное место задания.