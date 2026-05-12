# Less Map Markers
Less Map Markers is an EU5 workshop mod that reduces map-marker clutter by hiding most non-player country markers while keeping the player's own markers visible.

`README.md` is the repo-facing description for GitHub.
`STEAM_PAGE.bbcode` is the Steam Workshop description source.
`changenotes/0.1.0.bbcode` is the versioned Workshop changenote for `0.1.0`.

## Behavior

The mod filters major map-marker setting categories through the in-game GUI layer:

- City markers
- Market markers
- Raw goods markers
- Import/export markers
- Blocked vision markers
- Building, army, navy, and conquistador construction markers
- Fort and toll markers

These markers remain visible when they belong to the player's country and are hidden when they belong to other countries.

The mod avoids gameplay script changes and does not alter unit, combat, siege, or cabinet-action logic.
