---
title: Known issues
nav_order: l0s002
toc: false
---

# Known issues

- Editing a VI description with the **Format Bold Text** option turned on is very buggy. With the release of version 2.4.0, you should at least be able to use <kbd>Ctrl+B</kbd> and <kbd>Ctrl+Shift+B</kbd> to successfully edit bold tags with the option turned on, but the option should still be used for visualization purposes only.
- When editing a VI icon from the tool, template information cannot be changed. This had to be done to avoid an underlying bug in the LabVIEW Icon API where template information is lost when editing an icon by calling `Launch Icon Editor.vi`.
- The <b>File &rarr; Reload Source</b> functionality only works correctly if the source hierarchy has not changed at all, meaning no items have been added, removed, renamed, or rearranged.
- As of version 2.4.0, many more properties are able to be edited — properties like inlining, reentrancy type, automatic error handling, etc. Importantly, the tool does not currently perform any checks to validate new values of these properties. For example, it is possible to turn off reentrancy on a recursive VI, set different properties for a child method than its parent method, turn on inlining on a VI with automatic error handling enabled, and so on. It is up to the user to be diligent about editing these properties.