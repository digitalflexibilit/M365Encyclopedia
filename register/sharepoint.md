# SharePoint

Last updated: 2026-11-22

## Current features

### Agent access heatmap
- **Status:** Roadmap
- **Last change:** 2026-11-17, announced at Ignite 2026, GA expected in December 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

A heatmap for SharePoint admins that shows where agents access SharePoint and OneDrive content, broken down by sensitivity label, department and agent platform. It helps admins spot risky agent access before it becomes oversharing.

### Agent access insights report
- **Status:** GA
- **Last change:** 2026-11-21, highlighted at Ignite 2026 together with a file-level Everyone except external users report
- **More info:** [Monitor agent access to SharePoint and OneDrive](https://learn.microsoft.com/en-us/sharepoint/insights-on-agent-access)

Shows SharePoint admins how agents, such as SharePoint agents, declarative agents and custom agents, read and search content across SharePoint and OneDrive, based on audit logs. Admins see the sites with the most agents and the top agents per site, and can apply Restricted access control or Restricted content discovery from the report. Found in the SharePoint admin center under Reports, Agent insights, or through PowerShell. Without SharePoint Advanced Management, admins must first enable data collection.

### App Intelligence for SharePoint and OneDrive
- **Status:** Roadmap
- **Last change:** 2026-11-17, announced at Ignite 2026, GA expected in December 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

Helps admins find third-party apps with high-privilege access to SharePoint and OneDrive and restrict that access. Intended to reduce the risk of apps reading more content than they need.

### Application Restrictions for apps and agents
- **Status:** Rolling out
- **Last change:** 2026-11-17, announced as GA at Ignite 2026, cmdlets rolling out
- **More info:** [Restrict SharePoint site access for applications and agents with Application Restrictions](https://learn.microsoft.com/en-us/sharepoint/restrict-application-agent-access)

Lets SharePoint admins decide which third-party apps and agents can reach a site, even when the app has Entra consent and SharePoint permissions. Each site gets an allow list or a deny list, and a tenant deny list blocks an app everywhere; an agent blueprint ID covers all agents built from it. Configured only with SharePoint Online PowerShell. Microsoft first-party apps and OneDrive are not in scope.

### Catalog management
- **Status:** GA
- **Last change:** 2026-11-21, highlighted at Ignite 2026 for governance at scale
- **More info:** [Catalog management in SharePoint Advanced Management](https://learn.microsoft.com/en-us/sharepoint/catalog-management)

Groups SharePoint sites into categories and groups from existing metadata, such as department, region, custom site properties or Entra ID extension attributes. Admins use the groups to understand where content sits and to apply Restricted content discovery to up to 20,000 sites at once. Part of SharePoint Advanced Management, found under Reports in the SharePoint admin center.

### Copilot in SharePoint PDF, version history and Advanced Autofill
- **Status:** Rolling out
- **Last change:** 2026-10, PDF page and section tools, version history restore, Advanced Autofill
- **More info:** [What’s new in Copilot in SharePoint: October 2026](https://techcommunity.microsoft.com/blog/spblog/what%E2%80%99s-new-in-copilot-in-sharepoint-october-2026/4535423)

Copilot can work with PDFs at page and section level, such as extracting sections, reordering pages and splitting a file. It can read a file’s version history, explain what changed and restore an earlier version. Autofill fills library columns from a description, and Advanced Autofill needs Copilot Credits. End users need a Microsoft 365 Copilot license.

### Copilot metadata understanding for libraries and folders
- **Status:** Rolling out
- **Last change:** 2026-07, column metadata used in Copilot queries scoped to a library or folder
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

When a SharePoint document library or folder is attached to Microsoft 365 Copilot, or its URL is given, Copilot now uses the column metadata of that library. This makes answers about the documents more accurate. End users use it in Copilot on the web with a Microsoft 365 Copilot license.

### Everyone except external users permissions report
- **Status:** GA
- **Last change:** 2026-10-06, released on web
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

Gives SharePoint Advanced Management admins an item-level report of content shared with the Everyone and Everyone except external users groups. Admins use it to find oversharing, for example before rolling out Copilot.

### File archive policies
- **Status:** Preview
- **Last change:** 2026-11-17, file-level archive announced as GA and inactive file policies in public preview at Ignite 2026
- **More info:** [New-SPOFileArchivePolicy](https://learn.microsoft.com/powershell/module/microsoft.online.sharepoint.powershell/new-spofilearchivepolicy?view=sharepoint-ps)

Admins can archive individual inactive files instead of whole sites. A policy sets how many months without access count as inactive, which file types are included and which SharePoint sites or OneDrive accounts are in scope, and a what-if mode reports what would be archived first. Policies are created with New-SPOFileArchivePolicy or through the SharePoint Admin Agent.

### HTML pages with Copilot
- **Status:** Preview
- **Last change:** 2026-10-31, public preview from early October, general availability planned mid-November to late December 2026
- **More info:** [Create, edit and publish HTML pages in SharePoint](https://support.microsoft.com/en-us/sharepoint/create-edit-publish-html-pages)

Authors create an HTML page with Copilot or upload their own HTML to the Site Pages library, then edit, publish and share it alongside ASPX pages. Creating or editing with Copilot needs a Microsoft 365 Copilot license. Site owners can control it with the Allow HTML files setting.

### Multi-Geo default geo move
- **Status:** Preview
- **Last change:** 2026-11-17, public preview announced at Ignite 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

Customers with Multi-Geo can move their default SharePoint and OneDrive geo location to a more specific region, such as Germany or Korea. This helps meet data residency requirements for the central location.

### Permission report for a group
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, date moved from June to November 2026
- **More info:** [Microsoft 365 Roadmap item 561039](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=561039)

A new data access governance report in the SharePoint admin center shows every site a given group can access and the level of that access. Admins use it to find broad or vendor groups that expose sensitive content.

### Restrict collaboration by agentic users
- **Status:** Roadmap
- **Last change:** 2026-11-17, announced at Ignite 2026, public preview expected in December 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

A setting that limits Agentic Users to sharing sites and content only with their manager. AI admins turn it on when they onboard an agent template in the Agent 365 portal, and SharePoint admins manage it under Agent Governance in the SharePoint admin center settings.

### SharePoint Admin Agent
- **Status:** GA
- **Last change:** 2026-11-22, Content Governance Hub for admins expected GA in December 2026, Governance Hub for site owners in public preview
- **More info:** [SharePoint Admin Agent overview](https://learn.microsoft.com/en-us/sharepoint/content-governance-agent)

An AI agent for SharePoint admins that answers natural-language questions about the tenant, such as oversharing, storage, inactive sites and agent access, and suggests remediation steps. Admins open it in the Copilot app, in Teams or through Copilot in the SharePoint admin center. A Content Governance Hub on the Home tab of the SharePoint admin center brings its assessments, findings and tasks together, expected GA in December 2026. A Governance Hub for site owners, in public preview, shows owners their pending governance reviews. Needs SharePoint Advanced Management and the SharePoint Advanced Management Administrator role.

### SharePoint extra storage pay-as-you-go
- **Status:** Preview
- **Last change:** 2026-11-17, public preview, GA planned for January 2027
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

A pay-as-you-go meter for SharePoint storage beyond the tenant quota, billed at USD 0.20 per GB per month at GA. Admins pay for what they use instead of buying fixed storage add-ons.

### SharePoint list agent
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, create Microsoft Lists from natural-language prompts
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

The list agent creates a Microsoft List from a natural-language prompt and generates the list schema and setup. End users use it on the web instead of building columns by hand.

### SharePoint tools in Work IQ
- **Status:** Preview
- **Last change:** 2026-11-19, public preview, highlighted at Ignite 2026
- **More info:** [SharePoint Tools for Work IQ](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq/sharepoint-iq)

Gives Copilot and agents more than 60 SharePoint operations, such as working with lists and libraries, organizing files, approvals, version history and knowledge bases. Developers and makers use them through the Work IQ MCP interface with the WorkIQ.Read or WorkIQ.Act permission, and admins must enable Work IQ. Users' own SharePoint permissions and tenant policies still apply. Usage is billed in Copilot Credits.

### Tenant-wide version trimming
- **Status:** Preview
- **Last change:** 2026-11-17, public preview announced at Ignite 2026
- **More info:** [Microsoft 365 Copilot and AI Agent readiness and resiliency with SharePoint Content Governance](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

Admins can trim old file versions across the whole tenant to free storage, with a what-if analysis that shows the effect before anything is deleted. Available first through PowerShell, with SharePoint Admin Agent support to follow.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
