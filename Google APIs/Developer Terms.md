Google API Services User Data Policy

Stay organized with collections Save and categorize content based on your preferences.


==============================================================================================================================

_Last updated February 15, 2024_

Google API Services, including Google Sign-In, are part of an authentication and authorization framework that gives you, the developer, the ability to connect directly with Google users when you would like to request access to Google user data. The policy below, as well as the [Google APIs Terms of Service](https://developers.google.com/terms), govern the use of Google API Services when you request access to Google user data. Please check back from time to time as these policies are occasionally updated.

Accurately represent your identity and intent
---------------------------------------------

If you wish to access Google user data you must provide Google users and Google with clear and accurate information regarding your use of Google API Services. This includes, without limitation, requirements to accurately represent:

* **Who is requesting Google user data?** All permission requests must accurately represent the identity of the application that seeks access to user data. If you have obtained authorized client credentials to access Google API Services, keep these credentials confidential.
* **What data are you requesting?** You must provide clear and accurate information explaining the types of data being requested. In addition, if you plan to access or use a type of user data that was not originally disclosed in your privacy policy (or in-product disclosures) when a Google user initially authorized access, you must update your privacy policy and prompt the user to consent to any changes before you may access that data.
* **Why are you requesting Google user data?** Be honest and transparent with users when you explain the purpose for which your application requests user data. If your application requests data for one reason but the data will also be utilized for a secondary purpose, you must notify Google users of both use cases. As a general matter, users should be able to readily understand the value of providing the data that your application requests, as well as the consequences of sharing that data with your application.

Be transparent about the data you access with clear and prominent privacy disclosures
-------------------------------------------------------------------------------------

You must publish a privacy policy that fully documents how your application interacts with user data. You must list the privacy policy URL in your OAuth client configuration when your application is made available to the public.

**Your Privacy Policy and all in-product privacy notifications should be accurate, comprehensive, and easily accessible.** Your privacy policy and in-product privacy notifications must thoroughly disclose the manner in which your application accesses, uses, stores, or shares Google user data. Your use of Google user data must be limited to the practices explicitly disclosed in your published privacy policy, but you should consider the use of additional in- product notifications to ensure that users understand how your application will handle user data. If you change the way your application uses Google user data, you must notify users and prompt them to consent to an updated privacy policy before you make use of Google user data in a new way or for a different purpose than originally disclosed.

**Disclosures about data use should be prominent and timely.** Your privacy policy and any in-product notifications regarding data use should be prominently displayed in your application interface so that users can find this information easily. Where possible, disclosures about data use should be timely and shown in context.

Request the minimum relevant permissions
----------------------------------------

Permission requests should make sense to users, and should be limited to the critical information necessary to implement your application.

**Don't request access to information that you don't need.** Only request access to the permissions necessary to implement your application's features or services. If your application does not require access to specific permissions, then you must not request access to these permissions. Don't attempt to "future proof" your access to user data by requesting access to information that might benefit services or features that have not yet been implemented.

**Request permissions in context where possible.** Only request access to user data in context (via incremental auth) whenever you can, so that users understand why you need the data.

Deceptive or unauthorized use of Google API Services is prohibited
------------------------------------------------------------------

You are strictly prohibited from engaging in any activity that may deceive users or Google about your use of Google API Services. This includes without limitation the following requirements:

**Do not misrepresent what data is collected or what you do with Google user data.** Be up front with users so that they can make an informed decision to grant authorization. You must disclose all user data that you access, use, store, delete, or share, as well as any actions you take on a user's behalf.

You are not permitted to access, aggregate, or analyze Google user data if the data will be displayed, sold, or otherwise distributed to a third party conducting surveillance.

Overall there should be no surprises for Google users: hidden features, services, or actions that are inconsistent with the marketed purpose of your application may lead Google to suspend your ability to access Google API Services.

**Do not mislead Google about an application's operating environment.** You must accurately represent the environment in which the authentication page appears. For example, don't claim to be an Android application in the user agent header if your application is running on iOS, or represent that your application's authentication page is rendered in a desktop browser if instead the authentication page is rendered in an embedded web view.

**Do not use undocumented APIs without express permission.** Don't reverse engineer undocumented Google API Services or otherwise attempt to derive or use the underlying source code of undocumented Google API Services. You may only access data from Google API Services according to the means stipulated in the official documentation of that API Service, as provided on Google's [Developer Page](https://developers.google.com/).

**Do not make false or misleading statements about any entities that have allegedly authorized or managed your application.** You must accurately represent the company, organization, or other authority that manages your application. Making false representations about client credentials to Google or Google users is grounds for suspension.

Child-directed apps
-------------------

The Children's Online Privacy Protection Act, or [COPPA](https://www.ftc.gov/tips-advice/business-center/privacy-and-security/children%27s-privacy), applies to websites, apps, and services directed to children under the age of 13 and general audience apps, websites, or services with users known to be under the age of 13. While [child-directed apps may use some Google services](https://play.google.com/about/families/coppa-compliance/child-directed/), developers are responsible for using these services according to their obligations under the law. Please review the FTC's guidance on COPPA (including information about the differences between mixed audience apps and apps directed primarily to children from the [FTC's website](https://www.ftc.gov/tips-advice/business-center/guidance/complying-coppa-frequently-asked-questions)) and consult with your own legal counsel.

**Child-directed apps:** If your application is directed primarily at children, it should not use Google Sign-In or any other Google API Service that accesses data associated with a Google Account. This restriction includes Google Play Games Services and any other Google API Service using the OAuth technology for authentication and authorization.

**Mixed audience apps:** Applications that are mixed audience shouldn't require users to sign in to a Google Account, but can offer, for example, Google Sign-In or Google Play Games Services as an optional feature. In these cases, users must be able to access the application in its entirety without signing into a Google Account.

Maintain a secure operating environment
---------------------------------------

We expect all user data is secure in transit and at rest. Take reasonable and appropriate steps to protect all applications or systems that make use of Google API Service and any data derived from it against unauthorized or unlawful access, use, destruction, loss, alteration, or disclosure.

Additional Requirements for Specific API Scopes
-----------------------------------------------

Certain Google OAuth API Scopes (the "[Sensitive](https://support.google.com/cloud/answer/9110914#sensitive-scopes) and [Restricted](https://support.google.com/cloud/answer/9110914#restricted-scopes) Scopes") are subject to additional requirements that can be found in each product's User Data and Developer Policy or the [Google Developer Page](https://developers.google.com/). More information about the requirements to obtain (or keep) access to these scopes is also available in the [OAuth Application Verification FAQ](https://support.google.com/cloud/answer/9110914#restricted-scopes).

> **Note:** If your app is only used by users within your own domain, then these requirements do not apply. [Google Workspace](https://support.google.com/a/topic/29157?ref_topic=7570177) can control access to connected applications [via allowlisting](https://support.google.com/a/answer/7281227). Learn more about [best practices](https://cloud.google.com/blog/products/g-suite/take-charge-your-oauth-ecosystem-these-best-practices) for managing your enterprise OAuth ecosystem.

**Unless stated otherwise in the product's User Data and Developer Policy, additional requirements include:**

1. **Appropriate Access:** Developers may only request access to the scopes for a permitted Application Type described by the product. Such application types can be found under an Appropriate Access heading in the product specific policy or the product's [Google Developer Page](https://developers.google.com/).
    
2. **Limited Use:** Your use of data obtained via the product's specified scopes must comply with the below requirements. These requirements apply to the raw data obtained from the scopes and data aggregated, anonymized, or derived from them.
    
    1. Limit your use of data to providing or improving user-facing features that are prominent in the requesting application's user interface;
        
    2. Transfers of data are not allowed, except:
        
        1. To provide or improve your appropriate access or user-facing features that are visible and prominent in the requesting application's user interface and only with the user's consent;
        2. For security purposes (for example, investigating abuse);
        3. To comply with applicable laws; or,
        4. As part of a merger, acquisition, or sale of assets of the developer after obtaining explicit prior consent from the user.
    3. Don't allow humans to read the data, unless:
        
        1. You first obtained the user's affirmative agreement to view specific messages, files, or other data, with the limited exception of use cases approved by Google under additional terms applicable to the Nest Device Access program;
        2. It is necessary for security purposes (for example, investigating a bug or abuse);
        3. It is necessary to comply with applicable law; or
        4. The data (including derivations) is aggregated and used for internal operations in accordance with applicable privacy and other jurisdictional legal requirements.
    
    All other transfers, uses, or sales of user data are prohibited, including:
    
    1. Transferring or selling user data to third parties like advertising platforms, data brokers, or any information resellers.
    2. Transferring, selling, or using user data for serving ads, including retargeting, personalized or interest-based advertising.
    3. Transferring, selling, or using user data to determine credit-worthiness or for lending purposes.
    
    You must ensure that your employees, agents, contractors, and successors comply with this Google API Services User Data Policy.
    
3. **Secure Data Handling:** Applications accessing the product specified scopes (the "[Sensitive](https://support.google.com/cloud/answer/9110914#sensitive-scopes) and [Restricted](https://support.google.com/cloud/answer/9110914#restricted-scopes) Scopes") must demonstrate that they adhere to certain security practices. Depending on the API being accessed and number of user grants or users, applications must pass an annual security assessment and obtain a Letter of Assessment from a Google-designated third party. More information about the assessment requirements to obtain or keep access to the scopes is also available in the [OAuth Application Verification FAQ](https://support.google.com/cloud/answer/9110914#restricted-scopes) and the product's [Google Developer Page](https://developers.google.com/).
    

Enforcement
-----------

You must access Google API Services in accordance with the [Google APIs Terms of Service](https://developers.google.com/terms). If you are found to be out of compliance with the [Google APIs Terms of Service](https://developers.google.com/terms), this Google API Services: User Data Policy, or any Google product policies that are applicable to the Google API Service you are using, Google may revoke or suspend your access to Google API Services and other Google products and services if you are found in violation of other product policies, terms of service, or other guidelines. Your access to Google API Services may also be revoked if your application enables end-users or other parties to violate the Google APIs Terms of Service and/or Google policies.