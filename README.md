# PaperModXM

PaperModXM is a fork of [PaperModX](https://github.com/reorx/hugo-PaperModX), which is a fork of [PaperMod](https://github.com/adityatelange/hugo-PaperMod), that aims to add some more features and a bit more color to the original theme.

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
- [ ] Add foldable callouts
