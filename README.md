# Malpractice

*An online multiplayer hospital game of social deduction - and surgery.*

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
4. In the lobby, dress up at the wardrobe if you like, then everyone presses the **Ready** button and the host pulls the
   start lever (**F**).

## The shift

Everyone starts in the lifts of Blackwood's reception. Most of you are **Humans** - the surgical staff. One or more of you
are **Doppelgangers**, wearing a colleague's face (the current download still calls the two sides the medical staff and the
evil players). Nobody knows who is who - voice chat is open-mic, so talk.

**Humans** work through today's theatre list, shown on the big screen in the conference room off reception: five patients,
spread over two surgical wings with eighteen beds. For each patient on the list:

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
things are hidden. Their job: put every human on the floor before the list is finished.

- **Humans win** when all five listed patients have been operated on and are resting in Recovery, or when every
  Doppelganger is down.
- **Doppelgangers win** when every human is down.

## Controls

WASD move · Shift sprint · C crouch · Space jump · F interact · E second action · LMB use / attack · 1 / 2 hands · G drop ·
Tab inventory · T phone · Y phone torch · M mute voice · Esc menu. Every key can be changed in **Settings › Controls**.

**Phone:** mouse wheel select · LMB open / confirm · RMB back.
**Surgery:** mouse + hold LMB to follow the cut line · W A S D for instrument calls · Space to stabilise · Esc to step away.

## Coming in the next build

*In development - not in the current download yet.*

- **Humans vs Doppelgangers.** The two sides get their names: Blackwood's **Humans**, and the **Doppelgangers** wearing their faces. When the shift starts, a reveal tells you which one you are - over a heartbeat, or through static.
- **Specialisations.** A personnel terminal on the lobby table: pick one specialisation for each side, hero-select style. Whichever side the shift deals you, you play that side's pick. The first specialisations are still being designed.
- **Shift briefing.** The Surgical Suites Manager texts everyone the day's job. The Doppelgangers hear from someone else.
- **Phone.** Notification sound (on/off) or a silent buzz, a HUD notice that only says a message arrived, chats you can scroll back through, and a selection box that stays put.
- **Mouse buttons** in every control hint are drawn as a mouse with that button lit.
- Medication rooms lined with glass medicine cabinets, a new lab analyzer screen, a head-bob slider, steadier first-person gun shots, first aid that fills on its own, more detailed platters of food - and the lifts no longer make that noise.

## Known issues

This is an early alpha, so expect bugs. Please report anything odd in [Issues](../../issues): what happened, roughly when, and
how many players there were.
