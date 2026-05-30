# Screenshot Checklist

Use this checklist when preparing the public wiki, store page, or release screenshots. Capture images on a clean test server with a normal player account where possible, then repeat admin-only screenshots with an admin account.

The repository currently includes placeholder PNGs so the site can build before final screenshots are ready. Replace the matching files in `docs/images/` when you capture the real images.

## Player First Steps

| Filename | Use On Page | What To Capture |
| --- | --- | --- |
| `images/hero-camera-album.png` | `index.md` | A polished first-view image showing a camera item, photo maps, and an album map together. |
| `images/crafting-recipe.png` | `getting-started.md` | The default camera crafting recipe in a crafting table: glass pane, iron, redstone, and paper. |
| `images/holding-camera.png` | `getting-started.md` | A normal player holding the ShutterBug camera before taking a photo. |
| `images/help-command.png` | `getting-started.md` | `/sb help` output for a normal player, showing only player-available commands. |
| `images/settings-menu.png` | `getting-started.md`, `camera-settings.md` | The `/sb settings` menu with clear mode, size, FOV, exposure, and filter controls. |
| `images/first-photo-map.png` | `getting-started.md` | A player's first completed photo rendered onto a map item. |
| `images/tab-completion.png` | `commands.md` | Tab completion after `/sb`, captured from a player whose suggestions are permission-filtered. |

## Camera Settings Comparisons

Use the same scene for each low/high pair so the difference is obvious.

| Filename | Use On Page | What To Capture |
| --- | --- | --- |
| `images/profile-comparison-contact-sheet.png` | `camera-settings.md` | The same scene captured with Classic, Normal, and HQ/HQ2/HQ3/HQ4 profiles where permitted. |
| `images/cinematic-mode-comparison.png` | `camera-settings.md` | A comparison of Normal and cinematic/HQ output for a visually interesting scene. |
| `images/photo-size-comparison.png` | `camera-settings.md` | A labeled sheet showing 1x1, 2x2, 3x3, and 5x2 photo sizes. |
| `images/size-single.png` | `camera-settings.md` | A single-map photo shown in inventory or on a wall. |
| `images/size-large.png` | `camera-settings.md` | A larger multi-map photo displayed in item frames. |
| `images/size-2x2.png` | `camera-settings.md` | The exported 2x2 photo size example. |
| `images/size-3x3.png` | `camera-settings.md` | The exported 3x3 photo size example. |
| `images/size-5x2.png` | `camera-settings.md` | The exported 5x2 photo size example. |
| `images/hq4-size-detail-1x1.png` | `camera-settings.md` | A 1x1 HQ4 photo of the same scene used for the HQ4 size detail comparison. |
| `images/hq4-size-detail-3x3.png` | `camera-settings.md` | A 3x3 HQ4 photo of the same scene used for the HQ4 size detail comparison. |
| `images/fov-comparison.png` | `camera-settings.md` | A labeled sheet showing low, normal, and high FOV. |
| `images/fov-low.png` | `camera-settings.md` | A low-FOV zoomed-in shot of one subject. |
| `images/fov-normal.png` | `camera-settings.md` | A normal-FOV shot of the same location. |
| `images/fov-high.png` | `camera-settings.md` | A high-FOV wide shot of the same location. |
| `images/exposure-comparison.png` | `camera-settings.md` | A labeled sheet showing low, normal, and high exposure. |
| `images/exposure-low.png` | `camera-settings.md` | A bright scene with lower exposure preserving highlights. |
| `images/exposure-high.png` | `camera-settings.md` | A dark scene with higher exposure revealing detail. |
| `images/viewfinder-overlay.png` | `camera-settings.md` | The camera viewfinder while aiming at a clear subject. |
| `images/paper-cost-settings.png` | `camera-settings.md` | A help or settings view that makes paper consumption/cost visible on the test server. |

## Filter Examples

Use the same scene for every filter screenshot.

| Filename | Use On Page | What To Capture |
| --- | --- | --- |
| `images/filter-comparison.png` | `camera-settings.md` | A labeled sheet showing all filter outputs from the same scene. |
| `images/filter-none.png` | `camera-settings.md` | The baseline image with no filter. |
| `images/filter-sepia.png` | `camera-settings.md` | The same image with Sepia enabled. |
| `images/filter-black-white.png` | `camera-settings.md` | The same image with Black & White enabled. |
| `images/filter-inverted.png` | `camera-settings.md` | The same image with Inverted enabled. |
| `images/filter-warm.png` | `camera-settings.md` | The same image with Warm enabled. |
| `images/filter-cool.png` | `camera-settings.md` | The same image with Cool enabled. |
| `images/filter-vintage.png` | `camera-settings.md` | The same image with Vintage enabled. |

## Albums And Admin Pages

| Filename | Use On Page | What To Capture |
| --- | --- | --- |
| `images/album-item-lore-progress.png` | `albums-and-collections.md` | Album item lore showing selected collection and progress. |
| `images/album-collage-map.png` | `albums-and-collections.md` | Album map/collage output after several subjects have been captured. |
| `images/album-cycle-collections.png` | `albums-and-collections.md` | Album state before or after cycling to another collection. |
| `images/config-excerpt.png` | `admin-configuration.md` | A cropped editor view of safe, non-secret `config.yml` settings such as paper consumption and render defaults. |
| `images/collection-definition-example.png` | `admin-configuration.md` | A cropped `collections.yml` example with a clear collection name and a few subjects. |
| `images/reload-confirmation.png` | `admin-configuration.md` | Successful `/sb reload` confirmation in chat. |
| `images/permissions-admin-groups.png` | `permissions.md` | Permission plugin group setup or a clean permissions table from your admin tooling. |
| `images/photo-import-url-map.png` | `permissions.md` | Admin-created URL photo map from `/sb photo give <player> <image-url>`, using an image you have rights to use. |

## Capture Notes

- Use `{GITBOOK_URL}` in staged help text until the real public docs URL is configured.
- Capture normal player help separately from admin help so permission-aware behavior is obvious.
- Avoid showing private server IPs, license keys, private coordinates, or player information.
- Use the same texture pack, shader, and UI scale across comparison screenshots.
- Prefer readable chat and inventory screenshots over dramatic angles when documenting commands or settings.
- Keep originals somewhere outside the repo so screenshots can be recropped later if needed.
