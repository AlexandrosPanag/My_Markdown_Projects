# Footnotes

Footnotes let you add references without cluttering the main text.

**Syntax:**

```markdown
Here is a sentence with a footnote.[^1]

[^1]: This is the footnote content.
```

**Rendered:**

Here is a sentence with a footnote.[^1]

[^1]: This is the footnote content.

---

## Multiple Footnotes

```markdown
Markdown was created by John Gruber[^gruber] in 2004[^year].

[^gruber]: John Gruber runs the blog Daring Fireball.
[^year]: The original spec was published on December 17, 2004.
```

---

## Multi-line Footnote

```markdown
[^long]: This footnote spans multiple lines.
    Indent continuation lines with 4 spaces.
    They will appear as a single paragraph.
```

> ⚠️ Footnotes are supported on GitHub and most extended Markdown renderers, but not in basic CommonMark.
