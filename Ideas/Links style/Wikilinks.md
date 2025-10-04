# Wikilinks

```markdown
[[Note]]
[[Note|Alias]]
```

**Relative links**:

```
[[./relative/path/to/note]]
[[../relative/path/to/note]]
```

**Absolute links**:

```markdown
[[/absolute/path/to/note/from/the/vault/root]]
```

## Pros

- Quick to type

## Cons

- Not a part of the markdown spec
- Supported by less tools (even `GitHub` does not support them)
- Non-relative links are ambiguous, depend on which folder is opened as a vault root
- Allows to ignore folder hierarchy
- Paths that don't start with `./` or `../` have a potential [bug](https://forum.obsidian.md/t/add-settings-to-control-link-resolution-mode/69560) in Obsidian
