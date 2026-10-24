# Copilot Studio

Last updated: 2026-10-24

## Current features

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

### Per-agent operations analytics
- **Status:** GA
- **Last change:** 2026-06, build 2026.6.3
- **More info:** [Copilot Studio Platform build 2026.6.3](https://learn.microsoft.com/en-us/power-platform/released-versions/copilotstudio/2026.6.3)

Agent operations analytics shows per-agent, over-time metrics, with health reported as error rate. Makers and admins use it to monitor agents.

### Review panel
- **Status:** GA
- **Last change:** 2026-10-07, generally available
- **More info:** [Review agent readiness and status in Microsoft Copilot Studio (GitHub Copilot)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/authoring-agent-status)

The Review panel in the top menu bar lists blocking issues and warnings while a maker builds an agent, such as data policy blocks or missing sign-in. Each issue has an explanation and an action, and shows when an organization policy causes the restriction.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
