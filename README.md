<!-- References -->
[repo]: https://github.com/csqrl/roblox-plugin-importer
[repo/actions]: https://github.com/csqrl/roblox-plugin-importer/actions
[repo/license]: /LICENSE
[releases/latest]: https://github.com/csqrl/roblox-plugin-importer/releases/latest
[releases/library]: https://www.roblox.com/library/336673829
[forum/thread]: https://devforum.roblox.com/t/292069
[forum/dm]: https://devforum.roblox.com/new-message?username=csqrl

[package/rojo]: https://rojo.space

[images/cover]: https://doy2mn9upadnk.cloudfront.net/uploads/default/f6cad402b72c666d8af255a8594c7d00d2ec4de2
[images/ci-status]: https://github.com/csqrl/roblox-plugin-importer/actions/workflows/ci.yml/badge.svg
[images/latest-release]: https://img.shields.io/github/v/release/csqrl/roblox-plugin-importer?label=version
[images/license]: https://img.shields.io/github/license/csqrl/roblox-plugin-importer

<!-- Content -->
# Plugin Importer
[![# Plugin Importer][images/cover]][forum/thread]
[![CI Status][images/ci-status]][repo/actions] [![Latest Release][images/latest-release]][releases/latest] [![License][images/license]][repo/license]

Plugin Importer is a handy tool for developers <font color="grey">(and the curious!)</font> to qucikly and easily download and import the source code of any free or purchased plugins directly into Studio.

# Installation
* [Download from the Roblox website/toolbox][releases/library] **(Recommended)**
* [Download a copy from the Releases tab][releases/latest]
* [Sync into your game with Rojo][package/rojo]
* ~~Import with Plugin Importer~~

# Features
* Import plugins using their asset ID *or* library page URL
* Quick access to the last 100 imported plugins via the "Recent" tab
* Import directly from your own personal catalogue of published plugins (requires HTTP permissions) via the "Creations" tab

# Usage
1. Copy and paste a plugin ID or URL from the website; e.g.
    * `https://www.roblox.com/library/336673829/Plugin-Importer`
    * `336673829`
2. Paste it into the textbox on the "Recent" tab, and hit <kbd>Enter</kbd>.
3. The plugin will be automatically inserted to `ServerStorage`, inside a Folder named `"Plugin_"` followed by the plugin's ID, and will be selected in the Explorer window.
