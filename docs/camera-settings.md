# Camera Settings

![ShutterBug camera settings menu](images/settings-menu.png)

Use `/sb settings` as the main settings surface for camera behavior. Depending on your server version and permissions, the menu can cover render profile, photo size, FOV, exposure, filter, and related capture options.

## Render Profiles

Core render profile shortcuts include:

| Profile | Typical Use |
| --- | --- |
| Classic | Original-style rendering for fast or nostalgic shots. |
| Normal | Balanced everyday photos. |
| Custom FOV | Framing a broader or tighter shot through the FOV setting or supported FOV command use. |
| Exposure | Brightening or darkening a shot with `/sb exposure:<amount>` where available. |

![ShutterBug render profile comparison contact sheet](images/profile-comparison-contact-sheet.png)

## Cinematic And HQ Modes

Players with `shutterbug.cinematic` may also see cinematic or HQ shortcuts such as `classichq`, `cinematic`, `hq`, `hq2`, `ultra`, `hq3`, `hq4`, and `extreme`. These profiles are intended for showcase shots. They may cost more time to render depending on server settings and scene complexity.

![ShutterBug cinematic mode comparison](images/cinematic-mode-comparison.png)

## FOV, Exposure, And Filters

FOV controls how much of the scene fits in the photo. Lower FOV values feel zoomed in; higher values capture more of the scene.

Exposure brightens or darkens a shot. Small adjustments are usually best, especially in scenes with bright sky, lava, torches, or deep shadows.

Filters apply a final style to the photo. The exact filter list depends on the server's current plugin build and settings menu.

## Photo Size And Paper Cost

Some servers allow larger photos made from multiple map tiles. Larger photos can use more storage and may require more paper if paper consumption is enabled.

When `consume-paper` is enabled, ShutterBug can consume paper when photos are taken. The exact cost is controlled by the server configuration, so players should check `/sb help`, `/sb settings`, or server rules for local behavior.

![ShutterBug paper cost setting](images/paper-cost-settings.png)
