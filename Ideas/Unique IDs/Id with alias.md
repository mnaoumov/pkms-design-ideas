# Id with alias

```markdown
---
id: 39beade3967f4cacafe307372c943785
aliases:
  - 39beade3967f4cacafe307372c943785
---
```

`id` key is added to the frontmatter and duplicated as an alias.

## Pros

- Notes have short unique identifier.
- Notes can be navigated to using their ids.

## Cons

- Requires additional tool/plugin support to generate unique ids for all your notes and handle notes merging.
- False-positive matches in `Quick Switcher` when your id part collides with the desired note name part, such as searching for `39` for our note example.
- Such IDs are impossible to memorize, so for navigation/linking purposes they can be only copy-pasted.
