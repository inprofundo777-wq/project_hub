# In Profundo — Development Map

**Тип:** Living Development Map  
**Статус:** 🟢 Active Working Map  
**Базовая проверка направлений:** 2026-09-05  
**Полная project-level сверка:** 2026-09-12 — Project Overview recovery + Parallel Branch Convergence + live publication state  
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

                              OWNER
                                │
              ┌─────────────────┴─────────────────┐
              ▼                                   ▼
      FUNDAMENTAL LAYER                 🗺 PROJECT OVERVIEW
             🟡                                  🟡
              │                                   │
              │                          continuity / connections
              └─────────────────┬─────────────────┘
                                │
                                ▼
                    SYSTEMS / CAPABILITIES
                                │
       ┌──────────────┬─────────┼──────────┬──────────────┐
       ▼              ▼         ▼          ▼              ▼
 PUBLICATION        NOTION   EDITORIAL   RESEARCH       BOOKS
   MASTER 🟡          🟡        🟡          🟢             🟡
                       │         │           │              │
                       │         │           └─────⛓───────┘
                       │         ▼
                       │     PUBLICATION 🟢
                       │         │
                       ▼         ▼
               CONTENT STRATEGY / PORTFOLIO 🟡
                       │         │
                       │         └──→ DISTRIBUTION
                       │                 ├── Telegram 🟢 / lightweight
                       │                 └── Facebook 🟡 / experiment
                       │
                       ▼
               AUDIENCE / DISCOVERY 🟡
                       │
                       └────────────↔ Notion / Strategy

       ВЗГЛЯД 🟡
       отдельная развивающаяся ветка;
       не обязана проходить через editorial pipeline

                                │
                                ▼
                  INFRASTRUCTURE / MEMORY
                                │
          ┌─────────────────────┴─────────────────────┐
          ▼                                           ▼
    GITHUB / ARCHIVE                          CONTINUITY MEMORY
          🟡                                        🟡

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
● Audit Correction завершён; содержательный перенос проверен 22/22.  
● DS-01 Fresh-context write recovery — PASS.  
● DS-02 Correct Stop — PASS в контролируемом сценарии; реальный рабочий случай остаётся открытым.  
● DS-04 Observation Restraint — PASS.  
● Role Activity Log и Parallel Branch Convergence Gate введены как Working Pilot.  
● первый реальный Parallel Branch Convergence получил PASS: принимающая ветка обнаружила уже выполненное архивирование Publication Master и не повторила операцию.  
● Project Overview сохраняет основную роль при Owner и не становится управляющим центром систем.

### Открытая validation

◐ повторяемость Parallel Branch Convergence.  
○ real Temporary Role Exit / DS-03 при естественной задаче.  
○ real Correct Stop в рабочем процессе.  
○ Long-term Re-entry после реального интервала.

### Snapshot state

● Audit Correction Control Point 2026-09-08 остаётся текущим Snapshot Project Overview.  
◐ project-level baseline 2026-08-30 всё ещё формально Current Project Baseline, но уже не отражает весь новый operational state.

**СЕЙЧАС → использовать v0.4 как рабочую capability; перед material cross-branch action выполнять Convergence Gate; не расширять документацию без нового evidence.**

---

# 6. PUBLICATION MASTER — 🟡

**Рабочая область:** архитектурная связность узкой Publication System; временное принятие ограниченного системного вопроса до решения, Handoff и Role Exit.

### Подтверждено

● каноническое имя — Publication Master; Master Editor — историческое имя.  
● RR-2026-007 утверждён Owner как Final Analytical Review.  
● общепроектные continuity, horizons и roadmapping не принадлежат Publication Master.  
● recovery-поколение прежнего пакета архивировано и проверено.  
● новый Publication Master Role Package v0.1 Candidate пересобран: 10/10 документов.  
● Change Set имеет статус `Implemented / Documentation Updated / Awaiting Validation`.  
● Observation before Architecture, Existing Capability Check, Transfer Threshold, Capability Delta, Handoff и Role Exit встроены в новый пакет.

### Текущий переход

◐ пакет `Awaiting Validation`.  
○ Fresh-context Recovery Test.  
○ рабочий experiment `Project Overview → Publication Master → Coach Review → Role Exit → Scale Recovery`.

**СЕЙЧАС → провести ограниченную validation нового пакета; не запускать новый redesign Publication Master. Обычные VIA принадлежат Coach.**

---

# 7. NOTION / CONTENT INTELLIGENCE — 🟡

**Функция:** structured working memory и устойчивая содержательная память.

### Подтверждено

● Topics, Rubrics, Series, Human States и Relations существуют.  
● Notion ≠ production archive.  
● Human State ≠ Reader Theme ≠ Blogger Label ≠ Search Query.  
● selective enrichment подтверждён отдельным historical synchronization pass.  
● `VIA-2026-012–019 → Notion Content Intelligence` синхронизированы историческим консолидированным проходом.  
● GitHub / VIA удерживает material, evidence и process history; Notion — current substantive understanding.  
● не требуется переносить Draft, Reviews, Process Map, SEO package, Distribution packages и административную хронологию VIA.

### Promotion boundary

    raw evidence
          ↓
    candidate signal
          ↓
    Strategy interpretation
          ↓
    durable content intelligence
          ↓
        Notion

### Текущий переход

◐ `VIA-2026-020` выполняет первый live Content Intelligence Feedback Test.  
○ на Close определить `0–3` material signals либо `No material content-intelligence signal`.  
○ Strategy фильтрует candidate signal до durable knowledge.  
○ только durable knowledge получает exact Notion update.

### Граница

Новая архитектура feedback loop не требуется; ретроспективное обогащение всех карточек не запускается.

**СЕЙЧАС → завершить live feedback test внутри VIA-2026-020; сохранять feedback постепенным и избирательным.**

---

# 8. ДАЛЬНИЙ СОДЕРЖАТЕЛЬНЫЙ ГОРИЗОНТ — 🟡

**Функция:** видеть содержание дальше ближайшего Portfolio без превращения будущего в обязательный план.

> **Видеть дальше, чем планируем; планировать только то, что достаточно созрело.**

### Подтверждено

● дальний горизонт нужен и отличается от Portfolio.  
● отдельная тяжёлая knowledge-management architecture не нужна.  
● Strategic Snapshot существует.  
● второй Portfolio уже различает Near Publication Horizon и Far Development Horizon внутри реального Strategy cycle.  
● Far Development Horizon не считается Reserve и не создаёт обязательства реализации.

### Текущий переход

◐ проверить это различение через закрытие `Content Portfolio 2026-02`.  
○ проверить сохранение candidate signals без расширения ближайшей очереди.  
○ durable knowledge → Notion только после Strategy interpretation.

**СЕЙЧАС → удерживать Far Horizon как потенциал, не превращать его в production plan.**

---

# 9. CONTENT PORTFOLIO — 🟡

**Функция:** выбирать из пространства возможностей материалы, достаточно зрелые для развития.

### Доказано первым циклом EXP-001

● заранее выбранный буфер сохранял полезность несколько недель.  
● темы не требовали нового стратегического выбора внутри каждого VIA.  
● Portfolio Cards удерживали центральный вопрос, связь с корпусом, риски и readiness.  
● Reader и SEO давали разные типы evidence.  
● Owner мог запускать следующий VIA одной ссылкой на уже выбранную тему.  
● Notion оказался полезен как content memory, но не production tracker.

### Первый Portfolio

◐ последний активный item первого Portfolio — `VIA-2026-020`, «После сотого падения».  
○ после его закрытия первый publication queue практически завершает свой operational cycle.

### Второй Portfolio — `Content-Portfolio-2026-02`

● предварительный Strategist analysis завершён.  
● Near Publication Horizon и Far Development Horizon различены.  
● Strategy Draft завершён 12 сентября 2026.  
◐ следующий этап — Reader Review.  
○ SEO Review.  
○ Strategy Integration.  
○ Strategy Close.  
○ Closed Portfolio → Owner → Coach → VIA.

**СЕЙЧАС → довести второй Portfolio до Strategy Close без активации кандидатов до закрытия процесса.**

---

# 10. EDITORIAL SYSTEM / VIA — 🟡

**Функция:** проводить выбранный материал через достаточный редакционный цикл до стабильного Final Text и publication handoff.

### Устойчивый слой

● `VIA/README.md` → canonical VIA Operational Protocol.  
● VIA Protocol ≠ VIA Template ≠ Concrete VIA ≠ Role Documentation ≠ Development.  
● Process Map → canonical state authority.  
● Lifecycle Status отделён от Step Status.  
● Current Handoff → article-specific task.  
● Template → минимальный case-file skeleton.  
● Coach Workflow согласован с VIA logic.  
● Final Text Assembly отделён от Publication Package.  
● SEO Publication Package отделён от фактической Scheduled / Public Publication.  
● Close классифицирует material evidence и маршрутизирует его в существующие destinations.

### Live evidence

● `VIA-2026-018` завершён и дал первый live protocol evidence.  
● `VIA-2026-019` прошёл compressed independent Reviews, Coach Integration, Revision, targeted re-checks, Final Text Assembly и Publication Preparation; затем был передан в Blogger publication / scheduled state.  
● новый cycle показал, что selective re-check возможен без полного повторного Review.  
● one-link activation blocker был отдельно зафиксирован как evidence, а не скрыт.

### Активный VIA

◐ `VIA-2026-020 — После сотого падения`.  
● Portfolio → VIA / Editorial Brief завершён.  
● Longform Draft завершён.  
○ Theology / Reader / Literary Reviews.  
○ Coach Integrated Review.  
○ Revision / Finalization / Required Re-checks.  
○ Publication / Close.  
◐ параллельно — Live Content Intelligence Feedback Test.

**СЕЙЧАС → завершить VIA-2026-020 как последний item первого Portfolio; использовать его как production cycle и live feedback validation, а не как повод для нового redesign.**

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

**Функция:** превращать стабильный Final Text в фактически подготовленный и опубликованный материал.

### Подтверждено

● Publication Preparation существует.  
● SEO Publication Package существует.  
● Blogger preparation существует.  
● Scheduled / Public Publication отделена от Final Text Assembly.  
● несколько VIA прошли границу Editorial → Publication.

### Текущий переход

◐ `VIA-2026-020` должен пройти тот же реальный publication route.  
○ продолжать накапливать operational evidence без отдельного redesign.

**СЕЙЧАС → публикация является главным operational focus проекта.**

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

# 16. RESEARCH LAB — 🟢 capability / IP-001 🟡

**Функция:** производить проверяемое исследовательское знание независимо от заранее желаемого применения.

### Foundation

● Recovery CLOSED.  
● Methodological Normalization CLOSED.  
● Constitution v0.2 — Current / Active.  
● Methodology v0.3 — Current / Active.  
● Research Editor separation — READY.  
● durable source-of-truth хранит capability.  
● рабочие chat sessions могут быть заменяемыми.

### IP-001

● Protocol v0.2.  
● Primary Observation Output Contract v0.2.  
● attribution discipline.  
● calibration / controlled re-run evidence.  
◐ готовность к Full NT Corpus Research.

### Активность

⚪ capability готова, но текущий project-level priority — publication work.  
○ минимальный Research Editor launcher при возвращении.  
○ Full NT Corpus Research.  
○ Cross-corpus Verification / Broader NT Synthesis.

**СЕЙЧАС → не redesign Research Lab; сохранять готовность к re-entry и возвращаться к IP-001 после ближайшего publication block.**

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

## NOW — публикационный блок

    VIA-2026-020
          ↓
    Reviews / Revision / Publication
          ↓
    Close
          ↓
    Content Intelligence Feedback Test

Параллельно:

    Content Portfolio 2026-02
          ↓
    Reader Review
          ↓
    SEO Review
          ↓
    Strategy Integration
          ↓
    Strategy Close
          ↓
    Closed Portfolio → Owner → Coach → next VIA

## NEXT — validation без нового redesign

    Publication Master v0.1 Candidate
          ↓
    Fresh-context Recovery Test
          ↓
    real handoff experiment
          ↓
    Role Exit / Scale Recovery evidence

И:

    Project Overview
          ↓
    следующий material Parallel Branch Convergence
          ↓
    repeatability evidence

## MAINTAIN / EXPERIMENT

    Telegram
      → lightweight channel production

    Facebook
      → experimental native formats
      → comparative evidence

    Notion
      → selective live feedback only

## PAUSED / WATCH

    Research Lab / IP-001
      → ready for re-entry after publication block

    Book
      → dependency on Research evidence

    External Orchestrator
      → paused until workload / economics justify return

    Взгляд
      → preserve concept, no production system

---

# 23. ГЛАВНЫЙ ПЕРЕХОД ПРОЕКТА

Предыдущий период:

> **восстановить → различить → спроектировать → нормализовать capability**

Текущий период:

> **публиковать → использовать созданные capabilities → наблюдать → получить evidence → закрыть цикл → сохранить только подтверждённое learning**

Главный риск следующего этапа:

> продолжать улучшать внутреннюю архитектуру быстрее, чем проект использует уже созданные capabilities.

Главный operational приоритет:

> **закрыть первый Portfolio через VIA-2026-020 и одновременно подготовить следующий закрытый Portfolio, не создавая между циклами новый слой архитектуры.**

Главный критерий:

> **Новая документация должна возникать из доказанной рабочей необходимости, а не из желания сделать систему административно завершённой.**
