# How to inject custom Javascript in iOS Safari

Hyperweb lets you inject a (supported subset of) Greasemonkey scripts into any page. This is a free feature.

You can do this from `Popular > Custom Scripts`.

![](/static/images/dual-facing-script.png)

From here you can enable a suggested user script or add your own from a valid `.js` URL, e.g. `https://raw.githubusercontent.com/insightbrowser/scripts/main/probable_adblock.js`

* Supported [Greasemonkey metadata](https://wiki.greasespot.net/Metadata_Block):
  * `include`
  * `match`
  * `exclude`
  * `require`
  * `resource`

* Supported [Greasemonkey functions](https://wiki.greasespot.net/Greasemonkey_Manual:API):
  * `GM_getResourceText`
  * `GM_getResourceURL`
  * `GM_addStyle`
