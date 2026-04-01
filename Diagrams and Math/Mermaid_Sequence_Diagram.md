# Mermaid — Sequence Diagrams

Sequence diagrams show how processes interact over time.

**Syntax:**

````markdown
```mermaid
sequenceDiagram
    participant User
    participant Browser
    participant Server

    User->>Browser: Enter URL
    Browser->>Server: GET /index.html
    Server-->>Browser: 200 OK + HTML
    Browser-->>User: Render page
```
````

**Rendered:**

```mermaid
sequenceDiagram
    participant User
    participant Browser
    participant Server

    User->>Browser: Enter URL
    Browser->>Server: GET /index.html
    Server-->>Browser: 200 OK + HTML
    Browser-->>User: Render page
```

---

## Arrow Types

| Syntax | Meaning |
| :----- | :------ |
| `A->>B` | Solid arrow (request) |
| `A-->>B` | Dashed arrow (response) |
| `A-xB` | Solid with X (async/lost) |
| `A--xB` | Dashed with X |

---

## With Notes and Loops

```mermaid
sequenceDiagram
    participant Client
    participant API

    Note over Client: User clicks login
    Client->>API: POST /auth
    loop Retry on timeout
        API-->>Client: 503 Try again
        Client->>API: POST /auth
    end
    API-->>Client: 200 OK + token
```
