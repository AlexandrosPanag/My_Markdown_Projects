# Syntax Highlighting in Code Blocks

Add a language identifier after the opening triple backticks to enable syntax highlighting.

**Syntax:**

````markdown
```python
def greet(name: str) -> str:
    return f"Hello, {name}!"
```
````

---

## Language Examples

**Python:**

```python
def greet(name: str) -> str:
    return f"Hello, {name}!"
```

**JavaScript:**

```javascript
const greet = (name) => `Hello, ${name}!`;
console.log(greet("world"));
```

**Bash:**

```bash
#!/bin/bash
echo "Hello, world!"
for i in {1..5}; do
  echo "Count: $i"
done
```

**JSON:**

```json
{
  "name": "My Project",
  "version": "1.0.0",
  "description": "A sample project"
}
```

**SQL:**

```sql
SELECT name, email
FROM users
WHERE active = true
ORDER BY created_at DESC;
```

**HTML:**

```html
<!DOCTYPE html>
<html lang="en">
  <head><title>Hello</title></head>
  <body><h1>Hello, world!</h1></body>
</html>
```

---

## Common Language Tags

| Language | Tag |
| :--- | :--- |
| Python | `python` |
| JavaScript | `javascript` or `js` |
| TypeScript | `typescript` or `ts` |
| Bash / Shell | `bash` or `shell` |
| HTML | `html` |
| CSS | `css` |
| JSON | `json` |
| YAML | `yaml` |
| SQL | `sql` |
| Markdown | `markdown` or `md` |
| C / C++ | `c` / `cpp` |
| Java | `java` |
| Go | `go` |
| Rust | `rust` |
| Diff | `diff` |
