# Hugo Tiny

## _Make it simple and clean, focus on contents_

__Tiny__ is a lightweight [Hugo](https://gohugo.io) theme suitable for personal blogs with a simple and clean design. To make it lightweight, I avoided using any existing frameworks and wrote every HTML and CSS by myself. Currently it contains 329 lines of HTML and 284 lines of CSS.

A temperate of blog article can be found in [archetypes/default.md](https://github.com/Lencerf/hugo-theme-tiny/blob/master/archetypes/default.md). Explanation of some options:
* `highlightLanguages`: __Tiny__ does language highlighting through [highlight.js](https://highlightjs.org). To avoid loading additional css and js, only languages specified here will be highlighted.
* `needKatex` and `needMathjax`: __Tiny__ supports math LaTeX expression through [KaTeX](https://katex.org) and [MathJax](https://www.mathjax.org). From my experience, KaTeX is more lightweight but MathJax is more powerful. Set one of these options to `true` to render math equations surrounded by `$` (inline) and `$$` (display).
* `indent2Char`: set it to `true` to 
indent the first line of paragraphs by 2 characters.
* `warning: "warning text"`. If this option presents in a post, on opening the webpage, a dialog with `warning text` will show up to first to ask readers whether continue reading or not. This option is useful if the article content contains andy spoilers.

A sample site config can be found in [sample-config.toml](https://github.com/Lencerf/hugo-theme-tiny/blob/master/sample-config.toml). 

[Demo](https://lencerf.github.io)(my personal blog).