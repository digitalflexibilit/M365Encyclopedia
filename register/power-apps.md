# Power Apps

Last updated: 2026-11-14

## Current features

### AI row summaries in the modern Data Grid control
- **Status:** Preview
- **Last change:** 2026-11-10, public preview announced in the October/November feature update
- **More info:** [Data Grid modern control in canvas apps](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/controls/modern-controls/modern-control-data-grid#ai-row-summaries)

Makers set the ShowAIRowSummary property on a canvas app Data Grid so users can open a short AI summary of a Dataverse row without leaving the grid. The grid reuses the row summary configured on the Dataverse table. An admin must allow "Summary in canvas data grid" for the environment in the Copilot settings of the Power Platform admin center. It is off by default.

### AI-generated descriptions for canvas apps
- **Status:** Retiring
- **Last change:** 2026-11-14, removal after 2026-11-30 announced
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 30 November 2026 the "Create descriptions using AI" option is no longer available for canvas apps in the Publish dialog or the app designer Settings panel. Existing descriptions stay, and makers can still write or edit them by hand.

### AI-generated descriptions for model-driven apps
- **Status:** Retiring
- **Last change:** 2026-11-02, option removed after 2026-11-30
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 30 November 2026 the "Create descriptions using AI" option is no longer available in the Publish dialog or the app designer Settings panel. Existing descriptions stay, and makers can still write them by hand. Makers who want AI help can use the model app-builder skill.

### Attachments modern control in canvas apps
- **Status:** Preview
- **Last change:** 2026-11-11, documented as preview on Microsoft Learn
- **More info:** [Attachments modern control in canvas apps (preview)](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/controls/modern-controls/modern-control-attachments)

Makers add a modern Attachments control to a canvas app so users can add, download and remove files on a record, with a file picker and drag-and-drop on the web. Unlike the classic control it works outside a form, and its output can go straight to Patch for SharePoint or Dataverse attachments or a Dataverse file column. Makers set limits for file count, file size and file types. Modern controls and themes must be turned on in the app.

### Authoring agent in canvas studio
- **Status:** Preview
- **Last change:** 2026-11-10, public preview announced in the October/November feature update
- **More info:** [Build canvas apps with the authoring agent in Power Apps canvas studio (preview)](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/canvas-authoring-agent)

An agent pane in Power Apps Studio builds or edits a canvas app from a plain-language description. The agent shows a plan for approval, then creates screens, controls and Power Fx formulas in the open app. Makers sign in with a GitHub account, and GitHub bills that account for usage. A tenant admin must turn on "Agentic Coauthoring in Power Apps using GitHub". The preview is limited to the United States and English.

### Calendar and card view layouts in model-driven apps
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, preview planned for December 2026 and GA for February 2027
- **More info:** [Microsoft 365 Roadmap item 575294](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=575294)

Makers can show a view as a calendar or as a stack of cards instead of the default grid. They set the layout in the model-driven app designer, and users get a different way to see and work with the records.

### Canvas authoring agent plugin
- **Status:** GA
- **Last change:** 2026-09-01, generally available
- **More info:** [Canvas authoring agent plugin now generally available](https://www.microsoft.com/en-us/power-platform/blog/power-apps/turbocharge-your-canvas-development-with-the-canvas-authoring-agent-plugin-now-generally-available/)

Lets makers and coding agents such as GitHub Copilot or Claude Code coauthor the same canvas app. Agents use an MCP server to create screens, add controls, write Power Fx formulas and validate changes. Power Apps Studio must be open with coauthoring enabled.

### Copresence in Power Apps plans
- **Status:** Retiring
- **Last change:** 2026-11-11, removed after 2026-11-30
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 30 November 2026 plans in Power Apps no longer show which other authors are working on the plan, and multi-author editing is not supported. Makers coordinate so that only one author edits a plan at a time.

### Cross-environment comment import and export
- **Status:** Retiring
- **Last change:** 2026-11-02, dedicated action removed after 2026-12-31
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 31 December 2026 makers can no longer use the dedicated action to import and export comments between environments in the Power Platform component designers, including the model-driven app designer. Comments inside an environment keep working and existing comments are not removed. Microsoft suggests keeping collaboration notes in source-controlled documentation or ALM pipelines.

### Data Grid pagination in canvas apps
- **Status:** Rolling out
- **Last change:** 2026-11-10, announced in the October/November feature update
- **More info:** [Data Grid modern control in canvas apps](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/controls/modern-controls/modern-control-data-grid#pagination)

The modern Data Grid control can load more records as users scroll or show numbered pages with an adjustable page size. Makers set the Pagination and PageSize properties. Pagination is off by default, so existing apps keep their behavior, and it does not bypass delegation limits.

### Dataverse.Unmask function
- **Status:** Preview
- **Last change:** 2026-11-10, preview listed in the October/November feature update
- **More info:** [Dataverse.Unmask function](https://learn.microsoft.com/en-us/power-platform/power-fx/reference/function-dataverse-unmask)

A Power Fx function that requests the unmasked value of one masked (secured) Dataverse column for a single record, on demand. Makers use it in canvas apps so sensitive values stay masked until a user needs them. Dataverse column security and permissions still decide whether the value is returned.

### Generative pages: custom APIs and Application Insights telemetry
- **Status:** Preview
- **Last change:** 2026-11-10, both capabilities in public preview
- **More info:** [Generate a page using natural language with model-driven apps in Power Apps](https://learn.microsoft.com/en-us/power-apps/maker/model-driven-apps/generative-pages)

Generative pages in model-driven apps can call Dataverse custom APIs to run server-side business logic, such as approvals or price calculations, as the signed-in user. When an admin sets up Application Insights data export for the environment, page load performance, errors, data operations and navigation telemetry are exported automatically. Used by makers and admins.

### Modernized Personal settings in model-driven apps
- **Status:** Roadmap
- **Last change:** 2026-11-14, added to the Microsoft 365 Roadmap, planned for December 2026
- **More info:** [Microsoft 365 Roadmap item 579899](https://www.microsoft.com/microsoft-365/roadmap?filters=&searchterms=579899)

The Personal settings page in model-driven apps gets clearer organization, updated navigation and a more consistent design. It is on by default, and users can switch back to the classic page with a button.

### Power Apps Ideas and formula generation in canvas apps
- **Status:** Retiring
- **Last change:** 2026-11-02, removed after 2026-12-11
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 11 December 2026 Power Apps Ideas, "Create a formula" and formula generation from code comments are no longer available in canvas apps. "Explain this formula" and "Explain this selection" are not affected, and existing formulas keep working. Makers write Power Fx directly in the formula bar.

### Record-level copresence in model-driven apps
- **Status:** Retiring
- **Last change:** 2026-11-11, removed after 2026-11-30
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 30 November 2026 users of model-driven apps no longer see who else is working on the same record or open a presence card from that view. Record sharing and user pictures and status in grids and lookups are not affected, and no data migration is needed.

### Rename controls with Copilot
- **Status:** Retiring
- **Last change:** 2026-11-11, removed after 2026-12-11
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

After 11 December 2026 Copilot no longer suggests names for canvas app controls or applies suggested names to several controls at once. Makers rename controls by hand in Tree view, and Power Apps updates references automatically.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
