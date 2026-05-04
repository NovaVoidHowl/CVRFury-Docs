---
layout: page
permalink: /conversion-tools/vrcfury-to-cvrfury-prefab
parent: Conversion Tools
title: Importing VRCFury Content
nav_order: 1
---

## Importing VRCFury Content

CVRFury now includes native stubs for VRC and VRCFury components. There is no longer a separate prefab
conversion step — you can directly import data from VRCFury prefabs in your scene.

### Before You Import

{: .warning-no-title }

> <img src="../assets/images/icons/warning.512x512.png" alt="warning" width="25" height="25"> \
> **Complete the following steps before clicking any green import buttons on the DSU.**
>
> Some features (e.g. `FullController`) depend on converted CVRFury-format files existing in your project
> before import is triggered. Importing without these in place will fail or produce incomplete results.
>
> 1. **VRC Components** — If the prefab has VRC components (PhysBones, Contacts, etc.), convert them first.\
>    See [VRC Component Handling](/conversion-tools/vrc-component-handler).
> 2. **Expression Parameters** — Convert any VRC parameter files to CVRFury format first.\
>    See [Menu and Parameter Conversion](/conversion-tools/vrc-menu-and-param).
> 3. **Expression Menus** — Convert any VRC menu files to CVRFury format first.\
>    See [Menu and Parameter Conversion](/conversion-tools/vrc-menu-and-param).

### Import Workflow

1. Drag the VRCFury prefab into your Unity scene hierarchy
2. **Unpack the prefab** — right-click it in the hierarchy and choose `Prefab → Unpack Completely`.\
   Adding components to a packed prefab can cause issues and is not supported.
3. With the unpacked GameObject selected, add a `CVRFury DSU` (Data Storage Unit) component to it
4. The DSU will automatically detect any VRCFury data present on the object and list the features found

<div align="left">
  <img
    src="/assets/images/conversion-tools/dsu-import-features.png"
    alt="DSU component showing detected VRCFury features ready for import"
  >
</div>

Green entries are supported and can be imported to the DSU. Click them to do so.\
Grey entries are not currently supported for import — see [Feature Support](/feature-support) for the current list.

{: .info-no-title }

> <img src="../assets/images/icons/info.512x512.png" alt="info" width="25" height="25"> \
> If the prefab contains VRC components (e.g. PhysBones, Contacts), CVRFury will flag these in the Validator.
