# The Sentinel Privacy Policy

**Last updated** 13 November 2026

**Application** The Sentinel for Root

This notice covers The Sentinel inside Root, including setup, verification, moderation, and visual routines. The local development demo uses sample accounts and activity.

## Operator and contact

Michal “Seddsy” Myška develops and operates The Sentinel. The privacy contact is [seddsylive@gmail.com](mailto:seddsylive@gmail.com?subject=The%20Sentinel%20privacy).

For personal data processed through Root’s Developer Platform, Root Communications, Inc. is the controller and the app operator acts as Root’s processor. Root’s own processing is described in its privacy policy. [Root Developer Terms and Data Processing Addendum](https://www.rootapp.com/developer-terms-of-service) · [Root Privacy Policy](https://www.rootapp.com/privacy-policy)

## Information used by Sentinel

- **Identity and permissions.** Sentinel uses Root user and community IDs, display names, and role memberships to identify members and authorize features. It shows role and channel names and IDs in the owner's configuration screens.
- **Configuration.** Sentinel stores selected role and channel IDs, staff role mappings, monitored channel choices, verification rules, filter lists, and routines. When the owner provisions isolation resources, Root stores the role, group, channel, and access rules as community resources.
- **Monitored chat and moderation.** The owner selects the Root text channels Sentinel monitors. Sentinel can store text, observed edits and removals, message, member, and channel IDs, timestamps, and evidence saved for cases. Routines use these records to evaluate rules and, in Protect mode, can take actions configured by the community. Sentinel keeps records of sanctions, staff decisions, and action outcomes. The configured isolation channel is excluded from text monitoring.
- **Member activity.** When Root supplies the events, Sentinel records joins and departures, role changes, and entry to and exit from visible voice channels. It temporarily uses Root device identifiers to distinguish multiple connections to the same voice visit. The activity timeline stores times and channel information. Sentinel does not record voice audio.
- **Verification and access.** Sentinel stores rule acceptance, verification status, challenge attempts and retry counts, access decisions, and private help conversations. The optional CAPTCHA runs inside Sentinel. The challenge expires after five minutes, and Sentinel removes its image and stored answer check when the attempt is completed.
- **Reports, appeals, and notices.** Sentinel stores confidential reports, sanction appeals, replies, outcomes, and in-app notices. A report can hide the reporter's name from moderators. The community owner can see who submitted it. A report, appeal, or help request can contain the information you choose to share.

## Hosting and access

Root hosts the app and its community-specific datastore. Community owners configure which text channels Sentinel monitors and who can use staff tools. Authorized staff can see records according to their permissions. Member profiles restrict channel activity and evidence to channels the moderator can open in Root unless the owner grants access across channels. Owners can authorize staff to download audit records. If a routine posts a notice in a Root channel, the channel's access rules govern who can see it. Root also delivers notifications that direct recipients to their notices in Sentinel. The operator may assist Root with support and privacy requests under the Developer Terms. [Root App hosting](https://docs.rootapp.com/docs/app-docs/get-started/app-overview/)

Owners can import a ban list or other filter list from a saved export. Sentinel uses the imported data in that community under the owner's configured rules and expiry. This version imports lists manually and does not automatically publish community records to other communities.

GitHub hosts this policy. If you email the operator directly, the email address and message are used to answer or route your request. Correspondence is retained as needed to resolve the request and meet applicable obligations. The contact mailbox uses Gmail. [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) · [Google Privacy Policy](https://policies.google.com/privacy)

## Retention and deletion

The default message retention periods are 7 days for ordinary message text, 90 days for edited or removed message text, and 90 days after a case closes for its saved message evidence. Evidence remains available while a case is open. The community owner can adjust these periods in **Management → Settings → Message retention**. On an upgrade with previously stored messages, Sentinel hides expired content and starts removing expired copies after the owner saves the retention settings.

Community configuration, audit and sanction records, membership and voice activity metadata, verification records, reports, appeals, replies, and notices are stored separately from message cleanup. The message retention settings do not delete these records. Removing a monitored channel stops new text collection from that channel. Root manages the hosted datastore and its backups. The community owner manages roles, channels, and their access rules separately in Root. [Root persistence and backups](https://docs.rootapp.com/docs/app-docs/design/save-data-early-and-often/)

To ask for access, correction, or deletion of information associated with Sentinel, contact [Root Support](https://www.rootapp.com/support) or [email the operator](mailto:seddsylive@gmail.com?subject=The%20Sentinel%20privacy) with the subject **The Sentinel privacy**. Include the Root community and enough detail to identify the records involved. The operator will route requests about Root-controlled app data to Root and assist under its instructions.

## Changes

This notice will be updated when the native app changes how it handles information. The date above identifies the current scope.
