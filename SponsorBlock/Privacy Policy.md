[](#privacy-policy-for-sponsorblock)Privacy Policy for SponsorBlock
===================================================================

SponsorBlock is a browser extention that allows you to submit segments in YouTube videos and fetch segments that other people have submitted.

Also see [the terms of use](https://gist.github.com/ajayyy/9e8100f069348e0bc062641f34d6af12).

[](#log-files)Log Files
-----------------------

Almost all data that is collected through this extension can be downloaded from [https://sponsor.ajay.app/database](https://sponsor.ajay.app/database). Some more sensitive data such as votes and _hashed_ IPs are stored in a private database.

The only things I keep are:

*   Information you submit (segments, votes)
*   A hashed version of your userID (a randomly generated value assigned when you first install the extension)
*   The time the submission happened
*   A hashed + salted version of your ip address for ratelimiting. This process makes it close to impossible to retrieve the original value if they don't have access to the salt.
*   The name of your client (if using an extension, another port, etc.)

The extention also optionally logs whenever you skip a segment. This is used to let other users know how much their submissions have helped others (leaderboard). The skip tracking is completely anonymous and can be disabled in settings.

[](#requests-sent-to-the-server-while-using-the-extension)Requests sent to the server while using the extension
===============================================================================================================

Each time you browse to a new YouTube video:

*   An anonymous request is sent asking for the segments for that video.
    *   This request contains a [**prefix** of the videoID hash](https://github.com/ajayyy/SponsorBlock/wiki/K-Anonymity), and returns a list of videos that potentially could be the one you are looking for
    *   This request contains no personally identifiable information and no IPs are logged connected with this request

Each time you skip a segment: IF you have skip tracking enabled:

*   An anonymous request is sent with the ID of the segment to record one skip
    *   This request contains no personally identifiable information and no IPs are logged connected with this request

Each time you vote on a submission:

*   A request with your userID and the segment ID is sent
    *   A hashed IP is stored with this information to help prevent spammers

Each time you submit a segment

*   A request with the video ID, your user ID and the submission is sent
    *   A hashed IP is stored with this information to help prevent spammers

### [](#user-counting)User counting

For every request:

*   A hashed + salted (salt rotated every 48 hours) IP address is temporarily stored **without** the actual request details
    *   This allows the stats page to have count the number of users of the API
    *   This data is stored in a seperate program from the main server and stored in memory. Form more details on how it works, [see here](https://github.com/ajayyy/PrivacyUserCount/#privacy-user-counter)

[](#extension-local-storage)Extension Local Storage
===================================================

This data stays on your device

Each time you skip a segment:

*   A sum is counted of the amount of time you have skipped in total

Each time you downvote or hide a segment: If you have downvote storage enabled:

*   A hash prefix of the videoID is stored locally along with a hash of the segment ID to keep that segment hidden when you watch the video in the future

[](#childrens-information)Children's Information
------------------------------------------------

Children under 13 are not allowed to use this service without permission from a legal guardian.

[](#consent)Consent
-------------------

By using this browser extension or API, you hereby consent to the Privacy Policy.

[](#data-accessdeletion-requests-gdpr)Data Access/Deletion Requests (GDPR)
--------------------------------------------------------------------------

Please email me with your request.

[](#use-of-youtube-api)Use of YouTube API
-----------------------------------------

The extension uses the YouTube API on the server-side to verify that submissions are for valid videos, and provide information about videos that have been downvoted to moderators. The use of the YouTube API is governed by the [Google Privacy Policy](https://policies.google.com/privacy) and the [YouTube Terms of Service](https://www.youtube.com/t/terms)

[](#error-logging-and-cloudflare)Error logging and Cloudflare
-------------------------------------------------------------

While I try to keep it's use to a minimum, I sometimes have to enable Cloudflare proxy to reduce load on the servers. I don't use it most of the time. When it is enabled, it logs some information, such as the number and location of connecting IPs. More information can be found at [https://www.cloudflare.com/privacypolicy/](https://www.cloudflare.com/privacypolicy/)

I sometimes need to enable error logging in nginx. This does log IPs associated with connection errors (not all requests), but I will delete these logs within 72 hours whenever that is enabled.

[](#additional-info)Additional Info
-----------------------------------

If you have additional questions or require more information, contact me through email at [dev@ajay.app](mailto:dev@ajay.app). You can also ask me questions on Discord (Ajay#1922) or [Matrix](https://matrix.to/#/@ajay:ajay.app).