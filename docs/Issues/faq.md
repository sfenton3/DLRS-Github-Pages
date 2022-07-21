---
layout: default
title: FAQ
nav_order: 1
parent: Having Issues?
has_children: false
---

# Frequent Asked Questions

## Why do I need to allow Metadata API in remote site settings?

To **configure** rollups with this tool your user needs a connection and permissions to the **Salesforce Metadata API**. The **Welcome** tab for the tool provides a check for this and help guide through the configuration required. If your org is using **My Domain** you will have a much easier time and no Remote Site setting will be required. Regardless though your user will need the following permissions.

- API Access
- Metadata API Access or Modify All Data
- Author Apex (needed to use Manage Child Triggers button)
- Customize Application (needed to use Manage Rollup Summaries tab to update Custom Metadata)

**Note:** The above are powerful permissions [please review fully before enabling](https://help.salesforce.com/articleView?id=000198725&r=https:%2F%2Fwww.google.com%2F&type=1) - typically these are enabled for Admin users.

**Known Issues**

- Release v2.12 Welcome tab incorrectly stated in some cases the Remote Site was created when it was not
- Starting with v2.13 of the Welcome tab has been fixed and enhanced to improve the setup experience
- Session based IP restrictions can interfere with the tool, see [here](https://github.com/afawcett/declarative-lookup-rollup-summaries#usage-information-and-known-issues).

##
