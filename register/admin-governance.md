# Admin and governance

Last updated: 2026-11-24

## Current features

### Action center for agents
- **Status:** Roadmap
- **Last change:** 2026-11-17, announced at Ignite 2026, preview planned for December 2026
- **More info:** [What's new in Microsoft Agent 365: Ignite 2026](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)

A place in the Microsoft 365 admin center that lists governance tasks, such as inactive or ownerless agents, so admins can review and clean them up.

### Agent 365 Business Analytics
- **Status:** Preview
- **Last change:** 2026-11-17, rolling out in the Frontier program
- **More info:** [How to use the Agent 365 Business Analytics Overview page (Frontier)](https://learn.microsoft.com/en-us/a365-business-analytics/overview)

An app that connects AI spend, usage and value across Microsoft and non-Microsoft AI services, with cost forecasts, budget tracking and top cost drivers. Business leaders and IT see metrics such as success rate, satisfaction and estimated assisted hours. Insights for Microsoft services need at least one Microsoft 365 Copilot license in the tenant, and insights for non-Microsoft services need Agent 365 or Microsoft 365 E7.

### Agent 365 usage insights for Microsoft agents
- **Status:** GA
- **Last change:** 2026-11-17, generally available without an Agent 365 license
- **More info:** [What's new in Microsoft Agent 365: Ignite 2026](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)

Admins see agent overview, active users and usage metrics for Microsoft-built and Microsoft-platform agents in the Microsoft 365 admin center with a qualifying Microsoft 365 subscription. Insights for non-Microsoft agents and advanced governance and security still need Agent 365 or Microsoft 365 E7.

### Agent Rewind
- **Status:** Preview
- **Last change:** 2026-11-17, private preview announced at Ignite 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

Lets admins roll Microsoft 365 resources back to a chosen point in time after harmful changes by an agent or attacker, with suggested timestamps. It comes with anomaly detection for ransomware or mass deletion and restores the most recently active content first. Part of Microsoft 365 Backup.

### Agent use case classification
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, Frontier preview
- **More info:** [Understand use case classification in Microsoft Cowork and Agent 365 (Frontier)](https://learn.microsoft.com/microsoft-agent-365/admin/business-use-case-for-agents)

Classifies agent sessions and Cowork activity against a built-in taxonomy of use cases and shows the result in Agent Map, the Registry and an agent's Activity tab. Admins use it to see what agents do, find agents doing similar work and link AI costs to use cases. It is on by default, can be turned off, and needs a Frontier tenant with at least 50 Copilot licenses.

### Agents usage report
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, new report in the Microsoft 365 admin center
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Shows active agent users and agents for Microsoft 365 Copilot and Copilot Chat, split by licensed and unlicensed users and publisher type, with per-user, per-agent and user-agent detail. Admins use it to track agent adoption.

### Authoritative content management for Copilot Search
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, designate up to 100 authoritative SharePoint sites
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Admins designate up to 100 SharePoint sites as authoritative under Copilot, Search, Authoritative content, with bulk import and export. Before this there was no central management for these sources.

### Auto-labeling scalability improvements
- **Status:** GA
- **Last change:** 2026-11-19, announced as generally available at Ignite 2026
- **More info:** [Secure the data that fuels AI with Microsoft Purview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/secure-the-data-that-fuels-ai-with-microsoft-purview/4573266)

Microsoft Purview auto-labeling can now label up to 500,000 SharePoint and OneDrive files per tenant per day, up from 100,000, and simulation preview covers up to 20 million items. Admins can target sites by attribute with no cap on matching sites.

### Baseline Security Mode 2026
- **Status:** GA
- **Last change:** 2026-11-17, generally available with phased rollout, adds Intune, Purview and Dynamics 365
- **More info:** [Announcing Microsoft Baseline security mode 2026 general availability](https://techcommunity.microsoft.com/blog/microsoft_365blog/ignite%E2%80%9926-spotlight-announcing-microsoft-baseline-security-mode-2026-general-ava/4572694)

A set of Microsoft-recommended security settings that a Global Administrator applies or simulates from Microsoft 365 admin center > Org settings > Security & privacy > Baseline security mode. The 2026 version adds controls such as making external users wait in the Teams lobby, blocking guests from eDiscovery roles and requiring MFA for guests. Azure and Windows settings are in private preview.

### Claude models in the EU Data Boundary
- **Status:** Roadmap
- **Last change:** 2026-11-05, announced: processing moves into the EU Data Boundary by the end of 2026
- **More info:** [Bringing Claude models in Microsoft Copilot into the EU Data Boundary](https://www.microsoft.com/en-us/copilot/blog/2026/11/05/bringing-claude-models-in-microsoft-copilot-into-the-eu-data-boundary/)

Anthropic Claude models in Copilot, including Copilot Cowork, will be processed inside the EU Data Boundary for organizations in the EU and EFTA by the end of 2026. Organizations that already use Claude need to do nothing, because processing moves automatically once available. The admin setting for Claude stays off by default in the EU and EFTA, and admins can turn it on for all users or for selected users and groups in the Microsoft 365 admin center.

### Copilot Chat fair use limits for unlicensed users
- **Status:** Rolling out
- **Last change:** 2026-11-09, rollout to organizations with more than 2,000 seats; 2026-11-02, rollout to organizations with 2,000 or fewer seats
- **More info:** [Limits for features in Microsoft Copilot Chat](https://support.microsoft.com/microsoft-365-copilot/standard-versus-priority-access-to-features-in-microsoft-365-copilot-chat)

Users without a Microsoft 365 Copilot license get fair use limits on more Copilot Chat features, not only image generation. When a user hits a limit, Copilot shows when the feature is available again and can offer to request a Microsoft 365 Copilot license from the admin. Admins cannot view or change the limits, and Microsoft does not publish the numbers. Copilot Chat stays included in Microsoft 365 subscriptions.

### Copilot connector rule editing
- **Status:** Rolling out
- **Last change:** 2026-10-06, query string and user identity mapping rules can be edited after creation
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

Admins can edit the query string and user identity mapping rules of a Copilot connector under Settings, Search & intelligence, Data sources in the Microsoft 365 admin center. Before, this needed a support ticket.

### Copilot Credits cost management
- **Status:** GA
- **Last change:** 2026-11-17, expanded as Agent 365 Cost Management (preview) with model access controls and delegated budgets
- **More info:** [Understand usage-based billing and cost management for Copilot Credits](https://learn.microsoft.com/en-us/microsoft-365/copilot/usage-based-billing-overview-copilot-credits)

Admins configure spending policies, set user and organization limits, route credit requests and review consumption by user, group, agent and service. Covers Cowork, Code, Copilot Managed Runtime, Work IQ API and more. Agent 365 Cost Management, in preview, adds limits at resource level, model access controls that reserve premium models for chosen teams, delegated budget management for business leaders, and export to Fabric for chargeback.

### Cross-tenant orchestrated migration
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, planned for December 2026
- **More info:** [Microsoft 365 Roadmap item 576273](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=576273)

From the Microsoft 365 admin center, admins can move data from one Microsoft 365 tenant to another. User data migration covers mailboxes, OneDrive, Teams chats and meetings. Shared data migration covers Microsoft 365 Groups, SharePoint sites, group mailboxes, and teams and channels.

### Custom MCP connectors
- **Status:** Rolling out
- **Last change:** 2026-10-27, listed in Copilot release notes (Roadmap ID 501585)
- **More info:** [Set up custom federated connectors](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/set-up-custom-federated-connectors)

Admins create a connector to their own Model Context Protocol (MCP) server in the Microsoft 365 admin center (Copilot, Connectors) and deploy it across the organization. Microsoft 365 Copilot can then read and act on internal data with user-scoped sign-in. Needs the Global Administrator or AI Administrator role.

### Default library labels for existing files
- **Status:** Preview
- **Last change:** 2026-11-19, public preview announced at Ignite 2026
- **More info:** [Secure the data that fuels AI with Microsoft Purview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/secure-the-data-that-fuels-ai-with-microsoft-purview/4573266)

Extends a SharePoint document library's default sensitivity label to files already in the library, without anyone opening or editing them. Compliance admins use it to protect data at rest.

### DLP for Copilot Cowork
- **Status:** GA
- **Last change:** 2026-11-12, roadmap status Launched, general availability October 2026
- **More info:** [Learn about using Microsoft Purview Data Loss Prevention to protect interactions with Microsoft 365 Copilot, Copilot Chat, and Cowork](https://learn.microsoft.com/purview/dlp-microsoft365-copilot-location-learn-about)

The Purview DLP policy location for Microsoft Copilot and Copilot Chat now also covers Copilot Cowork, so one policy applies to all three. Admins can stop Cowork from processing labeled files and emails, block prompts that contain sensitive information types and stop such prompts from going to web search. Blocking external email and custom policy tip links are not yet supported for Cowork.

### DLP for local AI agents on Windows
- **Status:** Roadmap
- **Last change:** 2026-11-19, public preview planned for January 2027
- **More info:** [Secure the data that fuels AI with Microsoft Purview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/secure-the-data-that-fuels-ai-with-microsoft-purview/4573266)

Microsoft Purview will show the activity of local agents on Windows, such as Claude Code, GitHub CLI, the GitHub Copilot app and Claude Desktop, and DLP can block prompts and tool calls that contain sensitive information. Policies can be scoped to specific agents.

### DLP for sensitive files in Copilot grounding
- **Status:** Preview
- **Last change:** 2026-11-17, public preview planned for January 2027
- **More info:** [Secure the data that fuels AI with Microsoft Purview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/secure-the-data-that-fuels-ai-with-microsoft-purview/4573266)

Purview DLP policies can stop Copilot from grounding responses on files that contain sensitive information, even when the files have no sensitivity label. Prompt protection also covers sensitive data in attachments and linked files. Used by compliance admins.

### Dynamic agent risk
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, preview
- **More info:** [What's new in Microsoft Agent 365: Ignite 2026](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)

Gives each agent one continuously updated risk level based on identity, access, data and activity signals. The same risk level is shown in the Microsoft 365 admin center, Defender, Entra and Purview, so admins and security teams work from one assessment.

### Environment routing for Copilot Managed Runtime
- **Status:** GA
- **Last change:** 2026-11-16, listed in the October/November 2026 Power Platform feature update; documentation updated 2026-11-13
- **More info:** [Environment routing for Microsoft Copilot Managed Runtime](https://learn.microsoft.com/en-us/power-platform/admin/default-environment-routing-copilot-managed-runtime)

Environment routing for Copilot Managed Runtime is on in every tenant and admins cannot turn it off. If a tenant has no routing rules, an Everyone rule and a default environment group are created, and makers get personal managed environments without Dataverse. If routing rules already exist, only makers in the rule security groups can build apps on Copilot Managed Runtime until admins add an Everyone rule. Admins can limit app creation in the Microsoft 365 admin center under Set up app creation spaces.

### Expanded DLP enforcement in Edge for Business
- **Status:** Roadmap
- **Last change:** 2026-11-11, added to roadmap, planned for December 2026
- **More info:** [Microsoft 365 Roadmap item 579894](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=579894)

Microsoft Edge for Business extends its Data Loss Prevention enterprise connectors. Admins can enforce policy consistently on download, upload, paste and print, require a justification to bypass a block and show their own guidance to users.

### Local agents in the Microsoft 365 admin center
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026 with Entra Agent ID for local agents and Intune controls, all in preview
- **More info:** [Local agents in Microsoft 365 admin center (Preview)](https://learn.microsoft.com/en-us/microsoft-agent-365/admin/agent-local)

A Local Agents page in the Microsoft 365 admin center shows developer AI tools found on managed Windows devices, such as Claude Code, GitHub Copilot CLI, Codex CLI and VS Code agent extensions, with the devices they run on. Admins can block some of them through an Intune policy. Supported local agents, starting with GitHub Copilot CLI and Claude Code, can also get their own Microsoft Entra Agent ID, and Intune can mark devices with unapproved agents as noncompliant. It needs the Frontier program, Intune enrollment and at least a Microsoft 365 E3 license.

### Low-latency Monitor alerts
- **Status:** Preview
- **Last change:** 2026-11-11, public preview in all commercial clouds by 2026-11-20
- **More info:** [Alerts in Monitor](https://learn.microsoft.com/en-us/power-platform/admin/monitoring/alerts#monitor-critical-resources-with-low-latency-alerts-preview)

Admins set an alert rule's data review period to 1 hour, so Monitor evaluates the metric every hour instead of once a day. It covers metrics for canvas, code, model-driven and Copilot Managed Runtime apps, cloud flows and agents, with a 24-hour hourly chart. Up to 10 hourly rules per admin center, and Managed Environments requirements apply.

### Maker guidelines for Copilot Studio
- **Status:** Preview
- **Last change:** 2026-11-16, public preview announced in the October/November 2026 Power Platform feature update
- **More info:** [Configure maker guidelines for Copilot Studio (preview)](https://learn.microsoft.com/en-us/power-platform/admin/maker-guidelines)

Power Platform admins can write a short message (up to 400 characters), with an optional link button and contact email, that Copilot Studio makers see in the Review pane of an agent. It points makers to internal guidance, request processes or support while they build. Admins set it per environment or environment group in the Power Platform admin center under Copilot, Settings. Available only in Managed Environments.

### Managed developer environment requirement
- **Status:** Retiring
- **Last change:** 2026-11-15, creation of unmanaged developer environments ends; suspended 2026-12-15, deleted 2027-01-15
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

From 15 November 2026 new developer environments must be managed, with one per user, and the Power Apps Developer Plan no longer creates one. Existing unmanaged developer environments are suspended on 15 December 2026 and deleted on 15 January 2027. Admins enable Managed Environments or move solutions, and makers export their solutions. Managed Environments use rights need a premium license.

### Microsoft 365 Backup recovery window up to 10 years
- **Status:** GA
- **Last change:** 2026-11-17, configurable recovery window generally available
- **More info:** [Create, view, and edit backup policies in Microsoft 365 Backup](https://learn.microsoft.com/en-us/microsoft-365/backup/backup-view-edit-policies?view=o365-worldwide#configure-the-backup-recovery-window)

Admins set how long Microsoft 365 Backup keeps restore points per policy: from 3 months up to 10 years for SharePoint and OneDrive, and up to 2 years for Exchange. Existing policies default to 1 year. Shortening the window deletes older restore points only after a 30-day grace period.

### Microsoft 365 Copilot add-on SKU rename
- **Status:** Rolling out
- **Last change:** 2026-10-16, current offers renamed with (add-on); standalone offers from 2026-12-01
- **More info:** [October 2026 announcements - Partner Center](https://learn.microsoft.com/en-us/partner-center/announcements/2026-october)

From 16 October 2026 the Copilot offers that need a base subscription carry (add-on) in the name. From 1 December 2026 new Copilot and Copilot Business offers can be bought without a base subscription, at the same price.

### Microsoft Agent 365
- **Status:** GA
- **Last change:** 2026-05-01, feature listed
- **More info:** [Microsoft Agent 365, now generally available](https://www.microsoft.com/en-us/security/blog/2026/05/01/microsoft-agent-365-now-generally-available-expands-capabilities-and-integrations/)

A control plane for AI agents with governance, observability and security for the agents an organization runs. Used by admins and security teams.

### Monitor alert routing to connector destinations
- **Status:** Preview
- **Last change:** 2026-11-10, public preview announced in the October/November feature update
- **More info:** [Create alerts for your resources](https://learn.microsoft.com/en-us/power-platform/admin/monitoring/alerts)

A "When an alert fires" trigger in the Power Platform for Admins V2 connector lets admins route Power Platform Monitor alerts through Power Automate to any connector-backed destination, such as a Teams channel or a ticketing system. Used by admins who watch the health of critical apps and flows.

### Monitor metrics export API
- **Status:** Preview
- **Last change:** 2026-11-10, announced in the October/November feature update
- **More info:** [Export Monitor metrics by using the API](https://learn.microsoft.com/en-us/power-platform/admin/monitoring/monitor-data-export)

A REST API returns Monitor's daily metric aggregates for Power Platform resources in OpenTelemetry (OTLP JSON) format. Admins store the data themselves to keep it beyond Monitor's 30-day window, share it with colleagues or combine it with other operational data in tools such as Datadog or Splunk.

### Multi-tenant agent management
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, public preview
- **More info:** [What's new in Microsoft Agent 365: Ignite 2026](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)

Partners and organizations with several tenants get one view to deploy, compare and approve or block agents across tenants, instead of managing each tenant separately.

### Office LTSC 2021 end of support
- **Status:** Retiring
- **Last change:** 2026-10-13, feature listed
- **More info:** [October 2026 announcements - Partner Center](https://learn.microsoft.com/en-us/partner-center/announcements/2026-october)

Office, Project and Visio LTSC 2021 no longer receive updates or security fixes. Copilot works only on cloud-backed Microsoft 365 apps.

### Plugin and skill governance
- **Status:** GA
- **Last change:** 2026-11-17, plugins and skills governance generally available, gateway support in preview
- **More info:** [Overview of the Tools page in Microsoft 365 admin center](https://learn.microsoft.com/en-us/microsoft-agent-365/admin/agent-tools-overview)

Admins use the Tools page in the Microsoft 365 admin center to see and block plugins, skills, MCP servers and connectors, and to assign plugins and skills to users and groups for Copilot and Cowork. Before blocking an MCP server, admins can see which agents and plugins depend on it. Azure AI Gateway and LiteLLM support is in preview.

### Power Platform Admin in Cowork
- **Status:** Preview
- **Last change:** 2026-11-10, public preview highlighted in the October/November feature update
- **More info:** [Power Platform Admin in Cowork (preview)](https://learn.microsoft.com/en-us/power-platform/admin/power-platform-admin-cowork)

A plugin for Copilot Cowork that lets Power Platform, Dynamics 365 and Global admins ask plain-language questions about environments, inventory, usage, ownership, capacity and licensing. Cowork can turn answers into reports, draft emails to owners or repeat a question on a schedule. The plugin is read-only, and questions consume Copilot Credits.

### Shadow AI in the Microsoft 365 admin center
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, Frontier public preview
- **More info:** [Shadow AI in Microsoft 365 admin center (Preview)](https://learn.microsoft.com/en-us/microsoft-agent-365/admin/agent-shadow-ai)

A Shadow AI page lists unmanaged AI apps and agents found on devices, such as ChatGPT Desktop, Claude Desktop, Ollama and OpenClaw, with device, user and network details. Admins can block OpenClaw on Intune-managed Windows devices. It needs the Frontier program, Defender for Endpoint, Intune and a Microsoft 365 E5 license.

### Share custom organizational attributes with people experiences
- **Status:** Rolling out
- **Last change:** 2026-11-19, listed in the November 17, 2026 release notes
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Admins choose custom organizational attributes in the Microsoft 365 Organizational Data Service to share with the Microsoft 365 people store. Shared attributes are visible to all users and guests in the tenant. The setting is off by default.

### Skills in Copilot Studio setting
- **Status:** GA
- **Last change:** 2026-11-16, announced in the October/November 2026 Power Platform feature update
- **More info:** [Configure skills in the Power Platform admin center](https://learn.microsoft.com/en-us/power-platform/admin/skills-copilot-studio-rule)

Admins choose which types of skills Copilot Studio agents can reference, per environment (Security, Data and privacy) or per environment group (Rules tab) in the Power Platform admin center. It gives environment-level governance and observability for skills. Advanced connector policies do not support this rule. Replaces Copilot Studio virtual connectors in classic data policies.

### Teams channel backup
- **Status:** Preview
- **Last change:** 2026-11-17, private preview announced at Ignite 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

Microsoft 365 Backup can protect Teams channels, recover a channel together with its SharePoint content and restore deleted or edited channel messages within 30 days. New channels in a protected team are protected automatically. Hard deletion is not yet covered.

### Work IQ enterprise controls
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, preview
- **More info:** [What's new in Work IQ at Ignite 2026: agents that get work done](https://techcommunity.microsoft.com/blog/microsoft_365blog/whats-new-in-work-iq-at-ignite-2026-agents-that-get-work-done/4572219)

Admins can set a tenant-wide ceiling for agent actions in Work IQ, for example read, create and update but not delete, that per-agent policies cannot exceed. Separate WorkIQ.Read and WorkIQ.Act permissions let policies allow, block or require a person's approval for an action.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
