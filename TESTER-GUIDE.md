# Open demo tester guide

**Build: 1.0.0-beta.demo.5 · Windows x64 · solo pilot**

Thank you for trying Depthmarked: The Hunt Below. Anyone can join this solo playtest; an invitation or tester code is not required. If you were given a code, you can include it in feedback. A first session of roughly 20–30 minutes is useful; continue toward the guardian and demo completion if you have time.

## 1. Install a fresh copy

- Use the [Windows demo ZIP](https://github.com/jjwasser/depthmarked-demo-releases/releases/download/v1.0.0-beta.demo.5/Depthmarked-Demo-1.0.0-beta.demo.5-win-x64.zip), about 1.22 GB. Allow about 4 GB free for the ZIP and extracted files.
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

- Follow the on-screen controls and use the settings/controls help as needed.
- Try movement, looking around, attacking, defending, using a light, and inspecting items.
- Tell us where your objective or next action becomes unclear, which encounters feel tense, and anything that feels unfair or prevents progress.
- If you have time, reach the guardian and demo completion screen, then check that starting another solo adventure works.

## 4. Check save and resume

Use a new save slot if saving is available. Return to the menu and choose **Solo Demo → Resume**. Check that your hero and progress return correctly. Report any missing or unexpected state. Demo saves are separate from full-game saves.

## 5. Send optional feedback

[Pilot feedback form](https://github.com/jjwasser/depthmarked-demo-releases/issues/new?template=pilot-feedback.yml) · [Bug/blocker form](https://github.com/jjwasser/depthmarked-demo-releases/issues/new?template=bug-report.yml)

These GitHub forms require a GitHub account and create public issues under your GitHub username. Include your tester code and build number, not your real name or email. Do not attach raw logs, account details, personal screenshots, or private file paths.

Without a GitHub account, or for a private reply, fill in [PILOT-FEEDBACK.txt](https://github.com/jjwasser/depthmarked-demo-releases/releases/download/v1.0.0-beta.demo.5/PILOT-FEEDBACK.txt) and reply to your invitation.

Please answer:

1. Could you download, launch, and reach the dungeon? Was this your first time playing Depthmarked?
2. Which hero did you choose, and approximately how long were the loading screens?
3. What made you tense, where were you confused, and what stopped you playing?
4. Did save/resume, the guardian, completion, and replay work, where attempted?

## Pilot availability

This is the **offline solo** pilot. Online Hunted, registration, online report submission, and the public update feed are not active. The first dungeon remains playable offline without an expiry date. [Known issues](KNOWN-ISSUES.md) lists the current limits.

Fresh downloads on other Windows PCs are part of this open playtest. Please report installation, loading and first-entry problems even if you cannot continue. Automated checks do not replace those human acceptance results.
