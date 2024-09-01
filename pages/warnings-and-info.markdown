---
layout: page
permalink: /warnings-and-info
title: Warnings and Info
nav_order: 2
---

## ⚠️ Warnings ⚠️

Due to a breaking change in CCK 3.10 only that or later versions of the CCK are now compatible with this software.

### Post VRCFury 1.744.0 / Datastore V3 support

Datastore V3 compatibility added as of CVRFury 0.124.0-experimental

If you imported a prefab into your scene that was made for a version of VRCFury after 1.744.0, you will need to
re-convert its VRCFury prefab and re-add it, as if it was there before it's 'content' datastore will be corrupted

{: .info-no-title }

> <img src="assets/images/icons/info.512x512.png" alt="warning" width="25" height="25"> \
> Import support of V3 datastore items is currently a work in progress, please see the 'Feature list' section of this
> document for more info

### Nested Prefabs

Nested prefabs (a prefab with another prefab inside it), are not supported for import/conversion\
Note attempting conversion of such a prefab may result in missing components depending on how it was constructed

______________________________________________________________________

## Things that are not included

The following are not features of this project, you will need to handle the following conversions by hand,
or find a tool that can do them

- PhysBone to Dynamic Bone conversion
- PhysBone to Magica Cloth (1 or 2) conversion
