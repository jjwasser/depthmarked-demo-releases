# Known issues and pilot limits

**1.0.0-beta.demo.6 · open solo and guest Hunted playtest**

- Use beta.demo.6 for guest Hunted; older solo builds do not have the guest-entry screen. Use `Depthmarked.Game.exe`. Email registration is not required.
- Online is limited to two rooms/eight players. Matches need two or three adventurers and one human Master; there may be no immediate match. Disconnected expedition slots may remain reserved briefly.
- Guest identity is retained per Windows user/device in Credential Manager. Deleting it can lose access/progress; recovery and account linking are not implemented.
- New guests are rate limited. Keep your existing credential and retry resumption later if service/capacity is unavailable. Offline solo remains available.
- The shared bandwidth guard can pause online hosting before the monthly host allowance is exceeded. No permanent online availability is promised.
- Online report submission and the public update feed are not active; use the optional public feedback form.
- The optional updater may report that the update feed is unavailable. Offline play is available without checking updates.
- The game preloads the complete hero roster and first-dungeon package. Initial loading can take time; minimum hardware requirements and loading times across different PCs are being measured in this pilot.
- A failed model or material load blocks dungeon entry and asks you to re-extract/restart. Report the visible message and whether the entire ZIP extracted successfully.
- Only the opening dungeon is included. Completion does not unlock another dungeon or settlement. Full-game saves and accounts do not transfer to this demo.
- A clean-PC human first-dungeon playthrough, save/resume, guardian completion, and replay remain pilot acceptance tasks. Automated checks and native captures have passed on the development machine.
- Movement and reconnect feel still need human playtest feedback. Report your role, any interruption, and whether you could resume the same expedition.

For a blocker, use the [public bug form](https://github.com/jjwasser/depthmarked-demo-releases/issues/new?template=bug-report.yml). For private feedback or no GitHub account, reply to your invitation using the plain-text feedback sheet. Keep personal information and raw diagnostics out of public issues.
