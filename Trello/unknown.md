Data and Encryption Policies Certifications and Assessments

Trello, Inc. (“we”, “us” or “our”) is SOC2 Type 2 certified—we receive and review our data hosting providers’ SOC1 and SOC2 reports every 6 months under NDA. Trello is ISO/IEC 27001 certified which validates our information security management system (ISMS) and the implementation of our security controls. More information is available on the Atlassian Trust Management System. Trello is PCI-DSS certified and complies with Privacy Shield.

Vulnerability Detection and Bug Bounty Program

Automated scans of Trello's production site are conducted a minimum of every 7 days. All changes are peer reviewed and vulnerability and security lists are actively monitored for CVE and other vulnerability disclosures with appropriate actions taken. We participate in an active bug bounty program on Bugcrowd and mitigate all material findings as appropriate.

Data Centers and Location

Trello production services are hosted on Amazon Web Services’ (“AWS”) EC2 platform. The physical servers are located in AWS’s EC2 data centers. As of this date, AWS (i) has certifications for compliance with ISO/IEC 27001:2013, 27017:2015 and 27018:2014, (ii) is certified as a PCI DSS 3.2 Level 1 Service Provider, and (iii) undergoes SOC 1, SOC 2 and SOC 3 audits (with semi-annual reports). Additional details about AWS’ compliance programs, including FedRAMP compliance, can be found at AWS’ website.1

All user content is stored within US regions of AWS and Google Cloud Storage ("GCS"). Trello’s production environment is hosted on an AWS EC2 platform. User content can also be found in Trello backups, stored in AWS EC2, S3, Glacier, and GCS.

We currently do not offer customers the option of hosting Trello on a private server, or to otherwise use Trello on a separate infrastructure.

Production Environment

We maintain separate and distinct production, staging, and development environments for Trello.

To access Trello’s production environment, authorized and trained members of Trello's SRE and select Engineering team members (“Authorized Personnel”) authenticate to the VPN using unique strong passwords and TOTP based 2FA and then only access the production environment via ssh terminal connections using passphrase protected personal RSA certificates. An IDS system is in place on all production servers, which includes real-time monitoring and alerting of any changes to the production system files or configuration and anomalous security events. For Authorized Personnel, any workstations running Windows or macOS must be running current and active anti-virus software. Those members are also trained not to replicate non-public user data stored in Trello’s production environment onto their workstations or mobile devices. For clarity, users of Trello can access data via mobile apps.

Network Security

Trello uses Akamai for DDoS protection. AWS Network ACL and Security Groups are used to restrict access to Trello’s systems as appropriate to their role. Active monitoring of these security rules is in place with alerting mechanisms in place for any changes to the configuration. Public access is restricted to port 443 and 80 on the network load balancers for public traffic.

Login security

SAML 2.0 SSO is supported for Trello Enterprise customers. All customers can enable 2FA on their accounts or use Google OAuth. If SSO or OAuth is used to access Trello, Trello will inherit the login security settings in the user's IdP or Google account.

If logging in directly to Trello using a username or email and password, Trello requires a minimum of 8 characters. Repeated failed login attempts trigger a 30 second lock before a user can retry. Passwords are stored in a hashed form and will never be sent via email—upon account creation and password reset, Trello will send a link to the email associated with the account that will enable the user to create a new password.

Password complexity and session length requirements cannot be customized within the app. However, these can be set within an IdP for an SSO-enforced team.

Access Control

All user data stored in Trello is protected in accordance with our obligations in the Atlassian Cloud Terms of Service, and access to such data by Authorized Personnel is based on the principle of least privilege. Only Authorized Personnel have direct access to Trello’s production systems. Those who do have direct access to production systems are only permitted to view user data stored in Trello in the aggregate, for troubleshooting purposes or as otherwise permitted in Trello’s Privacy Policy.

Trello maintains a list of Authorized Personnel with access to the production environment. These members undergo criminal background checks and are approved by Trello’s Engineering management. Trello also maintain a list of personnel who are permitted to access Trello code, as well as the development and staging environments. These lists are reviewed quarterly and upon role change.

Trained members of the Trello customer support team also have case-specific, limited access to user data stored in Trello through restricted access customer support tools. Customer support team members are not authorized to review non-public user data stored in Trello for customer support purposes without explicit permission. When a Trello user submits a support ticket, they have the option of authorizing the customer support team to view their data. The Trello customer support team will only receive such access to the account if it is granted by the user, either by selecting the "Give Trello support staff temporary access to your account" option when submitting a help request, or by clicking a link sent to the user's email by the Trello Support team. The account owner can revoke such access at any time.2

Upon role change or leaving the company, the production credentials of Authorized Personnel are deactivated, and their sessions are forcibly logged out. Thereafter, all such accounts are removed or changed.

Public Content and Other Permissions

User data entered on public boards or included in public profile information may be viewed or accessed by anyone. In addition, notwithstanding anything to the contrary, data may be collected, shared, retained and used as described in Trello’s Privacy Policy or customer’s agreement(s) with Trello.

Third Party Access

User data may be shared by Trello with third-party service providers (a user's email address for an email delivery provider, for example) pursuant to Trello’s Privacy Policy and in compliance with Trello’s applicable signed service agreements.

Physical Security

In some instances our offices share buildings with other companies. For that reason, we require mandatory visitor check-in with the building security team and that visitors wear identification badges. Additionally, visitors must check-in with our front desk and require an escort throughout the building at all times. Employee access to physical facilities is protected by electronic badge readers and building security. CCTV covers entry and exit points 24/7 with logs made available to us internally.

Trello's production services are hosted on Amazon Web Services’ (“AWS”) EC2 platform. The physical servers are located in AWS’ secure data centers.3 We require that production critical data is never to be stored by those with privileged access on physical media outside of our data hosting provider's production environments. See above for information on AWS’ compliance programs.

Corporate Environment and Removable Media

Strict firewall rules prohibit access to necessary ports for the usage of Trello (e.g., 443), to help ensure limited access to the production environment to our VPN network and authorized systems. Our corporate network has no additional access to the production environment, with Authorized Personnel required to connect to the VPN in order to access any special systems or environments.

Authorized Personnel with access to Trello’s production environment are trained as noted above. In addition, employee workstations are required to time out and lock after a maximum of one minute once sleep or the screen saver begins. We do not have a clean desk policy.

Encryption In-Transit

Trello uses industry standard Transport Layer Security (“TLS”) to create a secure connection using 128-bit Advanced Encryption Standard (“AES”) encryption. This includes all data sent between the web, desktop, iOS, and Android apps and the Trello servers. There is no non-TLS option for connecting to Trello. All connections are made securely over HTTPS.

Encryption At-Rest

Data drives on servers holding user data use full disk, industry-standard AES encryption with a unique encryption key for each server. File attachments to Trello cards are stored in Amazon’s S3 service. Each such attachment is assigned a unique link with an unguessable, cryptographically strong random component, and are only accessible using a secure HTTPS connection. File attachments to Trello cards uploaded after June 3, 2015 are encrypted using Amazon S3 server side 256-bit AES encryption. The encryption, key management, and decryption process is inspected and verified internally by Amazon on a regular basis as part of their existing audit process. At an Enterprise customer’s request, attachments uploaded prior to June 3, 2015 can be retroactively encrypted within Amazon S3. All Trello backups are encrypted with AES encryption.

Encryption Keys

Encryption keys for Trello attachments, stored in S3, are managed by Amazon. The encryption, key management, and decryption process is inspected and verified internally by Amazon on a regular basis as part of their existing audit process. Encryption keys for Trello attachments managed by our team are rotated upon relevant changes of roles or employment status. Encryption keys managed by our team are not stored outside of Trello’s production backup environment and are managed by the our SRE team. Trello backups are of the entire data set, so they are encrypted using a shared key.

Data Deletion - Termination of Agreement

Upon termination of a Trello Business Class or Enterprise contract, if requested by the Trello customer’s administrator, the user content that is stored on the terminated team’s boards, lists and cards will be completely removed from the live Trello production database. All file attachments uploaded directly to Trello will be removed from the live Trello production database within 30 days. The team’s data will remain in encrypted Trello database backups until those backups fall out of the 90-day backup retention window and are destroyed in accordance with our data retention policy. In the event that a database restore is necessary within 90 days of a requested data deletion, we will re-delete the data as soon as reasonably possible after the live production system is fully restored.

For clarity, if a customer continues to use Trello pursuant to a free account or different plan following the termination of a Business Class or Enterprise contract, such data may be retained for use in accordance with the terms and conditions applicable to such account or plan.

Data Deletion - User Personal Data

In the case of a Trello user account being deleted, upon deletion, Trello deletes the user’s personal data, including items like name, email address and location, within 30 days of the request. After 30 days, such personal data will remain in encrypted Trello database backups until those backups fall out of the 90-day retention window and are completely destroyed.

In certain cases where Trello has a legitimate business or legal purpose to do so, Trello may keep user personal data. Some examples of this include financial information related to things like purchases and billing records. records showing why the account was deleted. or data relating to a litigation or other legal inquiry.

Upon deletion of an individual user account, Trello does not automatically delete the content that was created by individual users in Trello. For example, items typed into cards like a comment or an added file will remain visible even if the removed user no longer exists. The applicable team’s administrators or users, depending on the permission settings, would need to delete that content manually.

Users may have installed third party applications or custom applications, e.g., Power-Ups, that add features to Trello. These apps may have stored user personal data. To see a list of apps that may have stored personal data, users should navigate to their Trello Settings page (before deleting their account).

Development, Patch and Configuration Management

All changes to the Trello production system, be they code or system configuration changes, require review prior to deployment to the production environment. Thousands of automated unit tests are run against all production code prior to deployment. Production code is also subject to regularly conducted automated vulnerability scans. All changes to Trello’s code are tested in a staging environment prior to deployment to production. Patches to the Trello web client are deployed on a rolling basis, usually several times per week. Trello production servers are managed via a centralized configuration system. All Trello system changes are peer reviewed and patches are deployed as relevant to their level of security and stability impact, with critical patches able to be deployed well within 24 hours of availability as appropriate.

We restrict access as noted above and maintain separate lists of relevant roles with access to source code, development, staging, and production environments. These lists are reviewed quarterly and upon role change. We use source code management tools and repositories.

All production servers are running a LTS (Long Term Support) distribution of their operating system to ensure timely updates are available. CVE lists and notifications are actively monitored and any systems can be patched in a timeline relevant to the severity of the issue. A centralized configuration system is used for the management of production servers, and when needed a patch can be deployed within hours of its availability.

Event Logging

Certain user actions which manipulate user data are stored within Trello and are available for the customer/user (e.g., when viewing the action history on a card, board, or team). This information is available within Trello unless a card is deleted (not archived), at which point it cannot be restored.

All Trello API calls and application logs are kept for our internal purposes for at least 30 days without sensitive information (no full user tokens, no user generated content), and are available only for authorized employees as required by their role for monitoring of Trello to ensure service availability and performance and to prevent abuse.

Application logs for Trello are centrally collected in an ElasticSearch cluster for a minimum of 30 days for monitoring and analysis. Security, authentication, and Intrusion Detection System (IDS) logs for Trello are additionally retained in S3 CloudWatch buckets with a 12 month lifecycle to ensure retention.

Asset Management

While some assets are not owned by a specific individual, ownership and maintenance of the confidentiality, integrity, and availability of our systems is distributed amongst the SRE and Operations teams. Assets are transferred upon role change or leaving the company.

Data Within Trello

Trello validates files for well-formedness and the like, however, we have explicitly designed Trello to support any type of content users may choose to store within Trello. All attachments are stored and accessed from a completely separate domain to help prevent any potential access by such attachment to other user data or cookies.

User Team Management and Access

Admins for a Trello Enterprise account will be set via the customer’s account manager. Admin, regular, and observer roles can be assigned within Trello.

It is not possible to limit the geolocations allowed to access data within Trello. Data can be accessed by users who have access to such data within the app from any geolocation. All third-party developer access to user data stored in Trello is via the API which includes strict authorization checks. All Authorized Personnel go through strict security group/firewall rules which limits access to authorized instance roles on authorized ports required for them to fulfill their role.

Power-Ups cannot be restricted within a team. Power-Ups which connect Trello to other services (such as Evernote or Dropbox) may require authentication with an existing account in that service before the Power-Up is active. If working within a corporate environment, the domain used to authenticate that account can be blocked in your environment's firewall.

Backup, Business Continuity, and Disaster Recovery Policy Backup Policy

Data entered into Trello is backed up regularly. All backups are encrypted and stored at multiple offsite locations to help ensure that they are available in the unlikely event that a restore is necessary.

Files uploaded to Trello as card attachments are not backed up on the same schedule, and instead rely on Amazon S3’s internal redundancy mechanism.

Files associated with Trello cards from a supported cloud storage provider are also subject to the storage provider’s own backup procedures and policies.

Trello database backups are immediately encrypted with 256-bit AES encryption using GNU Privacy Guard (“GPG”) with a password-protected symmetric cipher. Encrypted backups can only be decrypted by members of the Trello operations team who have received training and have been authorized to decrypt the backups.

Because user data stored in Trello is on a shared infrastructure, it is not possible for us to recover a subset of that information from backups. If any customer is particularly concerned with maintaining a complete record of their information in Trello, we suggest that such customer frequently exports its data or use our API4 to connect a DLP tool to Trello.

Backup Interval

A rolling live replica of Trello’s primary database is constantly being taken on a 1-hour delay. Additionally, a full backup snapshot of the primary database is taken once every 24 hours.

Backup Storage

All Trello backups are retained on the following schedule:

*   AWS EC2 on a dedicated backup server for two days
*   AWS S3 for 7 days
*   Google Cloud Storage for 30 days
*   AWS Glacier for 90 days

Only authorized members of the Trello operations team have access to the backup locations, so that they are able to monitor the performance of the backup processes, and in the very unlikely event that a restore becomes necessary. After 90 days, the encrypted backup files are destroyed.

Attachments directly uploaded to Trello are handled differently than the primary database backups. To backup file attachments, Trello primarily relies on S3’s internal redundancy mechanism, which Amazon states provides 99.99% yearly data durability. Attachments are also backed up to Google Cloud Storage for additional redundancy.

Data Portability

Trello board data is available for export by board members in JSON format via the Trello REST API. File attachments can be individually retrieved directly from Amazon S3 using the file’s unique hyperlink.

Trello personal data is available for export by individual users in JSON format and can be found by clicking this link. The “Download Personal Data” button will export personal data and deliver it via an API endpoint in JSON format.

Trello Business Class and Enterprise plans offer a simplified data export process for all team data and attachments. Each Business Class and Enterprise team includes one-click export of all Boards within the team. Optionally, file attachments uploaded directly to Trello can be included in the export file. Within the export, each board’s data is included in both JSON and Comma Separated Values (“CSV”) format.

Business Continuity

The Trello operations team has designed systems to keep the service running even if the underlying infrastructure experiences an outage or other significant issue. Every critical Trello service has a secondary, replicated service running simultaneously with mirrored data in a different AWS availability zone than the primary server. Additionally, each Trello database server has a replicated service running in a third availability zone with data that is mirrored on a one hour delay.

Because it is critical to have reliable access to your business’ important projects and data, Trello has been architected to survive a single availability zone outage without significant service interruptions.

Disaster Recovery

In the unlikely event that two Amazon EC2 availability zones have long-term service interruptions, Trello has been designed to recover with limited service interruption and a target maximum of 1 hour of data loss.

In the even more unlikely event that Trello’s entire AWS EC2 region is irrecoverably lost, we will restore servers using automated configuration systems. In this event, Trello’s systems are designed to recover user data as quickly as reasonably possible, with a target of no more than of 24 hours of data loss.

Trello's SRE team regularly tests the various components of its Business Continuity architecture to ensure continued operations. Trello does not currently run anything like Chaos Monkey.

Trello does not have an SLA or credit policy. Trello had over 99.99% uptime in 2017 and 2018, and any downtime is documented at Trello's status page.5

Incidents and Response

A Trello problem impacting a Trello Enterprise customer will be assigned a Severity Level and handled according to the resolutions in Table 1.

Table 1: Incidents and Response Severity Levels:

Level Description Resolution Examples Severity 1 Trello is not available or is unusable. Work begins within 1 hour from report, temporary resolution within 4 hours, final resolution within 7 hours. The site is not responding. all text on the site is being translated into elven runes. Severity 2 Service or performance is substantially degraded in a way that prevents normal use. Work begins within 2 hours from report, temporary resolution within 48 hours, final resolution within 14 days. Search only finds cards with the search terms in the title. Trello cannot be used with the new Firefox version that came out today. Severity 3 A service not essential to Trello’s main functionality is unavailable or degraded. Work begins within 72 hours from report, temporary resolution within 7 days, final resolution within 30 days. Activity indicators are not showing who is active. updates are taking 30 seconds to propagate to other board viewers. Severity 4 Minor or cosmetic issues with Trello services, and all feature requests. Resolution at Trello team’s discretion. Board background images aren’t scaling properly. feature request for dependencies between cards. Employee Policies Anti-Virus

Trello has a centrally managed antivirus solution deployed across both our Windows and macOS environments. For Authorized Personnel, any workstations running Windows or macOS used for ssh terminal access to the production environment must be running update-to-date and active instances of our centrally deployed Cylance antivirus software with real-time monitoring and at-least-daily updates.

Authorized Personnel may choose to run linux as their workstation operating system. Given the inadequate state of linux antivirus software and the lack of prevalence of viruses for that platform, our policy does not require those workstations to run antivirus. All of the existing controls for Authorized Personnel, including restricting access from those workstations to the production environment via ssh terminal connections only and with no replication of user data onto those workstations, still apply.

Remote Access

Many of Trello’s team members work remotely. Strict firewall rules are in place thus limiting access to the production environment to our VPN network and authorized systems. Certain other controls described above, including Authorized Personnel and corporate environment controls, also apply to remote access as appropriate.

Security Awareness and Confidentiality

Security awareness and user data access policies are covered during our employee onboarding as appropriate to the role and employees are updated as relevant policies or practices change. Our employees also sign a confidentiality agreement.

In the event that a security policy is breached by an employee, Trello reserves the right to determine the appropriate response, which may include termination.

Background Checks

All our employees undergo an extensive interview process before hiring. Our employees with direct access to the production environment undergo a criminal background check. Other employees may undergo a check depending on their role (e.g., academic for legal roles or credit for finance roles). Appropriate NDAs are in place with third parties as appropriate.

Maintenance Policy Planned Maintenance

When it is necessary to perform planned maintenance on Trello services, the Trello operations team will perform the work during one of two scheduled weekly maintenance windows. We will make reasonable efforts to announce maintenance procedures that could potentially impact users of Trello on the @trellostatus Twitter account6 at least 24 hours prior to the event, and via an in-app announcement at least 30 minutes prior to the event.

Planned Maintenance Windows

*   Tuesday from 10:00 PM US Eastern Time through Wednesday at 2:00 AM US Eastern Time
*   Saturday from 10:00 PM US Eastern Time through Sunday at 2:00 AM US Eastern Time

These windows have been selected with the goal of minimizing service downtime, slowness, or other impact to the people and businesses that rely on Trello.

We do our best to make outages as short as possible. Additionally, our maintenance schedule will frequently be evaluated to ensure that we keep user impact as low as reasonably possible. Should we need to reschedule these windows, the updated schedule will be announced on our Status Blog and Twitter accounts with reasonable advance notice.

Unplanned Maintenance

Due to unforeseen events, we may have to infrequently perform unplanned maintenance on Trello infrastructure or software components. This maintenance might cause some or all of the Trello services to be inaccessible by our users for a period of time. It is our goal to do this as infrequently as possible. Any unplanned or emergency maintenance that causes Trello to be inaccessible will be announced on the Trello Status Blog and in-app with as much advance notice as reasonably possible. As with planned maintenance, we do our best to minimize disruption caused by service outages.

It is not possible for us to customize the maintenance window, as our users are on a shared infrastructure. However, we've used this maintenance window extremely rarely—about once a year, for under 15 minutes each time.

**Footnotes:**

1http://aws.amazon.com/security/

2https://trello.com/your/account

3http://aws.amazon.com/security/

4http://developers.trello.com/

5https://trello.status.atlassian.com/

6https://twitter.com/trellostatus

Changelog

*   **January 2019** – Updates to the following sections to reflect current practices: Penetration Testing and Bug Bounty Program, Production Environment, Network Security, Access Control, Third-Party Access, Physical Security, Corporate Environment and Removable Media, Encryption on Mobile Devices, Removing/Deleting Data from Trello, Event Logging, Data Within Trello, User Team Management and Access and Employee Policies
*   **February 2018** - Updates to links or cross-references in the following Sections: Data Center, Access Control, Physical Security, Encryption In-Transit, Development, Patch and Configuration Management, Backup Policy, Disaster Recovery Policy and Planned Maintenance.
*   **September 2017** - First version of page goes live. Replaces previous Operations &. Security Guide PDF.