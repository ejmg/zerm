+++
title="demo"
description="a basic demo of zola."
date=2019-08-06

[taxonomies]
tags = ["demo", "zola", "highlighting"]
categories = ["programming", "wu tang",]

[extra]
+++

Here's a general demo of Zola and how things look with zerm.

# Header I

Inline code: `println!("Wu Tang!");`

Zola has built in syntax highlighting. If there's not a theme you like, you can
easily add more.

zerm uses Fira Code fonts, which means we get ligatures in addition to
Zola's powerful syntax highlighting ✨.

```rs
fn foo(arg: String) -> Result<u32, Io::Error> {
    println!("Nice!"); // TODO: the thingy
    if 1 != 0 {
        println!("How many ligatures can I contrive??");
        println!("Turns out a lot! ==> -/-> <!-- <$> >>=");
    }
    Ok(42)
}
```

## Header II

Want block quotes? We got block quotes.

Remember the wise words of Ras Kass:

> In Hotel Rwanda, reminder to honor these street scholars who ask why
U.S. Defense is twenty percent of the tax dollar. Bush gave 6.46 billion to
Halliburton for troops support efforts in Iraq; meanwhile, the hood is hurting,
please believe that.
> 
> -- "Verses", _Wu-Tang Meets The Indie Culture_

### Header III

| members          | age | notable album                                | to be messed with?                                                      |
|------------------|-----|----------------------------------------------|-------------------------------------------------------------------------|
| GZA              | 52  | Liquid Swords                                | no                                                                      |
| ODB              | 35  | Return to the 36 Chambers: The Dirty Version | absolutely not                                                          |
| Raekwon Da Chef  | 49  | Only Built 4 Cuban Linx...                   | `"no"`  that's spanish for "no"                                         |
| Ghostface Killah | 49  | Fishscale                                    | i swear you keep asking that question and the answer ain't gonna change |
| Inspectah Deck   | 49  | CZARFACE                                     | `protect ya neck, boy`                                                  |


#### Header IV

Here's a video of my rabbit, Smalls, loaf'n to lofi beats:

{{ youtube(id="UUpuz8IObcs") }}

