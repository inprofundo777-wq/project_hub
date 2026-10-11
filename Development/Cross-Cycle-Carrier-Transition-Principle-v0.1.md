# Cross-Cycle Carrier Transition Principle v0.1

**Статус:** DISCUSSION DRAFT / CROSS-CYCLE COMPARISON  
**Дата:** 11 октября 2026  
**Steward:** Project Overview  
**Нормативный статус:** ненормативный project-level candidate; не изменяет существующие системы, роли или authority  
**Основание:** реальный Cross-System Formation case + сравнительная проверка Brainstorm, VIA, Content Portfolio, Research и Book/long-form dependency

> Цель документа — проверить, является ли обнаруженный в Brainstorm принцип локальной особенностью или общим правилом пересечения границ рабочих циклов In Profundo.

---

# 1. Вопрос проверки

Рабочая гипотеза:

> Работа не обязана оставаться внутри process carrier, в котором она началась. Если в ходе действующего цикла возникает самостоятельный объект или вопрос, требующий собственного набора участников, состояний, outputs, verification, synthesis или Owner gate, текущий carrier должен проверить, остаётся ли он достаточным. Если нет — требуется явный carrier transition.

Проверка проводится не для унификации внутренних workflow. VIA, Portfolio, Research, Brainstorm и Book могут сохранять разную архитектуру.

Проверяется только возможное общее ядро перехода:

    DETECT
    → CLASSIFY
    → HOLD / CLOSE / ESCALATE PARENT
    → OPEN APPROPRIATE CARRIER
    → PIN DEPENDENCY / VERSION
    → EXECUTE
    → ACCEPT RESULT
    → RETURN / RESUME / CLOSE PARENT

---

# 2. Что такое cycle carrier в этой проверке

Cycle carrier — канонический рабочий объект, который позволяет восстановить как минимум:

- что сейчас происходит;
- какое состояние действительно;
- кто имеет активное задание;
- какие inputs обязательны;
- какие решения уже закрыты;
- где сохраняется значимый output;
- что является completion condition;
- куда возвращается результат;
- где находится следующий Owner gate.

Carrier не обязан содержать все outputs физически внутри одного файла. Он может ссылаться на отдельные artifacts, если их принадлежность, версия, состояние и return route однозначны.

---

# 3. Cross-cycle comparison

## 3.1. Brainstorm

### Нормальное внутреннее развитие

BR-001 показал модель, где несколько участников работают в одном living brainstorm: центральный вопрос, stages, Living Map, append-only findings, handoff и Owner gate остаются в одном carrier.

### Boundary trigger

Cross-System Formation породил отдельный `Formation Frame`, который стал предметом нового многоучастникового reasoning: Publication consultation, Lead consultation, Auditor consultation, synthesis и отдельный Owner gate.

### Что произошло

Новый объект получил отдельные durable artifacts, но новый carrier не был открыт. Substantive assignment частично переносился через installation prompts новых веток и Owner handoff.

### Кандидатный переход

    Brainstorm Round 1
    → Frame / самостоятельный вопрос
    → CLOSE / ESCALATE
    → Brainstorm Round 2 carrier
    → consultations
    → synthesis
    → Owner gate

### Вывод

**Подтверждает гипотезу.** Внутренний finding стал самостоятельным многоучастниковым объектом и потребовал нового round/carrier.

---

## 3.2. VIA

### Нормальное внутреннее развитие

VIA уже является единым case file конкретного редакционного материала. Его Process Map удерживает состояние, Active Handoff — участника и задание, а Draft / Reviews / Revision / Finalization / Publication остаются частями одного редакционного объекта.

Обычный Theology Review, Reader Review, Revision или Final Check не требуют нового carrier только потому, что меняется участник.

### Boundary trigger

Граница появляется, если редакционный цикл обнаруживает вопрос, который нельзя честно закрыть существующей editorial capability, например:

- самостоятельный research question;
- material factual/theological uncertainty, требующий отдельного исследовательского цикла;
- новый product/application question, который нельзя решить редактурой;
- system-level defect, который нельзя исправить внутри конкретного VIA без изменения архитектуры.

### Кандидатный переход

    VIA
    → material dependency detected
    → VIA сохраняет точный вопрос / blocked dependency / affected version
    → Research / Development / other appropriate carrier
    → accepted result pinned to version
    → return to VIA
    → VIA resumes or closes

VIA при этом не становится Research Project и не обязан закрываться полностью. Он может удерживать зависимый шаг как waiting/blocked state.

### Вывод

**Подтверждает общее ядро, но не Brainstorm-specific Round model.** Переход может быть child dependency с возвратом в тот же VIA.

---

## 3.3. Content Portfolio

### Нормальное внутреннее развитие

Portfolio удерживает стратегический выбор, независимые Reader/SEO и другие предусмотренные reviews, Strategy Integration, Close и handoff. Смена reviewer сама по себе не означает смену carrier.

### Boundary trigger

Portfolio может обнаружить объект, который больше не является только выбором/приоритизацией контента:

- дальнее исследовательское направление;
- новый corpus-development question;
- новая product/system opportunity;
- вопрос, требующий Formation или отдельного multi-participant exploration до стратегического решения.

Существующий Portfolio 2026-02 уже различает Near Publication Horizon и Far Development Horizon и передаёт их в разные downstream routes, не превращая дальний горизонт в ближайший production plan.

### Кандидатный переход

    Portfolio
    → candidate / far-development object
    → Portfolio disposition фиксирован
    → Research / Brainstorm / Formation carrier
    → самостоятельный результат
    → возможный возврат в будущий Portfolio / Owner decision

Не каждый дальний кандидат обязан возвращаться в тот же Portfolio. Return может означать future strategic intake, а не resume исходного документа.

### Вывод

**Подтверждает общее ядро.** Carrier transition может быть не временным ответвлением, а передачей объекта в новый жизненный цикл.

---

## 3.4. Research

### Нормальное внутреннее развитие

Research Lab уже использует сильную staged carrier model: Run Record, Process Map, Events, linked Artifacts, Stage gates, Next Owner и отдельные verification dependencies.

В IP-001 Acts один book-scale research cycle может содержать Stage 0–4 только при отдельных authority/verification gates. Отдельный artifact сам по себе не создаёт новый project carrier, пока он остаётся частью установленного Research cycle.

### Boundary trigger

Граница появляется, когда результат или запрос требует capability, которой текущий Research carrier не владеет:

- независимая verification вне проверенного role envelope;
- interdisciplinary subject competence вне текущего предмета Lab;
- application/safety acceptance;
- product formation;
- downstream editorial/publication work;
- новый research request, не являющийся продолжением уже санкционированного stage.

RQ-RL-002 является сильным примером: Formation/Installation может описать ограниченный research route, но широкий запрос обнаруживает внешние clinical/psychological/suicide-prevention competence dependencies и не становится исполнимым только потому, что Research carrier существует.

### Кандидатный переход

    Research carrier
    → bounded accepted subject result OR explicit blocked dependency
    → project-level / other subject carrier when required
    → synthesis/application acceptance if separately authorized
    → downstream product/editorial carrier

или внутри Research:

    current Stage
    → capability/verification dependency
    → separate authorized validation carrier/event
    → accepted capability result
    → return to parent Research cycle

### Вывод

**Сильно подтверждает общее ядро.** Наличие carrier не создаёт отсутствующую competence/authority; переход должен сохранять provenance и точный уровень acceptance.

---

## 3.5. Book / long-form project

### Нормальное внутреннее развитие

Книга может иметь собственную архитектуру, manuscript, revision и product decisions. Обычная переработка главы или композиции не требует превращения каждого вопроса в отдельный project cycle.

### Реальный boundary case In Profundo

`Тот, Кто остаётся` имеет существующую архитектуру и основной manuscript, но дальнейшая стабилизация зависит от IP-001. При этом книга не размораживается автоматически только потому, что IP-001 дошёл до принятого Stage 2; следующий book-relevant research step требует отдельного Owner gate.

Это уже фактически демонстрирует parent/child dependency:

    Book
    → research dependency identified
    → IP-001 Research carrier
    → bounded research stages / Owner gates
    → accepted relevant result when sufficient
    → return to Book decision

Книга не должна становиться контейнером Research Lab stages, а Research Lab не становится owner книги.

### Boundary trigger

- claim/section зависит от отдельного исследования;
- требуется самостоятельная historical/textual verification;
- возникает новый product route;
- появляется вопрос, требующий нескольких внешних capabilities и отдельного synthesis.

### Вывод

**Подтверждает общее ядро**, хотя Book carrier пока менее формализован, чем VIA или Research. Это аргумент за project-level principle, а не за перенос Research workflow внутрь книги.

---

# 4. Comparative result

| Carrier | Обычная смена участника остаётся внутри? | Может породить новый carrier? | Типичный return |
|---|---:|---:|---|
| Brainstorm | да | да | synthesis → Owner / parent question |
| VIA | да | да | accepted dependency → resume VIA |
| Portfolio | да | да | result → future strategy / next carrier |
| Research | да | да | verified result → parent stage / synthesis / downstream |
| Book | да | да | accepted evidence → book decision / revision |

Сравнение не поддерживает идею одного универсального workflow.

Оно поддерживает более узкое общее ядро:

> **Каждый carrier может обнаружить работу, которая больше не принадлежит его внутреннему циклу. В этот момент требуется явное решение о границе и переходе, а не молчаливое расширение текущего документа, роли или Owner-mediated handoff.**

---

# 5. Candidate Cross-Cycle Carrier Transition Principle

## 5.1. Core principle

> Если в ходе действующего цикла возникает самостоятельный объект, вопрос или dependency, для которого текущий carrier не может однозначно удерживать необходимые authority, participants, states, outputs, verification и return route, руководящая/координирующая функция должна остановить молчаливое расширение текущего цикла и определить явный carrier transition.

## 5.2. Transition does not mean abandonment

Parent carrier может:

- `CONTINUE` — если новый вопрос остаётся обычным внутренним stage;
- `HOLD / WAIT` — если нужен внешний dependency result;
- `ESCALATE` — если вопрос требует нового уровня/round;
- `SPLIT` — если возник отдельный самостоятельный объект;
- `HANDOFF` — если дальнейшая жизнь объекта принадлежит другой capability;
- `CLOSE` — если parent выполнил свою функцию;
- `DEFER` — если новый carrier сейчас не должен запускаться.

## 5.3. Minimal transition contract

Перед запуском child/next carrier должно быть понятно:

1. **Parent** — какой carrier породил переход.
2. **Trigger** — почему внутреннего продолжения недостаточно.
3. **Object / Question** — что именно передаётся.
4. **Disposition** — что происходит с parent: continue/hold/escalate/split/handoff/close/defer.
5. **Target carrier** — куда переходит работа.
6. **Authority** — кто разрешил переход и что именно разрешено.
7. **Pinned input/version** — какой объект является входом.
8. **Expected result** — что должно вернуться или быть создано.
9. **Acceptance type** — contract / subject / synthesis / application / product / other applicable acceptance.
10. **Durable output** — где сохраняется результат.
11. **Return route** — кому и в какой carrier возвращается результат.
12. **Resume/Close condition** — что происходит после возврата.

Не каждый переход требует отдельного большого документа. Эти поля могут быть частью VIA handoff, Research Event, Portfolio disposition, Brainstorm Round или Book decision record.

---

# 6. Boundary triggers

Следующие сигналы требуют проверки достаточности текущего carrier, но не автоматически создают новый:

- появились участники/capabilities, которых текущий процесс не умеет назначить без импровизации;
- возник самостоятельный synthesis с отдельным accepter/reviewer;
- требуется authority или competence вне текущего role/system envelope;
- отдельные artifacts существуют, но current state/route уже нельзя восстановить из parent carrier;
- installation prompt новой ветки начинает нести substantive workflow вместо canonical assignment;
- следующий участник не может восстановить задачу из одной canonical точки входа;
- Owner вынужден повторно переносить substantive output между уже санкционированными участниками;
- Owner должен объяснять связь между artifacts, хотя нового material decision от него не требуется;
- значимый output не имеет заранее определённого durable path;
- один объект получает несколько конкурирующих current states;
- downstream use требует нового типа acceptance, которого parent carrier не обеспечивает.

---

# 7. Owner Ping-Pong as diagnostic signal

Owner ping-pong не является самостоятельной архитектурой и не всегда означает дефект.

Нормальный Owner action:

- принять material decision;
- изменить scope;
- дать authority;
- решить resource question;
- принять Owner-owned gate;
- санкционировать новый цикл.

Process signal возникает, когда Owner без нового material decision вынужден:

- вручную переносить уже готовый substantive result;
- повторно предоставлять существующий artifact;
- отдельно напоминать о durable сохранении;
- реконструировать следующий participant/route;
- возвращать review к правильному owner;
- соединять stages, которые уже должны быть связаны process contract.

В этом случае первый вопрос:

> **Не пересекла ли работа границу carrier без явного transition?**

---

# 8. Installation boundary as cross-cycle rule

Fresh-context branch creation не является carrier transition сама по себе.

Общий порядок для нового участника:

    INSTALL / RECOVER ROLE
    → CONFIRM IDENTITY / AUTHORITY / STOP CONDITIONS
    → OPEN CANONICAL CARRIER
    → READ CURRENT ASSIGNMENT
    → EXECUTE
    → WRITE / RETURN ACCORDING TO CARRIER

Installation может указывать canonical carrier, но не должна быть единственным местом, где существует substantive assignment многоучастникового цикла.

Это правило применимо не только к Brainstorm: новая ветка Editor, Researcher, Auditor, Lead, Coach, Strategist или иной capability должна после установки входить в действующий объект работы, а не заменять его текстом installation prompt.

---

# 9. Durable output and return

Если результат необходим следующему участнику и его содержание уже разрешено создавать, default:

    WRITE
    → VERIFY
    → COMMIT
    → LINK / REGISTER IN CARRIER
    → HANDOFF

Если Owner acceptance действительно должен предшествовать записи/активации:

    DO NOT WRITE / DO NOT ACTIVATE
    → RETURN TO OWNER
    → OWNER DECISION
    → WRITE / REVISE / CLOSE

Выбор режима должен быть известен до выполнения задания.

Durable storage сам по себе не заменяет carrier. Файл может быть прекрасно сохранён, но процесс всё равно сломан, если неизвестно, кому он принадлежит, какая версия действует и куда результат возвращается.

---

# 10. What should remain local

Общепроектный принцип не должен определять:

- VIA Process Map statuses;
- Research stages и verification methodology;
- Portfolio selection logic;
- Brainstorm participant sequence;
- Book chapter/revision workflow;
- профессиональные Output Contracts ролей.

Это остаётся внутри соответствующих systems/carriers.

Общий уровень отвечает только на вопрос:

> **Что делать, когда работа перестала помещаться в действующий carrier?**

---

# 11. Result of the comparison

Результат сравнительной проверки:

**B — ЧАСТИЧНО УНИВЕРСАЛИЗИРОВАТЬ.**

Подтверждается универсальное ядро:

- boundary detection;
- explicit parent disposition;
- target carrier selection;
- authority and pinned input;
- durable output;
- acceptance type;
- return route;
- resume/close condition.

Не подтверждается необходимость:

- одного универсального workflow;
- единого шаблона всех carriers;
- одинаковых stages/statuses;
- новой постоянной cross-system role;
- немедленного изменения всех role packages.

`Brainstorm Round / Multi-Participant Carrier v0.1` следует считать специализированным применением этого общего принципа к случаю, когда один brainstorm порождает следующий многоучастниковый round.

---

# 12. Candidate placement in project documentation

Если Owner примет направление, принцип лучше разместить **на project-level выше отдельных systems**, но ниже Foundation/identity-level норм.

Предпочтительная функция будущего документа:

- common operating principle для переходов между carriers;
- reference point для Project Overview, Director, Master, Lead, Coach, Strategist и других orchestration functions;
- источник, на который локальные VIA / Portfolio / Research / Brainstorm / Book mechanisms могут ссылаться без копирования полного текста.

Не рекомендуется сейчас массово редактировать все роли. Сначала достаточно принять/проверить project-level principle и затем добавлять локальные ссылки только там, где реальная практика показывает необходимость.

---

# 13. Validation path

До превращения Discussion Draft в project-level working principle требуется не новый теоретический аудит всех ролей, а operational evidence.

Минимальная проверка:

1. использовать principle при следующем реальном boundary crossing;
2. зафиксировать parent disposition до запуска child carrier;
3. для fresh branch отделить installation от substantive assignment;
4. заранее определить WRITE / DO NOT WRITE, durable path и return route;
5. проверить, смог ли следующий участник восстановить задачу из canonical carrier без Owner reconstruction;
6. проверить, вернулся ли accepted result в правильный parent/next carrier;
7. отметить Owner ping-pong как `NONE / REQUIRED DECISION / PROCESS DEFECT`.

Один успешный кейс подтверждает применимость, но не универсальную устойчивость. Желательно evidence как минимум из двух разных типов carrier.

---

# 14. Project Overview recommendation

Сохранить этот документ как **Discussion Draft** и использовать его как рабочую линзу при следующем естественном cross-cycle переходе.

Не создавать искусственный pilot только ради проверки.

Не изменять пока массово VIA, Research, Portfolio, Brainstorm, Book или role packages.

При следующем реальном trigger Project Overview или соответствующая orchestration function должна задать вопрос:

> **Это всё ещё внутренний stage текущего carrier — или работа уже требует явного carrier transition?**

Если требуется transition, минимальный контракт §5.3 должен быть определён до запуска следующего substantive участника.

После двух разных реальных применений вернуться к Owner с evidence и предложением одного из решений:

- принять как project-level Working Principle;
- сузить;
- оставить локальными реализациями;
- отказаться как от избыточной абстракции.
