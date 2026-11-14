# Copilot Studio

Last updated: 2026-11-14

## Current features

### Agent accounts
- **Status:** Preview
- **Last change:** 2026-11-12, Frontier preview listed in What's new in Copilot Studio for October 2026
- **More info:** [Give your agent an account (Frontier)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/authoring-agent-account)

A maker gives an agent its own Microsoft Entra account, mailbox and presence in Teams and the directory, so people can email, chat with and @mention it like a colleague. The agent keeps one shared memory across everyone it works with. It needs an early release cycle environment, admin activation in the Microsoft 365 admin center and the Power Platform admin center, Frontier enrollment and one Microsoft 365 Frontier for AI Teammates license per agent. Makers need Microsoft 365 E5 with Agent 365 or Microsoft 365 E7.

### Agent management Power Platform API
- **Status:** GA
- **Last change:** 2026-06, build 2026.6.3
- **More info:** [Copilot Studio Platform build 2026.6.3](https://learn.microsoft.com/en-us/power-platform/released-versions/copilotstudio/2026.6.3)

New Power Platform API endpoints let admins and developers create, update, list, get and delete agents and read agent components. Authorization failures now return HTTP 403.

### Apps in Copilot Studio
- **Status:** Preview
- **Last change:** 2026-10-07, public preview
- **More info:** [New and improved: Build apps, extend agents, and transform business processes in Microsoft Copilot Studio](https://www.microsoft.com/en-us/copilot/blog/copilot-studio/new-and-improved-build-apps-extend-agents-and-transform-business-processes-in-microsoft-copilot-studio/)

Makers describe an app in natural language and Copilot Studio generates a draft that they refine in conversation, with access to the underlying code. Apps sit next to workflows and agents so one solution can combine an interface, repeatable steps and an agent. Apps run on Copilot Managed Runtime.

### Claude Fable 5.1 model
- **Status:** GA
- **Last change:** 2026-09-23, available in Copilot Cowork and Copilot Studio
- **More info:** [Introducing the new Copilot with Home, Code and Autopilot](https://blogs.microsoft.com/blog/2026/09/25/introducing-the-new-copilot-with-home-code-and-autopilot/)

Makers can select Anthropic Claude Fable 5.1 as a model for agents in Copilot Studio, next to other frontier models.

### Copilot Studio MCP
- **Status:** GA
- **Last change:** 2026-11-14, listed in the October 2026 Copilot Studio release notes
- **More info:** [Connect to Microsoft Copilot Studio with MCP](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/copilot-studio-mcp)

Copilot Studio MCP brings Copilot Studio tools into MCP-compatible clients such as Visual Studio Code and GitHub Copilot CLI. The client starts the Microsoft-published @microsoft/copilot-studio-mcp npm package, the maker signs in and picks an environment, and can then create, test, deploy and monitor agents and workflows from that tool. Used by makers and developers.

### Customer Conversation harness
- **Status:** Preview
- **Last change:** 2026-11-12, listed in What's new in Copilot Studio for October 2026
- **More info:** [Agents powered by the Customer Conversation harness overview (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/overview-customer-conversation)

Makers build customer-facing agents, called Customer Assist Agents, that answer questions and resolve issues over voice and chat. The harness uses specialized sub-agents, each with its own escalation path to a human representative, for example through Teams Phone, email or a live agent. Agents can be published on a website or given a phone number. Usage is billed in Copilot Credits.

### Foundry IQ knowledge for agents
- **Status:** GA
- **Last change:** 2026-10-07, generally available
- **More info:** [Connect to Foundry IQ from an agent (GitHub Copilot)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/foundry-iq-connect)

Makers connect an agent built with the GitHub Copilot harness to a Foundry IQ knowledge base from Azure AI Foundry, added as a tool. One knowledge base can be reused across agents, answers include citations, and private networking is supported. Each agent can have one Foundry IQ connection.

### GPT-5 Mini fine-tuned model
- **Status:** GA
- **Last change:** 2026-06, enabled by default in build 2026.6.3
- **More info:** [Copilot Studio Platform build 2026.6.3](https://learn.microsoft.com/en-us/power-platform/released-versions/copilotstudio/2026.6.3)

A fine-tuned GPT-5 Mini model is enabled by default and can be selected in the Copilot Studio interface by makers.

### Hooks for agents
- **Status:** Preview
- **Last change:** 2026-10-07, preview for agents using the GitHub Copilot harness
- **More info:** [Hooks (GitHub Copilot) (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/hooks-overview)

A hook runs a workflow every time a lifecycle event fires, such as session start, user prompt, before or after a tool call, or an error. Makers use hooks to add context, block or change a tool call, redact results or log activity. Only the pre tool use event can block an action.

### Knowledge source controls for agents
- **Status:** GA
- **Last change:** 2026-11-12, listed in What's new in Copilot Studio for October 2026
- **More info:** [Choose knowledge sources for agents built in Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/choose-knowledge-sources)

Admins use the Knowledge sources for agents setting in the Power Platform admin center to decide which knowledge sources makers can add: uploaded documents, SharePoint and OneDrive, and public websites, each on its own. Blocking document uploads does not block files from SharePoint or OneDrive. Endpoint filtering can allow or deny specific SharePoint sites or websites.

### MCP and A2A client channels
- **Status:** Preview
- **Last change:** 2026-11-12, listed in What's new in Copilot Studio for October 2026; early release cycle environments only
- **More info:** [Connect clients to your agent with the MCP and A2A channels (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/publication-channels-mcp-agent-to-agent)

A published agent can be exposed as a remote Model Context Protocol (MCP) server or as an Agent2Agent (A2A) agent, so IDEs, tools and other orchestrators can call it. Clients sign in with Microsoft Entra ID on behalf of the user, and Copilot Studio checks that the user has access to the agent. An admin or maker creates an app registration with the Copilot Studio delegated permissions first.

### Per-agent operations analytics
- **Status:** GA
- **Last change:** 2026-06, build 2026.6.3
- **More info:** [Copilot Studio Platform build 2026.6.3](https://learn.microsoft.com/en-us/power-platform/released-versions/copilotstudio/2026.6.3)

Agent operations analytics shows per-agent, over-time metrics, with health reported as error rate. Makers and admins use it to monitor agents.

### Privacy statement link for agents
- **Status:** Preview
- **Last change:** 2026-11-14, listed in the October 2026 Copilot Studio release notes
- **More info:** [Configure a privacy statement link for Microsoft Copilot Studio agents (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/configure-privacy-statement-link)

A Power Platform admin sets a link to the organization's privacy policy per environment, and it is shown at the start of agent conversations. The URL can be set, but the message shown to users cannot be changed. Applies to agents on the standard harness.

### Review panel
- **Status:** GA
- **Last change:** 2026-10-07, generally available
- **More info:** [Review agent readiness and status in Microsoft Copilot Studio (GitHub Copilot)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/authoring-agent-status)

The Review panel in the top menu bar lists blocking issues and warnings while a maker builds an agent, such as data policy blocks or missing sign-in. Each issue has an explanation and an action, and shows when an organization policy causes the restriction.

### Shared skills marketplace
- **Status:** Preview
- **Last change:** 2026-11-14, listed in the October 2026 Copilot Studio release notes
- **More info:** [Manage and delete skills in an agent](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/skills-manage)

Makers can browse and add skills that admins or skill owners shared through the marketplace, and share their own skills with specific people, groups or the whole organization. Recipients are notified when a shared skill is updated and can choose to move to the new version. Applies to agents on the Microsoft Copilot harness.

### Triggers for autonomous agents
- **Status:** Preview
- **Last change:** 2026-11-12, listed in What's new in Copilot Studio for October 2026
- **More info:** [Add triggers to an agent (GitHub Copilot) (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/authoring-add-event-trigger)

Makers add triggers so an agent built on the GitHub Copilot harness runs on its own when an event happens, such as a new SharePoint item, an incoming email or a scheduled time. After publishing, the maker activates the agent for themselves or shares it so others run it with their own credentials and edit only the trigger options the maker allows. Usage is billed in Copilot Credits through the hosting environment.

### Upgrade agents to the Microsoft Copilot harness
- **Status:** Preview
- **Last change:** 2026-11-14, listed in the October 2026 Copilot Studio release notes
- **More info:** [Upgrade agents to the Microsoft Copilot harness (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/upgrade-to-github-copilot-from-standard-harness)

Makers can ask Copilot Studio to move an existing agent from the standard harness to the Microsoft Copilot harness. Instructions, tools and prompts are carried over, topics are rebuilt as skills or workflows, and a migration report shows what came over, what needs attention and what was skipped. Agents on the new harness use usage-based billing in Copilot Credits.

### WhatsApp channel through Azure Communication Services
- **Status:** Retiring
- **Last change:** 2026-11-14, new connections closed since 2026-10-23
- **More info:** [Publish an agent to WhatsApp](https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-add-bot-to-whatsapp)

Publishes a Copilot Studio agent to WhatsApp through Azure Communication Services. Since 23 October 2026 no new WhatsApp connections can be made through this channel, whatever the agent's creation date. Agents connected before that date keep working.

### Work IQ in Copilot Studio
- **Status:** GA
- **Last change:** 2026-11-12, generally available and added by default to new agents on the GitHub Copilot harness; Business apps workload stays in preview
- **More info:** [Work IQ in Microsoft Copilot Studio (GitHub Copilot)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/add-work-iq)

Work IQ grounds an agent in the user's work context from SharePoint, OneDrive, Outlook mail, Teams, Calendar and People, and can take actions. Makers keep or clear whole workloads; write operations are on by default within the organization's permissions and policies. The Business apps workload, with context from Dynamics 365 and Power Apps, is a preview workload that makers turn on in the agent settings. Usage is billed in Copilot Credits.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
