## Features

- Blocks certain item actions for players lacking permission
- Useful for preventing item spam from crushing skulls or gutting fish

## Permissions

- `blockitemactions.bypassall` -- Allows the player to bypass all item action restrictions.

## Configuration

Default configuration:

```json
{
  "BlockedItemActions": [
    "crush",
    "gut"
  ]
}
```

- `BlockedItemActions` -- List of item actions to block. No players will be able to perform these item actions, unless they have the `blockitemactions.bypassall` permission.
