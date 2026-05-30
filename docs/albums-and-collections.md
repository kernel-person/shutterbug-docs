# Albums And Collections

![ShutterBug album item lore and progress](images/album-item-lore-progress.png)

Albums give players a map-based way to track configured photo collections. By default, players craft one with a glass pane, paper, and a book and quill in the center column. Some servers also allow `/sb album` as a convenience command.

## Collections

Collections are sets of photo subjects defined by server admins. A collection can ask players to capture specific subjects such as mobs, places, biomes, dimensions, weather, time-of-day scenes, or selfies, depending on how the server has configured it.

When a player captures a matching subject, ShutterBug records progress for that collection. Albums update their display and lore to show the selected collection, progress, and current or available collection state.

## Album Progress

Album item lore can show:

- the selected collection
- progress through the current collection
- a check or cross for each photo subject
- a short description of how to capture each subject
- the current collection position
- available collection state
- controls for moving between collections
- a short collection description

![ShutterBug album collage map](images/album-collage-map.png)

## Cycling Collections

Albums can cycle between available collections. If a collection is empty or no collections are configured, ShutterBug should show a user-facing empty state instead of presenting progress that cannot be completed.

![ShutterBug cycling album collections](images/album-cycle-collections.png)

## Admin Notes

Admins define collections in `collections.yml`. Good collections are specific, achievable, and easy for players to understand from album text. After changing collections, use `/sb reload` if available and `/sb album refresh` while holding an album to update its display.

Useful admin commands include `/sb album give [player]`, `/sb album status [player] [collection]`, and `/sb album reset <player> [collection|all]`.
