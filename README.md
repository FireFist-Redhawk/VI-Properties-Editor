# VI Properties Editor

[![Image](https://www.vipm.io/package/redhawk_lib_vi_properties_editor/badge.svg?metric=installs)](https://www.vipm.io/package/redhawk_lib_vi_properties_editor/) [![Image](https://www.vipm.io/package/redhawk_lib_vi_properties_editor/badge.svg?metric=stars)](https://www.vipm.io/package/redhawk_lib_vi_properties_editor/)

VI Properties Editor is a LabVIEW tool that allows the user to mass edit VI properties and documentation by loading a folder, project, library, or class. It began with a simple desire to be able to press <kbd>Ctrl+B</kbd> to add bold tags when editing VI documentation.

![Image](assets/images/vi-properties-editor-main.png)

## Features

- Press <kbd>Ctrl+B</kbd> to add bold tags to VI Description; press <kbd>Ctrl+Shift+B</kbd> to remove nearest tags
- View VI Description formatted so that bold tags become bold text
- View all controls or only controls on the connector pane
- Perform mass replacements on various properties
- Copy a VI's properties to all other VIs with the same name
- Add or edit copyright info for all VIs or one-by-one
- Filter and sort VIs by custom filters that can leverage regular expressions
- Filter on saved data or edited data
- History of last 10 folders selected kept in <b>File &rarr; Recent Folders</b>
- History of last 10 projects/libaries/classes selected kept in <b>File &rarr; Recent Files</b>
- History of last 10 custom filters used kept in <b>View &rarr; Recent Filters</b>
- Optional confirmation dialogs for various high-risk actions

<b>Properties of VIs that can be edited:</b>

- Window Title
- Same as VI name?
- VI Description
- VI Icon
- Help Path
- Help Tag
- Help URL
- Help Type
- Control names (labels)
- Control captions
- Control descriptions
- Control tip strips

## Requirements

- LabVIEW 2020 or newer
- VI Package Manager

## Getting started

- Download and install the latest version of the tool. It can be found by searching for it on VI Package Manager. It can also be found on [vipm.io](https://www.vipm.io/package/redhawk_lib_vi_properties_editor/) and in the [Releases](https://github.com/FireFist-Redhawk/VI-Properties-Editor/releases) section of the repository.
- After being installed, it is integrated into the LabVIEW development environment and can be launched by clicking <b>Tools &rarr; Redhawk &rarr; VI Properties Editor</b> in any LabVIEW window.


## Support

At the time of writing, this project is actively maintained. If you find a bug or have a suggestion for an improvement, [create an issue](https://github.com/FireFist-Redhawk/VI-Properties-Editor/issues) on GitHub.

## Contributing

If you find this tool useful, please consider starring the VIPM package and Github repository to show your support. If you would like to contribute directly, fork the `develop` branch of the repository and open a pull request.
