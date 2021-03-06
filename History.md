# master

# 4.0.1

* Add missing animated-overlay.gif asset and fix image path.

# 4.0.0

* Upgrade to jQuery UI 1.10.0

* No more automatic `//= require jquery`
  ([#30](https://github.com/joliss/jquery-ui-rails/pull/30), original
  discussion at [#17](https://github.com/joliss/jquery-ui-rails/pull/17)).
  This means that you have to add `//= require jquery` to your application.js
  file before you require any of the jQuery UI JavaScript modules.

# 3.0.1

* Fix stylesheet dependencies

# 3.0.0

* Upgrade to jQuery UI 1.9.2
* Switched from storing the map of file dependencies locally to leveraging
  the grunt build system's .json files for determining file dependencies.
  This simplifies the maintenance of this wrapper project, and allows us to
  delete dependencies.js
* Renamed jquery.effects.all to jquery.ui.effect.all, to match the effects files
  renamed in 1.9.2 (see [Renamed all effects files][1])
* Changed license to MIT only instead of MIT or GPL, to match jQuery UI's
  license (see [commit][2])

[1]: http://jqueryui.com/upgrade-guide/1.9/#renamed-all-effects-files
[2]: https://github.com/jquery/jquery-ui/commit/485ca7192ac57d018b8ce4f03e7dec6e694a53b7

# 2.0.2

* Upgrade to jQuery UI 1.8.24

# 2.0.1

* Add draggable and resizable to the dependencies of dialog (#1)

# 2.0.0

* Do not require the main datepicker module from datepicker i18n modules.
  Fixes Heroku precompilation timeouts. If you are using a datepicker i18n
  module, be sure to also require jquery.ui.datepicker. (#9)

# 1.1.1

* Upgrade to jQuery UI 1.8.23

# 1.1.0

* Upgrade to jQuery UI 1.8.22

# 1.0.0

* No change. Bumping version to indicate that jquery-ui-rails is considered
  stable, and that we are following semver.

# 0.5.0

* Upgrade to jQuery UI 1.8.21

# 0.4.1

* Add jquery.effects.all

# 0.4.0

* Upgrade to jQuery UI 1.8.20

# 0.3.0

* Upgrade to jQuery UI 1.8.19

# 0.2.2

* Protect copyright notices against minification with `/*! ... */`

# 0.2.1

* Upgrade to jQuery UI 1.8.18

# 0.2.0

* Upgrade to jQuery UI 1.8.17

# 0.1.0

* Initial release packaging jQuery UI 1.8.16
