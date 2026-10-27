# Wonderland Moonlight

Current client: **0.60.26**, published **October 25, 2026**.

**[Download the full game ZIP](https://github.com/ItzBrandy/Moonlight-Public/releases/download/moonlight-client-v0.60.26/Moonlight-Client.zip)** · **[0.60.26 release notes and assets](https://github.com/ItzBrandy/Moonlight-Public/releases/tag/moonlight-client-v0.60.26)**

## Install, update, and play

1. Download **Moonlight-Client.zip** from the release above and choose **Extract All**.
2. Close all Moonlight game windows before installing updates.
3. Open the extracted game folder and run **Moonlight Patcher.exe**. Let it finish checking for and installing updates.
4. Open **aLogin-English** in the game folder to play. Use the patcher for updates; launch the game with **aLogin-English**.

You can play from the extracted folder. The server connection is already configured.

If an older launcher cannot update, run the [small installer for 0.60.26](https://github.com/ItzBrandy/Moonlight-Public/releases/download/moonlight-client-v0.60.26/Moonlight-Installer.exe) into your existing player folder once, then follow the update and launch steps above.

The release also provides **Moonlight-Setup.exe** as an alternative installation package. The ZIP is the full client download; the separate `.pak` files and JSON manifests are update/package assets, not game launchers. In particular, **moonlight-0.60.26-from-0.60.25.pak** is an incremental update from 0.60.25, not a full installation.

Version 0.60.26 keeps one user-facing patcher and one **aLogin-English** game executable. Required Tools/Update helpers remain included. Older duplicate launchers are moved into a recovery folder, abandoned installer temporary folders are cleaned automatically, and player data and settings are kept.

For download verification, the release includes **Moonlight-Client.zip.sha256** and **SHA256SUMS.txt**. Compare your downloaded file's SHA-256 hash with the corresponding published checksum.

## Create an account

Enter an unused account name beginning with **LD00** and choose a password. Then use **Create Char**. The first character wizard sets a new login password and a separate deletion code; keep both and use the new password on later logins.

## What's new in 0.60.26

- **Battle watching and joining:** Battle bubbles support watching and stopping watching. You can join an ongoing fight when the leader enables **Joining Battle** and fewer than four player seats are occupied. Pets and spectators do not use player seats. Joining actors wait until the next round before acting.
- **Battle fixes:** Joining clients initialize their current-round display, reinforcements first act on the following round, and idle updates no longer overwrite shared-battle HP/SP with older saved values. Grouped monster single-target attacks apply when the group is within 100 SPD.
- **Party tents:** Nearby party members enter the leader's tent together and return to the outdoor position together. Guests cannot change the owner's furniture or storage. Outdoor tent visibility and reclaiming after leaving are restored.
- **Persistent Storage Room:** Deposits, moves, and withdrawals persist. Nonempty storage cannot be packed up.
- **Crafting recovery and attachments:** Fixes cover variable-length requests, original recipe timers, zero-minute recipes, and resuming or collecting saved jobs. Compatible Work Platform attachments, including Stone Knife and Wooden Saw, are supported and their saved records are restored. Placement/pickup feedback is shown, with redundant completion and item-received messages removed.
- **World and quest fixes:** Corrected beach and identified GS cave/Waterfall Grotto battle backgrounds, idle cellar/cask objects, and a one-Star reward for a new successful Pig Nightmare completion. Earlier Mining, Soul Dodge, and Arrow Rain reward/recovery changes remain included; this does not mean every prerequisite quest is complete.
- **Tools and character reset:** Item catalog searches run in the background with cached icons, and pet EXP targets the active battle pet. A confirmed character-reset action returns the character to level 1, clears learned skills, and refunds allocated stat points while retaining inventory and quests, with a recovery backup.

See the [full release notes](https://github.com/ItzBrandy/Moonlight-Public/releases/tag/moonlight-client-v0.60.26) for all changes.

## Known limitations

- Cha Park crystal-ball hand-in and the complete GS quest chain are **not fixed** in this release.
- The permanent E-remote button, missing Korea quest markers, Daniel pose/rebirth clipping, and spacecraft-capsule activation remain unfinished.
- Crafting progress-bar graphics and the latest join-round floating-number correction still need in-game visual confirmation.
- This is a testing release; not all reported bugs are resolved.

## Testing and support

This is a testing server with **100× battle EXP**. Server availability depends on the host keeping the service online. Report bugs to the host.

**[All releases](https://github.com/ItzBrandy/Moonlight-Public/releases)**

This public repository contains player downloads and instructions. Server source, accounts, saves, credentials, and private host configuration are excluded.
