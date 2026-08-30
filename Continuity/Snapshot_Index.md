# Strategic Snapshot Index

Этот файл служит лёгким индексом Strategic Snapshots In Profundo.

Snapshot фиксирует состояние направления или проекта в конкретный момент и сохраняет:

- что было известно;
- что было доказано;
- что оставалось открытым;
- текущий горизонт;
- Re-entry Question;
- Re-entry Trigger.

Snapshot не является living roadmap и не должен постоянно переписываться.

Если состояние существенно изменилось, создаётся новый Snapshot, а предыдущий сохраняется как историческая контрольная точка.

---

## Current Snapshots

| Дата | Направление | Snapshot | Статус | Контрольная точка |
|---|---|---|---|---|
| 2026-08-29 | Audience / Discovery | `Snapshots/Audience-Discovery/Audience_Discovery_Strategic_Snapshot_2026-08-29.md` | CURRENT | Analysis → Live Validation |
| 2026-08-30 | In Profundo / Project-level | `Snapshots/Project/In_Profundo_Strategic_Snapshot_2026-08-30.md` | CURRENT PROJECT BASELINE | Internal Maturity → External Validation |

---

## Historical Snapshots

| Дата | Направление | Snapshot | Статус | Контрольная точка |
|---|---|---|---|---|
| 2026-08-21 | Research Lab | `Snapshots/Research-Lab/Research_Lab_Strategic_Snapshot_2026-08-21.md` | HISTORICAL | Strategic Re-entry → Normalization Required |

---

## Planned Replacement Points

### Research Lab

Новый Snapshot создаётся после завершения Methodological Normalization.

Исторический Snapshot от 2026-08-21 не изменяется.

Новый Snapshot должен зафиксировать:

- результат Normalization;
- состояние Methodology;
- состояние IP-001 Protocol;
- Research Output Contract;
- готовность Research Editor;
- готовность к продолжению IP-001;
- новый Re-entry Question;
- новый стратегический горизонт.

---

## Snapshot Discipline

Новый Snapshot создаётся только если есть реальная контрольная точка:

- завершён значимый этап;
- направление уходит в паузу;
- направление возвращается после паузы;
- существенно изменилось стратегическое состояние;
- текущий Snapshot перестал быть достаточной точкой восстановления.

Не создаются Snapshots:

- после каждого рабочего цикла;
- ради полноты документации;
- вместо Pilot / Review / Decision Record;
- для направлений, состояние которых уже достаточно удерживается текущими рабочими документами.

---

## Current Snapshot Map

```text
Audience / Discovery   🟢 CURRENT
Research Lab           🟡 HISTORICAL → replacement after Normalization
Project-level          🟢 CURRENT PROJECT BASELINE

Notion                 ○ snapshot exists outside current Continuity index / revisit later
Distribution           ○ Evidence Synthesis currently sufficient
Editorial              ○ separate Snapshot not required
Book                   ○ Snapshot premature
```
