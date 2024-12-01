---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /conversion-tools/vrcfury-to-cvrfury-prefab
parent: Conversion Tools
title: VRCFury to CVRFury Prefab
nav_order: 3
---

## VRCFury to CVRFury Prefab Converter

This tool converts VRCFury to CVRFury prefabs.

<div align="left">
  <img
    src="/assets/images/conversion-tools/vrcfury-to-cvrfury.png"
    alt="image of a DSU component with its import section active"
  >
</div>

Before you run the prefab though this converter you should put it thorough the
[VRC Component Handler](/conversion-tools/vrc-component-handler) converter first if it has any VRC components on it
(eg. PhysBone)

Once the output prefab is created, you can then drag it into your project and un-pack it.

<div align="left">
  <img
    src="/assets/images/conversion-tools/unpack-prefab.png"
    alt="image of a DSU component with its import section active"
  >
</div>
At this point you can choose what features you wish to import, (note not all VRCFury features can be imported
see [Feature Support](/feature-support) for an up-to-date list)

If you want to import a `FullController` feature then you must make sure to run the related Menu and Parameter files
though the [converters](/conversion-tools/vrc-menu-and-param) first.
