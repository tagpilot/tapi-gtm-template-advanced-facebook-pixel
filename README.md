# Advanced Facebook Pixel implementation

Advanced (yet simple to use) Facebook Pixel implementation supporting eCommerce events and Advanced Matching (also for Single Page Application).
It pairs well with server-side GTM Conversions API implementations.

It is based on the official, now archived [Facebook pixel template](https://github.com/facebookarchive/GoogleTagManager-WebTemplate-For-FacebookPixel/blob/main/template.tpl).

We kept the main loading logic, but removed a lot of legacy code and focused on GA4 events standard.

Features:

- simple code mapping for standard GA4 eCommerce events
- support for Advanced Matching for traditional and Single Page Application, automatically reinitializing the pixel
- support Google Ads User-provided data
- support external ID
- support event ID