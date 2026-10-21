# M365 Encyclopedia: maintenance rules

This repository is maintained by a daily Claude Code routine. It has two goals:

1. A daily digest of Microsoft 365, Microsoft 365 Copilot and Power Platform news, without repeating earlier news.
2. A register per app that always shows the current state of features, with an explanation and an official Microsoft link for each feature.

Follow these rules exactly on every run.

## Repository structure

- `README.md`: index of all register files with feature counts and last update date.
- `register/<app>.md`: one file per app area (see the list below). This is the encyclopedia.
- `digests/YYYY-MM-DD.md`: one digest per run. Together these are the memory of earlier runs.

## App areas and register files

| File | Covers |
|---|---|
| `register/copilot.md` | Microsoft 365 Copilot, Copilot Chat, agents in Microsoft 365 |
| `register/copilot-studio.md` | Copilot Studio |
| `register/teams.md` | Microsoft Teams |
| `register/outlook.md` | Outlook |
| `register/word.md` | Word |
| `register/excel.md` | Excel |
| `register/powerpoint.md` | PowerPoint |
| `register/onenote.md` | OneNote |
| `register/sharepoint.md` | SharePoint |
| `register/onedrive.md` | OneDrive |
| `register/loop.md` | Loop |
| `register/planner.md` | Planner |
| `register/other-m365.md` | Other Microsoft 365 apps (Forms, Bookings, Viva, Whiteboard, Clipchamp and similar) |
| `register/power-apps.md` | Power Apps |
| `register/power-automate.md` | Power Automate |
| `register/power-bi.md` | Power BI |
| `register/power-pages.md` | Power Pages |
| `register/dataverse.md` | Dataverse |
| `register/ai-builder.md` | AI Builder |
| `register/admin-governance.md` | Admin, security, compliance and licensing for Microsoft 365 and Power Platform (admin centers, Managed Environments, DLP, Purview, Copilot controls) |

A Copilot feature inside a specific app (for example Copilot in Excel) goes in that app's file, not in `copilot.md`.

## Sources

Search broadly, but every feature in the register and every item in a digest must link to an official Microsoft source. Allowed domains:

- learn.microsoft.com
- support.microsoft.com
- microsoft.com (including the Microsoft 365 Roadmap)
- techcommunity.microsoft.com
- powerplatform.microsoft.com, powerapps.microsoft.com, powerautomate.microsoft.com, powerbi.microsoft.com, powerpages.microsoft.com
- devblogs.microsoft.com
- adoption.microsoft.com

Choose the link in this order of preference:

1. The Microsoft Learn or Microsoft Support documentation page for the feature (most durable).
2. The Microsoft 365 Roadmap item or Power Platform release plan page.
3. The official Microsoft announcement blog post.

Never link to third-party blogs or news sites. If you find news on a third-party site, look up the official Microsoft source. If there is none, leave the item out.

Open every link before using it, to confirm it works and is about this feature.

## Register file format

Each register file looks like this:

```
# <App name>

Last updated: YYYY-MM-DD

## Current features

### <Feature name>
- **Status:** Roadmap | Preview | Rolling out | GA | Retiring
- **Last change:** YYYY-MM-DD, <what changed>
- **More info:** [<page title>](<official Microsoft URL>)

<What it does, in 2 to 4 sentences of plain language: what problem it solves, who uses it (end user, maker or admin), how you use it, and the license needed if relevant. If it replaces another feature, end with "Replaces <old name>.">

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
```

## Register rules

- One entry per feature. Before adding, search all register files for an existing entry, including under old or alternative names.
- New feature: add an entry under "Current features". Keep entries sorted alphabetically.
- Change to a known feature (status, date, scope, licensing, name): update the existing entry in place. Never create a duplicate.
- A feature that replaces, renames or absorbs an older one: the new entry ends with "Replaces <old name>.", and the old entry is removed from "Current features" and added as a row to the "Retired / replaced" table with the date and the successor.
- A retired feature: remove it from "Current features" and add it to the "Retired / replaced" table.
- Update "Last updated" in every file you change.
- After changes, update `README.md`: feature count and last update date per file.

## Digest format

File `digests/YYYY-MM-DD.md`:

```
# Digest YYYY-MM-DD

## Copilot
- **<Feature>** (<product>, <status>): <one or two sentences on what changed>. [More info](<official URL>)

## <Other app area>
- ...
```

- Copilot items first (Microsoft 365 Copilot, Copilot Studio, Copilot in apps), then the other app areas.
- Mark updates to earlier reported items with "Update:" and say what changed.
- If there is no notable news: one line, "No notable updates since the last digest."

## Writing style

- English.
- Plain, factual language. No marketing language.
- Never use the em dash character. Use a comma, colon or new sentence instead.
