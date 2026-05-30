# Commands

![Permission-aware ShutterBug tab completion](images/tab-completion.png)

Use `/sb` for ShutterBug commands. `/shutterbug` is an alias for the same command.

Command visibility is permission-aware. `/sb help` only lists commands the sender can use, and tab completion follows the same filtered list. Admins can use this to keep the player command surface simple while still exposing staff tools to trusted roles.

## Player Commands

These commands are intended for normal camera use. Exact visibility depends on server permissions and enabled state.

| Command | Purpose |
| --- | --- |
| `/sb` | Show a short starter card for crafting, shooting, albums, wiki, and help. |
| `/sb help` | Show the personalized ShutterBug help menu. |
| `/sb wiki` | Show the public guide link configured by the server. |
| `/sb settings` | Open the camera settings menu. |
| `/sb album` | Receive or open an album map for configured collections. |

Photos are taken with the camera item, not a command. Left-click shows the viewfinder, right-click opens camera settings, sneak and right-click takes a photo, and sneak and left-click takes a selfie. Use `/sb settings` to change FOV, exposure, filters, render quality, and photo size before shooting.

## Admin Commands

| Command | Permission | Purpose |
| --- | --- | --- |
| `/sb give` | `shutterbug.give` | Give a camera through the plugin command where available. |
| `/sb album give [player]` | `shutterbug.give` | Give a Photo Album to yourself or another online player. |
| `/sb album status [player] [collection]` | `shutterbug.give` | Inspect album progress. |
| `/sb album reset <player> [collection\|all]` | `shutterbug.give` | Reset album progress and saved album thumbnails. |
| `/sb reload` | `shutterbug.reload` | Reload ShutterBug configuration, language, and collection files. |
| `/sb photo give <player> <image-url>` | `shutterbug.photo.give` | Create a photo map from an image URL for a player. |

## Admin And Testing Tools

Some builds expose admin/testing tools for checking render output, particles, camera behavior, albums, and controlled photo environments. These are staff tools, not normal player commands.

Examples that may appear for permitted senders include `debug`, `debug_chest`, `design_album`, `testmob`, `testitem`, `testselfie`, `debugtestselfie`, `debugpitchselfie`, `debug_bed`, `locktime`, `lockweather`, `testsound`, and `testparticle`.

Because these tools are permission-aware and may vary by build, admins should rely on `/sb help` and tab completion in-game to confirm the exact available list.

## Need More Detail?

Server owners can link players to `{GITBOOK_URL}` from the in-game help text or a server guide.
