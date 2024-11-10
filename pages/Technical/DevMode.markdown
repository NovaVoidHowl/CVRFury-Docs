---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /technical/DevMode
parent: Technical Notes
title: Dev Mode
nav_order: 2
---

## Dev Mode

{: .warning-no-title }

> Note all the following options are volitile and can lead to project corruption and/or optimisation issues.
> Use at your own risk.

The installed app can have development features activated by adding scripting define symbols as follows

- `NVH_CVRFURY_DEV_ENABLED` - enables low level options that should NEVER be used in normal usage of the app see `NVH-> CVRFury -> Debug -> Development` to access/use them
- `NVH_CVRFURY_DEV_PACKAGE_OVERRIDE` - disables protections on `Update Manager`

