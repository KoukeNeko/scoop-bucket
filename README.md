# scoop-bucket

A [Scoop](https://scoop.sh) bucket for KoukeNeko's tools.

## Taiga CLI

An independent command-line client for [Taiga](https://taiga.io) — not affiliated with the Taiga project.

```powershell
scoop bucket add koukeneko https://github.com/KoukeNeko/scoop-bucket
scoop install koukeneko/taiga-cli
```

The manifest is `taiga-cli` (Scoop's `extras` bucket already has an unrelated `taiga`, the anime tracker), and the bucket-qualified name avoids that clash. The installed command is `taiga`.

Update with `scoop update taiga-cli`. Uninstall with `scoop uninstall taiga-cli`.

## ShareCodex

Track shared Claude Code and Codex subscription quota — see [ShareCodex](https://github.com/KoukeNeko/ShareCodex).

```powershell
scoop bucket add koukeneko https://github.com/KoukeNeko/scoop-bucket
scoop install koukeneko/sharecodex
```

Update with `scoop update sharecodex`. Uninstall with `scoop uninstall sharecodex`.
