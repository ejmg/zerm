# zerm

a minimalist and dark theme for [Zola](https://getzola.org).

![Screenshot](../master/zerm-preview.png?raw=true)

[**Live Preview!**](https://zerm.ejmg.now.sh/)

Largely a port of Radek Kozieł's [Terminal
Theme](https://github.com/panr/hugo-theme-terminal) for Hugo. 4/5ths of my way
through porting this theme, I discovered Paweł Romanowski own independent fork
for Zola, [Terminimal](https://github.com/pawroman/zola-theme-terminimal),
which helped me get the PostCSS to Sass styling conversion done more
quickly. My sincerest thanks to both of you!

## differences

This theme is largely true to the original by Radek, but there are some mild
differences. They are almost all stylistic in nature and are intended to
emphasize minimalism even more. Some of them are as follows:
- tags are now included in a post's meta data.
- no post image previews.
- categories are included in the taxonomy.
- bullet points have slightly more margin and different symbols for nesting.
- no social media or comment support.

Some of these might be added later and [PR's are always
welcomed](https://github.com/ejmg/zerm/pulls).

## configuration

Please follow the Zola documentation for [how to use a
theme](https://www.getzola.org/documentation/themes/installing-and-using-themes/#installing-a-theme).

In `config.toml`, you will find all values for customization that are supported
thus far have documentation explaining how they are used. If there is any confusion or something is not working as intended, [please open an issue](https://github.com/ejmg/zerm/issues)!

## math
You can use KaTeX for mathematical typesetting.
Assets are only available if you opt-in on a per-page level through
a single line (`math=true`) on the extra section of the page frontmatter.

``` md
# index.md
+++
title="this page title"
...

[extra]
math=true
+++

Content
```

Pages wich doesn't opt-in are not affected in any way, so you doesn't have
to worry about any performance hit.

## license

MIT. See `LICENSE.md` for more details.
