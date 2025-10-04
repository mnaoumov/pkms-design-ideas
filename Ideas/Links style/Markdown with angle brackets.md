# Markdown with angle brackets

```markdown
[Note](<Note.md>)
[Alias](<Note.md>)
[Relative path](<./Note.md>)
[Relative path](<./relative/path/to/note.md>)
[Relative path](<../relative/path/to/note.md>)
[Path with spaces](<Path with spaces.md>)
```

## Pros

- Inherently relative path
- Work in all tools
- Paths with space are readable

## Cons

- Verbose
- Paths that don't start with `./` or `../` have a potential [bug](https://forum.obsidian.md/t/add-settings-to-control-link-resolution-mode/69560) in Obsidian

