# Malpractice

*An online multiplayer hospital game of social deduction.*

> **Blackwood Hospital, 06:58.**
>
> Blackwood was a good hospital once. Private, quiet, expensive - the kind of place where the theatre list ran on time and the coffee in the staff room was real.
>
> Then the night porter stopped answering his radio. On the CCTV he steps back out of the lift forty minutes later, smiling, and clocks in for a shift he was never rostered for. Nobody thinks anything of it. Nobody ever does.
>
> They don't break in. They take a face - a colleague's, a friend's, yours - and wear it perfectly: the voice, the handwriting, the way you take your tea, the password you never wrote down. They are not human. They never were. The staff call them **Doppelgangers**, when they dare to call them anything at all.
>
> They don't want money, and they don't want the drugs locked in the medication room. They want every human being gone - and a hospital, where everyone wears the same scrubs and the same mask and the patients can't run, is the perfect place to start.
>
> This morning there are five names on the theatre list. Find your patients, check their wristbands against their records, prepare a suite, scrub in and operate - before the shift turns on you. Keep your phone close, and don't trust every text you get.
>
> Some of the surgeons standing next to you are not who they say they are.

## Download

Get the latest Windows build from **[Releases](../../releases/latest)**: open the release and download the `.zip` from its
Assets list.

Requirements: Windows 10/11 64-bit, a DirectX 12 graphics card, and **Steam running and signed in**.

## Play with friends

1. Start Steam. The game uses Steam for lobbies, invites and voice chat. It runs under Steam's free test app
   ("Spacewar", App ID 480), so nobody needs to buy anything.
2. Unzip the download anywhere and run `Malpractice/Malpractice.exe`. If Windows SmartScreen warns about an unknown app,
   choose **More info → Run anyway**: the build isn't code-signed.
3. One player picks **CREATE LOBBY**. Everyone else picks **JOIN LOBBY** and joins that lobby, or accepts the host's
   Steam invite. Everyone needs the same version.
4. In the lobby, dress up at the wardrobe if you like and choose the specialisation you'd prefer at the personnel terminal
   on the table. Then everyone presses the **Ready** button and the host pulls the start lever (**F**).

## The shift

Everyone starts in the lifts of Blackwood's reception. Most of you are **Humans** - the surgical staff. One or more of you
are **Doppelgangers**, wearing a colleague's face. A reveal tells you which you are and which specialisation you were dealt,
and nobody else knows - voice chat is open-mic, so talk.

**Humans** work through today's theatre list, shown on the big screen in the conference room off reception: five patients,
spread over two surgical wings with eighteen beds. The Surgical Suites Manager texts everyone the day's job. For each patient
on the list:

1. Find them on the wards and check their wristband against the patient record: name, date of birth and MRN.
2. Prepare a Surgical Suite: unlock it with that wing's **Surgical Suite key**, load the medication trolley with the five
   medications (the bottles are unlabelled - the lab analyzer tells you what's inside), and run the anaesthetic machine's
   self-check (its password is on a sticker note somewhere in the building).
3. Wheel the patient's bed next to the operating table, move them onto it, take their clothes off and drape them with a
   **Surgical Procedure Pack**.
4. Scrub in at a scrub sink with a **Theatre Scrubs Package**, then put on the full sterile set: gown, pants, hat + mask and
   **Sterile Surgical Tools**.
5. Operate: three minigames run at once, and up to three surgeons can share the work.
6. Move the patient back onto a bed and wheel them into **Recovery**.

Nothing tells you an operation was on the right patient, so keep your own list - and anything unsterile touching the draped
patient ruins the surgery. Keys, keycards (Laboratory, Medication Room, Weaponry), medications and the odd weapon are hidden in
furniture and crates: search them with **F**. Anyone who goes down can be revived with a full **First Aid Package**.

**Doppelgangers** look like everyone else. Their phone's **Aura** app shows the staff through walls, and where the useful
things are hidden, and **The Hive** texts them too. Their job: put every human on the floor before the list is finished.

- **Humans win** when all five listed patients have been operated on and are resting in Recovery, or when every
  Doppelganger is down.
- **Doppelgangers win** when every human is down.

The hospital goes dark at night, and it stays dark until morning: keep your phone's torch handy.

## Specialisations

Every player is dealt a specialisation when the shift starts, and either side can get any of them: a Human can be The Bomb,
a Doppelganger can be the Loot Goblin.

The personnel terminal on the lobby table is for your **preference**. You have a **50% chance** of getting the one you chose,
otherwise you get one of the others. If several players draw the same one, it goes to one of them at random.

| | Specialisation | What it does |
|---|---|---|
| S-01 | **Loot Goblin** | No ability: 8 item slots instead of 2, on keys 1 to 8. |
| S-02 | **Friendly Colleague** | Face a downed player and press **1**: they are up at once, with full HP. 2 minute cooldown. |
| S-03 | **The Bomb** | Press **1** to arm a bomb: the next thing you use gets it, and only you can see it. The next person to use it is blown off their feet and downed. 120 s cooldown. |
| S-04 | **The Ghost** | Press **1** to go completely invisible for 30 s, along with everything you hold or wear; only what you drop or leave stuck in somebody stays in sight. Your footsteps are 20% louder meanwhile. Press again to reappear. 120 s cooldown. |
| S-05 | **Night Hunter** | Only while the hospital is dark: press **1** for 300% movement speed, 300% stamina and 300% stamina regen, until the lights come back on. |

## Controls

WASD move · Shift sprint · C crouch · Space jump · F interact · E second action · LMB use / attack · 1 specialisation ability ·
2 / 3 hands · G drop · Tab inventory · T phone · Y phone torch · M mute voice · Esc menu. Every key can be changed in
**Settings › Controls**.

**Phone:** mouse wheel select · LMB open / confirm · RMB back · N notification sound on / off.
**Surgery:** mouse + hold LMB to follow the cut line · W A S D for instrument calls · Space to stabilise · Esc to step away.

## Known issues

This is an early alpha, so expect bugs. Please report anything odd in [Issues](../../issues): what happened, roughly when, and
how many players there were.
