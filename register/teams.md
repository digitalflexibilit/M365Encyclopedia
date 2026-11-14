# Microsoft Teams

Last updated: 2026-11-14

## Current features

### Agent response streaming in all conversation types
- **Status:** GA
- **Last change:** 2026-10-28, streaming extended from one-on-one chats to group chats, channels and meeting chats
- **More info:** [Teams Platform Developer Announcements](https://learn.microsoft.com/en-us/microsoftteams/platform/developer-announcements)

Agents built for Teams can now stream their reply while it is generated, in every conversation type. Users see informative updates under the message the agent is replying to. Developers update to the latest Teams SDK, or set `replyToId` when using the REST API outside one-on-one chats.

### AI Workflows in the Workflows app
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, Copilot-powered scheduled prompt templates in Workflows
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Users get Copilot-powered scheduled prompt templates in the Workflows app on Windows and Mac. Admins control access in Teams app management settings, and the feature is off unless the Workflows app is enabled.

### Alternative text for images from OneDrive and SharePoint
- **Status:** Rolling out
- **Last change:** 2026-11-14, rolling out in November 2026
- **More info:** [Microsoft 365 Roadmap item 571687](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=571687)

Users can add alternative text to images they share in Teams from OneDrive and SharePoint. Screen reader users then get a description of the image.

### Ask Copilot from Search on mobile
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 571299](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=571299)

In Teams mobile, typing in the search bar shows an option to ask Copilot next to the search results, and Ask Copilot on the results page turns the query into a Copilot conversation with follow-up questions.

### Automatic recording and transcription choices follow policy
- **Status:** Rolling out
- **Last change:** 2026-11-14, rolling out in November 2026
- **More info:** [Microsoft 365 Roadmap item 570468](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=570468)

In Meeting options, organizers only see the automatic recording and transcription choices that their meeting policies allow. A new "Record only" choice starts recording automatically without transcription. If policy turns off both recording and transcription, the automatic setting is hidden.

### Copilot Chat after a call in Queues
- **Status:** Rolling out
- **Last change:** 2026-10-27, listed in Copilot release notes
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

In the Recap tab of a recorded call queue call in the Queues app, users can open Copilot Chat to summarize the call and ask questions about it. Available on Windows and Mac, and the user needs Copilot.

### Default meeting templates
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 576609](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=576609)

Admins set meeting settings, including protection settings, that apply automatically when users schedule a Teams meeting from Outlook or the Teams calendar. Organizers then do not need to set meeting options by hand. Only organizers with a Teams Premium license can use default meeting templates.

### Facilitator follow-up mode
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, planned for December 2026
- **More info:** [Microsoft 365 Roadmap item 566523](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=566523)

Users can keep chatting with Facilitator in a meeting without @mentioning it in every message. Facilitator is the Copilot agent that takes notes and helps run Teams meetings.

### Facilitator scam alerts
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out
- **More info:** [Microsoft 365 Roadmap item 573450](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=573450)

When Facilitator is in a meeting, its Protection skill checks the transcript for signs that someone outside the organization is trying to trick participants into sharing sensitive information. If it detects an attempt, participants see a warning with options to end the meeting or temporarily restrict information sharing. Teams desktop on Windows and Mac.

### GitHub app in Teams
- **Status:** GA
- **Last change:** 2026-10-23, new app combines GitHub notifications and GitHub Copilot
- **More info:** [Turn GitHub notifications into code with GitHub Copilot in Microsoft Teams](https://techcommunity.microsoft.com/blog/microsoftteamsblog/turn-github-notifications-into-code-with-github-copilot-in-microsoft-teams/4566408)

The new GitHub app in Teams brings GitHub notifications and GitHub Copilot into Teams so developers can act on notifications from chat. Replaces GitHub (deprecated), the legacy app, which is retired on 16 November 2026.

### Granular Conditional Access for meetings
- **Status:** Rolling out
- **Last change:** 2026-11-14, rolling out in November 2026
- **More info:** [Microsoft 365 Roadmap item 571879](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=571879)

Admins can apply Microsoft Entra Conditional Access policies to selected Teams meetings instead of all meetings. Participants must meet the policy requirements before they can join, which helps protect sensitive meetings.

### Impersonation protection for meetings
- **Status:** Rolling out
- **Last change:** 2026-11-14, rolling out in November 2026
- **More info:** [Microsoft 365 Roadmap item 573157](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=573157)

Teams detects possible impersonation by meeting participants or organizers and shows warnings and risk indicators. This helps users recognize suspicious identities before or while they join a meeting. No user action is needed to turn it on.

### Intelligent recap without saving the transcript
- **Status:** GA
- **Last change:** 2026-11-12, roadmap status Launched, October 2026
- **More info:** [Microsoft 365 Roadmap item 558286](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=558286)

Organizers can choose in meeting options, before or during the meeting, to generate the intelligent recap without keeping the transcript after the meeting. The AI summary stays available, but chapters, topics, mentions and audio recap may not. Uses Copilot in Teams meetings.

### Keep calls visible in a separate window on the web
- **Status:** Rolling out
- **Last change:** 2026-11-04, listed in Teams release notes
- **More info:** [Release notes for Microsoft Teams](https://learn.microsoft.com/en-us/officeupdates/teams-admin)

In Teams for the web and the Teams PWA, a call can open in a simplified window that stays on top of other content when the user leaves or hides the browser tab. End users can keep an eye on the call while they work in other tabs.

### Pause all notifications
- **Status:** Rolling out
- **Last change:** 2026-10-07, feature listed
- **More info:** [Release notes for Microsoft Teams](https://learn.microsoft.com/en-us/officeupdates/teams-admin)

Users can temporarily pause all notifications without changing saved notification settings.

### Personal message reminders
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 565869](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=565869)

Users set private reminders on chat and channel messages, manage them in a Reminders view and get a notification when they are due. Available on desktop, web, Mac, iOS and Android, in worldwide and government clouds.

### Phishing detection in Teams chats
- **Status:** Rolling out
- **Last change:** 2026-11-14, rolling out in November 2026
- **More info:** [Microsoft 365 Roadmap item 575288](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=575288)

AI-based detection uses the conversation context to find phishing and social engineering, mainly in first-contact chats with external people. Users see a warning when something suspicious is found. Microsoft says the analysis is used only for security protection.

### Pinch to zoom on shared screens
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 576193](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=576193)

Users pinch on their touchpad to zoom in on content shared in Teams calls and meetings and zoom out again for the full view. Existing zoom controls stay available.

### Policy control over who can record and transcribe
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, planned for December 2026
- **More info:** [Microsoft 365 Roadmap item 579860](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=579860)

Admins use meeting policies to decide who can start recording and transcription: only organizers and co-organizers, or presenters as well. They can also decide whether organizers may change these settings or whether the policy enforces them.

### Profanity filtering control for meeting transcripts
- **Status:** Rolling out
- **Last change:** 2026-11-04, new meeting policy setting
- **More info:** [Release notes for Microsoft Teams](https://learn.microsoft.com/en-us/officeupdates/teams-admin)

Admins use a meeting policy to decide whether profane words are masked in live transcription and saved meeting transcripts. Masking is on by default, and the meeting organizer's policy decides the behavior. Live captions keep following each participant's own profanity setting.

### Require consent before joining meetings
- **Status:** Rolling out
- **Last change:** 2026-11-04, new setting in the Teams admin center
- **More info:** [Release notes for Microsoft Teams](https://learn.microsoft.com/en-us/officeupdates/teams-admin)

Admins can require every participant to give explicit consent, for example to the organization's own terms and conditions, before joining any meeting hosted in the organization. The setting is configured in the Teams admin center.

### SharePoint app in Teams opens page links
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 567314](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=567314)

On mobile, a SharePoint page or news link selected in a Teams chat or channel opens in the SharePoint app in Teams, when the user has access to it, instead of the mobile browser.

### Town hall optimization for VDI attendees
- **Status:** Rolling out
- **Last change:** 2026-10-07, feature listed
- **More info:** [Release notes for Microsoft Teams](https://learn.microsoft.com/en-us/officeupdates/teams-admin)

Town hall attendees on Windows virtual desktops such as Azure Virtual Desktop, Windows 365 and Citrix can offload audio and video to the local device.

### Two presenters sharing at the same time
- **Status:** Roadmap
- **Last change:** 2026-11-14, roadmap date moved to January 2027
- **More info:** [Microsoft 365 Roadmap item 80239](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=80239)

Two presenters can share a screen or window at the same time in a Teams meeting, and participants see both streams side by side. This makes it easier to compare content from two people.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
