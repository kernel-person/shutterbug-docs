# Permissions

![ShutterBug admin permission groups](images/permissions-admin-groups.png)

Use these nodes with your permissions plugin. Defaults are defined by the plugin.

| Permission | Default | Purpose |
| --- | --- | --- |
| `shutterbug.sb` | `true` | Base permission for the `/sb` command. |
| `shutterbug.use` | `true` | Allows normal camera use, including taking photos, settings, and albums where enabled. |
| `shutterbug.give` | `op` | Allows `/sb give` and staff-oriented admin/testing tools gated behind the give permission. |
| `shutterbug.reload` | `op` | Allows `/sb reload`. |
| `shutterbug.cinematic` | `op` | Allows cinematic/HQ render profile commands. |
| `shutterbug.photo.give` | `op` | Allows `/sb photo give <player> <image-url>`. |

## Help And Tab Completion

Normal `/sb help` and tab completion hide commands the sender cannot use. This keeps regular player help concise and lets admins safely expose staff commands only to the groups that need them.

## Suggested Groups

| Group | Suggested Nodes |
| --- | --- |
| Player | `shutterbug.sb`, `shutterbug.use` |
| Photographer | Player nodes plus `shutterbug.cinematic` if your server wants advanced render profiles available to trusted players. |
| Moderator | Photographer nodes plus selected staff permissions such as `shutterbug.give` only if moderators should distribute cameras or use testing tools. |
| Admin | All ShutterBug permissions. |

Review staff permissions carefully. `/sb photo give <player> <image-url>` can import external images onto maps and should be limited to trusted admins.

![ShutterBug URL photo map import](images/photo-import-url-map.png)
