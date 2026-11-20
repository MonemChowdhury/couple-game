# Couple Game

A personalised two-player game gift for couples. Single page, no server, runs on GitHub Pages.

This is the clean starting file. It has demo names (Mira & Sam), placeholder photos and an original demo tune. No real customer's details are in it.

## Making one for a customer

1. Copy this repo's files into the customer's new repo.
2. In `index.html`, edit only the `CONFIG` block at the top of the script:
   - `her` / `him`: first names (Partner 1 / Partner 2)
   - `herPlace` / `himPlace` and `herTz` / `himTz`: city on screen and IANA time zone
   - `lock`: 4 digits, DDMM. `lockHint`: the clue shown on the lock screen
   - `music`: set to `""` if the customer has no song
3. Replace the files in `media/`:
   - `puzzle.jpg`: one couple photo, cropped square around both faces
   - `w1.jpg` to `w5.jpg`: album photos, max 1100px, quality ~82
   - `music.mp3`: trimmed so it loops cleanly
4. Push, then turn on GitHub Pages (Settings → Pages → main → /root).

Made with love by Monem · info@monemshariar.com
