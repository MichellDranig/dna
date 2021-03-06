---
title: Browser Support
url: /docs/code-guidelines/browser-support
category: code-guidelines
primaryKeywords: code partial supported chrome ie internet explorer ie11 edge firefox opera safari
secondaryKeywords: device desktop phone tablet ios bugs windows mac
---

All contents in YouSee DNA is build for and tested in the browsers below. Any YouSee site or web application must be tested in the same browsers.

## Desktop
- Chrome (3 latest versions) for Windows, MacOS and Ubuntu <sup>[[1]](#ref1)</sup>
- Firefox (3 latest versions) for Windows, MacOS and Ubuntu <sup>[[1]](#ref1)</sup>
- Safari (2 latest versions) for MacOS <sup>[[2]](#ref2)</sup>
- Edge (3 latest versions) for Windows <sup>[[1]](#ref1)</sup>
- Internet Explorer 11 for Windows <sup>[[4]](#ref4)</sup>

## Phone & Tablet
- Chrome (3 latest versions) for Android and iOS <sup>[[1]](#ref1)</sup>
- Safari (2 latest versions) for iOS <sup>[[2]](#ref2)</sup>
- Samsung Internet (latest version) for Android <sup>[[3]](#ref3)</sup>

## Notes
Latest version cover only the major release version, patches and minor updates is not taken into consideration.

<ol>
    <li id="ref1">Chrome, Firefox and Edge has a short regular release cycle, support for 2 prior version is necessarily.</li>
    <li id="ref2">Safari has a longer release cycle, therefore support for only one prior version is necessary.</li>
    <li id="ref3">Samsung Internet is the new wildcard in the browser realm, luckily based on Chromium, however possibly never updated by the consumer. As a result, only the latest release can be supported.</li>
    <li id="ref4">Partial supported. Small visual bugs are acceptable, given that you can read and interact with the content.</li>
</ol>
