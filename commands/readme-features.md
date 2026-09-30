---
name: readme-features
description: Generate or update the features table in README.md
---

Study the project and craft feature descriptions with these rules:

- Always write each feature between 185 and 200 chars long.
- Always include at most 8 feature rows in the final table.
- Always ensure each line is grammatically correct and clean.
- Always start with a clear action or capability phrase first.
- Always end each feature description with a period mark.
- Always use plain text without emphasis or strong markup.
- Always avoid colons, semicolons, em dashes and odd symbols.
- Always capitalize product, project and person names here.
- Always vary the opening words across all descriptions here.
- Never use markdown formatting like bold or italic tags.
- Never include special symbols, emojis or non-ASCII marks.
- Never repeat the same opening phrase across descriptions.
- Never exceed 200 characters in any single feature cell.

Replace the features in this block, keeping indentation:

```markdown
<table>
  <tbody><tr><td width="99999">Feature description goes here</td><td>✅</td></tr></tbody>
  <tbody><tr><td>Feature description goes here</td><td>✅</td></tr></tbody>
</table>
```
