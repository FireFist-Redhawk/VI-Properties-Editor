---
title: Known issues
nav_order: l0s002
toc: false
---

# Known issues

- When editing a VI description with the **Format Bold Text** option turned on, unexpected results can occur when holding down keys to repeat them or simply when typing too quickly.
- After saving VIs that are members of classes, the owning classes stay in memory in the **NI.LV.Dialog** application instance (the instance where VIs from the Tools menu run).
- When editing a VI icon from the tool, template information cannot be changed. This had to be done to avoid an underlying bug in the LabVIEW Icon API where template information is lost when editing an icon by calling `Launch Icon Editor.vi`.