# CELL 1.1.5 Patch Notes: mouse and keyboard, socials, Discord link, QR codes in News and feedback

## New

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

## Improved

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

## For staff

- **Discord: CELL Player role.**
  - Players who link get the role automatically. You can see a member's CELL name without asking: right-click them → **Apps → CELL profile**.
  - In every staff command you can **@ a linked member** instead of typing their CELL name.
  - A ban takes the role away, and an unban gives it back.
  - **Set it up:** Staff site → **Discord**: paste the role's ID into **CELL Player role**. In Discord, drag the bot's role above it. Open **Add Cell bot to your server** again (it now asks for Manage Roles), then press **Register /cell commands**.
- **/status in Discord.** Anyone can type **/status** to see whether CELL is up: response time, sign-ups, players online and any Play Online servers that are down. There's also a status page anyone can open on a phone: **your-server/status**.
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
