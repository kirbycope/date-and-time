![Preview](addons/date_and_time/assets/date-and-time.png)

# Date and Time for Godot 4.8+

An in-game clock and calendar with a HUD display, and a day cycle other addons can follow.

**[Read the full documentation](addons/date_and_time/README.md)**, which ships with the addon so it is
there however you installed it.

## This repository

It uses the layout the [Godot Asset Library](https://docs.godotengine.org/en/stable/community/asset_library/submitting_to_assetlib.html) expects, so it is both the addon and a
project you can open and edit it in:

```
project.godot          the demo project, which is this repository
addons/date_and_time/  the addon itself
addons/gut/            the test runner
```

Clone it, open `project.godot` in Godot, and run the demo scene. The addon is mounted at
`res://addons/date_and_time/` exactly as it is in a game, so it is edited in place with nothing copied
anywhere first. Installing through the Asset Library takes `addons/` and skips the root
`project.godot` as a conflict, which is why that file can live here harmlessly.

## Installing it in a game

Copy `addons/date_and_time/` into your project's `addons/`. See the
[addon's README](addons/date_and_time/README.md) for what it needs and how to use it.
