# Mermaid — Gantt Charts

Gantt charts are great for project timelines and roadmaps.

**Syntax:**

````markdown
```mermaid
gantt
    title Project Roadmap
    dateFormat  YYYY-MM-DD

    section Planning
    Requirements       :done,    p1, 2024-01-01, 2024-01-07
    Design             :done,    p2, 2024-01-08, 2024-01-14

    section Development
    Backend            :active,  d1, 2024-01-15, 2024-02-15
    Frontend           :         d2, 2024-01-22, 2024-02-22

    section Launch
    Testing            :         t1, 2024-02-23, 2024-03-07
    Release            :milestone, 2024-03-08, 0d
```
````

**Rendered:**

```mermaid
gantt
    title Project Roadmap
    dateFormat  YYYY-MM-DD

    section Planning
    Requirements       :done,    p1, 2024-01-01, 2024-01-07
    Design             :done,    p2, 2024-01-08, 2024-01-14

    section Development
    Backend            :active,  d1, 2024-01-15, 2024-02-15
    Frontend           :         d2, 2024-01-22, 2024-02-22

    section Launch
    Testing            :         t1, 2024-02-23, 2024-03-07
    Release            :milestone, 2024-03-08, 0d
```

---

## Task Status Tags

| Tag | Meaning |
| :-- | :------ |
| `done` | Completed task (grey) |
| `active` | In progress (blue) |
| `crit` | Critical path (red) |
| `milestone` | Zero-duration milestone marker |
