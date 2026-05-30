# Getting Started

![Player crafting a ShutterBug camera](images/crafting-recipe.png)

Start with a camera. On most servers, players either craft it, receive it from a kit or shop, or get one from staff during events. If crafting is enabled, the default recipe is:

| Row | Items |
| --- | --- |
| Top | Glass Pane in the middle slot |
| Middle | Iron Ingot, Redstone, Iron Ingot |
| Bottom | Paper, Paper, Paper |

Admins can change or disable this recipe, so always follow your server's rules if the recipe shown here does not match what you see in-game.

## First Photo

![Player holding the ShutterBug camera](images/holding-camera.png)

1. Craft or receive a camera.
2. Hold the camera in your hand.
3. Run `/sb help` to see the commands available to you.
4. Open `/sb settings` and check the current mode, size, FOV, exposure, and filter.
5. Take a photo with the camera item or with an available `/sb` photo command.
6. Open the finished map item to view the photo.

![ShutterBug help command](images/help-command.png)

`/sb help` is personalized. It only lists commands your account can use on the current server. If cinematic modes, admin tools, photo imports, or reload commands are not granted to you, they should not appear in your normal help output.

## Open Camera Settings

![ShutterBug settings menu](images/settings-menu.png)

Use `/sb settings` before important shots. The settings menu is where you tune how the next photo is rendered. The main controls are:

| Setting | What It Changes |
| --- | --- |
| Mode | Render quality and visual style. |
| Size | How many map tiles the photo uses. |
| FOV | How wide or zoomed-in the camera feels. |
| Exposure | How bright or dark the final photo is. |
| Filter | Optional final color treatment. |

For detailed examples, see [Camera Settings](camera-settings.md).

## Albums

![First ShutterBug photo map](images/first-photo-map.png)

Run `/sb album` to receive an album map when collections are configured. Albums show the selected collection, how many subjects you have captured, and a collage of completed subjects. Left-click and right-click the album to cycle between available collections.

## If Something Looks Different

Servers can customize recipes, permissions, paper costs, render defaults, and collections. When this guide and your server disagree, trust the in-game `/sb help`, `/sb settings`, and your server's admin notes first.

For a longer guide, server owners can set `guide-url` so in-game help points to `{GITBOOK_URL}`.
