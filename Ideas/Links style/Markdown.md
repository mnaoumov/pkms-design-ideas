# Markdown

```markdown
[Note](Note.md)
[Alias](Note.md)
[Relative path](./Note.md)
[Relative path](./relative/path/to/note.md)
[Relative path](../relative/path/to/note.md)
[Path with spaces](Path%20with%20spaces.md)
```

## Pros

- Inherently relative path
- Work in all tools

## Cons

- Verbose
- Paths with spaces are unreadable
- Paths that don't start with `./` or `../` have a potential [bug](https://forum.obsidian.md/t/add-settings-to-control-link-resolution-mode/
