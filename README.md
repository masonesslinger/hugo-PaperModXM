# PaperModXM

PaperModXM is a fork of [PaperModX](https://github.com/reorx/hugo-PaperModX) that aims to add a bit more color and features such as callouts.

## Callouts

PaperModXM allows you to use hugo shortcodes to render [Obsidian-like callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) in your markdown with the following syntax.

```markdown
{{< callout "type" "Callout header text" >}}
Callout body markdown text
{{< /callout >}}
```

Currently, the supported types are:
- Info
- Quote
- Checklist
- Example
- Note
- Tip
- Question

![image](https://user-images.githubusercontent.com/88267614/230756378-69030297-20a4-4ede-8292-f7d0b151c892.png)

> As more default callout types are added, it is likely that the style of the current callouts will change.

**TODO:**
- [x] Add foldable callouts
  - [ ] Add animation when expanding and collapsing
  - [ ] Optimize conditional hugo code
