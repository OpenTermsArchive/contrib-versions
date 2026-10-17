![Spark icon](/_static/images/icons/spark.svg)

Page Summary
------------

outlined\_flag

*   The Google Ads API is a programmatic interface for managing Google Ads accounts and campaigns, suitable for large or complex setups.
    
*   Typical uses of the Google Ads API include automated account management, custom reporting, ad management based on inventory, and Smart Bidding strategy management.
    
*   The Google Ads API is recommended for developers comfortable with writing code and managing their own software infrastructure.
    
*   Google Ads scripts, BigQuery Data Transfer service, automated rules, bulk uploads, and Google Ads Editor are alternative tools for automating Google Ads for different needs and technical skill levels.
    

The Google Ads API is the programmatic interface to Google Ads, used for managing large or complex Google Ads accounts and campaigns. You can build software that manages accounts from the customer level down to the keyword level. Typical use cases include:

*   **[Automated account management](https://developers.google.com/google-ads/api/docs/account-management/overview)**: Create and link accounts, manage account hierarchies, and automate user access.
*   **[Custom reporting](https://developers.google.com/google-ads/api/docs/reporting/overview)**: Query performance metrics, segments, and resource attributes using the [Google Ads Query Language (GAQL)](https://developers.google.com/google-ads/api/docs/query/overview).
*   **[Campaign and inventory-based ad management](https://developers.google.com/google-ads/api/docs/campaigns/overview)**: Create and update [Performance Max](https://developers.google.com/google-ads/api/performance-max/getting-started), [Search](https://developers.google.com/google-ads/api/docs/campaigns/search-campaigns/getting-started), [Demand Gen](https://developers.google.com/google-ads/api/docs/demand-gen/overview), [Shopping](https://developers.google.com/google-ads/api/docs/shopping-ads/overview), [Video](https://developers.google.com/google-ads/api/docs/video/overview), and [App](https://developers.google.com/google-ads/api/docs/app-campaigns/overview) campaigns, [budgets](https://developers.google.com/google-ads/api/docs/campaigns/budgets/overview), and [assets](https://developers.google.com/google-ads/api/docs/assets/overview).
*   **[Conversion measurement](https://developers.google.com/google-ads/api/docs/conversions/overview) and [Smart Bidding strategy management](https://developers.google.com/google-ads/api/docs/campaigns/bidding/overview)**: Upload click, call, and enhanced conversions and configure automated bidding strategies.

Is the Google Ads API the right product for me?
-----------------------------------------------

Google provides multiple products to help automate Google Ads accounts. Use the following table to identify the product that best fits your requirements:

| Scenario | Recommendation |
| --- | --- |
| I am a developer who wants to build custom software or integrate with the Google Ads API, and I am comfortable managing server and database infrastructure. | Use the Google Ads API. Start with the [Quickstart](https://developers.google.com/google-ads/api/docs/get-started/make-first-call) to configure access and make your first API call. |
| I am a developer who wants to write custom logic, but I prefer not to manage server infrastructure. | Use [Google Ads scripts](https://developers.google.com/google-ads/scripts). |
| I am not a developer, but I want to learn basic programming to automate Google Ads. | Use [Google Ads scripts](https://developers.google.com/google-ads/scripts). |
| I am a data analyst who needs to download Google Ads reports for offline or warehouse analysis. | Use the [BigQuery Data Transfer Service](https://cloud.google.com/bigquery/docs/dts-introduction) for [Google Ads transfers](https://cloud.google.com/bigquery/docs/google-ads-transfer). |
| I am building Marketing Mix Models (MMM) and need Google Ads data. | Use the [MMM Data Platform](https://developers.google.com/mmm-data-platform). While many advertisers rely on the Google Ads API for data pulls, the Google Ads API is not ideal for MMM development. |
| I want to manage Google Ads in bulk without writing code. | Use [automated rules](https://support.google.com/google-ads/answer/2472779), [bulk uploads](https://support.google.com/google-ads/answer/10702932), or [Google Ads Editor](https://support.google.com/google-ads/editor/answer/2484521). |

Get started and explore key topics
----------------------------------

If the Google Ads API is the right fit for your project, use the following task guide to configure access, install a client library, and build your integration:

| Goal | Primary guide | Related resources |
| --- | --- | --- |
| **Make your first API call** | [Quickstart](https://developers.google.com/google-ads/api/docs/get-started/make-first-call) | [Google Cloud project setup](https://developers.google.com/google-ads/api/docs/oauth/cloud-project), [Access levels](https://developers.google.com/google-ads/api/docs/api-policy/access-levels), [Test accounts](https://developers.google.com/google-ads/api/docs/best-practices/test-accounts), [Basic concepts](https://developers.google.com/google-ads/api/docs/concepts/overview), [Next steps](https://developers.google.com/google-ads/api/docs/get-started/next-steps) |
| **Configure OAuth 2.0 and credentials** | [Authentication and authorization overview](https://developers.google.com/google-ads/api/docs/oauth/overview) | [Access model overview](https://developers.google.com/google-ads/api/docs/oauth/access-model), [Service account workflow](https://developers.google.com/google-ads/api/docs/oauth/service-accounts), [User authentication workflow](https://developers.google.com/google-ads/api/docs/oauth/user-authentication), [Brand verification](https://developers.google.com/google-ads/api/docs/api-policy/brand-verification), [Developer token sunset](https://developers.google.com/google-ads/api/docs/api-policy/developer-token) |
| **Install a client library or call REST** | [Client libraries](https://developers.google.com/google-ads/api/docs/client-libs) | [Java](https://developers.google.com/google-ads/api/docs/client-libs/java), [.NET](https://developers.google.com/google-ads/api/docs/client-libs/dotnet), [PHP](https://developers.google.com/google-ads/api/docs/client-libs/php), [Python](https://developers.google.com/google-ads/api/docs/client-libs/python), [Ruby](https://developers.google.com/google-ads/api/docs/client-libs/ruby), [Perl](https://developers.google.com/google-ads/api/docs/client-libs/perl), [Code samples](https://developers.google.com/google-ads/api/samples), [REST interface](https://developers.google.com/google-ads/api/rest/overview) |
| **Query reports and build GAQL queries** | [Reporting overview](https://developers.google.com/google-ads/api/docs/reporting/overview) | [Google Ads Query Language (GAQL)](https://developers.google.com/google-ads/api/docs/query/overview), [Interactive Query Builder](https://developers.google.com/google-ads/api/fields/v26/overview_query_builder), [Query Validator](https://developers.google.com/google-ads/api/fields/v26/query_validator), [Query Cookbook](https://developers.google.com/google-ads/api/docs/query/cookbook), [Reporting reference (v26)](https://developers.google.com/google-ads/api/fields/v26/overview) |
| **Use AI tools and interactive explorers** | [Google Ads API Developer Assistant](https://developers.google.com/google-ads/api/docs/developer-toolkit/what-is-developer-assistant) | [Install the Developer Assistant](https://developers.google.com/google-ads/api/docs/developer-toolkit/ai-assistant), [Google Ads MCP server](https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server), [Agent skills](https://developers.google.com/google-ads/api/docs/developer-toolkit/agent-skills), [API Explorer](https://developers.google.com/google-ads/api/docs/developer-toolkit/api-explorer) |
| **Troubleshoot errors and plan upgrades** | [Handle errors](https://developers.google.com/google-ads/api/docs/get-started/handle-errors) | [Common errors](https://developers.google.com/google-ads/api/docs/common-errors), [Understand API errors](https://developers.google.com/google-ads/api/docs/best-practices/understand-api-errors), [Release notes](https://developers.google.com/google-ads/api/docs/release-notes), [Upgrade your API version](https://developers.google.com/google-ads/api/docs/upgrade), [Deprecation and sunset schedule](https://developers.google.com/google-ads/api/docs/sunset-dates) |