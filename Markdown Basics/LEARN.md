# Markdown Syntax Reference

A complete, single-file guide to Markdown syntax — from the basics to GitHub-flavored features.

> For a quick external reference, see [Adam Pritchard's Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

---

## Table of Contents

1. [Formatting](#formatting)
2. [Headings](#headings)
3. [Lists](#lists)
4. [Task Lists](#task-lists)
5. [Tables](#tables)
6. [Code](#code)
7. [Links](#links)
8. [Images](#images)
9. [Icons & Badges](#icons--badges)
10. [Line Breaks](#line-breaks)
11. [Comments](#comments)
12. [Inline HTML](#inline-html)
13. [GitHub Features](#github-features)

---

## Formatting

| Style | Syntax | Output |
| :--- | :--- | :--- |
| Bold | `**bold**` or `__bold__` | **bold** |
| Italic | `*italic*` or `_italic_` | *italic* |
| Strikethrough | `~~strikethrough~~` | ~~strikethrough~~ |
| Inline code | `` `code` `` | `code` |

---

## Headings

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

> Use only one `# H1` per document (the page title). Structure the rest with H2–H4.

---

## Lists

**Unordered** — use `-`, `*`, or `+`:

```markdown
- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3
```

**Ordered** — numbers auto-increment, so just use `1.` for all items if you prefer:

```markdown
1. First item
2. Second item
3. Third item
```

---

## Task Lists

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another pending task
```

- [x] Completed task
- [ ] Incomplete task

---

## Tables

**Basic table:**

```markdown
| Column A | Column B | Column C |
| -------- | -------- | -------- |
| Value 1  | Value 2  | Value 3  |
| Value 4  | Value 5  | Value 6  |
```

**With column alignment:**

```markdown
| Left-aligned | Centered | Right-aligned |
| :----------- | :------: | ------------: |
| Apple        | Banana   | Cherry        |
| 10           | 20       | 30            |
```

---

## Code

**Inline code:**

```markdown
Use the `print()` function.
```

**Fenced code block** (with optional language for syntax highlighting):

````markdown
```python
def greet(name):
    print(f"Hello, {name}!")
```
````

---

## Links

```markdown
[Link text](https://example.com)
[Link text](https://example.com "Optional tooltip")

<!-- Reference-style -->
[Link text][ref-id]
[ref-id]: https://example.com
```

---

## Images

```markdown
![Alt text](https://example.com/image.png)
![Alt text](./local-image.png "Optional title")
```

To control size or alignment, use inline HTML:

```html
<img src="image.png" width="200px" alt="Description" />
```

---

## Icons & Badges

Use [shields.io](https://shields.io) for badges:

```markdown
![License](https://img.shields.io/badge/License-MIT-blue.svg)
```

Use [Simple Icons](https://simpleicons.org) for brand SVGs:

```html
<img alt="GitHub" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/github.svg" />
```

**Clickable icon link:**

```markdown
[<img alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/linkedin.svg" />](https://linkedin.com/in/yourprofile)
```

> ⚠️ Note: `simple-icons@3.13.0` (used in older examples here) is outdated — use `@v11` or the [latest version](https://github.com/simple-icons/simple-icons/releases).

---

## Line Breaks

To force a line break, use the HTML `<br>` tag:

```html
First line<br>
Second line
```

Or end a line with two trailing spaces (less readable in source).

---

## Comments

These are invisible in rendered output:

```markdown
[//]: # (This is a comment — most portable syntax)
[comment]: # (This also works)
```

---

## Inline HTML

Markdown supports raw HTML for things Markdown can't do natively:

```html
<details>
  <summary>Click to expand</summary>
  Hidden content goes here.
</details>

<p align="center">Centered text</p>

<kbd>Ctrl</kbd> + <kbd>C</kbd>
```

---

## GitHub Features

### Stats Card

```markdown
[![GitHub Stats](https://github-readme-stats.vercel.app/api/?username=YOUR_USERNAME&count_private=true&theme=default)](https://github.com/YOUR_USERNAME)
```

### Top Languages

```markdown
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&langs_count=6)](https://github.com/YOUR_USERNAME)
```

### Commit Streak

```markdown
[![GitHub Streak](https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=default)](https://git.io/streak-stats)
```

> ⚠️ Note: `github-readme-streak-stats.herokuapp.com` is no longer maintained — use `streak-stats.demolab.com` instead.

### Profile View Counter

```markdown
![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square&color=blue)
```

### Activity Graph

```markdown
[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github)](https://github.com/YOUR_USERNAME)
```

> ⚠️ Note: `activity-graph.herokuapp.com` is deprecated — use `github-readme-activity-graph.vercel.app`.

---

*Last updated: 2026 · Maintained by [@alexandrospanag](https://github.com/alexandrospanag)*
