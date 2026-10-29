# CELL Changelog

**CELL: The ONLY PS3 Social Media!** Newest release first. The latest version is **1.1.4**.

## CELL 1.1.4 Patch Notes: 6 languages, public bans, owner control and staff phone alerts

### New

- **CELL speaks your language.** CELL now comes in **English, Spanish, Portuguese, French, German and Italian**.
  - It picks your PS3's system language by itself.
  - To change it, go to **Settings → Language** and choose a language or **Auto (PS3 language)**.
  - Menus, buttons, messages and errors from the server are all translated. Dates and times follow your language too (24-hour clock, day before month).
  - Posts, comments and messages people write are never changed.
- **See how big CELL is.** A new card at the top of the Feed shows how many players are on CELL in total.
- **Public bans.** When staff choose to, a ban shows on the player's profile for everyone to see. A red bar across their banner reads **"(name) banned for (time): (reason)"**. A banned player's profile stays visible while the bar is up.
  - While banned, a player always shows as **offline**, and the Follow, Add friend and Message buttons on their profile are greyed out.

### Fixed

- **New post:** in some languages, the "Type" hint ran into the "Emoji" hint. They no longer overlap.

### For staff

- **Phone alerts.** Install the Staff site on your phone (Add to Home Screen) and open the new **Phone alerts** page to get CELL alerts like any other app.
  - **Urgent alerts:**
    - reports and flagged posts, messages and chat
    - @mentions of you
    - ban appeals
    - banned players trying to come back
    - raid warnings (sign-up or post bursts)
    - server problems: a crash restart, low disk space or missed backups
  - **Other alerts:**
    - new players (one each, or a list once an hour)
    - "I donated" claims
    - recovery codes used
    - what other staff do
    - games reported broken on Play Online
  - **Daily summary** at the hour you choose: new and active players, posts, open reports and appeals, staff actions and the top games.
  - **Your settings:**
    - Quiet hours, when only urgent alerts come through.
    - Turn each kind of alert on or off.
    - A **Send a test** button.
    - Every phone keeps its own settings.
  - Moderators and admins only get the alerts their role is allowed to see.
- **Ban dialog:** new **"Show it on their profile"** checkbox, on by default. Write the reason knowing everyone will read it.
- **The owner stays in control.**
  - **Nobody can act on the owner's account.** Admins and moderators can't warn, mute, ban, rename, reset or delete it, remove its posts, take its badges, or read its messages and activity.
  - **Staff can only moderate people below their own rank.** Admins can't moderate other admins, and moderators can't moderate admins. The owner can moderate everyone.
  - **No undoing a higher rank.** An admin can't lift a ban, mute or IP ban that the owner made.
  - **Link staff accounts to their player accounts** on the Staff page. Their PS3 account then gets the same protection, and @mentions of it reach their phone.
  - **Owner-only log.** What the owner does to staff accounts, and the owner's own checks on them, only show in the owner's view of the audit log and never go to Discord.
  - **Freeze a staff member, or freeze all staff at once.** Frozen staff can still look but can't act. **Sign out all staff** ends every staff session except the owner's.
  - **Tripwire:** if a staff member does too many bans, mutes or removals in a short time (15 in 10 minutes by default, and you can change it), they're frozen and signed out on the spot, and the owner gets an alert.
  - **Undo a staff member's actions** over a chosen time window, for example everything they did in the last 2 hours.
  - Deleting accounts is owner-only. IP and console bans never lock out the owner.

## CELL 1.1.3 Patch Notes: 1,384 emoji, account recovery and a new look on the XMB

### New

- **1,384 emoji.** The emoji picker went from 172 to 1,384: every single emoji on a phone keyboard (skin tones and flags aside).
  - Tabs like a phone: **Popular** (the old favourites), Faces, People, Animals, Food, Travel, Activities, Objects and Symbols. L1/R1 switches tabs.
  - Every emoji has a shortcode you can type, like `:pizza:`, `:upside_down_face:` or `:ferris_wheel:`. All the old ones still work.
- **Lost access to your account? Get it back with a recovery code.** On the "Create your username" screen there's a new **I already have an account** option. Ask CELL staff on Discord for a recovery code, type it in, and you're back in with all your posts and friends. That PS3 is then linked to your account, so reinstalling CELL there signs you in by itself again.
- **New XMB look.**
  - The CELL thumbnail has a **transparent background**, so "CELL." stands out on any XMB theme.
  - The picture behind the XMB when CELL is highlighted **changes every time you start CELL**: six different CELL screens.

### For staff (owner only)

- **Account recovery** card on a player's page:
  - **Make a recovery code:** a one-time code (like `ABCD-1234`) to give the player privately. It works once and expires after 24 hours. Tick "sign out every other PS3" if the account may have been taken over.
  - **Copy message** gives you the code plus instructions to paste into a Discord DM.
  - **Cancel code**, and **Unlink their PS3** (for a sold or shared console).
  - Only the owner sees this card. Making, using and cancelling codes, and unlinking, are all in the audit log.
  - Always check it's really the account's owner before giving a code.

---

## CELL 1.1.2 Patch Notes: custom GIFs and easier menus

### New

- **Use your own GIFs as your profile picture.** Put a .gif in **/dev_hdd0/photo** (over FTP) or on a USB drive, then go to Settings → Profile picture → **Your photos**. Your GIFs are listed first and show a real preview.

### Fixed

- **GIFs in the picture picker.** GIFs used to say "Can't open" in the picker. They now show their first frame like any other picture.
- **Play Online game pages are easier to use.** Use **left and right** to move between **It worked**, **It's broken** and **Plan a game night**, and up and down to move within a column. Before, only up and down worked, which wasn't obvious.
- **Settings:** the "APP" heading no longer floats between Blocked players and Colours & background.

### Improved

- The picker now lists up to 500 pictures (was 200), so big photo folders don't hide your newest files.

---

## CELL 1.1.1 Patch Notes: animated profile pictures

### New

- **GIF profile pictures.** Your profile picture can now be an animated GIF. It plays everywhere your picture shows: your profile, the feed, comments, Global Chat, Messages, Friends, Find players and the top bar.
- **Search GIFs for your picture.** Settings → Profile picture → **Search GIFs**, pick one and press ✕ "Set as my picture".
- **Or use your own GIF.** Settings → Profile picture → **Your photos**, then pick a .gif you sent over FTP or put on a USB drive (up to 3 MB). The preview shows a GIF tag so you know it will animate.

### Good to know

- GIFs are cut to a circle from the middle, just like normal pictures.
- Banners stay still pictures.
- To keep things smooth, up to 10 animated pictures play at once on screen. Any others show their first frame.

### For staff

- Animated profile pictures show up on the Staff site like any other picture, and **Remove picture** works the same way.

---

## CELL 1.1.0 Patch Notes: Block players

### New

- **Block players.** Open a profile, press **SELECT → Block**, and confirm.
  - **Hidden both ways:** you won't see each other's posts, comments, wall posts, Global Chat messages or "is typing".
  - **No contact:** neither of you can message, follow, friend, GG, comment on or write on the other's wall.
  - **Links removed:** any friendship, friend request and follows between you are removed, and no notifications go between you.
  - **Out of each other's lists:** they disappear from your Find players and game player lists, and your Messages conversation with them goes away.
  - **They aren't told.** To them, your profile simply can't be found.
- **Blocked players list:** Settings → Blocked players. Press ✕ twice to unblock someone. Unblocking doesn't bring back a friendship or follows.

---

## CELL 1.0.9 Patch Notes: pick your badge

### New

- **Choose your badge.** Got more than one badge? Pick which one shows next to your name: **Settings → Badge next to my name**.
  - Press ✕ to cycle through **Automatic** (your highest badge) and each badge you have. The row shows a preview of your name with that badge.
  - Your pick shows everywhere: the feed, comments, Global Chat, Messages and your profile.
  - Your profile banner still shows all your badges.
- **Console on profiles.** Profiles now show which console a player is on: a **PS3** tag next to Online. CELL fills this in by itself, so there's nothing to set up.

---

## CELL 1.0.8 Patch Notes: typing, Seen and badge icons

### New

- **"Is typing..." in Global Chat.** When someone is writing a message, you'll see it under the chat with bouncing dots: "NateDrake and KaiZ are typing..."
- **Typing in Messages too.** You can see when the person you're talking to is typing.
- **Delivered and Seen.** Your last message in a conversation shows **✓ Delivered**, then **✓✓ Seen** once they've opened it.
  - Message requests stay private: someone who hasn't accepted your request yet only ever shows "Delivered".
- **Three new badges:**
  - **Creator:** for people who make videos, streams or art about CELL or the PS3
  - **Revival Dev:** for members of the groups keeping PS3 games online
  - **Bug Hunter:** for players who reported a real bug that got fixed

### Improved

- **Every badge has an icon now:**
  - 👑 Owner: a crown
  - 🛡️ Admin: a shield
  - $ Donator: a money sign
  - 📣 Promoter: a megaphone
  - ⚗️ Beta-Tester: a lab flask
  - 📺 Creator: a TV
  - ➕ Revival Dev: a medic cross
  - 🐞 Bug Hunter: a beetle
- **The Owner badge is red,** and so is the owner's name.
- **Lots of badges?** When they don't all fit on a profile banner, the most important ones show first.

### For staff

- **Give the new badges** on the Staff site: Badges, or a player's page.
- **The Staff site shows the same badge icons** as the PS3.

---

## CELL 1.0.7 Patch Notes: 90+ games in Play Online

**CELL: The ONLY PS3 Social Media!** Play Online just went from 13 games to 92.

### New: 90+ games in Play Online

Every game has its own page with the DNS steps filled in, "It worked / It's broken" reports, game nights and who on CELL owns it.

- **PS Rewired:** Killzone 2, Killzone 3, MotorStorm, MotorStorm: Pacific Rift, MotorStorm: Apocalypse, Resistance: Fall of Man, **Resistance 2 (back in 2026!)**, NBA 07, Call of Duty: World at War
- **PSONE:** SOCOM Confrontation, Calling All Cars!, Pain, Ratchet: Deadlocked, WipEout HD
- **Warhawk Revived:** Warhawk, **Starhawk**
- **PS Reborn (32 games):** Guitar Hero III, World Tour, 5, Metallica, Aerosmith, Van Halen, Smash Hits and Warriors of Rock, Band Hero, Far Cry 3, Ghost Recon Advanced Warfighter 2 and Future Soldier, Splinter CELL: Double Agent, EndWar, Call of Duty 3, GRID, DiRT, Haze, Singularity, Wolfenstein, Ghostbusters, Stranglehold, Blood Stone, Quantum of Solace, Avatar, BlackSite, Operation Flashpoint: Dragon Rising, The Club, Stuntman: Ignition, Shaun White Skateboarding and Snowboarding, Battle for the Pacific
- **More community servers:** Blur, DJ Hero 1 and 2, five Transformers games, Burnout Paradise, Driver: San Francisco, Ratchet & Clank Collection, Medal of Honor, WWE 2K14, Fuel, Need for Speed: Carbon
- **Groups with their own setup guides:** ModNation Racers Revival, Refresh (LittleBigPlanet), Destination Home (PlayStation Home)
- **In testing (follow them to get a bell when they go live):** MAG, Metal Gear Online 2. Eleven more only work on the PC emulator for now: Battlefield: Bad Company 2, Skate 3, Demon's Souls, Modern Warfare 2, NHL 14 and others.
- **Still on official servers:** GTA IV, Ridge Racer 7, God of War: Ascension, Tekken 6, Sonic & SEGA All-Stars Racing and more

### Improved

- **Search Play Online.** Press SELECT on the Games tab and type a game or a group name ("resistance", "rewired").
- **Bigger list.** Play Online holds up to 200 games now (it was 64).

### Fixed

- **Global Chat:** when you scrolled up, pictures and GIFs hung over the text box. They're cut off cleanly at the edge of the chat now. Messages had the same problem and is fixed too.

### Heads-up

Revival servers are run by fan groups, not Sony. The new entries come from the groups' public lists and say "check steps" until staff confirm them. If a game doesn't connect, tap **It's broken** on its page so everyone knows.

### For staff

- **New games are added automatically, and your edits are kept.** Missing games are added, and games you never edited are updated with their group and DNS. Anything you've changed stays exactly as you left it.
- **Players following a revival get a bell when it goes live.** For example, followers of Resistance 2 are told when the update installs.
- **Confirm steps as you check each game** (Staff site → Play Online → Edit → "steps checked"). Hide anything you don't want listed.

---

## CELL 1.0.6 Patch Notes: Messages

**CELL: The ONLY PS3 Social Media!** now has private messages.

### New: Messages

- **A Messages tab** in the left menu, right under Notifications. A badge shows how many conversations have unread messages, plus any message requests.
- **Send text, emoji, GIFs and pictures**, just like Global Chat. △ opens emoji; □ attaches a GIF or a screenshot.
- **Message anyone, from anywhere:**
  - △ "New message" in the Messages tab (type their username)
  - The new **Message** button on any player's profile
  - △ on your Friends list
  - "Message <name>" in any post's SELECT menu
- **Conversations look like Global Chat.** Their messages are on the left and yours are on the right. Use ↑/↓ to read back and R3 to see a picture full screen.
- **New message alerts.** A pop-up tells you when a message arrives, unless you're already reading that conversation.

### Message requests

- **Friends land straight in your Messages.** Everyone else lands in **Requests** (switch with L1/R1), so you decide who you talk to.
- **□ accepts** a request, or you can just reply. **SELECT declines**, and a declined player can't message you again unless you write to them first.
- **Anti-spam:** until you accept, a stranger can send you at most 3 messages, and nobody can start conversations with more than 10 strangers an hour.
- **□ in Messages deletes a conversation** from your list. A new message brings it back.

### Safety

- **SELECT on any message to report it.** Staff review every report.
- **The Rules & Terms now say** that staff can see private messages to keep everyone safe. Be kind, and never share personal information.

### Fixed

- **If CELL's saved sign-in stops working,** CELL now looks up your account on this PS3 before sending you to sign-up.

### For staff

- **Staff site → Direct messages:**
  - Every conversation, searchable by message text or player.
  - Open any conversation to read it in full; reported messages are outlined in red.
  - Remove or restore single messages.
  - A **Reports** queue for messages players report or the word filter catches: Resolve, Dismiss, or jump to the player to warn, mute or ban.
- **Opening a conversation is recorded in the audit log** ("Read DMs"), so there's a record of who looked at what.
- **If you've customised your Rules,** add a line saying staff can see private messages. Only the default Rules were updated automatically.

---

## CELL 1.0.5 Patch Notes

**CELL: The ONLY PS3 Social Media!** This update rolls up everything from today: faster pictures, full news stories, accounts that survive a reinstall, the official Discord, and a new RGB background.

### New

- **RGB flow background.** Settings → Colours & background, then L1/R1. The background glides slowly through the whole rainbow and across the screen. It stays dark enough to read on, like the other gradients.
- **Join the official Discord.** There's a QR code card at the top of your Feed and a bigger one in Settings → Join the official Discord. Point your phone's camera at it and tap the link.
- **Full news stories.** Opening a story in News now shows the whole article (scroll with the D-pad), not just the headline. Menus, ads and cookie pop-ups are stripped out. List cards show the first few lines.

### Improved

- **Pictures load almost instantly.**
  - Box art, screenshots, GIFs, profile pictures and news images are saved on your PS3's hard drive, so they show straight away next time, even after a restart.
  - CELL downloads three pictures at once instead of one.
  - Pictures start loading before you scroll to them: the Feed, Global Chat, profiles, game pages, your library, Play Online and News.
  - The server fetches a game's box art the moment you look at it, instead of waiting in line.
- **Your account survives deleting CELL.**
  - Deleting CELL from the XMB used to log you out for good, so reinstalling meant making a new account. Now CELL remembers you two ways: a backup copy on the PS3 that a reinstall picks right up, and a link between your account and your console on the server.
  - Even after a formatted or new hard drive, starting CELL says **"Welcome back, <name>: your account is restored."**
  - Your console is identified by a scrambled code; your PSID itself never leaves the PS3.
  - Existing accounts get linked the first time you open 1.0.5.

### Fixed

- **The app and the server always match now.** Mismatched versions were causing problems. From now on, when a new release is out, CELL shows an "Update to CELL X" screen with a Download button. Your account, posts and friends stay safe on the server.
  - **Heads-up:** older versions of CELL can't show this screen. If you're on an older version, accept the update offer when CELL starts (or install 1.0.5 from Package Manager). Every update after this one arrives automatically.

### For staff

- **Updates → Release sync card.**
  - Shows the server version next to the PS3 app version, marked **In sync** or **Out of sync**.
  - A switch decides whether older PS3s *must* update.
  - A chart shows which CELL versions players used in the last 24 hours.
  - Publishing a PKG whose number doesn't match the server asks you to confirm first.
- **Discord → "Official Discord on the PS3":** paste your invite link here to turn on the QR codes. Only Discord invite links are accepted. Set the invite to never expire.
- **Console bans got stronger.** Banning a console now bans the real console, so deleting and reinstalling CELL can't dodge it.

### Housekeeping

- CELL is proprietary, closed-source software: © 2026 Dehz, all rights reserved. The license is in the package, and Settings shows "© 2026 Dehz".

---
