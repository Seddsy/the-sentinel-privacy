# The Sentinel Privacy Policy

**Last updated** 12 November 2026

**Application** The Sentinel 0.0.1 for Root

This notice covers **Setup** in the native Root app. Setup helps the Root community owner create or connect a dedicated isolation role, channel group, and channel, and optionally select a regular access role. The separate local demo is a development environment.

## Operator and contact

Michal “Seddsy” Myška develops and operates The Sentinel. The privacy contact is [seddsylive@gmail.com](mailto:seddsylive@gmail.com?subject=The%20Sentinel%20privacy).

For personal data processed through Root’s Developer Platform, Root Communications, Inc. is the controller and the app operator acts as Root’s processor. Root’s own processing is described in its privacy policy. [Root Developer Terms and Data Processing Addendum](https://www.rootapp.com/developer-terms-of-service) · [Root Privacy Policy](https://www.rootapp.com/privacy-policy)

## Information used by Setup

- **Authorization.** Setup uses the caller’s Root user ID, the community ID, and the current owner’s Root user ID to check access. It displays the community name and available role, channel group, and channel names and IDs to the owner during setup.
- **Saved configuration.** The community ID identifies the Setup record. The record contains the selected role, group, and channel IDs, any selected regular access role ID, a revision number, and any pending creation step. The revision and pending step help recover an interrupted setup and avoid creating duplicate resources.
- **Community resources.** When the owner asks Setup to provision resources, Root stores the new role, group, channel, and their access rules as community resources. The app’s ID and the community ID can appear in the isolation channel’s description. Root permissions determine who can view or manage these resources.

## Hosting and access

Root hosts the native app and stores its Setup record in the community’s app datastore. The Root community owner can see and change that community’s Setup configuration. The operator may assist Root with support and privacy requests under the Developer Terms. The native Setup feature uses Root services for its work. [Root App hosting](https://docs.rootapp.com/docs/app-docs/get-started/app-overview/)

GitHub hosts this policy. If you email the operator directly, the email address and message are used to answer or route your request. Correspondence is retained as needed to resolve the request and meet applicable obligations. The contact mailbox uses Gmail. [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) · [Google Privacy Policy](https://policies.google.com/privacy)

## Retention and deletion

Setup keeps the current configuration so it is available the next time the owner opens it. The owner can update or clear the saved selections in Setup. The Setup record has no automatic age-based deletion schedule and remains in the app datastore until it is removed. Root manages the hosted datastore and its backups. The community owner can manage or remove the role, group, channel, and access rules separately in Root. [Root persistence and backups](https://docs.rootapp.com/docs/app-docs/design/save-data-early-and-often/)

To ask for access, correction, or deletion of information associated with Setup, contact [Root Support](https://www.rootapp.com/support) or [email the operator](mailto:seddsylive@gmail.com?subject=The%20Sentinel%20privacy) with the subject **The Sentinel privacy**. Include the Root community and the setup record or resource involved. The operator will route requests about Root-controlled app data to Root and assist under its instructions.

## Changes

This notice will be updated when the native app changes how it handles information. The date and application version above identify the current scope.
