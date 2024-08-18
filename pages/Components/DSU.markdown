---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /components/dsu
parent: Components
title: DSU
nav_order: 1
---

## DSU (Data Storage Unit)

{: .warning-no-title }

> Note there is currently no proper config UI for modules stored in a DSU at this time
>
> You can however use the dev mode UI, this is not intended for general use but is functional.\
> To enable add a `Component Dev Mode Enabler` component to the
> same gameObject as the DSU and tick the 'Dev Mode Enabled' checkbox

This is the core component for each prefab.\
It is intended that you add one (and only one), to the root gameObject of your prefab.

This is also the component that allows you to import compatible modules from converted VRCFury prefabs (a DSU is
automatically added to the root of all converted prefabs)

<div align="left">
  <img src="/assets/images/components/DSU-with-import.PNG" alt="image of a DSU component with its import section active">
</div>
