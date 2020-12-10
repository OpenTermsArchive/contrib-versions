**[DuckDuckGo](https://duckduckgo.com/?q=&t=i) does not collect or share personal information.** That is our privacy policy in a nutshell. The rest of this page tries to explain why you should care.

*   [Why You Should Care - Search Leakage](#s1)
*   [Why You Should Care - Search History](#s2)
*   [Information Not Collected](#s3)
*   [Information Collected](#s4)
*   [Information Shared](#s5)

*   Last updated on 04/11/12. Removed ", which gets sent to my personal email." in last paragraph as our feedback is now handled by multiple team members via desk.com.
*   Before that, on 03/11/12. Removed [dead link](#change4) (Scroogle) and added a missing 'to'.
*   Before that, on 11/16/10. [This paragraph](#change3) was added.
*   Before that, on 9/25/10. [This paragraph](#change2) was added.
*   Before that, on 9/16/10. [This paragraph](#change) was added.

Why You Should Care
-------------------

* * *

### Search Leakage   \[[top](#top)\]

At other search engines, when you do a search and then click on a link, your search terms are sent to that site you clicked on (in the [HTTP referrer header](https://duckduckgo.com/HTTP_referrer)). We call this sharing of personal information "search leakage."

For example, when you search for something private, you are sharing that private search not only with your search engine, but also with all the sites that you clicked on (for that search).

In addition, when you visit _any_ site, your computer automatically sends information about it to that site (including your [User agent](https://duckduckgo.com/User_agent) and [IP address](https://duckduckgo.com/IP_Address)). This information can often be used to identify you directly.

So when you do that private search, not only can those other sites know your search terms, but they can also know that _you_ searched it. It is this combination of available information about you that raises privacy concerns.

DuckDuckGo prevents search leakage by default. Instead, when you click on a link on our site, we route (redirect) that request in such a way so that it does not send your search terms to other sites. The other sites will still know that you visited them, but they will not know what search you entered beforehand.

At some other search engines (including us), you can also use an [encrypted version](https://duckduckgo.com/) ([HTTPS](https://duckduckgo.com/HTTP_Secure)), which as a byproduct doesn't usually send your search terms to sites. However, it is slower to connect to these versions and if you click on a site that also uses HTTPS then your search is sent. Nevertheless, the encrypted version does protect your search from being leaked onto the computers it travels on between you and us.

At DuckDuckGo, our encrypted version goes even further and automatically changes links from a number of major Web sites to point to the encrypted versions of those sites. It is modeled after (and uses code from) the [HTTPS Everywhere](https://www.eff.org/https-everywhere/) FireFox add-on. These sites include Wikipedia, Facebook, Twitter, and Amazon to name a few.

Another way to prevent search leakage is by using something called a [POST request](https://duckduckgo.com/?q=POST+request), which has the effect of not showing your search in your browser, and, as a consequence, does not send it to other sites. You can turn on POST requests on our [settings page](https://duckduckgo.com/settings), but it has its own issues. POST requests usually break browser back buttons, and they make it impossible for you to easily share your search by copying and pasting it out of your Web browser's address bar.

Finally, if you want to prevent sites from knowing you visited them at all, you can use a proxy like [Tor](https://www.torproject.org/). DuckDuckGo actually operates a [Tor exit enclave](https://help.duckduckgo.com/privacy/tor-exit-enclave/), which means you can get end to end anonymous and encrypted searching using Tor & DDG together.

You can enter !proxy domain into DuckDuckGo as well, and we will route you through a proxy, e.g. [!proxy breadpig.com](https://duckduckgo.com/?q=!proxy+breadpig.com). This feature is part of our [!bang syntax](https://duckduckgo.com/bang). Unfortunately, proxies can also be slow, and free proxies (like the one we use) are funded by arguably excessive advertising.

Because of these drawbacks in HTTPS, POST and proxies we decided to take the redirect approach to combat search leakage. However, we leave the choice up to you. You can deviate from the default on our [settings page](https://duckduckgo.com/settings) by toggling the redirect or address bar settings. You can also use our [encrypted version](https://duckduckgo.com/).

### Search History   \[[top](#top)\]

Other search engines save your search history. Usually your searches are saved along with the date and time of the search, some information about your computer (e.g. your [IP address](https://duckduckgo.com/IP_Address), [User agent](https://duckduckgo.com/User_agent) and often a unique identifier stored in a [browser cookie](https://duckduckgo.com/HTTP_cookie)), and if you are logged in, your account information (e.g. name and email address).

With only the timestamp and computer information, your searches can often be traced directly to you. With the additional account information, they _are_ associated directly with you.

Also, note that with this information your searches can be tied together. This means someone can see everything you've been searching, not just one isolated search. You can usually find out a lot about a person from their search history.

It's sort of creepy that people at search engines can see all this info about you, but that is not the main concern. The main concern is when they either a) release it to the public or b) give it to law enforcement.

Why would they release it to the public? AOL famously released supposedly anonymous search terms for research purposes, except they didn't do a good job of making them completely anonymous, and they were ultimately [sued over it](https://yro.slashdot.org/story/06/09/25/2150209/AOL-Subscribers-Sue-Over-Release-Of-Search-Data). In fact, almost every attempt to anonymize data has similarly been later found out to be much less anonymous than initially thought.

The other way to release it to the public is by accident. Search engines could lose data, or get hacked, or accidentally expose data due to security holes or incompetence, all of which has happened with personal information on the Internet.

Why would search engines give your search history to law enforcement? Simply because law enforcement asked for it, usually as part of a legal investigation. If you read privacy policies and terms of service carefully you will notice that they say they can give your information on court order.

This makes sense because they may be legally obligated to do so. However, search engines are not legally obligated to collect personal information in the first place. They do it on their own volition.

The bottom line is if search engines have your information, it could get out, even if they have the best intentions. And this information (your search history) can be pretty personal.

For these reasons, DuckDuckGo takes the approach to not collect any personal information. The decisions of whether and how to comply with law enforcement requests, whether and how to anonymize data, and how to best protect your information from hackers are out of our hands. Your search history is safe with us because it cannot be tied to you in any way.

Information
-----------

* * *

### Information Not Collected   \[[top](#top)\]

When you search at DuckDuckGo, we don't know who you are and there is no way to tie your searches together.

When you access DuckDuckGo (or any Web site), your Web browser automatically sends information about your computer, e.g. your [User agent](https://duckduckgo.com/User_agent) and [IP address](https://duckduckgo.com/IP_Address).

Because this information could be used to link you to your searches, we do not log (store) it at all. This is a very unusual practice, but we feel it is an important step to protect your privacy.

It is unusual for a few reasons. First, most server software auto-stores this information, so you have to go out of your way not to store it. Second, most businesses want to keep as much information as possible because they don't know when it will be useful. Third, many search engines actively use this information, for example to show you more targeted advertising.

Another way that your searches are often tied together at other search engines are through [browser cookies](https://duckduckgo.com/HTTP_cookie), which are pieces of information that sit on your computer and get sent to the search engine on each request. What search engines often do is store a unique identifier in your browser and then associate that identifier with your searches. At DuckDuckGo, no cookies are used by default.

In response to efforts by the [EFF](https://duckduckgo.com/Electronic_Frontier_Foundation) and others, the major search engines have begun "anonymizing" their search log data after periods of time. Sure, this is better than not doing so, but you should note that this does not make your search history anonymous in the same way that it is at DuckDuckGo.

What search engines generally do when they anonymize data is get rid of part of your IP address or turn it into something that doesn't look exactly like an IP address. And they do the same thing for uniquely identifying cookies.

However, in many cases, this so-called anonymous data can still tie your searches together, which can be used to reconstruct who you are and what you searched for. Additionally, search engines usually are silent on what they do with the User agent, which [has been shown](https://www.eff.org/deeplinks/2010/01/tracking-by-user-agent) to also have enough information to often be personally identifiable, especially if isolated to a particular search session (day).

### Information Collected   \[[top](#top)\]

At DuckDuckGo, no cookies are used by default. If you have changed any [settings](https://duckduckgo.com/settings), then cookies are used to store those changes. However, in that case, they are not stored in a personally identifiable way. For example, the large size setting is stored as 's=l'; no unique identifier is in there. Furthermore, if you prefer not to use cookies to store settings, you can use [URL parameters](https://duckduckgo.com/params) instead.

Additionally, if you use our [!bang syntax/dropdown](https://duckduckgo.com/bang), which bangs you use are stored in a cookie so that we can list your most frequently used ones on top of the !bang dropdown box. Just like the other settings, this information is not saved on our servers at all, but resides solely on your computer. There is also a [setting](https://duckduckgo.com/settings) to turn this off, which you can also set via a [URL parameter](https://duckduckgo.com/params). Particular searches are of course not stored. An example cookie might look like: php=2&yelp=19&java=4.

We also save searches, but again, not in a personally identifiable way, as we do not store IP addresses or unique User agent strings. We use aggregate, non-personal search data to improve things like misspellings.

Similarly, we may add an affiliate code to some eCommerce sites (e.g. Amazon & eBay) that results in small commissions being paid back to DuckDuckGo when you make purchases at those sites. We do not use any third parties to do the code insertion, and we do not work with any sites that share personally identifiable information (e.g. name, address, etc.) via their affiliate programs. This means that no information is shared from DuckDuckGo to the sites, and the only information that is collected from this process is product information, which is not tied to any particular user and which we do not save or store on our end. It is completely analogous to the search result case from the previous paragraph--we can see anonymous product info such that we cannot tie them to any particular person (or even tie multiple purchases together). This whole affiliate process is an attempt to keep advertising to a minimal level on DuckDuckGo.

Finally, if you [give us feedback](https://duckduckgo.com/feedback), it may be stored in our email. However, you can give anonymous feedback (by not entering your email or other personal info on the feedback form).

### Information Shared   \[[top](#top)\]

If you turn redirects off in the [settings](https://duckduckgo.com/settings) and you don't either turn POST on or use our [encrypted site](https://duckduckgo.com/), then your search could leak to sites you click on. Yet as explained above, this does not happen by default.

Also, like anyone else, we will comply with court ordered legal requests. However, in our case, we don't expect any because there is nothing useful to give them since we don't collect any personal information.

Other
-----

* * *

### Other Search Engines   \[[top](#top)\]

If you care about search privacy, you might also want to check out these other search engines that take it seriously by default.

*   [Ixquick](https://ixquick.com/) \[[privacy policy](https://ixquick.com/eng/protect-privacy.html)\]

Each does things a bit differently in terms of privacy and very differently in terms of results. And not all go as far as DuckDuckGo in some aspects. However, none store your personal information by default, which make them all pretty safe in our opinion.

### Updates   \[[top](#top)\]

If this policy is substantively updated, we will update the text of this page and provide notice to you at [https://duckduckgo.com/about](https://duckduckgo.com/about) by writing '(Updated)' in red next to the link to this page (in the footer) for a period of at least 30 days.

### Feedback   \[[top](#top)\]

I ([Gabriel Weinberg](https://duckduckgo.com/?q=Gabriel+Weinberg)) am the founder of Duck Duck Go and personally wrote this privacy policy. If you have any questions or concerns, please [submit feedback](https://duckduckgo.com/feedback).