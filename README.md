# born2scan.github.io

> https://born2scan.github.io/

## Contributing

1. Clone the repo.
2. Create a new post or edit an existing one in [_posts](_posts).
    + Check [below](#conventions) and refer to [Jekyll's docs](https://jekyllrb.com/docs/posts/) for more infos.
3. Run `docker run --rm -it -v "$(pwd):/srv/jekyll" -p 4000:4000 jekyll/jekyll -- jekyll serve` to preview your changes locally at [localhost:4000](http://localhost:4000).

## Conventions

+ The filename format is **YYYY-MM-DD-{event_name}.md**
+ Put images in a subfolder in [assets/img](assets/img).
+ Start your posts with the appropriate front matter (see [below](#reference-post)).
+ First level headers (`#`) are reserved for categories, and second level ones (`##`) for single challenges' names. Use `---` to separate categories.
+ Use this syntax to blur flags:
    ```
    🏁 _<FLAG_HERE>_{: .spoiler}
    ```
+ **Don't take yourself too seriously!** Tasteful use of memes and other silly things is encouraged 🤪

### Reference post:

```
---
layout: post
title: "RandomCTF 1970"
subtitle: "Qualifiers"
date: 1970-01-01
---

<span class="align-center" markdown="1">
    <span class="categories-index">
        **Categories index**<br>
        [Web](#web) - [Misc](#misc)
    </span>
</span>

---

# Web

## HackYouBackInTime

> Challenge description, hints & co.

I did a lot of things. Some worked out, some did not.

🏁 _RandomCTF{d035n7_l00k_l1k3_574r5_70_m3}_{: .spoiler}

---

# Misc

## GotAnyMoreOfThoseChallenges

![Such screenshot, much image](/assets/img/RandomCTF_1970/cool_pic.png)

...

```