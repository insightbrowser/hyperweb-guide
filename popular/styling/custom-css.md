# How to inject custom CSS in iOS Safari

Hyperweb allows you to inject custom CSS on any website to change the style as you see fit. This is a free feature.

![](/static/images/dual-facing-wikidarklight.png)

Under the Popular tab go to Custom Styles. From there you can

1. Enable or disable a style suggested by us
2. A a custom style from a URL, e.g. https://gitlab.com/vednoc/dark-instagram/raw/master/instagram.user.styl

![](/static/images/dual-facing-css.png)

- Preprocessors supported: `default`, `uso`, [`stylus`](https://stylus-lang.com/) and [`less`](https://lesscss.org/)
- Supported [`@-moz-document`](https://developer.mozilla.org/en-US/docs/Web/CSS/@document) filters (these allow scoping styles to specific pages):
  - `url`
  - `url-prefix`
  - `domain`
  - `regexp`
- `@var` is supported;

Some galleries for CSS user styles:
- https://userstyles.world/
- https://userstyles.org/

Note that Safari loads the mobile version of pages by default, so any styles designed for the desktop version may not work properly.
