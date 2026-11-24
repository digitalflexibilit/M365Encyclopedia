# Power Pages

Last updated: 2026-11-24

## Current features

### Authentication governance controls
- **Status:** Preview
- **Last change:** 2026-11-09, public preview announced
- **More info:** [Use governance controls to manage site authentication](https://learn.microsoft.com/en-us/power-pages/security/external-auth-control)

Admins with the Power Platform Administrator or Dynamics 365 Administrator role can allow or block sign-in options for Power Pages sites in the Power Platform admin center: protocols (OpenID Connect, SAML 2.0, WS-Federation, OAuth 2.0), the Google, Microsoft and Facebook providers, and local authentication. Restrictions can apply to selected sites. Makers then see blocked options greyed out in design studio, and site owners get an email when a control changes.

### Client API
- **Status:** GA
- **Last change:** 2026-11-16, announced in the October/November 2026 Power Platform feature update
- **More info:** [Power Pages Client APIs overview](https://learn.microsoft.com/en-us/power-pages/configure/client-api/)

A JavaScript API ($pages) for pro developers to work with forms, controls, modern lists, user authentication, languages and Dataverse records, files and images on a site. It can call server logic and cloud flows, and send messages or events to Copilot Studio agents with $pages.agent.SendActivity.

### MCP server for Power Pages
- **Status:** Preview
- **Last change:** 2026-01-30 public preview, GA planned December 2026
- **More info:** [MCP Server for Power Pages overview](https://learn.microsoft.com/en-us/power-pages/configure/mcp-overview)

Lets AI agents such as Microsoft 365 Copilot create, read, update and delete Dataverse records through a Power Pages site while respecting web roles and table permissions. Used by makers.

### Non-SPA sites with agentic coding tools
- **Status:** Preview
- **Last change:** 2026-11-06, preview announced
- **More info:** [Create and edit non-SPA Power Pages sites with Agentic Coding tools](https://www.microsoft.com/en-us/power-platform/blog/power-pages/create-and-edit-non-spa-power-pages-sites-with-agentic-coding-tools/)

The Power Pages plugin (version 3.0.0 or later) for GitHub Copilot CLI or Claude Code can now create and edit traditional Power Pages sites built with web templates and Liquid, not only single-page app sites. Makers can add pages and navigation, edit content snippets, web templates, multilingual content and styling, and review a plan before deploying with PAC CLI. The site must use the enhanced data model.

### Power Pages sites in Power Platform inventory
- **Status:** Preview
- **Last change:** 2026-11-19, public preview announced, rolling out gradually across regions
- **More info:** [Power Pages sites in Power Platform inventory (preview)](https://learn.microsoft.com/en-us/power-pages/admin/power-pages-inventory)

Power Pages sites now appear in the tenant-wide inventory in the Power Platform admin center (Manage > Inventory), next to apps, flows, agents and environments. Admins with the Global, Power Platform or Dynamics 365 administrator role can find sites, check owners, and review sites that allow anonymous access or public developer sites. Site data can also be queried through Azure Resource Graph, the Power Platform API or the Power Platform for Admins V2 connector.

### Transfer site ownership
- **Status:** GA
- **Last change:** 2026-11-16, announced in the October/November 2026 Power Platform feature update
- **More info:** [Transfer ownership of a Power Pages site](https://learn.microsoft.com/en-us/power-pages/admin/transfer-ownership)

Admins move the primary owner of a Power Pages site to another member user in the Power Platform admin center, under Manage, Power Pages, site details, Edit. The previous owner can lose access, and the transfer can only be reversed by transferring back. Transfers are logged in Microsoft Purview.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
