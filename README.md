# ncm2-markdown-subscope

Language-specific completion for markdown fenced code blocks.

## Config

Completion will be enabled for the languages specified in

```
g:markdown_fenced_languages
```

if using tpope's [vim-markdown](https://github.com/tpope/vim-markdown) plugin,
or

```
g:vim_markdown_fenced_languages
```

if using plasticboy's
[vim-markdown](https://github.com/plasticboy/vim-markdown).

### `g:ncm2_markdown_subscope#filetypes`

Defaults to `['markdown']`.

A list of filetypes that the plugin should work for. This is useful if you have
files that have an e.g. `vimwiki.markdown` filetype.
