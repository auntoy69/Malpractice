# Malpractice — playtest builds

An online multiplayer hospital game of social deduction: the medical staff race to operate on the right patients while
evil players among them try to stop it.

## Download

Get the latest Windows build from **[Releases](../../releases/latest)** (`Malpractice-v0.1.0-alpha-Windows.zip`).

Requirements: Windows 10/11 64-bit, a DirectX 12 graphics card, and **Steam running and signed in**.

## Play with friends

1. Start Steam. The game uses Steam for lobbies, invites and voice chat. It runs under Steam's free test app
   ("Spacewar", App ID 480), so nobody needs to buy anything.
2. Unzip the download anywhere and run `Malpractice.exe`. If Windows SmartScreen warns about an unknown app, choose
   **More info → Run anyway**: the build isn't code-signed.
3. One player picks **CREATE LOBBY**. Everyone else picks **JOIN LOBBY** and joins that lobby, or accepts the host's
   Steam invite.
4. In the lobby, everyone presses the **Ready** button. Then the host pulls the start lever (F).

## The round

- **Medical staff:** the screen in the conference room lists the five patients on today's theatre list. Nine patients wait
  in the Surgery Waiting Bay, so check every name, date of birth and MRN against their wristbands. For each listed patient:
  1. Wheel their bed to the Surgical Suite and park it right next to the operating table.
  2. Transfer them onto the table and remove their clothes.
  3. Drape them with a **Surgical Procedure Pack**.
  4. Scrub in at a scrub sink with a **Theatre Scrubs Package**, then put on the full sterile set: gown, pants,
     hat + mask, and **Sterile Surgical Tools**.
  5. Operate: three minigames run at once, and more surgeons at the table means a faster operation.
  6. Move the patient back onto a bed and wheel them into **Recovery**.

  Nothing tells you an operation is done or that it was the right patient, so tick the list yourselves. Anything unsterile
  touching the draped patient ruins the surgery.
- **Medical staff win** when all five listed patients have been operated on and are in Recovery, or when every evil player
  is down.
- **Evil wins** when every member of the medical staff is down.

**Controls:** WASD move · F interact · E second action at the operating table · LMB use / attack · 1 / 2 hands · G drop ·
Tab inventory · T phone · M mute voice · Esc menu.
**Surgery:** mouse + hold LMB to follow the cut line · W A S D for instrument calls · Space to stabilise · Esc to step away.

## Known issues

This is an early alpha, so expect bugs. Please report anything odd: what happened, roughly when, and how many players
there were.
