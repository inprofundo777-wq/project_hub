# Brainstorm Round / Multi-Participant Carrier v0.1

**Статус:** CANDIDATE / POST-MORTEM + WORKING HYPOTHESIS  
**Дата:** 11 октября 2026  
**Steward:** Project Overview  
**Основание:** Cross-System Formation brainstorm; сравнение BR-001, VIA, Content Portfolio и Research Lab Run  
**Назначение:** зафиксировать наблюдаемый Owner ping-pong trigger и минимальную кандидатную модель для многоучастникового brainstorm следующего уровня  
**Нормативный статус:** не изменяет роли, Research Lab, Editorial System, VIA Protocol или постоянную архитектуру Brainstorm

> Это не новый постоянный Brainstorm Protocol. Документ фиксирует реальный process finding и кандидатную модель для последующей проверки.

---

# 1. Наблюдаемый сбой

В Cross-System Formation содержательная работа была выполнена успешно, но в ходе переходов между отдельными участниками возник повторяющийся Owner ping-pong:

- значимый output создавался как отдельный durable artifact;
- следующий участник работал уже не внутри исходного living brainstorm document, а вокруг нового artifact;
- маршрут между отдельными artifacts и участниками приходилось дополнительно восстанавливать через Owner;
- после завершения некоторых outputs требовался отдельный вопрос, сохранён ли результат в GitHub;
- независимая Auditor-ветка получила корректную задачу, но не имела единого cycle carrier, который одновременно задавал бы active participant, inputs, output location, return route и next gate.

Сбой не означает, что Auditor, Formation Lead или Project Overview выполнили содержательную работу неправильно. Он указывает на потерю общего carrier состояния и маршрута после изменения природы brainstorm.

---

# 2. Что показали существующие циклы

## 2.1. BR-001

BR-001 был многоучастниковым с самого начала. Один living brainstorm document содержал:

- центральный вопрос;
- role sequence;
- stages;
- living map;
- append-only findings;
- следующий handoff;
- Owner gate.

Отдельные участники менялись, но объект цикла оставался тем же.

## 2.2. VIA

VIA удерживает редакционный цикл одним case file. Process Map является state authority, Active Handoff задаёт конкретного участника, inputs, expected output и место результата. Даже там, где физический перенос остаётся Owner action, Owner не должен заново интерпретировать, интегрировать или проектировать routing.

## 2.3. Content Portfolio

Portfolio служит единой точкой работы Strategist и независимых reviews и затем одной точкой handoff к Coach / следующему циклу. Следующая роль получает закрытый стратегический объект, а не реконструирует выбор из отдельных сообщений.

## 2.4. Research Lab Run

Run Record удерживает Current State, Process Map, append-only Events, linked Artifacts и Next Owner. Большой output может существовать отдельным файлом, но остаётся дочерним artifact одного Run. Owner обычно должен передать только одну актуальную ссылку.

## 2.5. Общий паттерн

Зрелые циклы не требуют, чтобы все результаты физически находились в одном файле. Они требуют единого **cycle carrier**, который знает:

- текущее состояние;
- активного участника;
- необходимые inputs;
- durable location результата;
- следующий handoff;
- return route;
- Owner gate.

**Единый carrier ≠ единый файл всех результатов.**

---

# 3. Ключевой finding Cross-System Formation

Первичный brainstorm породил новый самостоятельный объект — `Cross-System Formation Frame v0.1`.

После появления Frame возник новый маршрут:

    Frame
    → Publication consultation
    → Research Project Lead consultation
    → Research Auditor consultation
    → Project Overview synthesis
    → Owner gate

Frame уже не был просто очередным finding внутри прежнего brainstorm. Он стал предметом дальнейшей многоучастниковой работы.

Однако новый многоучастниковый цикл не получил собственного carrier. Поэтому фактически произошёл переход на следующий уровень brainstorm без явного закрытия предыдущего уровня и без открытия нового round.

Предварительная формулировка:

> **Owner ping-pong возник не просто из-за слабого handoff, а потому что brainstorm породил новый многоучастниковый объект, но этот переход не был распознан как новый Brainstorm Round.**

---

# 4. Дополнительный trigger: Installation и substantive assignment были смешаны

В реальном кейсе новая ветка создавалась одновременно для двух разных операций:

1. установить / восстановить роль в fresh context;
2. сразу выполнить substantive brainstorm assignment вокруг нового Frame.

Это слияние затруднило разделение двух вопросов:

- **готова ли ветка действовать в своей роли?**
- **какое место эта роль занимает в текущем многоучастниковом brainstorm?**

Новая ветка сама по себе не является новым cycle carrier. Installation package восстанавливает identity, authority, stop conditions и operating rules роли. Он не должен автоматически становиться контейнером многоучастникового задания.

Кандидатное правило:

> **Installation first; cycle assignment second.**

Если для нового участника требуется fresh-context installation, сначала подтверждается установка роли. После этого substantive assignment читается из действующего cycle carrier / Brainstorm Round, а не существует только внутри installation request.

Это особенно важно при независимых reviews/audits: независимость ветки не заменяет явный маршрут внутри общего цикла.

---

# 5. Гипотеза Brainstorm Levels / Rounds

Не каждый новый finding требует нового round.

Новый round становится кандидатом, когда текущий brainstorm порождает самостоятельный объект или вопрос, который:

- требует нескольких новых участников или независимых lenses;
- имеет собственную последовательность inputs/outputs;
- требует отдельного synthesis;
- имеет собственный Owner gate;
- больше не может быть однозначно проведён через living map текущего round без превращения Owner в транспортный слой.

Тогда предыдущий round должен быть явно dispositioned:

    CLOSE
    ESCALATE
    SPLIT
    DEFER

а новый round получает собственный carrier.

Пример текущего кейса:

    Brainstorm Level 1
    → архитектурный вопрос обнаружен
    → Formation Frame создан
    → Level 1 CLOSE / ESCALATE
    → Brainstorm Level 2 OPEN
       → Publication consultation
       → Lead consultation
       → Auditor consultation
       → Synthesis
       → Owner Gate

`Level 2` здесь означает не более высокий authority, а новый уровень развития вопроса с собственным многоучастниковым циклом.

---

# 6. Candidate Brainstorm Round Carrier

Минимальный carrier нового round должен содержать:

## Identity

- Round ID / working title;
- parent brainstorm / source question;
- central question;
- status;
- steward / coordinator;
- authority envelope.

## State

- Living Map;
- active participant;
- completed participants;
- blocked / conditional steps;
- next Owner gate.

## Inputs

- parent artifact;
- pinned versions / links;
- closed decisions;
- boundaries not to reopen.

## Participant Assignment

Для каждого участника:

- role;
- purpose;
- exact inputs;
- task;
- independence requirement, если применимо;
- expected output;
- durable output path;
- write authority / `DO NOT WRITE`;
- completion condition;
- return route.

## Artifact Map

| Artifact | Owner / author | Status | Durable path | Used by |
|---|---|---|---|---|
| Parent Frame | Formation owner | accepted input | exact link | all relevant participants |
| Consultation A | named role | planned/complete | exact link | synthesis |
| Consultation B | named role | planned/complete | exact link | synthesis |
| Independent review | named role | planned/complete | exact link | synthesis |
| Synthesis | synthesis owner | planned/complete | exact link | Owner gate |

## Close

- synthesis result;
- unresolved questions;
- Owner decision required;
- what closes with this round;
- what may open a later round;
- exact durable record.

---

# 7. Write / Durable Output default

Если участник создаёт значимый output, необходимый следующему участнику, assignment должен заранее определить один из двух режимов.

### WRITE

    WRITE → VERIFY → COMMIT → LINK IN CARRIER → HANDOFF

Используется, если содержание не требует предварительного Owner acceptance до сохранения.

### DO NOT WRITE

    RETURN TO OWNER → OWNER DECISION → WRITE / REVISE / CLOSE

Используется, если предварительный Owner disposition действительно необходим.

Отсутствие режима не должно автоматически превращать Owner в технического посредника.

---

# 8. Installation boundary

Для новой fresh-context ветки рекомендуемый порядок:

    1. INSTALL ROLE
    2. CONFIRM ROLE / AUTHORITY / STOP CONDITIONS
    3. OPEN CURRENT CYCLE CARRIER
    4. READ ACTIVE ASSIGNMENT
    5. EXECUTE
    6. WRITE / RETURN according to carrier
    7. UPDATE carrier state

Installation request может содержать ссылку на будущий carrier для ориентации, но substantive assignment не должен зависеть только от текста installation prompt.

Если роль не установилась корректно, cycle assignment не начинается.

Если роль установилась, но carrier не даёт однозначного assignment, участник делает Correct Stop и возвращает finding координатору, а не реконструирует задачу из installation message.

---

# 9. Owner Ping-Pong Trigger

Следующее считается process signal:

> Owner вынужден вручную переносить уже созданный substantive output между участниками, повторно приносить artifact, отдельно спрашивать о его durable сохранении, возвращать независимую проверку первоначальному владельцу или реконструировать следующий route при отсутствии нового Owner decision.

При таком сигнале руководящая роль не должна только улучшать формулировку очередного handoff. Она проверяет:

1. существует ли действующий cycle carrier;
2. не породил ли текущий цикл новый самостоятельный многоучастниковый объект;
3. не требуется ли закрыть текущий round и открыть следующий;
4. отделена ли installation роли от substantive cycle assignment;
5. определены ли durable output, return route и next gate до запуска участника.

Owner остаётся необходим там, где требуется:

- authority;
- material decision;
- scope change;
- resource decision;
- acceptance, принадлежащее Owner;
- запуск следующего цикла, если он не был заранее санкционирован.

Owner не должен быть скрытым message bus между уже санкционированными стадиями.

---

# 10. Реконструкция Cross-System Formation как Level 2

Если бы кандидатная модель существовала до текущего кейса, маршрут мог выглядеть так:

| Step | Participant | Input | Durable output | Return |
|---|---|---|---|---|
| 0 | Project Overview / Formation | parent brainstorm | Formation Frame | Round carrier |
| 1 | Publication Master | Frame | Publication Boundary Consultation | Round carrier |
| 2 | Research Project Lead | Frame + relevant prior findings | Coordination Portability Consultation | Round carrier |
| 3 | Research Auditor | pinned Frame + consultation set required by assignment | Verifiability Consultation | Round carrier |
| 4 | Project Overview | Frame + three consultations | Formation Synthesis / Owner Decision Frame | Round carrier |
| 5 | Owner | complete round | disposition | CLOSE / PILOT ROUND / DEFER |

Новая Auditor-ветка сначала устанавливает роль, затем получает assignment из carrier. Её независимость сохраняется, но Owner не должен вручную конструировать ей отдельный процесс из предыдущих сообщений.

---

# 11. Что этот кейс пока не доказывает

Он не доказывает, что:

- каждый brainstorm должен иметь несколько уровней;
- каждый отдельный artifact требует нового round;
- нужен отдельный постоянный Brainstorm System;
- все руководящие роли должны получить одинаковый новый текст в role package;
- Owner никогда не должен физически передавать ссылку;
- fresh-context installation и assignment никогда нельзя упоминать в одном сообщении.

Он показывает более узко:

> когда новый durable object становится центром дальнейшего многоучастникового reasoning, существующий brainstorm должен проверить, остаётся ли он достаточным carrier или требуется новый round.

---

# 12. Минимальная проверка гипотезы

Перед превращением модели в постоянный Protocol достаточно проверить её на двух контрастах:

1. ретроспективно — Cross-System Formation как реальный сложный кейс;
2. проспективно — один небольшой настоящий brainstorm, который действительно породит второй многоучастниковый round.

Наблюдать:

- пришлось ли Owner переносить substantive outputs;
- был ли следующий участник однозначно определён;
- мог ли fresh-context participant восстановить assignment из carrier;
- сохранялись ли outputs без дополнительного напоминания;
- был ли Owner нужен только на реальных decision gates;
- не стал ли carrier тяжелее самого brainstorm.

---

# 13. Предварительная рекомендация Project Overview

Считать `Brainstorm Round / Multi-Participant Carrier` кандидатным развитием brainstorm practice, а не новой системой.

До проверки:

- не менять permanent role packages массово;
- не создавать универсальный Cross-System Lead;
- не превращать каждый brainstorm в сложный workflow;
- при следующем реальном multi-participant escalation создать carrier **до** запуска новых substantive участников;
- при fresh-context branch отделять успешную installation от последующего assignment через carrier;
- использовать Owner ping-pong как trigger для проверки границы round.

Следующий material gate после реальной проверки:

> достаточно ли этой модели как общего правила многоучастникового brainstorm, или evidence требует более общего cross-cycle principle для руководящих ролей и cycle documents?
