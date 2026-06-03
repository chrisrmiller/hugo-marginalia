# Marginalia

**Marginalia** is a Distill-inspired Hugo theme for technical blogs and journals. It includes margin notes and uses minimal JavaScript.

> **Status: early WIP.** This is the baseline fork. It builds, but the Distill look and margin-note capabilities are still a work in progress. Not even close to being ready for general use. Maintained as time allows. No support guaranteed.

## What this is

- A Hugo theme aimed at engineering/technical writing: readable, margin notes, citations, hand-drafted figures. It has the Distill feel without the JavaScript framework.
- Derived from [hugo-prose](https://github.com/yihui/hugo-prose); inspired by [Distill](https://distill.pub) and [tufte.css](https://github.com/edwardtufte/tufte-css).

## Requirements
- Hugo **Extended**, **developed on v0.161.0+**. Extended is needed for image processing. (TODO: test on 0.151.x, the most-likely minimal version)

## Local development
This repo ships an `exampleSite/` that doubles as the dev harness. From the repo root:

```sh
hugo server -s exampleSite --themesDir ../.. -D
```

Then open http://localhost:1313

## Using it in your own site

1. Add the theme (submodule or copy) into `themes/hugo-marginalia`:
   ```sh
   git submodule add https://github.com/chrisrmiller/hugo-marginalia themes/hugo-marginalia
   ```
2. Set it in your site config (`hugo.yaml`):
   ```yaml
   theme: hugo-marginalia
   ```

## Credits & license

- MIT licensed — see [LICENSE.md](LICENSE.md).
- Forked from hugo-prose (© Yihui Xie, MIT), with license notice retained.
- © Chris Miller.
