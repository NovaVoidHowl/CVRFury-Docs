---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /conversion-tools/vrc-component-handler
parent: Conversion Tools
title: VRC Component Handler
nav_order: 1
---

## VRC Component Handler

This converter takes a prefab as input and outputs a new prefab with the following conversions done:

- Physbone -> Physbone stub
- PhysboneColliders -> PhysboneColliders stub
- VRC Constraints -> Unity Constraints
- Contact Senders -> CVR pointers
- Contact Receivers -> CVR Triggers

{: .warning-no-title }

> Notes:
>
> - The Physbone stubs only allow you to look at the values saved in the component, they don't
>   implement any physics for your avatar.
> - VRC Contacts conversions only apply to prefabs not animations. This should not be an issue as it looks like VRC do not
>   permit animating the values of a contact at runtime ref [3rdparty extended docs](https://vrc.school/docs/Avatars/Contacts/#204b815eb3ba49c7af6c32aef243e484)

### CVR Triggers

Variables triggered by triggers must currently be set as global (this can be done via use of the Component Dev Mode
Enabler component), in the following example `Left/Right Foot Stepped` are used to trigger a particle effect when the
foot touches the ground

<div align="left">
  <img
    src="/assets/images/conversion-tools/Triggers-Global-Only.png"
    alt="image of a DSU component with its import section active"
  >
</div>
