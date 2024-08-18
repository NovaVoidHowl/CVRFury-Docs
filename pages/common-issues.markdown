---
layout: page
permalink: /common-issues
title: Common Issues
nav_order: 5
---

### ⏳ Long Running Tasks

If you have animations with large numbers of armature bones being animated in them, then expect long run times on the
ArmatureLink module as it will have to re-write them all.
TLDR: If its still showing as processing and you can see disk activity, then it is not hung as it may appear to be,
just let it run, and come back to it in a few minutes

### Custom Base Animator Not Working

If your custom base animator set in the `Advanced Settings` section, is not loading in as expected,

<div align="left">
  <img src="/assets/images/common-issues/aas-base-controller.PNG" alt="aas-base-controller">
</div>

ensure you have pressed the `Create Controller` followed by the `Attach created Override to Avatar` buttons under the
`Advanced Settings` section of your the CVR Avatar Component

<div align="left">
  <img src="/assets/images/common-issues/aas-base-controller-create-attach.PNG" alt="aas-base-controller-create-attach">
</div>

{: .info-no-title }

> <img src="/assets/images/icons/info.512x512.png" alt="warning" width="25" height="25"> \
> It is not recommended to inject a base animator this way as you will have to manually add new features that come
> with updated CCKs to your controller by hand.\
> The best way to add in custom layers is via use of a DSU with a FullController Module
