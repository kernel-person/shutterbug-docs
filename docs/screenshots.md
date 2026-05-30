# Screenshot Checklist

Use this checklist when preparing GitBook, store page, or release screenshots. Capture images on a clean test server with a normal player account where possible, then repeat admin-only screenshots with an admin account.

Do not add placeholder image files to the repository. Add final screenshots under `gitbook/images/` when they are ready.

## Required Screenshots

| Filename | Use On Page | What To Capture |
| --- | --- | --- |
| `images/hero-camera-album.png` | `README.md` | A polished first-view image showing a camera item and album/photo maps together. |
| `images/help-command.png` | `getting-started.md` | `/sb help` output for a normal player, showing only player-available commands. |
| `images/settings-menu.png` | `getting-started.md`, `camera-settings.md` | The `/sb settings` menu with clear mode, size, FOV, exposure, and filter controls. |
| `images/first-photo-map.png` | `getting-started.md` | A player's first completed photo rendered onto a map item. |
| `images/tab-completion.png` | `commands.md` | Tab completion after `/sb`, captured from a player whose suggestions are permission-filtered. |
| `images/profile-comparison-contact-sheet.png` | `camera-settings.md` | The same scene captured with Classic, Normal, and HQ/HQ2/HQ3/HQ4 profiles where permitted. |
| `images/cinematic-mode-comparison.png` | `camera-settings.md` | A comparison of normal and cinematic/HQ output for a visually interesting scene. |
| `images/paper-cost-settings.png` | `camera-settings.md` | A settings or help view that makes paper consumption/cost visible on the test server. |
| `images/album-item-lore-progress.png` | `albums-and-collections.md` | Album item lore showing selected collection and progress. |
| `images/album-collage-map.png` | `albums-and-collections.md` | Album map/collage output after several subjects have been captured. |
| `images/album-cycle-collections.png` | `albums-and-collections.md` | Album state before or after cycling to another collection. |
| `images/config-excerpt.png` | `admin-configuration.md` | A cropped editor view of safe, non-secret `config.yml` settings such as paper consumption and render defaults. |
| `images/collection-definition-example.png` | `admin-configuration.md` | A cropped `collections.yml` example with a clear collection name and a few subjects. |
| `images/reload-confirmation.png` | `admin-configuration.md` | Successful `/sb reload` confirmation in chat. |
| `images/permissions-admin-groups.png` | `permissions.md` | Permission plugin group setup or a clean permissions table from your admin tooling. |
| `images/photo-import-url-map.png` | `permissions.md` | Admin-created URL photo map from `/sb photo give <player> <image-url>`, using an image you have rights to use. |

## Capture Notes

- Use `{GITBOOK_URL}` in any staged help text until the real public GitBook URL is available.
- Capture normal player help separately from admin help so permission-aware behavior is obvious.
- Avoid showing private server IPs, license keys, database credentials, or player information.
- Use the same texture pack, shader, and UI scale across screenshots where possible.
- Prefer readable chat and inventory screenshots over dramatic angles when documenting commands or settings.
