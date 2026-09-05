# In Profundo — Development Map

**Тип:** Living Development Map  
**Статус:** 🟢 Active Working Map  
**Актуально:** 2026-09-05  
**Назначение:** карта зрелости, движения и связей основных capabilities In Profundo

---

# 1. Как читать карту

Development Map отвечает на три вопроса:

> **Что уже существует?**

> **Насколько каждая capability способна выполнять свою функцию?**

> **Какой следующий переход должен быть доказан практикой?**

Она не является:

- календарём публикаций;
- списком всех задач Owner;
- стратегическим Snapshot;
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

Зрелость и активность — разные координаты.

Capability может быть 🟢 и находиться на паузе.

Capability может быть 🟡 и активно развиваться.

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
              │                                   │
              └─────────────────┬─────────────────┘
                                │
                                ▼
                    SYSTEMS / CAPABILITIES
                                │
       ┌──────────────┬─────────┼──────────┬──────────────┐
       ▼              ▼         ▼          ▼              ▼
    MASTER          NOTION   EDITORIAL   RESEARCH       BOOKS
      🟡              🟡        🟡          🟢             🟡
                       │         │           │              │
                       │         │           └─────⛓───────┘
                       │         │
                       │         └── Additional / Modular Editorial 🟡
                       │
                       ▼
               CONTENT STRATEGY
                       🟡
                       │
                дальний горизонт
                       🟡
                       │
                       ▼
                    PORTFOLIO
                       🟡
                       │
                       ▼
                  EDITORIAL
                       │
                       ▼
                 PUBLICATION
                       🟢
                       │
              ┌────────┴────────┐
              ▼                 ▼
        DISTRIBUTION       BLOG NAVIGATION
            🟢                 🟡
              │                 │
              └────────┬────────┘
                       ▼
              AUDIENCE / DISCOVERY
                       🟡
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
● Master не является обязательным gate.  
● Project Overview не является supervisor систем.  
● Owner не должен становиться ручным integration layer между системами.

**Критерий развития:**

> Если capability работает только потому, что Owner вручную помнит и соединяет её части, capability ещё не полностью доказана.

---

# 4. FUNDAMENTAL LAYER — 🟡

**Функция:** удерживать идентичность, authority и фундаментальную архитектуру проекта.

### Подтверждено

● DNA rev 3.1.  
● ARC-001.  
● различены Constitution / Framework / Policy / Workflow.  
● определено направление первого нормативного корпуса.

### В развитии

◐ Constitution 1.0.  
○ FRM-001 Architecture and Authority Framework.  
○ POL-001 Documents, Decisions and Archive Policy.  
○ FRM-002 Research, Scripture and Editorial Integrity Framework.  
○ WF-001 Fundamental Decision Workflow.  
○ REG-001 Transfer Register.  
○ POL-002 Automation and Tool Governance Policy — позже.

### Placeholder layer

⚪ Core_Principles.  
⚪ Editorial_Philosophy.  
⚪ Language.  
⚪ Mission.

**СЕЙЧАС → фундаментальный корпус формируется; не ускорять документацию только ради административной завершённости.**

---

# 5. PROJECT OVERVIEW & CONTINUITY — 🟡

**Функция:**

> Owner directs spotlight; Project Overview preserves the map of the whole scene.

### Подтверждено

● role recovery.  
● Operating Model.  
● Project Map.  
● Decision Memory.  
● Development.  
● Recovery Snapshot.  
● Snapshot package собран.  
● Snapshot Index нормализован.  
● Development Map создана.  
● различены Snapshot / Development Map / Operational Panel / Decision Memory / Permanent Documentation.

### Текущий переход

◐ live normalization через реальную работу.  
● отдельный список «Созревшие ветки» признан ненужным; material change остаётся trigger для Snapshot review.  
● stale continuity claims по Notion / Book сняты на current-navigation уровне.  
○ normalization review только после нового существенного evidence.

**СЕЙЧАС → удерживать карту и закрывать continuity debt без превращения роли в project management system.**

---

# 6. MASTER — 🟡

**Функция:** работа с системной и стратегической неопределённостью до Transfer Threshold.

### Подтверждено

● Master ≠ постоянный supervisor Article Lifecycle.  
● Coach владеет production cycle.  
● Observation → Distinction → Interpretation → Decision.  
● symptom ≠ problem level.  
● practice before normativity.  
● Transfer Threshold.  
● Decision Memory.  
● способность остановить преждевременную архитектуризацию.

### Недавнее evidence

● Strategic Content Horizon Architecture Red Team.  
● VIA Integration Gap Architecture Review.  
● доказано, что отдельная `System Learning capability` не требуется.  
● VIA learning маршрутизируется через существующую архитектуру.

### Текущий переход

◐ live validation на реальных системных вопросах.  
○ permanent normalization после достаточного evidence.

**СЕЙЧАС → использовать Master там, где существует реальная неопределённость, а не как обязательный этап.**

---

# 7. NOTION / CONTENT INTELLIGENCE — 🟡

**Функция:** structured working memory и устойчивая содержательная память.

### Подтверждено

● Topics.  
● Rubrics.  
● Series.  
● Human States.  
● Relations.  
● Notion ≠ production archive.  
● Human State ≠ Reader Theme ≠ Blogger Label ≠ Search Query.  
● selective enrichment.

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

◐ feedback loop после реальной работы.  
◐ quality of interpretation.  
◐ promotion boundary через Portfolio / VIA / DIST.

**СЕЙЧАС → не redesign Notion; проверять способность возвращать durable knowledge из реальных циклов.**

---

# 8. ДАЛЬНИЙ СОДЕРЖАТЕЛЬНЫЙ ГОРИЗОНТ — 🟡

**Функция:** видеть содержание дальше ближайшего Portfolio без превращения будущего в обязательный план.

> **Видеть дальше, чем планируем; планировать только то, что достаточно созрело.**

### Подтверждено

● дальний горизонт нужен.  
● отличается от Portfolio.  
● работает с возможностями, а не обязательствами.  
● отдельная тяжёлая knowledge-management architecture не нужна.  
● Strategic Snapshot создан.

### Текущий переход

◐ capability test через ближайший Portfolio и реальные VIA / DIST cycles.  
○ проверить сохранение candidate signals.  
○ проверить Strategy filtering.  
○ durable knowledge → Notion.  
○ проверить, что Owner не становится integration layer.

**СЕЙЧАС → наблюдение практики, не redesign.**

---

# 9. CONTENT PORTFOLIO — 🟡

**Функция:** выбирать из пространства возможностей материалы, достаточно зрелые для развития.

### Подтверждено

● Portfolio ≠ Notion.  
● Portfolio ≠ дальний горизонт.  
● Portfolio отделяет possibility от development decision.  
● Portfolio передаёт закрытые upstream decisions в VIA.

### Открытый operational gap

◐ стратегическая capability существует, но простая видимая очередь уже выбранных материалов пока не имеет устойчивого места.

Нужно различить:

> Portfolio = что решено развивать.

> Publication / Production Map = что из уже выбранного сейчас движется через производство и публикацию.

○ проверить необходимость минимальной видимой карты без создания второго Portfolio.

**СЕЙЧАС → использовать Portfolio в реальном цикле и отдельно решить visibility gap.**

---

# 10. EDITORIAL SYSTEM / VIA — 🟡

**Функция:** проводить выбранный материал через достаточный редакционный цикл до стабильного Final Text.

### Новый устойчивый слой

● `VIA/README.md` → canonical VIA Operational Protocol.  
● VIA Protocol ≠ VIA Template ≠ Concrete VIA ≠ Role Documentation ≠ Development.  
● Process Map → canonical state authority.  
● Lifecycle Status отделён от Step Status.  
● Active Handoff → article-specific task.  
● Template → минимальный case-file skeleton.  
● Coach Workflow согласован с новой VIA logic.  
● Learning не является отдельной capability.  
● Close классифицирует material evidence и маршрутизирует его в существующие destinations.

### Production distinction

● Final Text Assembly отделён от Publication Package.  
● SEO / Publication Package отделён от фактической Scheduled / Public Publication.

### Validation

◐ `VIA-2026-018` проходит первый live validation новой VIA architecture.  
○ довести VIA-018 до Final Close.  
○ следующий новый VIA проверить на чистом Template.  
○ после validation определить стабильность Protocol / Template.

**СЕЙЧАС → завершить VIA-2026-018 и наблюдать реальную работу новой VIA architecture.**

---

# 11. EXTERNAL / ADDITIONAL EDITORIAL CAPABILITIES — 🟡

### External Literary Editor

● Recovery завершён.  
● capability восстановлена достаточно для live work.  
● Working Core сохранён.  
● Role Redesign не требуется.  
◐ live validation через реальные материалы.  
○ permanent role documentation после достаточного evidence.

Пока permanent documentation отсутствует, используется переходный minimal launcher:

> Working Core = capability.  
> VIA = конкретная задача и material context.

В `VIA-2026-018` capability вызывается селективно в режиме final literary polish / control без переоткрытия структуры.

### Modular Editorial

🟡 Full Capability + Minimal Invocation остаётся рабочей гипотезой.

○ проверять композицию capabilities только практикой.  
○ не создавать модульную архитектуру преждевременно.

---

# 12. PUBLICATION — 🟢

**Функция:** превращать стабильный Final Text в фактически подготовленный и опубликованный материал.

### Подтверждено

● Publication Preparation существует.  
● SEO publication package существует.  
● Blogger preparation существует.  
● Scheduled / Public Publication отделена от Final Text Assembly.

### Текущий переход

◐ проверить новую границу Editorial → Publication на VIA-018.  
○ накопить evidence нескольких циклов.

**СЕЙЧАС → использовать capability, а не redesign.**

---

# 13. DISTRIBUTION — 🟢

**Функция:** адаптировать и распространять опубликованный материал по каналам.

### Подтверждено

● platform-native adaptation.  
● production capability.  
● FB / TG distribution practice.  
● DIST evidence.

### Не доказано

○ устойчивый external reach.  
○ acquisition.  
○ meaningful exposure среди релевантных незнакомых людей.

**СЕЙЧАС → использовать Distribution как действующую capability и источник evidence.**

---

# 14. BLOG ARCHITECTURE / NAVIGATION — 🟡

**Функция:** помочь уже пришедшему читателю двигаться внутри корпуса In Profundo.

● Navigation ≠ Distribution.  
● публичная страница «Темы» существует как real pilot.  
◐ usefulness observation.  
○ следующий structural decision только после evidence.

**СЕЙЧАС → наблюдать, не расширять архитектуру преждевременно.**

---

# 15. AUDIENCE / DISCOVERY — 🟡

**Функция:** понять, встречается ли In Profundo с релевантными незнакомыми людьми и что происходит при этой встрече.

### Подтверждено

● internal maturity ≫ external validation.  
● publication ≠ distribution.  
● distribution ≠ discovery.  
● Discovery / Acquisition Capability Gap существует.  
● Discovery как primary project constraint пока не доказан.

### Текущий переход

◐ live validation.  
○ meaningful exposure.  
○ различить encounter problem и value problem.  
○ получить достаточный external evidence.

**СЕЙЧАС → evidence before positioning conclusions.**

---

# 16. RESEARCH LAB — 🟢

**Функция:** производить проверяемое исследовательское знание независимо от заранее желаемого применения.

### Foundation

● Recovery CLOSED.  
● Methodological Normalization CLOSED.  
● Constitution v0.2 — Current / Active.  
● Methodology v0.3 — Current / Active.  
● Research Editor separation — READY.  
● durable source-of-truth хранит capability.  
● рабочие chat sessions могут быть заменяемыми.

### IP-001 — 🟡

**Вопрос:**

> Какие действия Новый Завет непосредственно приписывает воскресшему Иисусу Христу после Его Вознесения?

● Protocol v0.2.  
● Primary Observation Output Contract v0.2.  
● attribution discipline.  
● calibration / controlled re-run evidence.  
◐ готовность к Full NT Corpus Research.

### Следующий operational переход

○ создать минимальный launcher для replaceable Research Editor sessions.  
◐ начать Full NT Corpus Research.  
○ Stage 0–4 по корпусу.  
○ Cross-corpus Verification.  
○ Broader NT Synthesis.

**СЕЙЧАС → переход от проектирования Research Lab к реальному IP-001 research.**

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

**СЕЙЧАС → не подменять исследование заранее желаемым выводом книги.**

---

# 18. ВЗГЛЯД — 🟡

**Функция:** практическая лаборатория внимания и восприятия.

● направление различено.  
● первый Strategic Snapshot существует.  
● photography признана возможным входом, но не определением направления.  
● practice before architecture.

◐ ожидание реальной практики.  
○ smallest meaningful experiment при естественном окне.

**СЕЙЧАС → не превращать направление в курс, школу или production system до практического evidence.**

---

# 19. PROJECT MEMORY / CONTINUITY — 🟡

### Подтверждено

● Snapshot package собран.  
● Snapshot Index синхронизирован.  
● CURRENT / CURRENT PROJECT BASELINE / CONCEPT / RECOVERY / HISTORICAL различены.  
● Development Map существует.  
● Operational Panel имеет отдельную функцию.  
● Decision Memory имеет отдельную функцию.

### Правило

> **Слепок хранит понимание.**

> **Карта развития хранит движение.**

> **Рабочая панель хранит текущее действие.**

● отдельный постоянный список «Созревшие ветки» не требуется.

### Текущий переход

◐ поддерживать current navigation без переписывания historical state.  
○ новый Snapshot только после material change.

---

# 20. GITHUB / ARCHIVE / PERMANENT DOCUMENTATION — 🟡

**Функция:** durable source-of-truth проекта.

● GitHub является permanent archive / source-of-truth.  
● старый Master Roadmap архивирован как `ARH-001-MASTER_ROADMAP.md`.  
● текущий `MASTER_ROADMAP.md` является Living Development Map.  
● permanent-doc cycle сформирован.

### Осталось

◐ archive hygiene.  
○ при накоплении архивных roadmap решить, нужен ли отдельный `Archive` / `Roadmap-Archive`.  
○ провести selective sweep устаревших experimental / pilot / development documents.

**СЕЙЧАС → не создавать архивную инфраструктуру ради одного файла; закрывать только реальные stale states.**

---

# 21. Ближайший горизонт

## СЕЙЧАС

    VIA-2026-018
          ↓
    Final Close
          ↓
    VIA v2 live validation

## После VIA-018

    старые VIA
        +
    открытые Pilots
        +
    Experimental / Development docs
        ↓
    selective closure sweep
        ↓
    KEEP / CLOSE / ARCHIVE / STILL ACTIVE

Цель sweep:

> не переписать историю, а убрать ложные открытые состояния и установить, какие вопросы уже получили ответ практикой.

## Следующая новая работа

    Research Lab 🟢
          ↓
    Research Editor launcher
          ↓
    IP-001 Full NT Corpus Research

Параллельно:

    Portfolio
       ↓
    проверить visibility gap
       ↓
    минимальная карта уже выбранных материалов?
       ↓
    VIA / Publication

И:

    Distribution
       ↓
    meaningful exposure
       ↓
    Audience / Discovery evidence

---

# 22. Главный переход проекта

Предыдущий период:

> **восстановить → различить → спроектировать → нормализовать capability**

Ближайший период всё больше становится:

> **использовать → наблюдать → получить evidence → закрыть цикл → сохранить только подтверждённое learning**

Главный риск следующего этапа:

> продолжать улучшать внутреннюю архитектуру быстрее, чем проект использует уже созданные capabilities.

Главный критерий:

> **Новая документация должна возникать из доказанной рабочей необходимости, а не из желания сделать систему административно завершённой.**
