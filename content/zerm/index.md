+++
title="what is zerm?"
description="a summary of what zerm is and why it is different."
date=2019-08-07
updated=2021-02-03

[taxonomies]
tags = ["rust", "test", "zola"]
categories = ["programming", "misc.",]

[extra]
ToC = true
+++

# hello

This is zerm, a minimalist theme for Zola based[^1] off of [panr's](https://twitter.com/panr)
theme for Hugo.

While it's largely faithful to the original, there are some changes:
- no prism.js integration, instead we use Zola's syntax highlighting to reduce overhead.
- removal of PostCSS and leveraging Zola's use of Sass for simple styling.
  - much thanks to [Paweł
    Romanowski's](https://github.com/pawroman/zola-theme-terminimal/)
    independent fork of Terminal. Their Sass stylings saved me the overhead of
    figuring it out myself.
- no preview images. I want a theme that is focused on content.
- support for anchor links.
- Other small, opinionated changes that I think lend to the minimalism and
  aesthetic of zerm.
  
  
Things this theme does not have but either Terminal or Terminimal might:
- better short-codes for things like embedding videos or images, though I will
  work on this over time.
- better support for things like comments and social media. As of now, I have
  no plans to add this but [PR's are always
  **welcomed**](https://github.com/ejmg/zerm/pulls).
  
## A quick demo

`println!("inline code");`

```rs
fn main(n: String) {
    println!("hello, zola!");
}
```

### Header III

> a somewhat kinda maybe large quote that maybe spans
> more than one line but I mean really who even cares
> okay maybe I do but point being is yes nice.

#### Header IV

| hello | tables    | nice |
|:-----:|:---------:|------|
| wow   | much love | yes  |

  
Like zerm? Then [install
Zola](https://www.getzola.org/documentation/getting-started/installation/) and
[get started](https://www.getzola.org/documentation/themes/installing-and-using-themes/#installing-a-theme)!

---

[^1]: fork? port? a little bit of the former, more of the latter?
