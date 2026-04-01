# Mermaid — Flowcharts

[Mermaid](https://mermaid.js.org) lets you create diagrams from text inside fenced code blocks with the `mermaid` language tag. GitHub renders these natively.

**Syntax:**

````markdown
```mermaid
flowchart TD
    A[Start] --> B{Is it raining?}
    B -- Yes --> C[Take an umbrella]
    B -- No --> D[Enjoy the sun]
    C --> E[Go outside]
    D --> E
```
````

**Rendered:**

```mermaid
flowchart TD
    A[Start] --> B{Is it raining?}
    B -- Yes --> C[Take an umbrella]
    B -- No --> D[Enjoy the sun]
    C --> E[Go outside]
    D --> E
```

---

## Node Shapes

```mermaid
flowchart LR
    A[Rectangle]
    B(Rounded)
    C{Diamond / Decision}
    D[(Database)]
    E((Circle))
    A --> B --> C --> D --> E
```

---

## Direction Options

| Code | Direction |
| :--- | :--- |
| `TD` or `TB` | Top → Down |
| `LR` | Left → Right |
| `RL` | Right → Left |
| `BT` | Bottom → Top |

> ✅ Supported natively on GitHub since 2022. For other platforms, use [mermaid.live](https://mermaid.live) to preview.
