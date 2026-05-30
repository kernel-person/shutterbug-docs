# Commands

![Permission-aware ShutterBug tab completion](images/tab-completion.png)

Use `/sb` for ShutterBug commands. `/shutterbug` is an alias for the same command.

Command visibility is permission-aware. `/sb help` only lists commands the sender can use, and tab completion follows the same filtered list. Admins can use this to keep the player command surface simple while still exposing staff tools to trusted roles.

## Player Commands

These commands are intended for normal camera use. Exact visibility depends on server permissions and enabled state.

| Command | Purpose |
| --- | --- |
| `/sb help` | Show the personalized ShutterBug help menu. |
| `/sb settings` | Open the camera settings menu. |
| `/sb album` | Receive or open an album map for configured collections. |
| `/sb classic` | Take a Classic render when available. |
| `/sb normal` | Take a normal camera shot when available. |
| `/sb exposure:<amount>` | Apply exposure to the current shot when available. |

Some builds also expose direct custom FOV use. Use `/sb help` on your server for the exact list available to your player.

## Cinematic And HQ Shortcuts

Cinematic shortcuts require both `shutterbug.use` and `shutterbug.cinematic`. These shortcuts are for higher-quality or specialized rendering profiles and may take longer than normal photos.

| Command | Purpose |
| --- | --- |
| `/sb cinematic` or `/sb hq` | Use the first cinematic/HQ profile when available. |
| `/sb hq2` or `/sb ultra` | Use the second cinematic/HQ profile when available. |
| `/sb hq3` | Use the third cinematic/HQ profile when available. |
| `/sb hq4` or `/sb extreme` | Use the highest cinematic/HQ profile when available. |
| `/sb classichq` | Use Classic HQ when it is present in the command catalog. |

If a shortcut does not appear in `/sb help` or tab completion, your server has not made it available to your player.

## Admin Commands

| Command | Permission | Purpose |
| --- | --- | --- |
| `/sb give` | `shutterbug.give` | Give a camera through the plugin command where available. |
| `/sb reload` | `shutterbug.reload` | Reload ShutterBug configuration, language, and collection files. |
| `/sb photo give <player> <image-url>` | `shutterbug.photo.give` | Create a photo map from an image URL for a player. |

## Admin And Testing Tools

Some builds expose admin/testing tools for checking render output, particles, camera behavior, albums, and controlled photo environments. These are staff tools, not normal player commands.

Examples that may appear for permitted senders include `debug`, `debug_chest`, `design_album`, `testmob`, `testitem`, `testselfie`, `debugtestselfie`, `debugpitchselfie`, `debug_bed`, `locktime`, `lockweather`, `testsound`, and `testparticle`.

Because these tools are permission-aware and may vary by build, admins should rely on `/sb help` and tab completion in-game to confirm the exact available list.

## Need More Detail?

Server owners can link players to `{GITBOOK_URL}` from the in-game help text or a server guide.
