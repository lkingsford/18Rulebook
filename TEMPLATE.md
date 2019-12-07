Template Language
=================

# Warning

As of writing, this template language is not entirely implemented. Please
remove this notice once it is.

A template file is [GitHub markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
with a few additions:

- `--` Comments out a line of text. Example: `-- This section has rules on capitalization`
- `{!var}` inserts the variable `var` in the text
- `{!if var}`, `{!else}` and `{!endif}` define blocks that will only be shown
   if `var` = True. They can be nested.