Webmaster Guidelines
====================

[](https://www.youtube.com/watch?v=yFxNda5Z4eE)

Following the **General Guidelines** below will help Google find, index, and rank your site.

We strongly encourage you to pay very close attention to the **Quality Guidelines** below, which outline some of the illicit practices that may lead to a site being removed entirely from the Google index or otherwise affected by an algorithmic or manual spam action. If a site has been affected by a spam action, it may no longer show up in results on Google.com or on any of Google's partner sites.

General Guidelines
------------------

Help Google find your pages

*   Ensure that all pages on the site can be reached by a link from another findable page. The referring link should include either text or, for images, an alt attribute, that is relevant to the target page. Crawlable links are [`<a>` tags with an href attribute](https://support.google.com/webmasters/answer/9112205).
*   Provide a [sitemap file](http://sitemaps.org/) with links that point to the important pages on your site. Also provide a page with a human-readable list of links to these pages (sometimes called a site index or site map page).
*   Limit the number of links on a page to a reasonable number (a few thousand at most).
*   Make sure that your web server correctly supports the `If-Modified-Since` HTTP header. This feature directs your web server to tell Google if your content has changed since we last crawled your site. Supporting this feature saves you bandwidth and overhead.
*   Use the robots.txt file on your web server to manage your crawling budget by preventing crawling of infinite spaces such as search result pages. Keep your robots.txt file up to date. [Learn how to manage crawling with the robots.txt file](https://developers.google.com/webmasters/control-crawl-index/docs/faq). Test the coverage and syntax of your robots.txt file using the [robots.txt testing tool](https://www.google.com/webmasters/tools/robots-testing-tool).

**Ways to help Google find your site:**

*   [Ask Google to crawl your pages](https://support.google.com/webmasters/answer/6065812).
*   Make sure that any sites that should know about your pages are aware your site is online.

Help Google understand your pages

*   Create a useful, information-rich site, and write pages that clearly and accurately describe your content.
*   Think about the words users would type to find your pages, and make sure that your site actually includes those words within it.
*   Ensure that your `<title>` elements and `alt` attributes are descriptive, specific, and accurate.
*   Design your site to have a clear conceptual page hierarchy.
*   Follow our recommended best practices for [images](https://support.google.com/webmasters/answer/114016), [video](https://support.google.com/webmasters/answer/156442), and [structured data](https://developers.google.com/structured-data/).
*   When using a content management system (for example, Wix or WordPress), make sure that it creates pages and links that search engines can crawl.
*   To help Google fully understand your site's contents, allow all site assets that would significantly affect page rendering to be crawled: for example, CSS and JavaScript files that affect the understanding of the pages. The Google indexing system renders a web page as the user would see it, including images, CSS, and JavaScript files. To see which page assets that Googlebot cannot crawl use the [URL Inspection tool](https://support.google.com/webmasters/answer/9012289); to debug directives in your robots.txt file, use the [robots.txt Tester](https://support.google.com/webmasters/answer/6062598) tool.
*   Allow search bots to crawl your site without session IDs or URL parameters that track their path through the site. These techniques are useful for tracking individual user behavior, but the access pattern of bots is entirely different. Using these techniques may result in incomplete indexing of your site, as bots may not be able to eliminate URLs that look different but actually point to the same page.
*   Make your site's important content visible by default. Google is able to crawl HTML content hidden inside navigational elements such as tabs or expanding sections, however we consider this content less accessible to users, and believe that you should make your most important information visible in the default page view.
*   Make a reasonable effort to ensure that advertisement links on your pages do not affect search engine rankings. For example, use [robots.txt](https://support.google.com/webmasters/answer/156449), `rel="nofollow"`, or `rel="sponsored"` to prevent advertisement links from being followed by a crawler.

Help visitors use your pages

*   Try to use text instead of images to display important names, content, or links. If you must use images for textual content, use the `alt` attribute to include a few words of descriptive text.
*   Ensure that all links go to live web pages. Use [valid HTML](https://validator.w3.org/).
*   Optimize your page loading times. Fast sites make users happy and improve the overall quality of the web (especially for those users with slow Internet connections). Google recommends that you use tools like [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) and [Webpagetest.org](http://www.webpagetest.org/) to test the performance of your page.
*   Design your site for all device types and sizes, including desktops, tablets, and smartphones. Use the [mobile friendly testing tool](https://search.google.com/test/mobile-friendly) to test how well your pages work on mobile devices, and get feedback on what needs to be fixed.
*   Ensure that  your site [appears correctly in different browsers](https://support.google.com/webmasters/answer/100782).
*   If possible, [secure your site's connections](https://support.google.com/webmasters/answer/6073543) with HTTPS. Encrypting interactions between the user and your website is a good practice for communication on the web. 
*   Ensure that your pages are useful for readers with visual impairments, for example, by testing usability with a screen-reader.

Quality guidelines
------------------

These quality guidelines cover the most common forms of deceptive or manipulative behavior, but Google may respond negatively to other misleading practices not listed here. It's not safe to assume that just because a specific deceptive technique isn't included on this page, Google approves of it. Webmasters who spend their energies upholding the spirit of the basic principles will provide a much better user experience and subsequently enjoy better ranking than those who spend their time looking for loopholes they can exploit.

If you believe that another site is abusing Google's quality guidelines, please let us know by filing a spam report. Google prefers developing scalable and automated solutions to problems, and will use the report for further improving our spam detection systems.

[Does Google take manual action on webspam?](https://www.youtube.com/watch?v=2oPj5_9WxpA)

Matt Cutts talks about manual action on webspam

### Basic principles

*   Make pages primarily for users, not for search engines.
*   Don't deceive your users.
*   Avoid tricks intended to improve search engine rankings. A good rule of thumb is whether you'd feel comfortable explaining what you've done to a website that competes with you, or to a Google employee. Another useful test is to ask, "Does this help my users? Would I do this if search engines didn't exist?"
*   Think about what makes your website unique, valuable, or engaging. Make your website stand out from others in your field.

### Specific guidelines

**Avoid** the following techniques:

*   [Automatically generated content](https://support.google.com/webmasters/answer/2721306)
*   Participating in [link schemes](https://support.google.com/webmasters/answer/66356)
*   Creating pages with [little or no original content](https://support.google.com/webmasters/answer/66361)
*   [Cloaking](https://support.google.com/webmasters/answer/66355)
*   [Sneaky redirects](https://support.google.com/webmasters/answer/2721217)
*   [Hidden text or links](https://support.google.com/webmasters/answer/66353)
*   [Doorway pages](https://support.google.com/webmasters/answer/2721311)
*   [Scraped content](https://support.google.com/webmasters/answer/2721312)
*   Participating in [affiliate programs without adding sufficient value](https://support.google.com/webmasters/answer/76465)
*   Loading pages with [irrelevant keywords](https://support.google.com/webmasters/answer/66358)
*   Creating pages with [malicious behavior](https://support.google.com/webmasters/answer/2721313), such as phishing or installing viruses, trojans, or other badware
*   Abusing [structured data](https://developers.google.com/search/docs/guides/sd-policies) markup
*   Sending [automated queries](https://support.google.com/webmasters/answer/66357) to Google

**Follow** good practices like these:

*   Monitoring your site for [hacking](https://support.google.com/webmasters/answer/2721435) and removing hacked content as soon as it appears
*   Preventing and removing [user-generated spam](https://support.google.com/webmasters/answer/2721437) on your site

If your site violates one or more of these guidelines, then Google may take [manual action](https://support.google.com/webmasters/answer/9044175) against it. Once you have remedied the problem, you can [submit your site for reconsideration](https://support.google.com/webmasters/answer/35843).