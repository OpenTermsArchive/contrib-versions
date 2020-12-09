YouTube API Services - Developer Policies
=========================================

**Note:** The new [Complying with the YouTube Developer Policies](https://developers.google.com/youtube/terms/developer-policies-guide) guide provides guidance and examples to help you ensure that your API clients adhere to specific portions of the YouTube API Services [Terms](https://developers.google.com/youtube/terms/api-services-terms-of-service) and [Policies](https://developers.google.com/youtube/terms/developer-policies) (API TOS). This guidance offers insight into how YouTube enforces certain aspects of the API TOS but does not replace any existing documents.

This document (the "**YouTube API Services Policies**" or "**Policies**") sets out the policies that you need to follow when accessing or using [YouTube API Services](#definition-youtube-api-services) in your service, product, or application. These Policies help you access and use [YouTube API Services](#definition-youtube-api-services) in ways that are consistent with YouTube's interests and that respect and foster the growth of YouTube's community of creators, viewers, content rights holders, and advertisers.

In addition to defining policies, this document explains some of the underlying principles that YouTube followed in creating these Policies. It also offers examples that demonstrate how these Policies would apply in practice.

Please note that this is a legal document and that these Policies are a component of the [Agreement](#definition-agreement), so you must comply with them. YouTube reserves the right to change these Policies, and your continued access to, or use of, [YouTube API Services](#definition-youtube-api-services) constitutes your agreement to and acceptance of any such changes. Policy changes, like changes to the YouTube API Services [Terms of Service](#definition-terms-of-service), will be documented in the [Terms of Service Revision History](https://developers.google.com/youtube/terms/revision-history), and you can subscribe to the [RSS feed](https://developers.google.com/youtube/terms/feeds/api-services-terms-of-service-revision-history.xml) for that revision history to be notified of any such changes.

I. Terminology and style
------------------------

This is a legal document that specifies policies about allowed or prohibited actions. As such, it uses certain terms to specifically indicate whether you can or cannot do something. With that in mind, the following terms are used to explain your requirements as related to these Policies:

1.  The terms **must** and required refer to absolute requirements.
2.  The term **must not** refers to an absolute prohibition.
3.  The terms **should**, **should not**, **recommend**, and **recommended** indicate that the statement describes a general best practice. While these terms suggest certain actions or behaviors, they acknowledge that you might decide to follow a different course based on specific aspects of your use case.
4.  The term **may** indicates that an action is optional and left entirely to your discretion or, depending on the context in which it is used, to YouTube's discretion.

In addition, the [Definitions](#iv-definitions) section that concludes this document identifies other terms that have a very specific meaning when used in this document. For your convenience, this document uses a special style for those terms to so that you can easily identify them in context and link to their definitions.

II. Software Development Principles
-----------------------------------

These principles underlie many of the policies in this document. Even though they might not cover every policy, if you violate or your [API Clients](#definition-api-client) violate any of these principles, you are likely also violating the terms of the [Agreement](#definition-agreement). That said, if local law requires you to do something other than what is stated in these policies -- for example, to store data for a particular length of time -- you should comply with that law.

1.  **Build high-quality applications and maintain them.**
    
    Build stable, easy-to-use, feature-rich [API Clients](#definition-api-client) that bring significant additional value to the YouTube ecosystem and its users. Promptly update [API Clients](#definition-api-client) as the features offered in [YouTube API Services](#definition-youtube-api-services) change.
    
2.  **Be honest and transparent.**
    
    This principle applies to all facets of [API Clients](#definition-api-client) and the way that they interact with users as well as with YouTube. In keeping with this principle, be clear about who you are and what your [API Client](#definition-api-client) does. Don't engage in any deceptive activity or messaging related to your identity, your data collection, storage, sharing, use and deletion practices, actions that your [API Client](#definition-api-client) takes on users' behalf, or anything else. Be honest and do not mislead or confuse users in the way you use and present data.
    
3.  **Give users control.**
    
    Building on the importance of transparency, this principle dictates that users must be aware of and have actively consented to the actions that an [API Client](#definition-api-client) takes on their behalf. It means that users know about and have final authority over any actions the [API Client](#definition-api-client) takes to insert, share, update, or delete their data. It also means that each [API Client](#definition-api-client) must provide a privacy policy that clearly informs users about the information that the [API Client](#definition-api-client) accesses, collects, stores, shares, and otherwise uses.
    
4.  **Respect users' privacy.**
    
    Make sure that your data collection, storage, use, security, and deletion policies and practices protect users. Don't allow unauthorized access to, or use of, user data. Don't store user data indefinitely, and provide a clear, straightforward process for them to delete data in your possession. Finally, don’t, and do not make attempts to, request, collect, or store users' YouTube login credentials.
    
5.  **Be a good citizen.**
    
    Don't create [API Clients](#definition-api-client) that encourage or enable people to abuse, threaten, or harass each other. Don't use, distribute, or promote viruses, spyware, malware, or other bad stuff. Don't break the law or encourage or enable others to do so. Hopefully, this is all common sense.
    

III. General Developer Policies
-------------------------------

### A. API Client Terms of Use and Privacy Policies

1.  [API Clients](#definition-api-client) must display a link to YouTube's Terms of Service ([https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)), and they must also state in their own terms of use that, by using those [API Clients](#definition-api-client), users are agreeing to be bound by the YouTube Terms of Service.
    
2.  Each [API Client](#definition-api-client) must require users to agree to a privacy policy before users can access the [API Client's](#definition-api-client) features and functionality. The privacy policy must:
    
    1.  be prominently displayed and easily accessible to users at all times,
        
    2.  notify users that the [API Client](#definition-api-client) uses [YouTube API Services](#definition-youtube-api-services),
        
    3.  reference and link to the Google Privacy Policy at http://www.google.com/policies/privacy,
        
    4.  clearly and comprehensively explain to users what user information, including [API Data](#definition-api-data) relating to users, the [API Client](#definition-api-client) accesses, collects, stores and otherwise uses,
        
    5.  clearly and comprehensively explain how the [API Client](#definition-api-client) uses, processes, and shares the user information described in section (III.A.2.e), including how the information is shared with either internal or external parties,
        
    6.  disclose, if it does so, that the [API Client](#definition-api-client) allows third parties to serve content, including advertisements,
        
    7.  disclose, if it does so, that the [API Client](#definition-api-client) stores, accesses or collects (or allows third parties to do so) information directly or indirectly on or from users’ devices, including by placing, accessing or recognizing cookies or similar technology on users' devices or browsers,
        
    8.  if the [API Client](#definition-api-client) accesses or uses [Authorized Data](#definition-authorized-data), explain that, in addition to the [API Client's](#definition-api-client) normal procedure for deleting stored data, users can revoke that [API Client's](#definition-api-client) access to their data via the Google security settings page at [https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions), and
        
    9.  if the [API Client](#definition-api-client) uses [Authorized Data](#definition-authorized-data), explain how users can contact the [API Client](#definition-api-client) owner or developer with questions or complaints about the [Client's](#definition-api-client) privacy practices.
        

### B. Maintainability and Deprecation

1.  [API Clients](#definition-api-client) must use the most recent versions of [YouTube API Services](#definition-youtube-api-services). This means that you must be able to update [API Clients](#definition-api-client) when newer versions of [YouTube API Services](#definition-youtube-api-services) are released. Non-website [API Clients](#definition-api-client), like mobile apps or installed applications, must be capable of being remotely updated to use the most recent versions of [YouTube API Services](#definition-youtube-api-services). You must update your [API Clients](#definition-api-client) to the most recent versions of the [YouTube API Services](#definition-youtube-api-services) within a specified time period if required by YouTube from time to time (e.g. for critical updates).
    
2.  When YouTube intends to make backward incompatible changes to the [YouTube API Services](#definition-youtube-api-services), such changes will be documented in the [Terms of Service Revision History](https://developers.google.com/youtube/terms/revision-history), and you can subscribe to the [RSS feed](https://developers.google.com/youtube/terms/feeds/api-services-terms-of-service-revision-history.xml) for that revision history to be notified of any such changes.
    
3.  You must promptly update non-deprecated [API Clients](#definition-api-client) to use newer versions of [YouTube API Services](#definition-youtube-api-services) as those versions are released.
    
4.  You must update deprecated versions of your [API Clients](#definition-api-client) to clearly indicate to users that some functions or features of [YouTube API Services](#definition-youtube-api-services) might stop working due to the [API Clients'](#definition-api-client) deprecated status.
    

### C. Implementing YouTube Features

1.  [API Clients](#definition-api-client) must also comply with the [Requirements for Minimum Functionality for YouTube API Services](https://developers.google.com/youtube/terms/required-minimum-functionality) ("**RMF**"). In addition, [API Clients](#definition-api-client) must not place any limitations on the YouTube functionality required by the RMF.
    
    For example, the RMF states that an [API Client](#definition-api-client) that enables users to upload videos to YouTube must enable those users to set a title for each uploaded video. YouTube's video title field has a maximum length of 100 characters, and an [API Client](#definition-api-client) must not set a shorter maximum length for that field.
    
2.  Any [API Client](#definition-api-client) feature that initiates a user action related to a YouTube resource must be:
    
    1.  clearly and unequivocally identifiable as a YouTube action,
    2.  distinct and not mixed with your [API Client's](#definition-api-client) functionality, and
    3.  clearly initiated by the user.
    
    Examples of YouTube resources include videos, channels, playlists, playlist items, and subscriptions. Examples of actions include playing a video, liking a video, adding a video to a playlist, and subscribing to a channel.
    
3.  [API Clients](#definition-api-client) that perform write operations may suggest parameter or property values, but users must have final control over the data that will be published to [YouTube Applications](#definition-youtube-applications). Similarly, [API Clients](#definition-api-client) must not modify user-provided values before sending them to YouTube by truncating, appending, or otherwise altering those values unless the user has explicitly consented to such changes.
    
    [API Clients](#definition-api-client) that suggest values for text fields, like video titles or descriptions, must incorporate relevant keywords into those values. For example an [API Client](#definition-api-client) that suggests video titles should not generate the same default titles for all users.
    
    These examples illustrate how this policy would apply to an [API Client](#definition-api-client) that uploads videos to YouTube:
    
    1.  The [API Client](#definition-api-client) may suggest a video description or pre-populate the video description. However, it must not add information to the video description after it is submitted by the user and before it is sent without the user's prior consent. For example, the [API Client](#definition-api-client) must not append the recording date, [API Client](#definition-api-client) name, or any other text unless the user has explicitly consented to such changes.
        
    2.  An [API Client](#definition-api-client) may provide an option to translate a video title to other languages. However, the [API Client](#definition-api-client) must not add any such translations without the user's consent. In addition, if the [API Client's](#definition-api-client) default behavior is to enable the option to translate the video title, it must clearly present to the user an easy way to disable that behavior.
        
4.  [API Clients](#definition-api-client) must clearly indicate how user-provided data will be used on YouTube.
    
    This policy is particularly relevant for [API Clients](#definition-api-client) that interface with multiple services and platforms since there may be functional or labeling differences between those services and platforms.
    
    For example, an [API Client](#definition-api-client) enables users to add comments about videos to multiple platforms, including YouTube. Each platform uses a different name to refer to the comment text. So, if the [API Client](#definition-api-client) labels the field "Feedback" in its comment form, it needs to clearly indicate that that value corresponds to the comment text on YouTube.
    
5.  [API Clients](#definition-api-client) that use search functionality provided by [YouTube API Services](#definition-youtube-api-services) must not modify or replace the text, images, information, or other content of, the search results returned by those Services.
    
    For example, [API Clients](#definition-api-client) must not merge or intermix results from sources other than YouTube and present them as YouTube search results.
    
6.  An [API Client](#definition-api-client) should not limit or reduce the functionality of a YouTube feature unless that limitation is a core aspect (as described in the examples below) of the [API Client](#definition-api-client) itself and that YouTube feature is not required by the RMF ("**Permitted Feature Limitation**").
    
    1.  **Example 1: Permitted Feature Limitation**
        
        The YouTube Data API service allows a video uploader to provide translations of a video's title. Generally speaking, an [API Client](#definition-api-client) that implements this feature should allow uploaders to translate video titles to any language that YouTube supports. However, an [API Client](#definition-api-client) that is specifically designed to teach users to speak French and that offers a range of features specific to French translations might be justified in only offering users the option to upload French translations of video titles.
        
    2.  **Example 2: Non-permitted Feature Limitation**
        
        A second [API Client](#definition-api-client) supports video uploading to YouTube and two other platforms, and all of those platforms allow the uploader to provide translations of the video's title. However, while YouTube supports more than 70 languages, the other two platforms each support half that number, and the three platforms support 25 languages in common. If the [API Client](#definition-api-client) supports only those 25 languages for translation, then that is a non-permitted feature limitation because the limited set of language options is not a core aspect of the [API Client](#definition-api-client). Instead, the [API Client](#definition-api-client) must offer the full range of languages that YouTube supports.
        
7.  [API Clients](#definition-api-client) with Permitted Feature Limitations must explain to users why each limitation is in place and make clear that the limitation is not imposed by YouTube. In many, if not all, cases, there are different ways that an [API Client](#definition-api-client) could provide that information, and you should choose an appropriate method for your [API Client](#definition-api-client). Within this explanation, an [API Client](#definition-api-client) should provide a mechanism for users to access the full feature (such as linking to YouTube Creator Studio or providing an expandable menu within the API Client).
    
    In the example 1 above, the [API Client](#definition-api-client) could explain that video uploaders can add translations for other languages in the YouTube Creator Studio and provide a link to that functionality.
    
8.  [API Clients](#definition-api-client) that offer features sourced from multiple services and platforms should offer feature parity to the extent that it exists across those sources, providing user choice. When [API Clients](#definition-api-client) include features that are supported on YouTube and on other platforms, [API Clients](#definition-api-client) must not consistently present YouTube features in a detrimental way (e.g., by only providing those features from other platforms).
    
    For example, suppose an [API Client](#definition-api-client) allows users to upload videos to YouTube and three other platforms, and all of those platforms support the ability to upload captions. If the [API Client](#definition-api-client) also supports caption uploading, then it must support that feature for YouTube.
    

### D. Accessing YouTube API Services

1.  API Credentials
    
    To access or use some [YouTube API Services](#definition-youtube-api-services), you must first use the [Google Developers Console](https://console.developers.google.com/) ([https://console.developers.google.com/](https://console.developers.google.com/)) to create [API Credentials](#definition-api-credentials) for your [API Project](#definition-api-project"). Those credentials enable Google and YouTube to link API activity to a particular [API Project](#definition-api-project") and [API Client](#definition-api-client).
    
    In addition to creating [API Credentials](#definition-api-credentials), the Developers Console might require you to provide certain other information, such as identification or contact details, before you can access or use the [YouTube API Services](#definition-youtube-api-services) associated with those credentials. YouTube reserves the right to require you to provide additional information to continue to access or use [YouTube API Services](#definition-youtube-api-services).
    
    If you need to create [API Credentials](#definition-api-credentials) to access or use a specific YouTube API service, the documentation for that service explains how to create those credentials. For example, the [YouTube Data API service](https://developers.google.com/youtube/registering_an_application), [YouTube Reporting API service](https://developers.google.com/youtube/reporting/guides/registering_an_application), [YouTube Analytics API service](https://developers.google.com/youtube/reporting/guides/registering_an_application), and [Android Player API service](https://developers.google.com/youtube/android/player/register) all document steps for creating [API Credentials](#definition-api-credentials). Those steps generally differ slightly from one API service to another. For example:
    
    *   Some services only support authorized API requests, while others support authorized and non-authorized requests.
        
    *   Services often support multiple access scopes. Each scope specifies the resources that an [API Client](#definition-api-client) can retrieve, insert, update, or delete on the user's behalf. Scopes enable [API Clients](#definition-api-client) to only request access to the resources they need, and scopes also enable users to control the amount of access that they grant to those Clients.
        
    
    The following policies also apply to access and use of [YouTube API Services](#definition-youtube-api-services):
    
    1.  You must not mask or misrepresent your identity or your [API Client's](#definition-api-client) identity when accessing or using [YouTube API Services](#definition-youtube-api-services) or when creating an [API Project](#definition-api-project") or [API Credentials](#definition-api-credentials).
        
    2.  You must only use [API Credentials](#definition-api-credentials) assigned to you and to your [API Project](#definition-api-project") to access [YouTube API Services](#definition-youtube-api-services). Similarly, you must not use any other means to mask or misrepresent your [API Client's](#definition-api-client) access to, or usage of, [YouTube API Services](#definition-youtube-api-services).
        
    3.  If your [API Client](#definition-api-client) needs to create [API Credentials](#definition-api-credentials) to access or use [YouTube API Services](#definition-youtube-api-services), you must create exactly one (1) [API Project](#definition-api-project") for that [API Client](#definition-api-client). Those [API Credentials](#definition-api-credentials) are intended to be used exclusively by the associated API Client, which means that you must not use that one (1) [API Project](#definition-api-project") for multiple [API Clients](#definition-api-client).
        
    4.  You may share your [API Credentials](#definition-api-credentials) with agents operating solely on your behalf and under a written duty of confidentiality. However, you must not share or disclose your [API Credentials](#definition-api-credentials) to any other third party, allow access to or use of your [API Credentials](#definition-api-credentials) by any other third party, or embed your [API Credentials](#definition-api-credentials) in open source projects.
        
2.  User Authentication and Authorization
    
    Authentication and authorization refer to the process by which users identify themselves and consent to allow an [API Client](#definition-api-client) to access certain user-specific data. Some [YouTube API Services](#definition-youtube-api-services) do not support access to user-specific data and therefore, do not require any authorization, others require authorization for some requests or data, and still others require authorization for all requests. For example:
    
    *   The YouTube IFrame Player API service, which lets you embed videos in a website, does not require authorization just as users do not need to log in to the YouTube website to watch a video.
    *   The YouTube Data API service requires authorization for some actions. For example, an [API Client](#definition-api-client) can search for public videos but does not need user authorization to do so. However, an [API Client](#definition-api-client) does need user authorization to upload a video to the user's YouTube channel.
    *   The YouTube Analytics API service and YouTube Reporting API service require authorization for all actions.
    
    1.  Authentication
        
        1.  [API Clients](#definition-api-client) must not (and must not attempt to) obtain, proxy, request, collect, modify, cache, store, or use any information that the user provides or that YouTube displays to the user during authentication processes, including YouTube user account login credentials like usernames and passwords.
            
        2.  [API Clients](#definition-api-client) must obtain user consent in accordance with the applicable laws and only request access to authorization scopes that they currently use. The access that an [API Client](#definition-api-client) requests should have a direct and transparent benefit to users of that Client. Do not try to future-proof your access to data by asking for permissions that would enable features that you have not yet built.
            
            For example, the YouTube Data API service supports one authorization scope that grants access to read data and another that grants access to read and write data. If a user granted an [API Client](#definition-api-client) access to the first scope, that [API Client](#definition-api-client) would be able to retrieve information about the current user's YouTube channel. However, if a user granted the [API Client](#definition-api-client) access to the second scope, the [API Client](#definition-api-client) could also upload a video to that channel.
            
            In this scenario, an [API Client](#definition-api-client) that does not support YouTube uploads (or other write-based actions) only needs to request access to the first authorization scope, which is more limited in the privileges it grants. Even if the [API Client's](#definition-api-client) developer plans to eventually introduce support for write-based actions, the developer cannot future-proof the [API Client](#definition-api-client) by requesting access to the authorization scope for writing data before the [Client](#definition-api-client) actually supports features that require that scope.
            
        3.  [API Clients](#definition-api-client) should request access to authorization scopes in context whenever possible. By requesting access to user data in context, via incremental authorization, an [API Client](#definition-api-client) enables users to more easily understand why it needs access to that data.
            
    2.  API Client Identification and Representation
        
        1.  [API Clients](#definition-api-client) must clearly and accurately identify to the user the entity or product that is requesting access to user data and the reason for requesting that access;
            
        2.  [API Clients](#definition-api-client) must not mislead users when requesting access to data so that users can make an informed decision about whether to grant access to those Clients. Users should be able to readily understand both the value of providing the data that an [API Client](#definition-api-client) requests access to and the consequences of sharing that data.
            
        3.  [API Clients](#definition-api-client) must clearly and comprehensively identify to users the purposes for which they access and use user data. [API Clients](#definition-api-client) must not use user data for secondary purposes that are not clearly disclosed to users.
            
            Users should not be surprised to learn that an [API Client](#definition-api-client) contains hidden features, services, or actions that are inconsistent with the [Client's](#definition-api-client) marketed purposes.
            
    3.  Revocation
        
        1.  Every [API Client](#definition-api-client) must provide a clearly explained and easy way for users to revoke any authorization consent they have provided to an [API Client](#definition-api-client) to access [YouTube API Services](#definition-youtube-api-services).
            
            When a user revokes consent through this mechanism, the [API Client](#definition-api-client) must programmatically revoke that token right away to communicate the change in permissions to Google. For example, an [API Client](#definition-api-client) could use a Google API Client Library to revoke the token.
            
            In addition, following revocation of consent through this mechanism, you and your [API Clients](#definition-api-client) must delete all [Authorized Data](#definition-authorized-data) that was accessed or stored pursuant to that consent. That deletion should happen as soon as possible and must take place within 7 calendar days of the revocation.
            
        2.  As noted in section (III.A.2.i), every [API Client](#definition-api-client) must include in its Privacy Policy a link to Google's security settings page ([https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions)). When a user revokes consent through that page, you and your [API Clients](#definition-api-client) must also delete all [API Data](#definition-api-data) related to that user that was accessed or stored pursuant to such consent. To comply with this policy, your [API Clients](#definition-api-client) will need to periodically reconfirm that its authorization tokens are still valid and delete [API Data](#definition-api-data) associated with users whose authorization tokens cannot be refreshed.
            
            Based on the requirements defined in section (III.E.4) regarding stored data, all such deletions should happen as soon as possible and must take place within 30 calendar days of that revocation.
            
3.  Usage and Quotas
    
    YouTube may use quotas and place use restrictions to ensure that [YouTube API Services](#definition-youtube-api-services) are accessed and used as intended and that you and your [API Clients](#definition-api-client) do not reduce service quality or limit access for others.
    
    If your [API Client](#definition-api-client) reaches the quota limit for a service, you can apply for a quota extension using [this form](https://support.google.com/youtube/contact/yt_api_form). In that case, your quota extension application must specify the use case for which you need the extension.
    
    If YouTube approves the application, you must use the additional quota granted only for the use case that YouTube approved. If your [API Client's](#definition-api-client) use case changes, you must notify YouTube of the change by completing a use-case change request application prior to using the quota extension for that non-approved use case.
    
4.  Inactivity
    
    YouTube reserves the right to disable or curtail your access to, or use of, specific [YouTube API Services](#definition-youtube-api-services) if your [API Project](#definition-api-project") has been inactive for 90 consecutive days. For example, YouTube could revoke your [API Credentials](#definition-api-credentials), or reduce (or eliminate) your [API Project's](#definition-api-project") quotas for specific [YouTube API Services](#definition-youtube-api-services). If your [API Client's](#definition-api-client) quota is reduced or eliminated, you may reapply for quota or a quota extension, and YouTube will review that application based on YouTube’s determination of your expected use of the [YouTube API Services](#definition-youtube-api-services).
    
5.  Contact Information
    
    YouTube’s primary means of contacting you about your [API Project](#definition-api-project") or [API Client](#definition-api-client) is the email address that is associated with the Google Account that you use to log in to the Google Developers Console. You must comply to any communication that YouTube sends you regarding compliance issues relating to your [API Clients](#definition-api-client).
    
    If users of your [API Client](#definition-api-client) have questions about your privacy practices, and you do not have a contact address in your [API Client's](#definition-api-client) privacy policy as discussed in section (A.2.i), YouTube may share your primary email address with those users.
    
6.  Prohibited Access
    
    You are prohibited from accessing or attempting to access [YouTube API Services](#definition-youtube-api-services) via any means if your [API Credentials](#definition-api-credentials) are suspended, revoked, or terminated, or if the Google Account you used to create those credentials is suspended or terminated, for any reason. In that case, you must not access or attempt to access [YouTube API Services](#definition-youtube-api-services) via any means, including by creating or using a proxy to create new Google Accounts, [API Credentials](#definition-api-credentials) or [API Projects](#definition-api-project).
    
7.  Undocumented Services
    
    You must not use undocumented APIs without express permission. You must access data from YouTube API services only according to the means stipulated in the authorized documentation of that YouTube API service.
    
    You must not reverse engineer undocumented YouTube API services or otherwise attempt to derive the underlying source code of these API services.
    

### E. Handling YouTube Data and Content

Aside from the permissions and rights granted in this section, you and your [API Clients](#definition-api-client) have no further permissions or rights to [API Data](#definition-api-data), including to temporarily stored [API Data](#definition-api-data).

1.  Audiovisual Content
    
    You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:
    
    1.  download, import, backup, cache, or store copies of YouTube audiovisual content without YouTube's prior written approval,
    2.  make content available for offline playback, or
    3.  use any aspect of the [YouTube API Services](#definition-youtube-api-services) to facilitate or promote copyright infringement or the exploitation of copyright-infringing materials.
2.  Data Aggregation
    
    1.  Do not aggregate [API Data](#definition-api-data) except that you may only aggregate [API Data](#definition-api-data) relating to YouTube channels that are under the same content owner as recognized by YouTube pursuant to content licensing agreement(s) between YouTube and such content owner. Such aggregated [API Data](#definition-api-data) must only be viewable by that content owner.
        
    2.  Do not aggregate [API Data](#definition-api-data) or otherwise use [API Data](#definition-api-data) or [YouTube API Services](#definition-youtube-api-services) to gain insights into YouTube's usage, revenue, or any other aspects of YouTube's business.
        
        For example, suppose that two different content owners recognized by YouTube have each authorized an [API Client](#definition-api-client) to retrieve [API Data](#definition-api-data) on their behalf for their respective viewing. That [API Client](#definition-api-client) may separately aggregate [API Data](#definition-api-data) retrieved for each content owner's channels provided that such aggregation per content owner does not provide insights into YouTube’s usage, revenue or any other aspects of YouTube’s business. The [API Client](#definition-api-client) must not combine [API Data](#definition-api-data) from the different content owners.
        
3.  Authorized Data Usage
    
    These policies relate to your use of [Authorized Data](#definition-authorized-data). They are relevant for any [API Client](#definition-api-client) that writes data via an API request or retrieves data that can only be accessed via a properly authorized API request. For example, these policies apply to any [API Client](#definition-api-client) that enables a user to upload videos, retrieve the user's list of uploaded videos, create playlists, or comment on videos.
    
    1.  [API Clients](#definition-api-client) must be honest and transparent about the types of user data and the purposes for which they collect, store, delete, share, safeguard, and otherwise use that data.
        
    2.  [API Clients](#definition-api-client) must not display or allow access to [Authorized Data](#definition-authorized-data) to anyone other than the authorizing user or agents expressly approved by that user.
        
    3.  [API Clients](#definition-api-client) must only access, collect and use [Authorized Data](#definition-authorized-data) in accordance with the scope of its privacy policy and user consent obtained in accordance with Section 2.
        
        This means that an [API Client](#definition-api-client) must prompt users to re-accept its privacy policy if the [Client](#definition-api-client) starts to access, collect, or use [API Data](#definition-api-data) in a way or for purposes that were not covered in the privacy policy that the user originally accepted.
        
    4.  [API Clients](#definition-api-client) must clearly identify any actions that they take to insert, share, update, or delete data or content on the authorizing user's behalf. In addition, the user must expressly consent to those actions prior to their actual execution.
        
    5.  [API Clients](#definition-api-client) must clearly identify the YouTube channel or content owner that is associated with any request that requires user authorization.
        
    6.  [API Clients](#definition-api-client) must clearly identify any content visibility settings that will be set or modified by any authorized user action. In addition, [API Clients](#definition-api-client) must not modify existing content visibility settings unless the authorizing user has expressly instructed the [API Clients](#definition-api-client) to do so.
        
        For example, in the YouTube Data API service, a video's privacy status can be set to `public`, `private`, or `unlisted`. If an [API Client](#definition-api-client) supports video uploads, the [Client](#definition-api-client) must clearly display an option for the user to choose one of those values. Similarly, if an [API Client](#definition-api-client) supports edits to a video's metadata, the [API Client](#definition-api-client) cannot change a video's privacy status without the user's express consent.
        
4.  Refreshing, Storing, and Displaying API Data
    
    Developers often need to balance the benefits of storing or caching data, such as improved performance or resource usage, with the desire to always retrieve the freshest data, which provides the best user experience possible. With that in mind, the following policies explain your requirements as well as your options in terms of storing, updating, and displaying YouTube [API Data](#definition-api-data).
    
    1.  [API Clients](#definition-api-client) may store authorization tokens for as long as is necessary provided that those tokens are used only for purposes consistent with the specific consent granted by an active user according to the applicable law.
        
    2.  [API Clients](#definition-api-client) may store the following types of [Authorized Data](#definition-authorized-data) for as long as is necessary provided that the data is used for purposes consistent with the specific consent granted by an active user according to the applicable laws:
        
        1.  data retrieved through the YouTube Analytics API service,
        2.  data provided through the YouTube Reporting API service, or
        3.  statistics provided through other YouTube API services, such as the number of views for a video, the number of channels for a subscriber, or the number of videos in a playlist. (All of those statistics can be retrieved via the YouTube Data API service.)
        
        Note that even though an [API Client](#definition-api-client) may store this data for more than 30 days, the [Client](#definition-api-client) must still ensure every 30 days that it is still authorized by the user to access that data.
        
        For example, an [API Client](#definition-api-client) may store view counts for a video for more than 30 days, but it must still verify every 30 days that its authorization to access the video uploader's data has not been revoked. The [API Client](#definition-api-client) must also verify, every 30 days, that the video has not been deleted.
        
        To be clear, an [API Client](#definition-api-client) must not store statistics retrieved as [Non-Authorized Data](#definition-non-authorized-data) for more than 30 days. For example, an [API Client](#definition-api-client) must not store the subscriber count for a YouTube channel for more than 30 days without authorization from the channel owner.
        
    3.  [API Clients](#definition-api-client) may store all other types of [Authorized Data](#definition-authorized-data) not identified in section (III.E.4.b) for as long as is necessary for the purposes of the specific consent granted by an active user and for no longer than 30 calendar days. After 30 calendar days, the [API Client](#definition-api-client) must either delete or refresh the stored data.
        
    4.  [API Clients](#definition-api-client) may temporarily store limited amounts of [Non-Authorized Data](#definition-non-authorized-data) for as long as is necessary for the purposes of the [API Client](#definition-api-client) but not longer than 30 calendar days. As in section (III.E.4.c) immediately above, this means that after 30 calendar days, the [API Client](#definition-api-client) must either delete or refresh the stored data.
        
    5.  In all cases, [API Clients](#definition-api-client) must use reasonable efforts to ensure that their stored [API Data](#definition-api-data) is consistent with the current data available through [YouTube API Services](#definition-youtube-api-services). For example, [API Clients](#definition-api-client) should reflect metadata changes and viewcount updates as quickly as possible.
        
    6.  [API Clients](#definition-api-client) must display the most updated [API Data](#definition-api-data) available in their user-facing presentations, including in user interfaces, although [API Clients](#definition-api-client) may display historical [API Data](#definition-api-data) provided that it is presented accurately in context of time.
        
    7.  Your [API Clients](#definition-api-client) that access or use user data must provide a way for a user to request that you delete stored data related to that user. For example, your [API Client](#definition-api-client) could display a button to delete stored data. If the user indicates that you should delete that data, you must then delete it as soon as possible and within 7 calendar days.
        
        The method for deleting stored data must make clear that deleting the data stored by the [API Client](#definition-api-client) does not, in any way, affect data stored by YouTube and that to delete data on YouTube, the user needs to use a YouTube Application or an authorized [API Client](#definition-api-client) that supports the ability to delete that data.
        
        Similarly, [API Clients](#definition-api-client) must respect any other means by which a user expresses an intent to prevent those Clients from accessing user data related to that user. For example, if a user deletes his account from your API Client, you must also delete any user data you have stored related to that user as soon as possible and within 7 calendar days.
        
    8.  Your [API Clients](#definition-api-client) must not (i) replace [API Data](#definition-api-data) with similar, independently calculated data, or (ii) access or use [API Data](#definition-api-data) to create new or derived data or metrics.  To the extent your [API Clients](#definition-api-client) display any information, data or metrics not based on [API Data](#definition-api-data) alongside [API Data](#definition-api-data), your [API Clients](#definition-api-client) must include a clear and prominent disclosure there that such information, data and metrics are not from YouTube and are part of your own product.
        
        For example, when displaying the number of likes for a video, your [API Client](#definition-api-client) must use the number returned in the [API Data](#definition-api-data). You must not substitute a different number to represent likes, such as the number of users of your [API Client](#definition-api-client) that liked the video. Similarly, you are not permitted to use the number of likes returned in the [API Data](#definition-api-data) to calculate other metrics, such as the percentage of total likes that were made through your [API Client](#definition-api-client) or a score that factors in likes, total views, or any other [API Data](#definition-api-data). However, you are permitted, for example, to display the number of likes that were made through your [API Client](#definition-api-client) as long as that number is displayed alongside the total likes returned in the [API Data](#definition-api-data) and as long as your [API Client](#definition-api-client) clearly communicates that the [API Client](#definition-api-client) calculates the additional metric independently of YouTube [API Data](#definition-api-data).
        
    9.  When your [API Client](#definition-api-client) loads, it collects and shares some basic user data with YouTube via the YouTube embedded player to render the video thumbnail and title, determine playability and content restrictions, and for fraud and abuse reasons. Additional data is collected and shared by your [API Client](#definition-api-client) upon video playback to customize the player on your [API Client](#definition-api-client) and third party sites and apps. Remember that if you enable Autoplay, playback will occur without any user interaction with the player; playback data collection and sharing will therefore occur upon page load. You can limit the data shared with YouTube before a user interacts with the YouTube embedded player by setting Autoplay to `false`. As noted in the [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service), you and your [API Clients](#definition-api-client) must comply with all applicable laws, rules, and regulations, including privacy laws and regulations.
        
    10.  [API Clients](#definition-api-client) must look up the Made For Kids status of each YouTube video that it embeds on its site or app by following the instructions in [this guide](https://developers.google.com/youtube/v3/guides/made_for_kids_status). For each video that is designated Made For Kids, [API Clients](#definition-api-client) must turn off tracking and make sure that all data collection with respect to that player is compliant with applicable law(s) including the U.S. Children's Online Privacy (COPPA) and E.U. General Data Protection Regulation (GDPR)). See the [YouTube Help Center](https://support.google.com/youtube/answer/9528076) for more information on determining content as Made for Kids.
        
5.  Security
    
    You and your [API Client](#definition-api-client) must:
    
    1.  maintain appropriate administrative, organisational, technical, and physical controls to ensure the privacy, security, and confidentiality of user data and [API Data](#definition-api-data);
    2.  use only industry-standard transport encryption;
    3.  protect [API Data](#definition-api-data) and any other data used in your [API Client](#definition-api-client) from unauthorized access, use, or disclosure.
6.  Scraping
    

You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to, directly or indirectly, scrape [YouTube Applications](#definition-youtube-applications) or [Google Applications](#definition-google-applications), or obtain scraped YouTube data or content. Public search engines may scrape data only in accordance with YouTube's robots.txt file or with YouTube's prior written permission.

### F. User Experience

1.  YouTube Look and Feel
    
    Innovative user experiences and user interface designs are among the most valuable contributions that [API Clients](#definition-api-client) can provide to the YouTube community. That said, YouTube's designers and engineers put a lot of thought into designing [YouTube Applications](#definition-youtube-applications) to ensure that those Applications provide a great user experience.
    
    Taking both of those points into account, your [API Clients](#definition-api-client) must not change or interfere with user interfaces in [YouTube Applications](#definition-youtube-applications) unless you have obtained YouTube's prior written approval. You can request that approval at [this form](https://support.google.com/youtube/contact/yt_api_form).
    
2.  Branding
    
    1.  Any [API Client](#definition-api-client) page or feature that displays YouTube content – including, without limitation, search results, YouTube videos, channels, playlists, thumbnails, and YouTube players – must make clear to the viewer that YouTube is the source of the relevant content by displaying [YouTube Brand Features](#definition-youtube-brand-features) in accordance with the requirements below and the YouTube Branding Guidelines ([https://developers.google.com/youtube/terms/branding-guidelines](https://developers.google.com/youtube/terms/branding-guidelines)).
        
        In some cases, an [API Client](#definition-api-client) might need to display [YouTube Brand Features](#definition-youtube-brand-features) next to multiple individual content elements to make the attribution clear to the viewer. For example, an [API Client](#definition-api-client) that displays search results from YouTube and from other sources on the same page needs to clearly identify YouTube as the source of only the search results from YouTube, including text, images, and other information pertaining to YouTube search results. The [API Client](#definition-api-client) cannot provide one general set of attribution for all search results from various sources.
        
    2.  Content that does not originate from YouTube must not be shown in a way that suggests that the content is originating from YouTube or in a way that can cause confusion as to the origin of that content.
        
    3.  You and your [API Clients](#definition-api-client) must not, and must not encourage, enable or require others to, directly or indirectly, interfere with or obscure any attribution provided by YouTube, including attribution provided via or shown in embedded YouTube players. Your [API Clients](#definition-api-client) must display applicable [YouTube Brand Features](#definition-youtube-brand-features) and any other YouTube-provided attribution on all types of devices.
        
3.  Playback Integrity
    
    Playback integrity refers to the ability to determine and measure how content and ads are served, how video playback is initiated and implemented, and how users interact with YouTube features in your [API Client](#definition-api-client). Playback integrity is critical to the YouTube platform, as it helps protect creators' interests, including their ability to monetize their content and develop their audience.
    
    YouTube believes that playback integrity is contingent on a user choosing to watch a video, and [API Clients](#definition-api-client) are prohibited from providing incentives for watching videos as follows:
    
    1.  [API Clients](#definition-api-client) must not charge users to watch content in an embedded YouTube player.
        
    2.  [API Clients](#definition-api-client) must not otherwise gate access to a video by requiring a user to take an action other than clicking the play button to view or continue playing YouTube audiovisual content. For example, [API Clients](#definition-api-client) must not require a user to subscribe to a channel or like a video to continue watching YouTube audiovisual content.
        
        For clarity, if your [API Client's](#definition-api-client) normal functionality requires a certain action that is not specific to [YouTube API Services](#definition-youtube-api-services), such as login or age verification, that functionality is allowed.
        
    3.  [API Clients](#definition-api-client) must not offer or provide incentives, rewards, or other compensation to users for engaging with [YouTube Applications](#definition-youtube-applications) (directly or indirectly) by performing actions like viewing content, liking content, sharing content, subscribing to channels, adding comments. For example, [API Clients](#definition-api-client) must not offer features or services that trade video views for a fee or that trade video views in return for other YouTube-related or non-YouTube-related actions.
        

### G. Distribution and Commercial Use

You may distribute or sell [API Clients](#definition-api-client) subject to the restrictions defined in the "Prohibited Actions" subsection below and, of course, to the other terms of the [Agreement](#definition-agreement).

In addition, you may distribute and display YouTube audiovisual content and accompanying metadata to users through your [API Clients](#definition-api-client) as long as those Clients comply with the [Agreement](#definition-agreement) and, specifically, do not engage in any of the prohibited actions listed immediately below.

1.  Prohibited Actions
    
    For specific policies in the following list that require YouTube's prior written approval, you can request that approval at [this form](https://support.google.com/youtube/contact/yt_api_form).
    
    You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:
    
    1.  sell, purchase, lease, lend, convey, redistribute, or sublicense all or any portion of [YouTube API Services](#definition-youtube-api-services), including YouTube audiovisual content;
        
    2.  sell [YouTube API Services](#definition-youtube-api-services) or access to any components of [YouTube API Services](#definition-youtube-api-services) unless you obtain YouTube's prior written approval;
        
    3.  sell advertising, sponsorships, or promotions that are placed on or within YouTube audiovisual content or the YouTube player without YouTube's prior written approval; or
        
    4.  sell advertising, sponsorships, or promotions on any page or screen that contains [YouTube API Data](#definition-api-data) unless other data, content, or material not obtained from YouTube appears on the same page and offers enough independent value to justify such sales if the [YouTube API Data](#definition-api-data) were removed.
        
2.  Permitted Actions
    
    All of the following commercial use cases are permitted subject to your and Your [API Clients](#definition-api-client)’ compliance with all other terms of the [Agreement](#definition-agreement), including the prohibited actions detailed in the previous section:
    
    1.  Selling an API Client;
        
    2.  Promoting your own business or artistic enterprise by uploading original audiovisual content to YouTube or maintaining channel(s) on YouTube;
        
    3.  Developing ad-enabled [API Clients](#definition-api-client), such as an ad-enabled blog or website, that use [YouTube API Services](#definition-youtube-api-services) subject to compliance with all other terms of the Agreement, including the restrictions in section III.G.1.d;
        
    4.  Placing your own branding in an [API Client](#definition-api-client) as long as that branding complies with the [YouTube Branding Guidelines](https://developers.google.com/youtube/terms/branding-guidelines) and does not interfere with YouTube audiovisual content playback or any [YouTube Brand Features](#definition-youtube-brand-features);
        
    5.  Selling or distributing devices that contain or run an API Client;
        

### H. Monitoring and Audits

YouTube reserves the right to survey, monitor, and/or audit your access to or use of [YouTube API Services](#definition-youtube-api-services) to ensure quality, to improve YouTube products and services, and to verify your compliance with the [Agreement](#definition-agreement). To that end, YouTube may survey users of your [API Clients](#definition-api-client).

You and those acting on your behalf must:

1.  not interfere with such surveys, monitoring efforts, or audits;
2.  not obscure or conceal from YouTube your access to or use of [YouTube API Services](#definition-youtube-api-services); and
3.  upon request, and within the timeframe stated in that request, provide YouTube with account(s) necessary to access all features or functions of the current, in-production version(s) of your [API Clients](#definition-api-client), so that YouTube may review those [API Clients](#definition-api-client) for compliance with the [Agreement](#definition-agreement).

YouTube may use any technical means to overcome non-compliance with these provisions.

### I. Additional Prohibitions

The policies in this section identify additional things that [API Clients](#definition-api-client) must not do. Actions contrary to these policies would be harmful to YouTube, to the YouTube community as a whole, or to individuals or groups of individuals within that community. These policies focus on the need for you and your [API Clients](#definition-api-client) to treat members of the YouTube community honestly and respectfully as well as on your need to respect the integrity of YouTube's services, content, and interests.

You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:

1.  use [YouTube API Services](#definition-youtube-api-services) to create, offer, or act as a substitute for, or substantially similar service to, any [YouTube Applications](#definition-youtube-applications). [API Clients](#definition-api-client) must not mimic or replicate YouTube's core user experiences by recreating features or process flows unless they add significant independent value or functionality that improves users' interactions with YouTube. For example, an [API Client](#definition-api-client) must not recreate the browse experience from any YouTube Application without adding significant independent value to that flow.
    
2.  misuse [YouTube API Services](#definition-youtube-api-services) or engage in abusive behaviors related to those Services. For example, you must not automate or trigger views, uploads, comments, likes, dislikes, or other actions without the user's prior specific and express consent;
    
3.  interfere, or attempt to interfere, in any way with the proper workings of any aspect of [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), or [Google Applications](#definition-google-applications), including interference or disruption of the servers or networks that provide those Services or Applications;
    
4.  modify, interfere with, replace, or otherwise disable any functionality, data, or content made available as part of, or in connection with, [YouTube API Services](#definition-youtube-api-services). For example, you must not remove, obscure, alter, or disable any links that appear in YouTube players or in [API Data](#definition-api-data).
    
5.  modify, interfere with, replace, or block advertisements placed or served by YouTube or by [YouTube API Services](#definition-youtube-api-services) including in [API Data](#definition-api-data), YouTube audiovisual content, or YouTube players;
    
6.  modify, build upon, or block any portion or functionality of a YouTube player;
    
7.  separate, isolate, or modify the audio or video components of any YouTube audiovisual content made available as part of, or in connection with, [YouTube API Services](#definition-youtube-api-services). For example, you must not apply alternate audio tracks to videos;
    
8.  promote separately the audio or video components of any YouTube audiovisual content made available as part of, or in connection with, the [YouTube API Services](#definition-youtube-api-services);
    
9.  create, include, or promote features that play content, including audio or video components, from a background player, meaning a player that is not displayed in the page, tab, or screen that the user is viewing;
    
10.  adversely affect the functionality or performance of any aspect of [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), or [Google Applications](#definition-google-applications), including actions that interfere with or disrupt [YouTube API Services](#definition-youtube-api-services) or the servers or networks that provide those Services;
    
11.  confuse, deceive, defraud, mislead, misrepresent, defame, abuse, stalk, threaten, spam, surprise, or harass anyone;
    
12.  introduce, or attempt to introduce, any viruses, worms, defects, Trojan horses, malware, spyware, adware, or other items of a destructive nature to [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), [Google Applications](#definition-google-applications), or YouTube users and the devices they use to access those services and properties;
    
13.  circumvent, interfere with, or render ineffective, any geographical restrictions, including IP address-based restrictions imposed by YouTube or [YouTube API Services](#definition-youtube-api-services);
    
14.  use any technology other than [YouTube API Services](#definition-youtube-api-services) to access or retrieve [API Data](#definition-api-data), including to access any portion of any YouTube audiovisual content;
    
15.  offer an API service that allows users to access any data or functionality directly or indirectly provided by the [YouTube API Services](#definition-youtube-api-services);
    
16.  modify, translate, create derivative works of, reverse engineer or otherwise attempt to extract the underlying source code from any [YouTube API Services](#definition-youtube-api-services) or from any software related to those Services;
    
17.  use [YouTube API Services](#definition-youtube-api-services) for any purpose or activity where the use or failure of those Services could lead to death, personal injury, or environmental damage, such as in the operation of nuclear facilities, air traffic control systems, or life support systems;
    
18.  infringe copyrights or exploit copyright-infringing materials;
    
19.  engage in, promote or facilitate unlawful online gambling; or
    
20.  create, display, promote or facilitate disruptive commercial messages or advertisements.
    

### J. Child-Directed API Clients

1.  If your API Client (or any part thereof) targets or directs itself to children (as defined under applicable law(s) including the U.S. Children's Online Privacy (COPPA) and E.U. General Data Protection Regulation (GDPR)) (referred to herein as a "**Child-Directed API Client**"), you and your Child-Directed API Client must:
    
    1.  ensure that your Child-Directed API Client, including its access to and use of any YouTube API Services, is compliant with COPPA, GDPR, and any other applicable laws or regulations at all times;
        
    2.  notify Google of the child directed nature of your Child-Directed API Client using the tools provided in [here](https://support.google.com/policies/answer/9664901). Each Child-Directed API Client notified to Google using such tools or otherwise is referred to herein as a "**Known Child-Directed API Client**"; and
        
    3.  not use personalized ads (including remarketing) to target past or current activity by any user of your Child-Directed API Client.
        
2.  1.  **For You and Your Child-Directed API Client.** You and your Child-Directed API Client will not, and must not attempt to, take any YouTube API Services write-based actions to YouTube websites, applications, services or products via your Child-Directed API Client.
        
    2.  Notwithstanding Section III.D.1.c (API Credentials) above which requires exactly one (1) [API Project](#definition-api-project) for each [API Client](#definition-api-client), you can upload your own videos to your own official YouTube channel(s) via the YouTube Data API Service (not via your Child-Directed API Client or anyone else’s API Client) by creating a new API Project ("**Upload Project**").
        
        1.  To upload your own videos to your own official YouTube channel(s) via YouTube Data API Service, you must (A) create one (1) new [API Project](#definition-api-project) using the [Google Developers Console](https://console.developers.google.com/) ([https://console.developers.google.com/](https://console.developers.google.com/)) (an "**Upload Project**") prior to uploading, (B) append _mfk110_ as a prefix in the ID of your Upload Project, and (C) only upload from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else’s API Client); and
            
        2.  Only you can use the Upload Project, and the Upload Project must only be used to upload your own videos to your own official YouTube channel(s) via the YouTube Data API Service from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else’s API Client). If you are uploading a Made for Kids video via the YouTube Data API Service from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else’s API Client), you must designate the YouTube Data API Service Made for Kids parameter as "true". See here for more information on determining if content is [Made for Kids](https://support.google.com/youtube/answer/9528076).
            
    3.  **For You and Users of Your Child-Directed API Client.** You and your Child-Directed API Client must not enable, encourage or require, users of your Child-Directed API Client to take YouTube API Services write-based actions (such as, but not limited to, uploading content, commenting and creating/sharing playlists). YouTube API Services write-based actions taken by users of Known Child-Directed API Clients will not be implemented on YouTube websites, applications, services and products. This means that, notwithstanding [Section 9.1 (Required Notice) of the YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service) pursuant to which users of your API Client may upload content to their YouTube channels or your YouTube channel(s), uploads from users of Known Child-Directed API Clients will not be implemented on YouTube websites, applications, services and products.
        
3.  You and your API Client’s access to, or use of, YouTube API Services can be suspended or terminated by YouTube for non-compliance with the YouTube API Services Terms of Service and Policies including non-compliance with this Section III.J.
    

### K. Reporting Noncompliance

If you are aware of anyone accessing or using [YouTube API Services](#definition-youtube-api-services) in a manner that is not compliant with these policies or any other part of the [Agreement](#definition-agreement), you may contact the YouTube API Services team to escalate the issue [using this form](https://support.google.com/youtube/contact/yt_api_form).

IV. Definitions
---------------

"**Agreement**" means the legal documents defined and referenced in Section 2 (The Agreement) of the YouTube API Services [Terms of Service](#definition-terms-of-service) currently located at [https://developers.google.com/youtube/terms/api-services-terms-of-service](https://developers.google.com/youtube/terms/api-services-terms-of-service).

"**API Client**" means a website or software application (including a mobile application) developed by you that accesses or uses the [YouTube API Services](#definition-youtube-api-services).

"**API Credentials**" means the credentials assigned by YouTube or Google via the Google Developer Console that each [API Project](#definition-api-project") authenticates with to access and use the [YouTube API Services](#definition-youtube-api-services).

"**API Data**" is defined within the definition of "[YouTube API Services](#definition-youtube-api-services)" later in this Definitions section.

"**API Project**" means the project created in the Google Developer Console that is required for API Client(s) to access and use the [YouTube API Services](#definition-youtube-api-services).

"**Authorized Data**" means [API Data](#definition-api-data) that an active user expressly authorizes an [API Client](#definition-api-client) to access or otherwise use via [User Credentials](#definition-user-credentials).

"**Google Applications**" means Google websites, applications, services, products, pages, and other properties.

"**Non-Authorized Data**" means [API Data](#definition-api-data) accessible by an [API Client](#definition-api-client) without [User Credentials](#definition-user-credentials).

"**Terms of Service**" means the YouTube API Services Terms of Service currently located at [https://developers.google.com/youtube/terms/api-services-terms-of-service](https://developers.google.com/youtube/terms/api-services-terms-of-service).

"**User Credentials**" means the credentials issued to users that users can authenticate with to permit API Client(s) to perform operations on their behalf that require authorization.

"**YouTube API Services**" means (i) the YouTube API services (e.g., YouTube Data API service and YouTube Reporting API service) made available by YouTube including those YouTube API services made available on the YouTube Developer Site (as defined below), (ii) documentation, information, materials, sample code and software (including any human-readable programming instructions) relating to YouTube API services that are made available on [https://developers.google.com/youtube](https://developers.google.com/youtube) or by YouTube, (iii) data, content (including audiovisual content) and information provided to [API Clients](#definition-api-client) (as defined above) through the YouTube API services (the "[API Data](#definition-api-data)"), and (iv) the credentials assigned to you and your API Client(s) by YouTube or Google.

"**YouTube Applications**" means YouTube websites, applications, services, products, pages, and other properties, including **https://www.youtube.com**, **m.youtube.com**, mobile applications like the YouTube Gaming application, and so forth, but excluding [YouTube API Services](#definition-youtube-api-services).

"**YouTube Brand Features**" means the trade names, trademarks, service marks, logos, domain names, and other distinctive brand features of YouTube.