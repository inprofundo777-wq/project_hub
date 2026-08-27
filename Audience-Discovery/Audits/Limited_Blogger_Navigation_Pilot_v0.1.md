# Limited Blogger Navigation Pilot v0.1

**Pilot status:** ACTIVE  
**Launch date:** 2026-08-27  
**Public entry point:** Blogger main menu → `Темы`
**Scope:** Audience Discovery / Blogger Reader Navigation  
**Basis:** Blogger Reader Navigation Prototype v0.2  
**Pilot type:** Limited live navigation experiment

---

## 1. Purpose

Этот Pilot проверяет не окончательную информационную архитектуру Blogger, а один ограниченный вопрос:

> Помогает ли reader-first страница `Темы` человеку выбрать релевантный путь в существующий корпус In Profundo?

Проверяется принцип:

**reader need → navigation route → relevant material**

а не:

**editorial taxonomy → navigation**

Pilot должен дать первый live evidence после этапов corpus analysis, Strategy, Reader Check и SEO Check.

---

## 2. Pilot Question

Главный вопрос:

> Помогает ли страница `Темы`, построенная вокруг узнаваемых человеческих ситуаций, находить подходящие материалы In Profundo?

Дополнительные вопросы:

- понятны ли основные reader-entry без знания внутренней структуры проекта;
- выбирают ли посетители предложенные маршруты;
- какие входы реально используются;
- существуют ли блоки или routes, которые оказываются непонятными или практически неиспользуемыми;
- появляется ли evidence, требующий изменить Prototype.

Pilot не предназначен для проверки всей Blogger IA.

---

## 3. Scope

В Pilot входит только:

1. создание публичной страницы `Темы`;
2. reader-facing content из `Blogger Reader Navigation Prototype v0.2`;
3. один естественный и заметный entry point на страницу `Темы` из существующего Blogger;
4. наблюдение за фактическим использованием этой навигации.

Текущая reader navigation:

- `Когда вера стала трудной`;
  - route: `Когда не видно Божьей работы`;
- `Вера в обычной жизни`;
- `Адвент и Рождество` — seasonal route.

---

## 4. Implementation Boundary

Во время Pilot разрешено изменить только то, что необходимо для появления и доступности страницы `Темы`.

### CHANGE

- создать страницу `Темы`;
- разместить на ней reader-facing версию Prototype v0.2;
- сделать ссылки на указанные статьи рабочими;
- добавить один понятный публичный entry point на страницу.

### DO NOT TOUCH

Pilot не является основанием:

- перестраивать всё меню Blogger;
- массово менять Blogger Labels;
- создавать новую систему Labels;
- переделывать существующие Rubrics;
- создавать Series navigation;
- массово менять старые статьи;
- проводить массовую внутреннюю перелинковку;
- создавать отдельные страницы для emerging domains;
- проектировать полную IA Blogger;
- добавлять новые reader domains ради полноты или симметрии.

Если во время Pilot возникает идея более крупного изменения, она фиксируется как observation, но не реализуется автоматически.

---

## 5. Entry Point

Для Pilot нужен как минимум один естественный публичный путь на страницу `Темы`.

Его функция:

> дать посетителю возможность перейти от отдельного материала или общей навигации блога к выбору следующего reader route.

На этапе Pilot не требуется создавать несколько конкурирующих entry points.

Точное место entry point фиксируется при реализации Blogger.

---

## 6. Evidence

Pilot должен собирать только evidence, которое реально помогает оценить reader navigation.

### Quantitative signals

Если доступно:

- посещения страницы `Темы`;
- переходы со страницы `Темы` к статьям;
- какие domains / routes получают переходы;
- какие anchor articles получают переходы;
- повторяющиеся различия между блоками.

### Qualitative signals

Фиксировать:

- заметную reader confusion;
- непонятные headings или descriptions;
- route, который требует дополнительного объяснения;
- очевидно слабый или неиспользуемый блок при достаточном exposure;
- неожиданный reader path;
- реальные отзывы читателей;
- Owner observations, возникающие при использовании страницы;
- новые вопросы, которые невозможно было увидеть на этапе кабинетного анализа.

Не каждое наблюдение требует немедленного изменения страницы.

---

## 7. No-Evidence Rule

Низкий трафик сам по себе не является evidence того, что reader navigation не работает.

Нельзя делать вывод:

**мало переходов → плохая архитектура**

если страница получила недостаточно meaningful exposure.

Необходимо различать:

**people do not encounter the navigation**

и

**people encounter the navigation but do not use it.**

Поэтому отсутствие достаточного exposure может привести к статусу:

**INSUFFICIENT EVIDENCE**

а не автоматически к `STOP` или `REVISE`.

Это особенно важно в текущем состоянии In Profundo, где Discovery остаётся отдельным исследуемым ограничением.

---

## 8. Observation Period

Pilot начинается с момента:

1. публикации страницы `Темы`;
2. появления рабочего публичного entry point.

**Start date:** 2026-08-27

Pilot не закрывается автоматически только по календарю, если meaningful exposure практически отсутствовал.

Первую содержательную оценку разумно проводить после накопления достаточного live evidence.

Если по истечении первоначального периода evidence остаётся слишком мало, Pilot может остаться открытым со статусом:

**INSUFFICIENT EVIDENCE — CONTINUE OBSERVATION**

вместо искусственного verdict.

---

## 9. Change Discipline During Pilot

После запуска структура не должна постоянно корректироваться по отдельным впечатлениям.

Во время observation period:

**observe → record → accumulate evidence**

а не:

**observe → immediately redesign**

Допустимы только:

- исправление сломанных ссылок;
- очевидные технические ошибки;
- опечатки;
- другие изменения, не меняющие проверяемую navigation hypothesis.

Содержательные изменения headings, domains, routes или anchors фиксируются как candidate revision и рассматриваются при Pilot Close либо при появлении явного blocker.

---

## 10. Close Criteria

Pilot закрывается одним из четырёх verdicts.

### KEEP

Использовать текущую reader navigation дальше, если:

- основные входы остаются понятными;
- реальные переходы подтверждают возможность использовать страницу как navigation layer;
- значимого reader confusion не обнаружено;
- нет evidence, требующего structural revision.

`KEEP` не означает, что текущая IA стала окончательной.

---

### REVISE

Локально изменить Prototype, если meaningful exposure показывает, что:

- конкретный heading систематически непонятен;
- description не помогает выбрать route;
- anchor article плохо выполняет функцию starting point;
- вложенность route оказывается неочевидной;
- один из blocks требует локального изменения scope;
- другое повторяющееся evidence указывает на конкретную исправимую проблему.

Revision должна быть пропорциональна evidence.

---

### STOP

Остановить именно эту navigation hypothesis, если достаточный live evidence показывает, что reader-first модель в данной форме:

- систематически не помогает человеку выбирать материалы;
- создаёт больше confusion, чем пользы;
- строит artificial relationships между материалами;
- требует настолько значительной перестройки, что дальнейшая корректировка перестаёт быть ограниченным Pilot.

`STOP` не означает отказ от reader navigation вообще.

---

### INSUFFICIENT EVIDENCE

Использовать, если:

- meaningful exposure недостаточно;
- посещений слишком мало для интерпретации;
- невозможно отделить проблему navigation от проблемы discovery.

В этом случае Pilot не считается проваленным.

Решение:

- продолжить наблюдение;
- либо вернуться к нему после увеличения exposure.

---

## 11. Pilot Close Record

При закрытии необходимо кратко зафиксировать:

### Exposure

Какой реальный exposure получила страница?

### Observed behavior

Какие reader paths использовались?

### Friction

Где возникали заметные проблемы?

### Unexpected evidence

Что обнаружилось, чего не предполагали Reader / SEO / Strategy checks?

### Verdict

`KEEP / REVISE / STOP / INSUFFICIENT EVIDENCE`

### Implication

Что этот результат позволяет заключить о следующем шаге Blogger reader navigation?

Не следует делать выводов шире полученного evidence.

---

## 12. Owner Actions

### Before Launch

Owner:

- [x] создаёт страницу `Темы` в Blogger;
- [x] переносит reader-facing content из Prototype v0.2;
- [x] добавляет рабочие ссылки на статьи;
- [x] добавляет один публичный entry point;
- [x] проверяет страницу с позиции обычного посетителя;
- [x] фиксирует дату запуска Pilot.

### During Pilot

Owner:

- [ ] не перестраивает navigation по единичным впечатлениям;
- [ ] фиксирует значимые observations;
- [ ] сохраняет реальные reader feedback, если они появляются;
- [ ] при наличии analytics сохраняет relevant usage signals.

### At Close

Owner:

- [ ] передаёт accumulated evidence на Pilot Review;
- [ ] утверждает итоговый verdict;
- [ ] принимает только те следующие изменения, которые поддерживаются evidence.

---

## 13. Current State

Current status:

**ACTIVE — OBSERVATION PERIOD**

Structural Reader blocker: **NO**

Structural SEO blocker: **NO**

Return to Strategy during observation: **NOT REQUIRED**

Pilot launch date:

**2026-08-27**

Public entry point:

**Blogger main menu → `Темы`**

Next action:

**Observe → record → accumulate evidence. Do not redesign during the observation period unless a clear blocker appears.**
