# CELL Changelog

**CELL: The ONLY PS3 Social Media!** Newest release first. The latest version is **1.1.5**.

## CELL 1.1.5 Patch Notes: auto-translate, accessibility, mouse and keyboard, socials and Discord link

### New

- **Use a USB mouse and keyboard.** Plug them into your PS3 and use them alongside the controller.
  - **Mouse:**
    - A cursor appears when you move the mouse.
    - Point at something to select it, left click to open it, right click to go back, and scroll with the wheel.
    - You can click the button hints at the bottom of the screen too: clicking "△ New post" works like pressing △.
    - The cursor hides when you pick the controller back up.
  - **Keyboard:**
    - The arrow keys move.
    - **Enter** = ✕, **Esc** or **Backspace** = ◯, **Tab** = △, **Space** = □.
    - **Page Up / Page Down** = L1 / R1, **F1** = SELECT, **F5** = START.
    - Whenever CELL asks you to type, the PS3's keyboard window takes your USB keyboard as normal.
- **Socials on your profile.** Show your YouTube, Twitch, X, Instagram, TikTok, Bluesky, Reddit, Kick and Discord.
  - Go to **Settings → My socials** and type just your username. CELL makes the link for you.
  - Up to 6 show on your profile, in a row above your buttons.
  - On anyone's profile, press **up** to reach their socials and **✕** to get a **QR code**. Scan it with your phone to open their channel or page.
  - Choose who sees them: **Everyone**, **Friends only** or **Nobody**.
- **QR codes on every news story.** Open a story in News and scan the code on the right with your phone to read the full article there. Codes stay small and easy to scan, even for long links.
- **Brewology news.** PS3 and PS Vita stories from Brewology now show in News (shared with Brewology's permission).
- **See how big CELL is.** The top of the Feed shows how many players are on CELL in total.
- **Send feedback or an idea.** New in **Settings**: write anything to the CELL team, whether it's an idea, a bug or a thank-you. The team reads every one and may send you a thank-you back.
- **Link your Discord.** New in **Settings → Link Discord**: CELL shows a 6-letter code. Type **/link** and the code in the CELL Discord and you get the **CELL Player** role, so everyone there knows it's you.
  - The code works once and lasts 15 minutes. Press ✕ for a new one.
  - Press □ to unlink. That removes the role.
- **Check connection.** New in **Settings**: if CELL won't connect or sign-ups fail, it checks each part and shows a ✓ or ✗ with what to do:
  - your PS3's network (IP and DNS)
  - finding CELL's server, and how fast it answers
  - whether the server is running and sign-ups are open
  - your account, and whether a newer CELL is out
  - It also warns you if your PS3 is still using a Play Online revival DNS.
- **One download for everyone.** CELL-1.1.5.pkg works on both CFW and PS3HEN. There's no separate HEN file any more.
- **Auto-translate.** Posts, comments, Global Chat and private messages now show in your language, so players from every country can talk to each other.
  - Translated text says **"Translated from Spanish"** (or whichever language) underneath. Press **SELECT** on it to **see the original**, and again to go back.
  - Your own posts and messages are never changed.
  - It's on by default. Turn it off in **Settings → Translate posts and chat**, which also shows how much of this month's translation allowance is used.
- **Accessibility.** New in **Settings → Accessibility**, so everyone can enjoy CELL:
  - **Text size:** Normal, Large or Extra large for posts, comments, Global Chat, Messages and News stories.
  - **High contrast:** black background, white text and a thick yellow outline on whatever is selected.
  - **Colour-blind friendly:** blue and orange instead of green and red.
  - **Reduce motion:** still backgrounds, no sparkles on names, and GIFs stay still.
  - **Read aloud:** CELL speaks whatever you move to through your TV, in your language. Press **L3** (or **F2** on a keyboard) to hear it again. Choose Slow, Normal, Fast or Faster.
  - **Flash the screen** and **vibrate the controller** (DualShock 3) when a message or notification arrives.
  - **Pop-ups stay on screen** for 3, 6 or 10 seconds, or until you close them.
- **Picture descriptions.** When you post a screenshot, press **SELECT** to describe it for players who can't see it. The description shows on the picture, and Read aloud reads it.

### Improved

- **"Can't reach CELL" now tells you why.** It checks your connection by itself and says whether your PS3 is offline, can't find the CELL server (DNS), or is being blocked, with how to fix it. **△ Check connection** shows the full checklist.
- **Gets past DNS that won't find CELL.** If your internet provider's DNS can't find the CELL server, CELL now asks Cloudflare (1.1.1.1) and Google (8.8.8.8) directly, so you can still sign in without changing any settings.
- **Play Online: every game's connection steps were checked and rewritten.**
  - Each game page now has the complete steps: Custom setup, IP Automatic, DNS Manual with a public secondary DNS (1.1.1.1), MTU Automatic, Proxy Do Not Use, **UPnP Enable**, and Test Connection. The old steps skipped some of these.
  - **"Not connecting?"** tips on every revival:
    - a backup server to try, where there is one
    - Wi-Fi and cable each keep their own DNS
    - install the game's latest update
    - set the DNS back to Automatic afterwards
    - other ways to set the DNS: on your router, or with the ps3ezDNS app on CFW
  - **Games on official servers** (GTA IV, Resident Evil: Operation Raccoon City and others) now say to put the DNS back to **Automatic**. A revival DNS left on from another game blocks official servers.
  - CELL's server checks every revival DNS server every 30 minutes. Each game page shows whether its server is answering right now.
  - Updated games:
    - **Ratchet: Deadlocked** gets a backup server (PSORG).
    - **MotorStorm** gets a backup server (PSORG).
    - **Warhawk** gets PSONE as a backup.
    - **Blur, DJ Hero and the Transformers games** are credited to Warehouse, with where to find a new DNS if theirs moves.
    - **Demon's Souls** and **ModNation Racers** now show a DNS that works on a real PS3.
  - Long pages scroll with the D-pad, so you can read every step and tip before reaching the buttons.
- "3 min ago", "2 h ago" and "just now" are now translated in every language.
- **The Revival Dev badge is now PS3 Developer,** for anyone who makes PS3 homebrew, apps, mods or revival servers. Everyone who had it keeps it.

### For staff

- **Discord: CELL Player role.**
  - Players who link get the role automatically. You can see a member's CELL name without asking: right-click them → **Apps → CELL profile**.
  - In every staff command you can **@ a linked member** instead of typing their CELL name.
  - A ban takes the role away, and an unban gives it back.
  - **Set it up:** Staff site → **Discord**: paste the role's ID into **CELL Player role**. In Discord, drag the bot's role above it. Open **Add Cell bot to your server** again (it now asks for Manage Roles), then press **Register /cell commands**.
- **/status in Discord.** Anyone can type **/status** to see whether CELL is up: response time, sign-ups, players online and any Play Online servers that are down. There's also a status page anyone can open on a phone: **your-server/status**.
- **Auto-translate for players** on the **Announcements** page:
  - Add a free **Microsoft Azure Translator** key (2 million characters a month on the free plan).
  - Set a **monthly limit** (1,900,000 to start, safely inside the free plan). When it's reached, CELL stops translating until the 1st, so there's never a surprise bill. The page shows how much is used and when it resets.
  - Each text is translated once per language and remembered, so the allowance goes a long way.
  - The staff **Translate** links use the same key when there's no DeepL key.
- **Picture descriptions** show under each picture on the **Media** page.
- **Read aloud's voice** runs on your server (espeak-ng: free, offline, installed with the update). If it's missing, the Overview page tells you how to add it.
- **Feedback & ideas** page on the Staff site.
  - Everything players send, with their CELL version and language.
  - Mark each one **Planned**, **Done** or **Closed**, and **Thank them** with a message that pops up in their app.
  - New feedback can also reach your phone (Phone alerts → "Feedback and ideas from players").
- **Translate** under every post, comment, chat message, private message, report, appeal and piece of feedback, into your browser's language.
  - Out of the box it opens Google Translate in a new tab.
  - The owner can add a free DeepL key on the **Announcements** page to show translations right on the page instead.
- **Badges are easy to give.**
  - Each badge card on the **Badges** page has its own box: type a name, press **Give**.
  - The owner can give any badge, Promoter included, with no notes or proof links. Admins still need 3 proof links for Promoter.
- **Socials** show on the player page, where staff can **Remove** one with a reason (the player is told why). Changes to socials are in the player's history like bio changes.
- **Donations: dismiss false claims.** A claim from someone who didn't really donate can be **Dismissed** (with an optional note, and optionally telling them in the app), so it stops waiting. **Restore** brings it back.
- **Play Online:**
  - Each game shows whether its DNS server is answering ("DNS answering" / "DNS not answering since …").
  - A red banner lists any games whose server is down, and **Check DNS now** checks them on demand.
  - Games now have a **Backup DNS servers** field.
  - Phone alerts tell you when a revival DNS stops answering, and when it's back.
- **News feed sources:** each source can now keep **Everything**, **PS3 only** or **PS3 + PS Vita** stories. If a site's feed stops working, CELL reads the article list straight off its page instead.

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
