# Microsoft 365 Copilot

Last updated: 2026-11-21

## Current features

### App Blocks
- **Status:** Rolling out
- **Last change:** 2026-11-12, roadmap status changed to rolling out, November 2026
- **More info:** [Microsoft 365 Roadmap item 577743](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=577743)

App Blocks turns a Copilot Chat request and its data into an interactive element inside the conversation, such as a calculator, dashboard, form, planner, comparison tool or simulation. Users can change inputs and see the result in place instead of reading a static answer. It can also retrieve current information first and then show it in the interactive element.

### Auto model routing
- **Status:** Preview
- **Last change:** 2026-11-17, Auto in Cowork rolling out to Frontier, chat-to-Cowork recommendations GA
- **More info:** [Home: your starting place for work in the Microsoft Copilot app](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)

Auto chooses the model and reasoning effort for each task or step, balancing quality, speed and cost. In Cowork it uses Microsoft-Decision-1.1 and splits large tasks across subagents that run side by side, which can use models from different providers. End users no longer need to pick a model by hand.

### Autopilot
- **Status:** Preview
- **Last change:** 2026-11-17, rolling out to Frontier program customers
- **More info:** [Autopilot (Frontier) overview](https://learn.microsoft.com/en-us/copilot/autopilot/overview)

Autopilot is a persistent, cloud-based agent in the Copilot app with its own Entra identity, mailbox, calendar, memory and workspace. An end user describes an outcome, sources and boundaries, and Autopilot prepares documents, follows up on work and runs routines on a schedule or on events, asking for approval before actions that don't match the request. Colleagues can @mention it in Teams channels and group chats. Needs Frontier enrollment and runs on usage-based billing. Replaces Scout.

### Brand Kit in Cowork
- **Status:** Rolling out
- **Last change:** 2026-11-17, rolling out
- **More info:** [What's new in Copilot Cowork at Ignite 2026](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/whats-new-in-copilot-cowork-at-ignite-2026/4572242)

Cowork applies an organization's named brand kit, with colors, fonts and brand voice, when it builds content. It helps end users produce on-brand documents and decks without manual formatting.

### Business Apps in Work IQ
- **Status:** Preview
- **Last change:** 2026-11-14, Microsoft 365 Roadmap item 573293 adds access from Copilot Cowork, planned for December 2026
- **More info:** [Business apps in Work IQ](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/business-applications-work-iq)

Brings business context from Dynamics 365 and Power Apps into Copilot and agents, with governed actions. Used by makers and admins who want agents to act on business data. Copilot Cowork users will also be able to reach business applications through Work IQ and use business skills to complete business processes.

### Business skills in Work IQ MCP
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, planned for November 2026
- **More info:** [Microsoft 365 Roadmap item 573290](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=573290)

Business skills are plain-language instructions that describe how an organization does a type of work: the steps, the information needed and the business rules. Agents find the skills they have access to through the Work IQ MCP server and follow them at runtime, so several agents handle the same process in the same way. Used by makers and admins who want agents to follow company processes.

### Claude Fable 5.2 model in Cowork
- **Status:** GA
- **Last change:** 2026-11, available in the Cowork model selector for select customers, replacing Fable 5.1
- **More info:** [What's new in Copilot Cowork](https://learn.microsoft.com/en-us/copilot/cowork/whats-new)

End users can select Anthropic Claude Fable 5.2 in the Cowork model selector. It replaces Fable 5.1 in Cowork and requires data retention by the model provider.

### Code in Copilot
- **Status:** Preview
- **Last change:** 2026-11-17, general availability planned for December 2026, local sandbox on Windows
- **More info:** [Use Copilot Code (Frontier)](https://learn.microsoft.com/en-us/copilot/code/use-code)

Code lets users describe an app, tracker, dashboard or automation in natural language and have Copilot build it in a sandbox, using the same technology as GitHub Copilot. Results can be hosted inside the tenant. Needs a Copilot license and runs on usage-based billing.

### Confluence Cloud connector query filters
- **Status:** Rolling out
- **Last change:** 2026-11-19, listed in the November 17, 2026 release notes
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Admins can include or exclude specific Confluence spaces and use CQL query strings to limit which Confluence Cloud pages the Copilot connector syncs. This keeps irrelevant or sensitive pages out of Copilot answers.

### Copilot Chat regenerate response
- **Status:** Rolling out
- **Last change:** 2026-10-06, Regenerate action with model switching on the web
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

The Regenerate action gives an alternative answer to the latest prompt, with Try Again or Switch Model options. End users no longer need to retype the prompt.

### Copilot Cost Management API
- **Status:** GA
- **Last change:** 2026-10, new API for governing Copilot credit consumption
- **More info:** [Understand usage-based billing and cost management for Copilot Credits](https://learn.microsoft.com/en-us/microsoft-365/copilot/usage-based-billing-overview-copilot-credits)

A Microsoft Graph API that lets admins manage spending policies, configure service access and notifications, and read tenant and user level Copilot Credit consumption. It reports credits only, not prices or invoices.

### Copilot Managed Runtime
- **Status:** GA
- **Last change:** 2026-11-17, generally available, Fabric storage option in Frontier preview
- **More info:** [Copilot Managed Runtime is now generally available](https://techcommunity.microsoft.com/blog/copilot-managed-runtime-blog/copilot-managed-runtime-is-now-generally-available-with-additional-new-preview-f/4571846)

Microsoft-operated hosting for apps built in Copilot Code, Cowork, Copilot Studio, GitHub Copilot, VS Code or third-party tools. Apps run inside the tenant with Entra identity, governed data and connector access, policy enforcement and audit logging, and stay editable and Git-backed. Admins see an app inventory and monitoring in the Microsoft 365 admin center. Consumes Copilot Credits.

### Copilot memory
- **Status:** Rolling out
- **Last change:** 2026-11-21, memory expanding to Word, Excel, PowerPoint, Workspaces, Pages, Outlook and Teams; memory citations GA; email writing style and Work IQ MCP memory access rolling out (announced 2026-11-18)
- **More info:** [The End of Starting Over: How Work IQ helps Copilot understand you and your work](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/the-end-of-starting-over-how-work-iq-helps-copilot-understand-you-and-your-work/4571169)

Copilot remembers custom instructions, saved memories and details from chat history so users do not have to repeat context. Memory now also learns formatting, tone and work structure across Word, Excel, PowerPoint, Workspaces, Pages, Outlook and Teams, and learns a user's email writing style for drafts. Memory citations under a response show which instructions, memories and past chats were used, and users can delete memories from there. Authorized agents can read the memory profile through a Work IQ MCP tool. Admins control it with the Enhanced personalization setting, which is on by default and can be turned off for the tenant or an Entra group.

### Copilot New Tab Page in Microsoft Edge
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, refreshed new tab page with search, chat and suggested actions
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

The refreshed Edge new tab page combines search, chat, Copilot-suggested actions, curated work content, news and activities in one search box. End users use it on the web.

### Copilot Pages
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, Frontier public preview
- **More info:** [Office at Ignite 2026: From apps to agentic system of work](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)

Copilot turns a prompt and source material into an interactive report, brief, dashboard or animation. Agents can keep the data in the page up to date in the background. End users with Microsoft 365 Copilot get it through the Frontier program.

### Copilot Search with embedded chat
- **Status:** Rolling out
- **Last change:** 2026-10-06, chat embedded in Copilot Search results on Windows and web (Roadmap ID 512429)
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

Microsoft 365 Chat is built into Copilot Search results. End users can ask follow-up questions, synthesize information and generate content without leaving the search page. A Microsoft 365 Copilot license is needed.

### Copilot usage metrics for apps
- **Status:** Rolling out
- **Last change:** 2026-10-27, new metrics for the Copilot app, Edge, OneNote, Outlook, Word, Excel and PowerPoint
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

The Copilot Dashboard and Viva Insights Advanced Analysis show new usage metrics for Copilot in the Copilot app, Edge, OneNote, Outlook, Word, Excel and PowerPoint. Admins and analysts use them to track adoption.

### Copilot Workspaces
- **Status:** Rolling out
- **Last change:** 2026-11-17, Copilot Notebooks renamed to Copilot Workspaces, with team collaboration added; phased rollout started late October 2026
- **More info:** [Copilot Notebooks is now Copilot Workspaces](https://support.microsoft.com/en-us/microsoft-365-copilot/copilot-notebooks-to-copilot-workspaces)

Workspaces are a shared place where a team collects files, pages and Copilot chats and works on them together with Copilot. Members can see who else is in the workspace, work across several documents at once and invite people from the Invite button. Personal work stays in Projects on the Home tab, and items can be moved from a project into a workspace to share them. Existing notebooks convert automatically with their content and sharing, and no features are removed. Replaces Notebooks in Microsoft 365 Copilot.

### Cowork and Chat in Home
- **Status:** GA
- **Last change:** 2026-11-17, Chat and Cowork in Home generally available, Home rolling out worldwide
- **More info:** [Home: your starting place for work in the Microsoft Copilot app](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)

Home is the starting point in the Copilot app, with one prompt box and a shared conversation history. Chat handles quick questions and drafts, and Cowork runs delegated, multistep tasks end to end. When a request is complex, Copilot can recommend switching from Chat to Cowork and carries the prompt and context over.

### Cowork event-driven triggers for non-Microsoft connectors
- **Status:** Rolling out
- **Last change:** 2026-10, tasks can start from events in supported non-Microsoft connectors and plugins
- **More info:** [What's new in Copilot Cowork](https://learn.microsoft.com/en-us/copilot/cowork/whats-new)

Besides scheduled prompts and Microsoft 365 events such as a matching email, Cowork tasks can now start from events in supported non-Microsoft connectors and plugins, for example a new case in a customer relationship management system. Users set this up by describing what to watch for, and Cowork proposes the automation to confirm. Power Platform and Copilot connectors can also be used to reach more external systems.

### Cowork local Microsoft Edge browser use
- **Status:** Rolling out
- **Last change:** 2026-11-06, released in the November 4 update
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Lets Cowork use the end user's local Microsoft Edge browser to complete web steps, including on sites the user is already signed in to. Cowork works in a separate Edge tab, and credentials, cookies and session tokens stay on the device.

### Cowork projects
- **Status:** GA
- **Last change:** 2026-11-17, Projects generally available across Chat and Cowork
- **More info:** [Home: your starting place for work in the Microsoft Copilot app](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)

Projects keep related Chat conversations, Cowork tasks, saved instructions, sources and outputs together. Users start tasks from a project, return to related chats and review the files the tasks produced, which are stored in OneDrive.

### Declarative agents in Copilot Cowork
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026, private preview through the Frontier program
- **More info:** [Microsoft Ignite 2026 Book of News](https://news.microsoft.com/events/ignite/2026/book-of-news/)

Cowork can suggest tasks for and call declarative agents that an organization has built, so company agents become part of Cowork tasks. End users with a Microsoft 365 Copilot license get it through the Frontier program while it is in private preview.

### Dynamics 365 plugins in Copilot
- **Status:** GA
- **Last change:** 2026-11-17, Sales and ERP plugins generally available
- **More info:** [What's new in Copilot Cowork at Ignite 2026](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/whats-new-in-copilot-cowork-at-ignite-2026/4572242)

Plugins that bring Dynamics 365 Sales, Customer Service and finance and operations skills into Copilot Cowork, PowerPoint and Excel. The Sales plugin covers account briefs, pitch decks, business reviews, proposals and pipeline insights, and the ERP plugin adds finance skills such as month-end close support. Users need a Copilot license and access to the Dynamics 365 data.

### Fabric IQ grounding for Copilot
- **Status:** GA
- **Last change:** 2026-09-25, GA in Chat and Cowork
- **More info:** [Introducing the new Copilot with Home, Code and Autopilot](https://blogs.microsoft.com/blog/2026/09/25/introducing-the-new-copilot-with-home-code-and-autopilot/)

Fabric IQ grounds Copilot Chat and Cowork in trusted business data, including Power BI semantic models. Business users get answers based on governed data without leaving Copilot.

### GPT-6.2 Sol and GPT-6.2 Astra models
- **Status:** Rolling out
- **Last change:** 2026-11-21, rolling out worldwide from 2026-11-20
- **More info:** [Available today: OpenAI's GPT-6.2 Sol and GPT-6.2 Astra in Microsoft Copilot](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/available-today-openais-gpt-6-2-sol-and-gpt-6-2-astra-in-microsoft-copilot/4574229)

Two new OpenAI models for Copilot. GPT-6.2 Sol is rolling out to eligible users in Copilot Chat, Copilot Cowork, Copilot Studio and Copilot in Word, Excel and PowerPoint. GPT-6.2 Astra is rolling out in Cowork and Copilot Studio, and Frontier users also get it in Copilot Chat and the Office apps. Admins manage model availability in the Microsoft 365 admin center.

### HubSpot connector in Researcher
- **Status:** Rolling out
- **Last change:** 2026-11-05, 2026-11-04, Researcher can use the HubSpot connector
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

Researcher can add HubSpot data to its responses through the HubSpot connector. End users use it for research that needs CRM data.

### Learning agent in Microsoft 365 Copilot
- **Status:** Rolling out
- **Last change:** 2026-11-21, AI upskilling tab, AI Skills Navigator playlists, starter prompts, prompt coaching and admin AI policy (Frontier) announced 2026-11-17
- **More info:** [Overview of Learning agent](https://learn.microsoft.com/en-us/viva/learning/learning-agent-overview)

An agent in Microsoft Copilot that gives employees personalized microlearning and structured learning paths, including Copilot upskilling tips, plans and assessments. An AI upskilling tab, AI Skills Navigator playlists and prompt coaching help users practice Copilot in their own work, personalized with Work IQ memory. End users add it from the agent store, and admins deploy it in the Microsoft 365 admin center, assign training and, in Frontier, add their AI usage policy. A Microsoft Copilot license is needed, and Viva Learning Premium unlocks advanced features.

### Office in Copilot
- **Status:** GA
- **Last change:** 2026-11-17, generally available in Chat and Cowork in the Copilot app
- **More info:** [Home: your starting place for work in the Microsoft Copilot app](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)

Word, Excel and PowerPoint are built into the Copilot app, so Copilot creates or updates real, editable documents, workbooks and presentations that people can coauthor and share. Files save to OneDrive and keep Microsoft 365 permissions, sensitivity labels and compliance controls. Used by end users with a Copilot license, with no metered usage for creating decks or spreadsheets.

### People and organizational context in Work IQ
- **Status:** Rolling out
- **Last change:** 2026-11-21, people and org data, analytical reasoning and skills insights rolling out to GA through December 2026; organizational context in Frontier (announced 2026-11-16)
- **More info:** [Copilot that understands your organization: Introducing people and org context in Work IQ](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/copilot-that-understands-your-organization-introducing-people-and-org-context-in/4573356)

Copilot can answer questions about people and organizational structure using authoritative HR data, including standard and custom attributes, and can calculate counts, ratios, averages and rankings. Organizational skills insights show how skills are spread across teams. Admins bring in HR data through the Microsoft 365 Organizational Data Service or Copilot connectors. In Frontier, admins and HR specialists can add company terminology, attribute definitions and guidelines in the Workforce Insights Agent, which needs Microsoft 365 Copilot licenses.

### Plugin registry
- **Status:** Rolling out
- **Last change:** 2026-09-25, rolling out now,  GA across surfaces in the coming weeks
- **More info:** [Introducing the new Copilot with Home, Code and Autopilot](https://blogs.microsoft.com/blog/2026/09/25/introducing-the-new-copilot-with-home-code-and-autopilot/)

A unified catalog of Microsoft, partner and custom plugins for Copilot. IT approves and manages plugins centrally, and developers publish once to extend Copilot across supported experiences.

### Rich entity cards for connector results
- **Status:** Rolling out
- **Last change:** 2026-10-27, listed in Copilot release notes
- **More info:** [Release Notes for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365/copilot/release-notes)

Results from Copilot connectors in Search appear as entity cards with metadata instead of plain text links. End users can see more about an item before opening it.

### Salesforce in Copilot
- **Status:** Preview
- **Last change:** 2026-11-17, public preview announced
- **More info:** [What's new in Copilot Cowork at Ignite 2026](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/whats-new-in-copilot-cowork-at-ignite-2026/4572242)

A plugin that brings Salesforce account, opportunity and pipeline context into Copilot Cowork, with more than 38 prebuilt sales skills. Sales users work with Salesforce data without leaving Copilot. Admins control which plugins are available.

### Tableau Copilot connector
- **Status:** Rolling out
- **Last change:** 2026-11-19, listed in the November 17, 2026 release notes
- **More info:** [Microsoft 365 Copilot release notes](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)

A Copilot connector for Tableau lets end users ask Copilot about Tableau dashboards and visualizations and get explanations of the data. Permissions from Tableau still apply, so users only see content they can already access. Admins set up the connector.

### Today
- **Status:** Preview
- **Last change:** 2026-11-17, private preview through the Frontier program
- **More info:** [Home: your starting place for work in the Microsoft Copilot app](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)

Today surfaces an end user's priorities across mail, calendar, Teams chats, meetings and Cowork tasks, in the Copilot app and in Outlook. It prepares drafts and scheduling changes for the user to review and approve. Today Brief is included with a Microsoft 365 Copilot license, and Today Feed uses Copilot Credits.

### Usage-based billing default for Copilot Business
- **Status:** Roadmap
- **Last change:** 2026-10-01, effective date moved from 2026-11-02 to 2026-12-01
- **More info:** [October 2026 announcements - Partner Center](https://learn.microsoft.com/en-us/partner-center/announcements/2026-october)

From 1 December 2026, usage-based billing is on by default for new Microsoft 365 Copilot Business licenses bought through CSP, with a default limit of 4,000 Copilot Credits per user per month that admins can change. Not available at first in several markets.

### Work IQ API declarative agent access
- **Status:** Rolling out
- **Last change:** 2026-10-27, listed in Copilot release notes
- **More info:** [Work IQ overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq/)

Developers get programmatic access to first-party and tenant-defined declarative agents through the Work IQ endpoint, so their own apps can call those agents.

### Work IQ API usage-based billing
- **Status:** Rolling out
- **Last change:** 2026-10-27, listed in Copilot release notes (Roadmap ID 559017)
- **More info:** [Work IQ overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq/)

Developers can call Work IQ endpoints (A2A, MCP and REST) from their own agents and apps without a pre-assigned Microsoft 365 Copilot license. Usage is billed in Copilot Credits per request, based on the agents and models invoked. Admins manage the cost in the Microsoft 365 admin center.

### Work IQ context enhancements
- **Status:** Preview
- **Last change:** 2026-11-21, rolling out to public preview from November 2026 (announced 2026-11-17)
- **More info:** [SharePoint and OneDrive at Microsoft Ignite 2026](https://techcommunity.microsoft.com/blog/spblog/sharepoint-and-onedrive-at-microsoft-ignite-2026-putting-ai-powered-content-to-w/4535416)

Gives custom agents built on Work IQ the same document understanding that Copilot uses, including Markdown, images, thumbnails, summaries and lookups inside a file. Developers and makers get better answers from SharePoint and OneDrive content without building their own processing. Deeper context for sites, chats, meetings and email is planned later, without dates.

### Work IQ listen capability
- **Status:** Preview
- **Last change:** 2026-11-17, announced at Ignite 2026
- **More info:** [What's new in Work IQ at Ignite 2026: agents that get work done](https://techcommunity.microsoft.com/blog/microsoft_365blog/whats-new-in-work-iq-at-ignite-2026-agents-that-get-work-done/4572219)

Agents that use Work IQ can react to events, such as a new message or a business event, without a person starting the conversation and without polling for updates. Makers and developers use it to build proactive agents.

### Work IQ plugin for ChatGPT
- **Status:** GA
- **Last change:** 2026-11-19, available in the ChatGPT plugin directory, announced at Ignite 2026
- **More info:** [What's new in Work IQ at Ignite 2026: agents that get work done](https://techcommunity.microsoft.com/blog/microsoft_365blog/whats-new-in-work-iq-at-ignite-2026-agents-that-get-work-done/4572219)

A Work IQ plugin brings Microsoft 365 work context, such as mail, meetings and files, into ChatGPT for ChatGPT Business and Enterprise customers. Users install it from the ChatGPT plugin directory, and Work IQ permissions and tenant policies still apply. A similar plugin for Anthropic is announced as coming soon.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
| Notebooks in Microsoft 365 Copilot | 2026-11-17 | Copilot Workspaces | [Copilot Notebooks is now Copilot Workspaces](https://support.microsoft.com/en-us/microsoft-365-copilot/copilot-notebooks-to-copilot-workspaces) |
