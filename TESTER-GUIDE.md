# Open demo tester guide

**Build: 1.0.0-beta.demo.6 · Windows x64 · solo and guest Hunted pilot**

Thank you for trying Depthmarked: The Hunt Below. Anyone can join this limited playtest; an invitation or tester code is not required. If you were given a code, you can include it in feedback. A first session of roughly 20–30 minutes is useful; continue toward the guardian and demo completion if you have time.

## 1. Install a fresh copy

- Use the [Windows demo ZIP](https://github.com/jjwasser/depthmarked-demo-releases/releases/download/v1.0.0-beta.demo.6/Depthmarked-Demo-1.0.0-beta.demo.6-win-x64.zip), about 1.22 GB. Allow about 4 GB free for the ZIP and extracted files.
- Extract the entire archive to a new folder. Do not merge it into a full-game installation or run directly from inside the ZIP.
- Open `Depthmarked.Game.exe`. The runtime is included; developer tools are not required.
- Choose **Solo Demo → New Adventure**. Sign-in and the updater are not needed for this test.

If downloading, extraction, or starting the game is blocked, record the exact message in the bug form. This is useful feedback even if you cannot reach the dungeon.

## 2. Check the hero browser and loading

- Note roughly how long it takes to reach the hero browser. The first loading screen prepares all six heroes.
- Browse all six heroes. Each should display a textured character model without another loading pause when you switch.
- Choose one. **Preparing the dungeon** should show preparation progress and then open the dungeon. Note its approximate duration and any blank screen or stalled progress.
- While preparation is incomplete, confirmation should not skip it. Escape, controller B, or Back to menu can cancel the loading screen.

Loading times depend on your machine. Please report what you observe rather than waiting indefinitely if it appears stuck.

## 3. Play normally

Default keyboard/mouse controls are below; existing profiles may have customized bindings. The on-screen prompts and in-game settings show your current controls.

| Action | Default control |
| --- | --- |
| Move | W / A / S / D |
| Look | Mouse |
| Attack | Left mouse button |
| Defend with your defensive equipment | Right mouse button |
| Sprint | Left Shift |
| Pick up an item | G |
| Inventory / pack | I |
| Quick slots | 1 / 2 / 3 / 4 |
| Settings and save options | Escape |

For a controller, use the left stick to move, right stick to look, right trigger to attack, and left trigger to defend. Follow the displayed button prompts for inventory, items and menus; bindings can be changed in settings.

- Follow the on-screen controls and use the settings/controls help as needed.
- Try movement, looking around, attacking, defending, using a light, and inspecting items.
- Tell us where your objective or next action becomes unclear, which encounters feel tense, and anything that feels unfair or prevents progress.
- If you have time, reach the guardian and demo completion screen, then check that starting another solo adventure works.

## 4. Check save and resume

Use a new save slot if saving is available. Return to the menu and choose **Solo Demo → Resume**. Check that your hero and progress return correctly. Report any missing or unexpected state. Demo saves are separate from full-game saves.

## 5. Send optional feedback

[Pilot feedback form](https://github.com/jjwasser/depthmarked-demo-releases/issues/new?template=pilot-feedback.yml) · [Bug/blocker form](https://github.com/jjwasser/depthmarked-demo-releases/issues/new?template=bug-report.yml)

These GitHub forms require a GitHub account and create public issues under your GitHub username. Include your tester code and build number, not your real name or email. Do not attach raw logs, account details, personal screenshots, or private file paths.

Without a GitHub account, or for a private reply, fill in [PILOT-FEEDBACK.txt](https://github.com/jjwasser/depthmarked-demo-releases/releases/download/v1.0.0-beta.demo.6/PILOT-FEEDBACK.txt) and reply to your invitation.

Please answer:

1. Could you download, launch, and reach the dungeon? Was this your first time playing Depthmarked?
2. Which hero did you choose, and approximately how long were the loading screens?
3. What made you tense, where were you confused, and what stopped you playing?
4. Did save/resume, the guardian, completion, and replay work, where attempted?

## 6. Try guest online Hunted

1. Use version **beta.demo.6**. Choose the online/Hunted option from the adventure menu, then **Play online as guest**. No email or password is required.
2. Try matchmaking, or have one friend create a room and share its code privately. Select adventurer or Dungeon Master; Hunted starts with at least two adventurers and one connected human Master, up to three adventurers plus a Master.
3. Wait for every player's loading stage to finish. The lobby may be waiting for an adventurer or Master. The initial service has two rooms/eight players; arrange a session with friends if no match is available.
4. Adventurers use the displayed movement/combat controls. Masters use the displayed Master panel, permitted creature choices and Scry/Listen tools. Both roles stay in the first dungeon.
5. Report your role, whether guest entry/resumption worked, lobby waiting time, movement/combat feel and any disconnect/reconnect. Keep room codes, guest IDs, secrets and tokens out of public feedback.

Guest access is retained in Windows Credential Manager for this Windows user and device. Removing it may lose online access/progress. Recovery/account linking is not available. If guest creation is throttled, capacity is full, or service is unavailable, choose **Play offline** (F4 / Y). No account is required for solo.

## Pilot availability

The pilot offers offline solo and limited guest online Hunted. Online report submission and the public update feed are not active. Online availability depends on capacity and the shared monthly bandwidth guard. The first dungeon remains playable offline without an expiry date. [Known issues](KNOWN-ISSUES.md) lists the current limits.

Fresh downloads on other Windows PCs are part of this open playtest. Please report installation, loading and first-entry problems even if you cannot continue. Automated checks do not replace those human acceptance results.
