Michael Jackson - Keynote
=========================

unpkg.com

* Created to allow people to use packages straight from npm through a CDN
* You can browse the structure of individual deployed packages
* DynamicCDNWebpackPlugin changes imports to CDN resources
* Combine with SystemJS for module support
* Can even work with browsers which support `<script type="module" />`
  * if you use unpkg which can change bare modules to real URLs

I wonder if you can combine with HTTP/2 to reduce the requests
