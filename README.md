Copy ShortURL Add-on
====================
by Fred Wenzel ``<fwenzel@mozilla.com>``

This is a Firefox add-on built with the Jetpack SDK.

On any webpage, this jetpack adds a new item in the right click menu called
“copy short URL”. When you click it, the add-on looks for a canonical short
URL exposed in the page header. Currently, a number of major websites
expose their own short URLs for any entry on their webpages, among these:

* youtube (“youtu.be/…”),
* flickr (“flic.kr/…”),
* wordpress.com,
* Arstechnica,
* Techcrunch,

and many more.

If, however, the site does not name its own short URL, the add-on
automatically falls back to making a short URL using tinyurl.com.

Either way, after a fraction of a second, you end up with a short URL in your
clipboard, ready to be used in forum posts, tweets, or wherever else you
please.

Dependencies
------------
* [Jetpack][jetpack] SDK 0.7 (trunk)

[jetpack]: https://jetpack.mozillalabs.com/
