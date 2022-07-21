---
layout: default
title: Installation
nav_order: 2
has_children: false
---

# How to Install DLRS - Page 1

1. Installation instructions
2. Uninstall instructions

# Uninstalling the package - Page 2

Triggers installed by DLRS can be removed by navigating to the Manage Lookup Rollup Summaries tab in the App. There is a Manage Child Trigger button on that page. If you click it, on the bottom of the screen is a "Remove" button that will remove the generated code from the org. This is generally limited to the Child Object associated with the DLRS configuration.

If you already deleted the DLRS configuration, it is usually enough to create another one with minimal fields configured as long as it is on the same child object. From there you can use Manage Child Trigger to ask DLRS to clear out the Apex for you.

If none of that works for whatever reason then you have to build a destructivechanges.xml deployment. Or using VSCode IDE or Setup > Apex Classes and Apex Tiggers UI to delete manually.
