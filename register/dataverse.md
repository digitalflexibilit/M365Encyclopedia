# Dataverse

Last updated: 2026-11-02

## Current features

### Dataverse Ask API
- **Status:** Preview
- **Last change:** 2026-10-31, announced at PPCC 2026
- **More info:** [Dataverse Ask API](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/ask/)

Lets developers define semantic models over Dataverse data and ask natural-language questions through the Web API or the Dataverse connector. It has several modes that trade performance against answer quality.

### Dataverse for Teams environment creation ends
- **Status:** Retiring
- **Last change:** 2026-11-15, creation of new environments ends; suspension 2027-09-15, decommissioning 2027-10-30
- **More info:** [Important changes (deprecations) coming in Power Platform](https://learn.microsoft.com/en-us/power-platform/important-changes-coming)

New Dataverse for Teams environments cannot be created from 15 November 2026. Environments not upgraded to Dataverse are suspended on 15 September 2027 and decommissioned on 30 October 2027. Admins upgrade needed environments to Dataverse, which needs enough capacity and Power Apps, Power Automate or Copilot Studio licenses for users.

### Power Platform dataflows in Dataverse for Teams
- **Status:** Retiring
- **Last change:** 2026-11-02, creation disabled 2026-09-01, refresh stops 2026-12-01, entry points removed from 2027-01-01
- **More info:** [Power Platform dataflows in Microsoft Teams (deprecated)](https://learn.microsoft.com/en-us/power-query/dataflows/dataflows-teams)

The preview dataflows integration with Dataverse for Teams is retiring in phases. New dataflows can no longer be created, refresh of existing dataflows stops on 1 December 2026, and the entry points in Teams and Power Apps are removed from 1 January 2027. Existing dataflows are not deleted. Dataflows in Power BI, Power Automate, Dynamics 365 and Power Apps outside Dataverse for Teams are not affected.

### Restore deleted records
- **Status:** GA
- **Last change:** 2026-10, documented for environments with Keep deleted Dataverse records turned on
- **More info:** [Restore deleted Microsoft Dataverse table records](https://learn.microsoft.com/power-platform/admin/restore-deleted-table-records)

Admins can turn on Keep deleted Dataverse records in an environment and keep deleted rows for 1 to 90 days. Deleted rows can then be restored from the Power Platform admin center or the Environment Settings app. Kept rows count toward storage until removed, and only rows deleted after the setting is on can be restored.

## Retired / replaced

| Feature | Date | Successor | More info |
|---|---|---|---|
