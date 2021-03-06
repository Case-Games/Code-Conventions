# HTML
## Doctype
Use as doctype: `<!DOCTYPE html>`.
## Tag names
Write tag names always with lowercase like `<html>` not `<Html>` or `<HTML>`.
## Close all tags
Always close all tags.
False:
```
<div>
  <p>Hello there!
  <p>Hello there!
</div>
```
Right:
```
<div>
  <p>Hello there!</p>
  <p>Hello there!</p>
</div>
```
## Attributes
### Names
Write attribute names always with lowercase like `style=""` not `Style=""` or `STYLE=""`.
### Values
Always write the values in quotemarks. like `id="ll"` and not `id=ll`.
## HTML 3.0 attributes
Don't use attributes from html 3.0. For attributes like `color=""` or `bgcolor=""` use always the `style=""` tag.
## HTML 4.0(1) Tags
Don't use:
* `<frame>`
* `<frameset>`
* `<noframes>`
* `<basefont>`
* `<big>`
* `<center>`
* `<font>`
* `<strike>`
* `<tt>`
* `<acronym>`
* `<applet>`
* `<isindex>`
* `<dir>`
## Include stylesheets
To include stylesheets use the `<link>` tag. Don't use `@import`.
## Use tabulator
Don't use space as tabulator. Indent code right.
## Encoding
Always use UTF-8 encoding in a document. Use `<meta charset="utf-8">`.
### Trailing Whitespace
Don't use a trailing whitespace. 
False:
```
<p>Hello there! </p>
```
Right:
```
<p>Hello there!</p>
```
