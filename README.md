# aiostreams-css

Custom CSS for the AIOStreams app on Android TV (NVIDIA Shield) and the desktop app.

The account's Custom CSS holds a single line that loads this file:

```css
@import url("https://iamslokker.github.io/aiostreams-css/aiostreams.css");
```

This file is not limited by the 20,000-character cap on the account's Custom CSS.

What it changes:

- **TV home:** a single glass top bar with icons only, and the avatar alone at the top left. The hero follows the focused card, with one row at a time.
- **Top bar extras:** Favourites, Calendar, Activity, Downloads, Playlists and Watch together fold behind a "+" and slide open when the bar has focus or the mouse is over it.
- **Card focus (glass):** the focused card grows a little and brightens, with a thin white ring, a soft glow and a diagonal glass sheen, after Nuvio HTPC's Shine and Card depth.
- **Title page (TV and desktop):** the art and trailer sit on the right only. Everything else goes in one left column with no poster. Series show the seasons as pills and a row of episode cards with the text under the picture.
- **Cast page:** a round photo, name, dates and bio in a left column, with the filmography grid on the right.
- **All episodes:** the season dialog fills the screen with a grid of 16:9 cards, text under the picture.
- **More info:** the full overview opens as a centred card with the artwork on top.
- **Discover:** the title, tabs, sort and pickers sit in one solid card above a denser poster grid; genres get their own row.
- **Favourites:** the same card header as Discover with a denser poster grid, and a centred empty state with a heart.
- **Downloads (PC):** the same card header with the total and folder buttons, small caps section labels, each download as a solid card with a wide still, a white progress bar and round buttons.
- **Player Episodes and Chapters:** a strip along the bottom with one row of wide stills, the season pills beside the title, a white tag on what is playing; the video stays visible above.
- **Are you still watching?:** like the pause screen, with the question, Up next and the buttons on the left and the next episode's still as a big card on the right.
- **Player error:** the same left-column look, with a warning icon, a small CAN'T PLAY THIS label, the message in large text and the buttons.
- **Activity (history):** each day is a row of posters with a short caption; a grouped show opens its episodes as cards beside the poster.
- **Playlists:** the panel opens as a centred window with the playlists as square cover cards.
- **Calendar:** a cleaner month grid with the month arrows on the right, today in white and a white ring on the focused day.
- **Card menu:** text-only rows with a small title line; the focused row is a white pill and the watched actions are dimmed. Notices match the dark panels.
- **Watch party:** the party panel is a solid side sheet with a big invite code (QR beside it on TV), pill tabs and white bubbles for your own messages; chat on the video uses dark bubbles. The player's party button is shown again.
- **Versions list:** a side sheet on the right with big cards and a white focus ring, without the filter bar.
- **Player:** a minimal HUD with a big middle play button between back and forward, then a pause screen with the logo, overview, a PAUSED pill, the clock and the time.
- **Player menus and extras:** subtitle, audio and other menus are small solid cards with a white focused row. The Skip button is white, the seek preview has a white frame, and the Up next card shows the still on top.
- **Search:** the field, suggestions and recent searches in a left column, with the result rows on the right.
- **Settings:** one floating glass sheet with a plain category list, a centred section title, compact cards, white switches and the search at the top right.
- **Desktop app:** the same home look, plus bigger posters.
