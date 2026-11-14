LUDO TABLE
Online Ludo for 2 to 4 players. Room codes, computer players, table chat with emoji. No ads, no accounts.

FILES (upload all 7 to your repository)
  index.html              the whole game
  manifest.json           lets phones install it as an app
  sw.js                   lets it open without a connection
  icon-192.png, icon-512.png, icon-maskable-512.png    app icons
  README.txt              this file

PUT IT ONLINE WITH GITHUB PAGES (works from a phone)
  1. In Chrome, tap the menu and turn on "Desktop site".
  2. Sign in at github.com, then go to github.com/new.
  3. Name the repository (for example "ludo"), choose Public, tap Create repository.
  4. Tap "uploading an existing file", then "choose your files" and select all 7 files.
     (GitHub cannot unzip, so unzip the download first.)
  5. Tap Commit changes.
  6. Open Settings > Pages. Under Branch choose main and / (root), then Save.
  7. After about 2 minutes your link appears, like https://yourname.github.io/ludo/

PLAY
  - Open the link, type your name, tap "Create an online room".
  - Send friends the invite link or the 5-letter code. They pick a seat with "Sit here".
  - Start the game. Chat and emoji are in the Table chat card.
  - Keep the host's page open while playing. If the host reloads, tap "Resume your room".

INSTALL AS AN APP
  Android: open the link in Chrome, menu > Install app.
  iPhone: open in Safari, Share > Add to Home Screen.

PLAY STORE (optional)
  Needs a Google Play developer account (one-time fee, about $25).
  Use https://www.pwabuilder.com with your link to make the Android package.
  Check Google's current testing rules for new accounts before you pay.

NOTES
  - Players connect through PeerJS Cloud (signalling) plus public STUN/TURN relays so friends on different mobile networks or countries can join more reliably.
  - Nothing is stored on a server of your own. The game still works peer-to-peer when a direct path is possible.
  - If a connection still fails on a very strict network, try Wi-Fi on at least one side.
  - If you edit a file later, change VERSION at the top of sw.js so phones pick up the update.
