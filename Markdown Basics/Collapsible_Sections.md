# Collapsible Sections

Use the HTML `<details>` and `<summary>` tags to create expandable/collapsible sections.

**Syntax:**

```html
<details>
  <summary>Click to expand</summary>

  Hidden content goes here. You can use **Markdown** inside too.

</details>
```

**Rendered:**

<details>
  <summary>Click to expand</summary>

  Hidden content goes here. You can use **Markdown** inside too.

</details>

---

## With a Code Block Inside

```html
<details>
  <summary>Show example code</summary>

  ```python
  def hello():
      print("Hello, world!")
  ```

</details>
```

<details>
  <summary>Show example code</summary>

  ```python
  def hello():
      print("Hello, world!")
  ```

</details>

---

## Open by Default

Add the `open` attribute to have it expanded on load:

```html
<details open>
  <summary>This starts expanded</summary>

  Content visible immediately.

</details>
```

> ✅ Works natively on GitHub, GitLab, and most Markdown renderers that support HTML.
