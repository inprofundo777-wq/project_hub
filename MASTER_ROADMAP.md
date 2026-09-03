# In Profundo — Development Map

**Тип:** Living Development Map  
**Статус:** 🟢 Active Working Map  
**Актуально:** 2026-09-03  
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
              │                          взгляд на проект сверху
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
                       │         ├── Additional / Modular Editorial 🟡
                       │         │
                       │         └── System Learning ◐
                       │
                       ▼
               CONTENT STRATEGY
                       🟡
                       │
                Development Horizon
                       ◐
                       │
                       ▼
                    PORTFOLIO
                       │
                       ▼
                  EDITORIAL
                       │
                       ▼
                 PUBLICATION
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

Owner находится в вершине карты, но не должен становиться ручным интегратором всех потоков evidence.

### Устойчивое понимание

● Owner определяет направление.  
● Owner утверждает существенные стратегические решения.  
● Owner не обязан лично интегрировать весь Research / Search / VIA / DIST evidence.  
● ясная задача может идти непосредственно в соответствующую capability.  
● Master не является обязательным gate.  
● Project Overview не является supervisor систем.

### Новый критерий

Если система работает только потому, что Owner вручную помнит и соединяет:

- Notion;
- Research;
- Search;
- VIA;
- DIST;
- Books;
- Audience Evidence,

то соответствующая integration capability ещё не доказана.

---

# 4. FUNDAMENTAL LAYER — 🟡

**Функция:** удерживать идентичность, границы, authority и фундаментальную архитектуру проекта.

### Подтверждено

● DNA rev 3.1 — active foundation.  
● ARC-001 — approved architectural map / provenance.  
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

Их функции пока не доказаны достаточно, чтобы заполнять преждевременно.

**СЕЙЧАС → фундаментальный корпус ещё формируется; локальные системы не должны незаметно создавать project-wide authority.**

---

# 5. 🗺 PROJECT OVERVIEW & CONTINUITY — 🟡

**Ответственная роль:** Project Overview & Continuity Partner.

**Функция:**

> **Owner directs spotlight; Project Overview preserves the map of the whole scene.**

### Capability

● SEE.  
● ASSESS.  
● CONNECT.  
● REMEMBER.  
● SNAPSHOT.  
● PRIORITIZE — показывать tradeoffs, не принимать решение за Owner.  
● ROUTE.  
● REVIEW FROM ABOVE.

### Различение с Master

> **Master помогает Owner понять, что делать с неопределённостью.**

> **Project Overview помогает Owner не потерять целое.**

Master работает в глубину неопределённости.

Project Overview работает в ширину проекта и continuity.

### Развитие

● role recovery проведён.  
● Operating Model восстановлен.  
● Project Map восстановлен.  
● Decision Memory восстановлена.  
● Development восстановлен.  
● Recovery Snapshot сохранён в GitHub.  
◐ роль проходит дальнейшую live normalization через реальную работу.  
○ normalization review после достаточного нового evidence или появления фундаментальной архитектуры.

**СЕЙЧАС → удерживать общую карту без превращения роли в project manager или параллельного Master.**

---

# 6. MASTER — 🟡

**Функция:** интеллектуальный партнёр Owner там, где идея, проблема или возможность ещё недостаточно ясны для передачи конкретной системе.

### Подтверждено

● Master ≠ постоянный supervisor Article Lifecycle.  
● Coach владеет production cycle.  
● Master возвращается при системной неопределённости.  
● Observation → Distinction → Interpretation → Decision.  
● symptom ≠ problem level.  
● practice before normativity.  
● Transfer Threshold сформирован.  
● Decision Memory существует.  
● Master package существует.

### Недавнее evidence

● Architecture Red Team по Strategic Content Horizon.  
● подтверждена способность не только создавать решение, но и **останавливать преждевременную архитектуризацию**.

Ключевой verdict:

> **Не каждая полезная capability требует новой системы.**

### Следующий переход

◐ live validation роли на системных вопросах.  
○ permanent normalization после достаточного evidence.

**СЕЙЧАС → использовать Master при реальной неопределённости, а не как обязательный этап каждого процесса.**

---

# 7. NOTION / CONTENT INTELLIGENCE — 🟡

**Функция:** structured working memory и Content Intelligence.

Notion не является production archive.

GitHub не заменяет Notion как живую содержательную карту.

### Основные объекты

● Topics.  
● Rubrics.  
● Series.  
● Human States.  
● Relations между ними.

### Устойчивые различения

● Human State ≠ Reader Theme.  
● Reader Theme ≠ Blogger Label.  
● Blogger Label ≠ Search Query.  
● Notion informs Portfolio.  
● Portfolio chooses.  
● VIA produces.  
● Distribution returns evidence.

### Новое понимание последних дней

> **Evidence может жить в разных системах. Устойчивая content memory должна оставаться одной — в Notion.**

Promotion boundary:

    raw evidence
          ↓
    candidate signal
          ↓
    Strategy interpretation
          ↓
    durable content intelligence
          ↓
        Notion

Не каждое наблюдение должно становиться Topic Card.

Не каждое learning должно возвращаться в Content Intelligence.

### Selective Enrichment

● признан принцип selective enrichment.

Связи и properties усиливаются прежде всего там, где тема:

- вошла в активный корпус;
- влияет на Portfolio;
- получила значимый Research / Search evidence;
- влияет на реальные решения.

> **Зрелость Content Intelligence определяется не полнотой заполнения полей, а качеством решений, которые она позволяет принимать.**

### Главный gap

◐ feedback loop после реальной работы.  
◐ quality of interpretation.  
◐ promotion boundary должен пройти capability test.

**СЕЙЧАС → не redesign Notion; проверить feedback loop на ближайших Portfolio / VIA / DIST.**

---

# 8. STRATEGIC CONTENT HORIZON — 🟡

**Функция:** видеть содержание дальше ближайшего Portfolio без преждевременного превращения будущего в план.

Главная формула:

> **In Profundo нужен не столько дальний план, сколько дальний взгляд.**

> **Видеть дальше, чем планируем; планировать только то, что достаточно созрело.**

### Устойчивое понимание

● дальний горизонт нужен.  
● он отличается от Content Portfolio.  
● он работает с возможностями, а не обязательствами.  
● видимое направление ещё не является решением его развивать.  
● отдельная тяжёлая knowledge-management architecture не обоснована.

### Архитектурное решение

> **Development Horizon — не новый реестр, а временное стратегическое представление над существующей памятью и evidence.**

Источники:

    Notion
    Research
    Search / SEO
    Books
    Audience Evidence
    Published Content
    VIA / DIST learning
    Owner observations
          ↓
    Strategic Horizon

### Promotion

    Idea
      ↓
    emerging direction
      ↓
    strategic maturation
      ↓
    development decision
      ↓
    Portfolio / Research / other capability

### Capability Test

◐ ближайший Portfolio cycle.  
○ следующие 2–3 VIA / DIST как observation window.  
○ 0–3 post-close candidate content signals.  
○ Strategy filters signals.  
○ durable content knowledge → Notion.  
○ transient evidence остаётся в source system.  
○ проверить, что Owner не становится integration layer.

### Критерий redesign

Redesign оправдан только при повторяющейся точке отказа:

- signals теряются;
- Strategy не восстанавливает Horizon;
- Portfolio захватывает слишком дальний горизонт;
- Notion заполняется transient evidence;
- Owner регулярно интегрирует всё вручную.

**СЕЙЧАС → Capability Test, не redesign.**

---

# 9. CONTENT PORTFOLIO — 🟡

**Функция:** отделить пространство возможного содержания от решения, что действительно развивать следующим.

### Подтверждено

● Portfolio ≠ Notion.  
● Portfolio ≠ Development Horizon.  
● Portfolio является более близким strategic selection layer.  
● ближайшие темы переходят из пространства возможностей только после достаточного созревания.

### Новый контекст

Ближайший Portfolio становится естественным первым тестом Strategic Content Horizon.

Проверить:

◐ может ли Strategy прочитать Notion как дальний горизонт;  
○ какие направления действительно созрели;  
○ какие должны остаться дальними;  
○ какие Research / Search signals меняют выбор;  
○ требуется ли Owner вручную восстанавливать связи.

**СЕЙЧАС → ближайший Portfolio cycle должен стать capability test существующей модели.**

---

# 10. EDITORIAL SYSTEM — 🟡

**Основная process-role:** Coach.

**Функция:** проводить конкретный материал через production cycle.

### Подтверждено

● VIA существует как live production document.  
● Coach ведёт процесс.  
● Master постепенно вышел из регулярного Article Lifecycle.  
● selective review развивается.  
● несколько реальных VIA прошли через систему.  
● production capability существует.

### Текущая зона развития

◐ VIA продолжает накапливать лишнюю повторяющуюся техническую информацию.  
◐ один статус может повторяться в нескольких местах.  
◐ process map и технические инструкции частично дублируются между VIA.  
◐ редакторы возвращают не только judgment по материалу, но и system learning.

### Новое наблюдение

VIA сейчас производит два разных типа learning:

    VIA / Editor Review
            │
            ├── CONTENT LEARNING
            │       ↓
            │   Strategy
            │       ↓
            │   durable?
            │       ↓
            │     Notion
            │
            └── SYSTEM LEARNING
                    ↓
                capability evidence
                    ↓
                durable?
                    ↓
                permanent Editorial documentation

Это пока **наблюдение / capability-test hypothesis**, а не принятая новая архитектура.

### Возможный Close

На следующих VIA проверить:

- 0–3 Content Intelligence candidates;
- 0–3 System Learning candidates.

Не создавать заранее отдельный research document для каждого редактора.

Сначала установить:

> **Какая техническая информация действительно повторяется и нужна за пределами конкретного VIA?**

**СЕЙЧАС → проверить, может ли VIA становиться легче за счёт постепенного переноса доказанного system knowledge в permanent documentation.**

---

# 11. ADDITIONAL / MODULAR EDITORIAL SYSTEM — 🟡

**Функция:** сохранять полную capability редакторов, но вызывать только нужную часть в конкретном цикле.

Принцип:

> **Full Capability + Minimal Invocation**

### External Literary Editor

● historical capability recovery.  
● Self-Review.  
● historical calibration.  
● blind validation.  
● capability recovered.  
● Working Core captured.  
◐ live validation на реальной редакционной работе.  
○ permanent capability capture после достаточного evidence.

### Более широкая гипотеза

◐ Literary / Theology / Reader и другие capabilities потенциально могут вызываться модульно.  
○ возможна композиция нескольких modules в одном context.  
○ каждый judgment должен сохранять provenance и competence boundary.  
○ Coach / VIA определяет нужную комбинацию по risk/stage.

### Не принято

Модульная editorial architecture ещё не является permanent architecture.

**СЕЙЧАС → live validation recovered capabilities; permanent documentation после evidence.**

---

# 12. EDITORIAL SYSTEM LEARNING / PERMANENT CAPABILITY CAPTURE — 🟡

**Статус:** emerging capability / ещё не отдельная система.

Последние VIA показывают растущую потребность отделить:

> evidence конкретного цикла

от

> знания о том, как работает редактор или Editorial System вообще.

Рабочая гипотеза:

    Editor / VIA
        ↓
    technical observation
        ↓
    repeated / validated?
        ↓
    candidate system learning
        ↓
    capability interpretation
        ↓
    durable?
       │
       ├── нет → остаётся evidence
       └── да → permanent documentation

### Потенциальный результат

Permanent documents могут постепенно забирать из VIA:

- повторяющиеся technical instructions;
- proven review criteria;
- role boundaries;
- invocation rules;
- stable output contracts;
- repeated process knowledge.

### Ограничение

Не создавать сейчас новый слой документов для каждого редактора автоматически.

Сначала проверить повторяемость на реальных VIA.

**СЕЙЧАС → observation / capability test.**

---

# 13. PUBLICATION — 🟢

**Функция:** довести готовый материал до реальной публикации на существующих площадках.

### Подтверждено практикой

● Blogger.  
● Facebook.  
● Telegram.  
● platform-native adaptation.  
● visual production.  
● регулярные публикационные циклы возможны.

Publication capability не равна Distribution capability и не равна Audience acquisition.

---

# 14. DISTRIBUTION — 🟢

**Функция:** адаптировать и распространять материал через существующие каналы.

### Evidence

● DIST-001.  
● DIST-002.  
● Distribution Evidence Synthesis завершён.  
● production / adaptation capability доказана.  
● supply существующих каналов доказан.

### Не доказано

Distribution сама по себе не доказала:

- external reach;
- discovery;
- acquisition;
- meaningful exposure среди незнакомой релевантной аудитории.

### Новый feedback role

DIST потенциально возвращает:

- content signals;
- audience/discovery evidence;
- system learning.

Но после Close следует возвращать только небольшой объём candidate signals, а не весь поток наблюдений.

**СЕЙЧАС → использовать DIST как evidence source внутри Capability Test.**

---

# 15. BLOG ARCHITECTURE / NAVIGATION — 🟡

**Функция:** помочь человеку двигаться внутри уже найденного In Profundo.

Ключевое различение:

> **Distribution приводит человека к In Profundo.**

> **Navigation помогает ему двигаться внутри уже найденного In Profundo.**

### Limited Navigation Pilot

● проблема ограниченной тематической навигации выявлена.  
● гипотеза topic page сформирована.  
● Limited Navigation Pilot v0.1 создан.  
● реальная страница «Темы» опубликована.  
◐ период наблюдения / тестирования.  
○ собрать evidence использования.  
○ проверить влияние на related-content discovery / depth of navigation.  
○ решить: сохранить / изменить / расширить / отказаться.

### Ограничение

Не менять навигацию во время observation period без blocker.

Пока одного pilot недостаточно, чтобы выделять Blog Navigation в отдельную большую систему.

**СЕЙЧАС → наблюдение.**

---

# 16. AUDIENCE / DISCOVERY — 🟡

**Функция:** понять, встречается ли In Profundo с релевантной внешней аудиторией и что происходит после встречи.

### Подтверждено

● Discovery / Acquisition Capability Gap доказан.  
● meaningful exposure пока недостаточно.  
● публикация ≠ distribution.  
● distribution ≠ discovery.  
● discovery bottleneck как единственный primary constraint не доказан.

### Current stage

◐ Live Validation.  
○ собрать meaningful exposure.  
○ отделить:

    people don't encounter In Profundo

от

    people encounter it but don't find enough value

○ проверить value proposition внешним evidence.

**СЕЙЧАС → live validation, не преждевременный positioning redesign.**

---

# 17. RESEARCH LAB — 🟢

**Функция:** независимое дисциплинированное исследование Писания.

Research Lab теперь следует отличать от конкретного Research Project.

### Foundation — 🟢

● Constitution Research Lab v0.2.  
● Methodology v0.3.  
● research capability подтверждена.  
● Research отделён от Editorial / Publication.

Общее наследование:

    DNA In Profundo
          ↓
    Constitution Research Lab
          ↓
    Methodology Research Lab
          ↓
    Research Projects

### IP-001 — 🟡

**Scope:** Новый Завет.

● Research Question + Scope.  
● IP-001 Protocol.  
● Output Contract.  
● Attribution discipline.  
● Research Judgment model.  
● controlled methodological validation на Romans.

Важно:

> **Romans controlled re-run проверял исследовательскую систему. Он не означает завершённый normalized Romans corpus IP-001.**

### Основной путь IP-001

◐ protocol-normalized research.

Повторно пройти по final documents:

○ Деяния.  
○ Римлянам.  
○ 1 Коринфянам.  
○ 2 Коринфянам.

Для каждого corpus:

    Stage 0
      ↓
    Stage 1
      ↓
    Stage 2
      ↓
    Stage 3
      ↓
    Stage 4

Затем:

○ remaining New Testament corpus.  
○ Cross-corpus Verification.  
○ Broader New Testament Synthesis.

### Research Close

После полного исследования:

    Broader Synthesis
          │
          ├── System Review
          │       ↓
          │   Research Lab Development
          │
          └── Knowledge Transfer
                  ↓
             Book / Articles /
             Other Forms

System Review должен проверить:

- что работало;
- что упростить;
- что улучшить;
- что сохранить;
- какие lessons относятся ко всей Research Lab;
- какие специфичны IP-001.

### IP-002 — ⚪

Направление уже видно, но Research Project не активирован.

При запуске наследует Constitution + Methodology и создаёт собственные Protocol / Contracts / Outputs.

**СЕЙЧАС → Research Lab capability установлена; IP-001 находится в начале полного normalized NT research path.**

---

# 18. BOOKS — 🟡

## Book 1 — «Тот, Кто остаётся»

### Сформировано

● центральный вопрос.  
● метод наблюдения.  
● архитектура четырёх частей.  
● perceptual reader arc.  
● Part I–III conceptual architecture.  
● Part IV identified as evidence-sensitive.  
● workbook concept.  
● trilogy horizon.

### Dependency

    Book 1 / Part IV
          ⛓
       IP-001
          ↓
    sufficient research evidence
          ↓
      selective Book Transfer

Книга больше не ждёт восстановления Research Lab.

Она зависит от **зрелости research evidence**, если зависимость Part IV от IP-001 сохраняется.

Не зафиксировано заранее, что необходимо ждать полного NT Broader Synthesis.

### Trilogy horizon

Book 1 — увидеть.  
Book 2 — различить.  
Book 3 — жить.

Это conceptual horizon, а не production commitment.

### «Когда слова заканчиваются»

🟡 Existing Book Asset / Function Unknown.

○ recovery/current-state review.  
○ оценить quality / DNA fit.  
○ определить revision need.  
○ только затем решить ecosystem function.

**СЕЙЧАС → Book 1 удерживается до достаточного research evidence; второй book asset требует отдельного recovery review.**

---

# 19. ВЗГЛЯД — 🟡

**Рабочее определение:**

> **развивающаяся практическая лаборатория внимания и восприятия.**

### Сформировано

● исходная линия mobile photography → noticing → attention → ability to see.  
● направление шире фотографии.  
● центральная интуиция: способность видеть можно развивать.  
● намечены возможные ветви развития.

### Возможные ветви

- observation practice;
- mobile photography;
- visual literacy;
- everyday discoveries;
- person in gaze;
- spiritual attention without religious illustration;
- visual forms In Profundo;
- educational formats после созревания практики.

### Ограничение

Не строить заранее полную школу / курс / content stream.

### Следующий переход

◐ map of directions.  
○ smallest practical experiment.  
○ проверить упражнения без превращения направления в photo training.  
○ после существенного развития — новый Snapshot.

**СЕЙЧАС → exploration / mapping, без принудительной production integration.**

---

# 20. PROJECT MEMORY / CONTINUITY — 🟡

**Функция:** сохранять понимание, решения и возможность возвращения к направлениям без реконструкции всей истории.

### Основные инструменты

## 📸 Strategic Snapshot

> **Слепок хранит понимание.**

Историчен.

Не переписывается при каждом изменении.

Существенный milestone → новый generation snapshot.

## 🚦 Development Map

> **Карта развития хранит движение.**

Живая.

Обновляется при реальных переходах maturity / state / connections.

## 📡 Рабочая панель

> **Что делаем сейчас?**

Краткосрочная операционная картина.

Зрелость ≠ активность.

### Принцип

> **Write quickly; document slowly.**

---

# 21. SNAPSHOT STATE — 🟡

## Физически подтверждены в GitHub

### Project-level

● `In_Profundo_Strategic_Snapshot_2026-08-30.md`

### Audience / Discovery

● current strategic snapshot существует.

### Project Overview

● `Project_Overview_Role_Recovery_Snapshot_2026-08-31.md`

### Notion / Content Intelligence

● `Notion_Content_Intelligence_Strategic_Snapshot_2026-08-31.md`

### Books

● `Tot_Kto_Ostaetsya_Book_Project_Strategic_Snapshot_2026-08-31.md`

### Research Lab

● historical snapshot 2026-08-21.  
● new CURRENT snapshot 2026-09-01.

---

## Подготовлены, но в GitHub сейчас не обнаружены

### Strategic Content Horizon

◐ Snapshot подготовлен 2026-09-02.  
○ перенести в GitHub.

Он должен сохранить:

- происхождение вопроса дальнего планирования;
- Development Horizon;
- Notion as single durable content memory;
- promotion boundary;
- selective enrichment;
- Owner ≠ manual evidence integrator;
- Architecture Red Team;
- Capability Test на Portfolio + 2–3 VIA/DIST.

### Взгляд

◐ Snapshot draft подготовлен ранее.  
○ перенос в GitHub не подтверждён.

### Development Map Concept

◐ Concept Snapshot был подготовлен.  
○ перенос в GitHub не подтверждён.

Он сохраняет архитектуру самой Development Map:

- maturity markers;
- development steps;
- connections;
- Owner at vertex;
- Foundation + Project Overview;
- systems/capabilities;
- infrastructure/memory;
- distinction Development Map / Snapshot / Operational Panel.

---

## Пока не требует отдельного Snapshot

### External Literary Editor

Recovery + Working Core уже сохраняют необходимое evidence.

Новый Snapshot оправдан после существенного live-validation milestone.

### Distribution

Evidence Synthesis уже выполняет достаточную функцию continuity.

### Editorial System Learning

Пока только emerging observation.

Сначала capability test.

---

# 22. GITHUB / ARCHIVE / PERMANENT DOCUMENTATION — 🟡

**Функция:** durable source of truth для устойчивых артефактов проекта.

Ключевое различение:

> **ДОКУМЕНТАЦИЯ = как устроена и регулируется capability.**

> **АРХИВ = что проект сохранил как долговременный результат / evidence.**

GitHub не является интеллектуальным manager проекта.

### Подтверждено

● permanent-doc cycle используется.  
● Research Lab имеет собственную normalized documentation architecture.  
● Project Overview docs существуют.  
● Snapshots физически сохраняются в Continuity.  
● Books имеют отдельный repository.  
● Editorial System имеет собственный repository.

### Незавершённое

◐ permanent documentation corpus ещё не нормализован целиком.  
◐ часть подготовленных Snapshots остаётся вне GitHub.  
◐ Snapshot Index ещё не обновлён новым пакетом.  
○ POL-001 должен позднее формализовать Documents / Decisions / Archive / provenance.

### Важное решение

`Snapshot_Index.md` не обновлять по одному документу.

Сначала завершить текущий пакет слепков, затем провести одно пакетное обновление.

**СЕЙЧАС → закрыть gap между уже подготовленными и реально сохранёнными continuity artifacts; после этого обновить Snapshot Index одним проходом.**

---

# 23. LEGACY MASTER_ROADMAP — 🔴 как актуальная карта

Существующий `MASTER_ROADMAP.md` исторически полезен, но больше не соответствует фактической архитектуре проекта.

Он всё ещё строится вокруг:

- недельного publication cycle;
- идеи одного главного приоритета после закрытия публикаций;
- четырёхнедельного / трёхмесячного планирования тем;
- старого понимания Research Lab;
- старого понимания Editorial roles;
- смешения roadmap, operational panel, archive и strategic directions.

Он не должен использоваться как текущая Development Map.

Дальнейшее решение о его:

- архивировании;
- переименовании;
- сохранении как historical artifact;
- или замене ссылок

должно приниматься отдельно.

Не переписывать его автоматически только ради синхронизации.

---

# 24. ОСНОВНЫЕ FEEDBACK LOOPS

## Content Intelligence Loop

    Notion
      ↓
    Strategic Horizon
      ↓
    Portfolio
      ↓
    Editorial
      ↓
    Publication
      ↓
    Distribution
      ↓
    candidate signals
      ↓
    Strategy interpretation
      ↓
    durable content intelligence
      ↘
       Notion

---

## Editorial System Learning Loop

    VIA / Editor Review
          ↓
    technical observation
          ↓
    candidate system learning
          ↓
    repeated / validated?
          ↓
    durable capability knowledge
          ↓
    permanent Editorial documentation
          ↓
    lighter future VIA

---

## Research Lab Learning Loop

    Research Lab Foundation
          ↓
       IP-001
          ↓
    Full Research Cycle
          ↓
    System Review
          ↕
    Research Lab Development

---

## Research → Knowledge Transfer

    IP-001
      ↓
    Broader Synthesis
      ↓
    Application Selection
      ├── Book
      ├── Articles
      ├── Educational use
      └── Other forms

---

## Audience Feedback Loop

    Publication / Distribution / Navigation
                  ↓
            Reader Exposure
                  ↓
          Audience Evidence
                  ↓
               Strategy
                  ↓
        durable Content Intelligence
                  ↓
                Notion

---

# 25. ГЛАВНЫЕ ТЕКУЩИЕ ПЕРЕХОДЫ

## 🟡 1. Fundamental Layer

Constitution 1.0 → foundational corpus.

## 🟡 2. Strategic Content Horizon

Architecture clarified → **Capability Test**.

## 🟡 3. Notion / Content Intelligence

Static structure → **selective feedback loop**.

## 🟡 4. Portfolio

Selection mechanism → **first Development Horizon capability test**.

## 🟡 5. Editorial System

VIA as accumulating container → **distinguish cycle evidence from durable system knowledge**.

## 🟡 6. Additional Editorial

Recovered capability → **live validation → permanent capability capture**.

## 🟡 7. Blog Navigation

Topic page created → **observation evidence**.

## 🟡 8. Audience / Discovery

Internal maturity → **meaningful external validation**.

## 🟢 / 🟡 9. Research

Research Lab capability established → **IP-001 full normalized NT research**.

## 🟡 10. Books

Book architecture → **sufficient research evidence → selective Book Transfer**.

## 🟡 11. Continuity

Multiple recovered understandings → **complete snapshot package → batch Snapshot Index update**.

---

# 26. ЧТО ОСОБЕННО ИЗМЕНИЛОСЬ ЗА ПОСЛЕДНИЕ ДНИ

Несколько направлений начали сходиться в одну более зрелую картину.

## 1. Research Lab перестал быть проблемой восстановления

Раньше вопрос был:

> «Работоспособна ли вообще Research Lab?»

Теперь:

> **Research Lab capability существует; IP-001 должен пройти реальное полное исследование.**

Это переносит dependency книги с системы Research Lab на зрелость конкретного research evidence.

---

## 2. Notion получил более точную границу

Notion больше не выглядит просто как «база тем».

Он становится единой durable content memory.

Но именно поэтому в него нельзя возвращать весь evidence.

Нужен promotion boundary.

---

## 3. Дальний контент перестал выглядеть как будущий roadmap

Вместо новой системы долгосрочного планирования появилась capability:

> **Development Horizon.**

Она должна быть transient strategic view, а не новым реестром.

---

## 4. Portfolio становится первым реальным тестом новой связности

Ближайший Portfolio должен показать, может ли Strategy:

- прочитать Notion;
- увидеть дальние направления;
- учесть Research / Search evidence;
- отделить дальнее от ближайшего;
- передать созревшее дальше без новой архитектуры.

---

## 5. VIA начинает показывать второй тип feedback

До сих пор внимание было прежде всего к содержательному learning.

Теперь видно, что VIA и редакторы производят ещё и:

> **evidence о самой Editorial System.**

Если это подтвердится, permanent documentation сможет постепенно вытеснять повторяющуюся техническую информацию из VIA.

---

## 6. Documentation начинает формироваться из практики

External Literary recovery, Research Lab normalization и VIA observations показывают общий паттерн:

> **сначала capability / практика / evidence → затем permanent capability capture.**

Не наоборот.

Это не следует пока превращать в универсальный норматив проекта, но паттерн становится всё заметнее.

---

# 27. СЕЙЧАС

Главная картина на 2026-09-03:

    FOUNDATION
       ◐

    PROJECT OVERVIEW
       ◐ live normalization

    MASTER
       ◐ system-level live use

    NOTION / CONTENT INTELLIGENCE
       ◐ feedback loop

    STRATEGIC HORIZON
       ◐ capability test

    PORTFOLIO
       ◐ nearest real test

    EDITORIAL
       ◐ system-learning distinction

    ADDITIONAL EDITORIAL
       ◐ live validation

    PUBLICATION
       ●

    DISTRIBUTION
       ● capability
       ◐ evidence return

    BLOG NAVIGATION
       ◐ observation

    AUDIENCE / DISCOVERY
       ◐ external validation

    RESEARCH LAB
       ● capability established

    IP-001
       ◐ full normalized research

    BOOK 1
       ⛓ research evidence

    ВЗГЛЯД
       ◐ exploration

    CONTINUITY
       ◐ snapshot package completion

    GITHUB / PERMANENT DOCUMENTATION
       ◐ normalization

---

# 28. БЛИЖАЙШАЯ СВЯЗКА, КОТОРУЮ СТОИТ НАБЛЮДАТЬ

Не один изолированный проект, а реальная цепочка:

    NOTION
      ↓
    STRATEGY / DEVELOPMENT HORIZON
      ↓
    PORTFOLIO
      ↓
    VIA
      ↓
    PUBLICATION
      ↓
    DIST
      ↓
    CLOSE
      │
      ├── Content candidate signals
      │       ↓
      │    Strategy
      │       ↓
      │    durable?
      │       ↓
      │     Notion
      │
      └── System Learning candidates
              ↓
         capability review
              ↓
         repeated / durable?
              ↓
         permanent documentation

Эта цепочка одновременно проверит:

- Strategic Horizon;
- Notion feedback loop;
- Portfolio selection;
- VIA Close;
- DIST evidence return;
- Owner load;
- Editorial System Learning;
- необходимость или ненужность новой архитектуры.

---

# 29. КРИТЕРИЙ СЛЕДУЮЩЕГО АРХИТЕКТУРНОГО ШАГА

Следующее изменение системы не должно появляться потому, что:

> «Можно сделать ещё лучше».

Оно должно отвечать повторяющемуся evidence:

> **Где существующая система реально теряет способность увидеть, интерпретировать, передать или сохранить важное знание?**

Только после обнаружения такой точки:

1. определить failure;
2. проверить повторяемость;
3. найти минимальное изменение;
4. только затем рассматривать новую сущность или redesign.

---

# 30. ИТОГОВАЯ КАРТИНА

In Profundo сейчас уже не выглядит как один editorial pipeline.

Это экосистема нескольких capabilities разной зрелости.

Owner удерживает направление.

Fundamental Layer удерживает границы.

Project Overview удерживает целое.

Master работает с неопределённостью.

Notion удерживает durable content memory.

Strategy смотрит дальше ближайшего решения.

Portfolio выбирает, что действительно развивать.

Editorial производит и одновременно начинает возвращать system evidence.

Publication и Distribution доводят материал до реального мира.

Audience / Discovery проверяет встречу с внешним читателем.

Research Lab производит независимое знание.

Books используют только релевантную часть этого знания.

Взгляд развивается как отдельная лаборатория внимания.

GitHub удерживает durable artifacts.

Snapshots сохраняют понимание.

Development Map сохраняет движение.

Главный принцип текущей стадии:

> **Не строить новую систему там, где сначала можно проверить capability существующей.**

И второй:

> **Evidence может жить в разных системах. Durable knowledge должно возвращаться туда, где ему действительно место.**

И третий:

> **Практика производит evidence. Evidence постепенно производит устойчивую документацию.**
