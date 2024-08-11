---
layout: page
permalink: /feature-support
title: Feature Support
nav_order: 4
---

## Feature Support

### Icon Key

```text
✔️ = Feature active/supported.
⚙️ = Implementation/review in progress
❌ = Feature pending implementation.
🔼 = High priority.
🔽 = Low priority.
❔ = Feature pending review.
🚫 = Feature will not be supported.
```

### Feature list

The following table gives a breakdown of what features are supported for import/install.\
Note at this time there is no native config UI for CVRFury modules yet (save the dev debug interface)

|        Feature         | Data Import Supported | Install Supported | Notes                                                                              |
| :--------------------: | :-------------------: | :---------------: | :--------------------------------------------------------------------------------- |
|   ObjectToggleAction   |         ✔️          |       ✔️        |                                                                                    |
|     MaterialAction     |         ✔️          |       ✔️        |                                                                                    |
|    BlendShapeAction    |         ✔️          |        ❌         |                                                                                    |
|     FxFloatAction      |         ✔️          |       ❌🔽       |                                                                                    |
|  AnimationClipAction   |         ❔🔽         |       ❔🔽       |                                                                                    |
| ShaderInventoryAction  |         ❔🔽         |       ❔🔽       |                                                                                    |
|  PoiyomiUVTileAction   |         ❔🔽         |       ❔🔽       |                                                                                    |
| MaterialPropertyAction |         ❔🔽         |       ❔🔽       |                                                                                    |
|      ScaleAction       |         ✔️          |        ❌         |                                                                                    |
|  BlockBlinkingAction   |         ✔️          |       ✔️        |                                                                                    |
|   BlockVisemesAction   |         ✔️          |       ✔️        |                                                                                    |
| FlipBookBuilderAction  |          ❔           |        ❔         |                                                                                    |
|                        |                       |                   |                                                                                    |
|        Blinking        |          ❔           |        ❔         |                                                                                    |
|       Breathing        |          ❔           |        ❔         |                                                                                    |
|     FullController     |         ✔️          |       ✔️        | Note: no support for menu section triggered toggles (CVR menu is flat, not a tree) |
|         Toggle         |         ❌🔽         |       ❌🔽       |                                                                                    |
|         Puppet         |          ❔           |        ❔         |                                                                                    |
|      SecurityLock      |         ❌🔽         |       ❌🔽       |                                                                                    |
|        Talking         |         ❌🔽         |       ❌🔽       |                                                                                    |
|      Toes Puppet       |         ❌🔽         |       ❌🔽       |                                                                                    |
|    Advanced Visemes    |          ❔           |        ❔         |                                                                                    |
|      ArmatureLink      |         ✔️          |       ✔️        |                                                                                    |
|     BoundingBoxFix     |         ✔️          |       ✔️        |                                                                                    |
|    FixWriteDefaults    |         ✔️          |       ✔️        |                                                                                    |
|   RemoveHandGestures   |         ❌🔽         |       ❌🔽       |                                                                                    |
|   AnchorOverrideFix    |         ✔️          |       ✔️        | fix is automatically applied for meshes missing probeAnchor setting                |
|      MoveMenuItem      |         ❔🔽         |       ❔🔽       |                                                                                    |
|     GestureDriver      |         ❔🔽         |       ❔🔽       |                                                                                    |
|         Gizmo          |         ❌🔽         |       ❌🔽       |                                                                                    |
|   DeleteDuringUpload   |         ✔️          |       ✔️        |                                                                                    |
|     BlendShapeLink     |         ❔🔽         |       ❔🔽       |                                                                                    |
|        SetIcon         |          🚫          |        🚫        | There are no icons on CVR menus                                                    |
|  OverrideMenuSettings  |          🚫          |        🚫        | Related to VRC menu structure only                                                 |
|  BlendshapeOptimizer   |         ❔🔽         |       ❔🔽       |                                                                                    |
|        Slot4Fix        |          ❔           |        ❔         |                                                                                    |
|  DirectTreeOptimizer   |         ❔🔽         |       ❔🔽       |                                                                                    |
|   ShowInFirstPerson    |         ✔️          |       ✔️        |                                                                                    |
|    MmdCompatibility    |         ❔🔽         |       ❔🔽       |                                                                                    |
|    Parameter Stream    |          🚫          |       ✔️        | VRC does not have Parameter stream equivalent                                      |
|  removeLegacyToggles   |          🚫          |       ⚙️        |                                                                                    |
