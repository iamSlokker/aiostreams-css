# aiostreams-css

Custom CSS for the AIOStreams app on Android TV (NVIDIA Shield) and the desktop app.

The account's Custom CSS holds a single line that loads this file:

```css
@import url("https://iamslokker.github.io/aiostreams-css/aiostreams.css");
```

This file is not limited by the 20,000-character cap on the account's Custom CSS.

What it changes:

- **TV home:** a single glass top bar with icons only, and the avatar alone at the top left. The hero follows the focused card, with one row at a time.
- **Title page (TV and desktop):** the art and trailer sit on the right only. Everything else goes in one left column with no poster. Series show the seasons as pills and a row of episode cards with the text under the picture.
- **Cast page:** a round photo, name, dates and bio in a left column, with the filmography grid on the right.
- **All episodes:** the season dialog fills the screen with a grid of 16:9 cards, text under the picture.
- **More info:** the full overview opens as a centred card with the artwork on top.
- **Discover:** the title, tabs, sort and pickers sit in one solid card above a denser poster grid; genres get their own row.
- **Favourites:** the same card header as Discover with a denser poster grid, and a centred empty state with a heart.
- **Activity (history):** each day is a row of posters with a short caption; a grouped show opens its episodes as cards beside the poster.
- **Playlists:** the panel opens as a centred window with the playlists as square cover cards.
- **Calendar:** a cleaner month grid with the month arrows on the right, today in white and a white ring on the focused day.
- **Card menu:** text-only rows with a small title line; the focused row is a white pill and the watched actions are dimmed. Notices match the dark panels.
- **Watch party:** the party panel is a solid side sheet with a big invite code (QR beside it on TV), pill tabs and white bubbles for your own messages; chat on the video uses dark bubbles. The player's party button is shown again.
- **Versions list:** a side sheet on the right with big cards and a white focus ring, without the filter bar.
- **Player:** a minimal HUD with a big middle play button between back and forward, then a pause screen with the logo, overview, a PAUSED pill, the clock and the time.
- **Player menus and extras:** subtitle, audio and other menus are small solid cards with a white focused row. The Skip button is white, the seek preview has a white frame, and the Up next card shows the still on top.
- **Search:** the field, suggestions and recent searches in a left column, with the result rows on the right.
- **Profile picker:** big round avatars with a white ring on the focused one, a coloured circle for profiles without a picture, no logo, and a matching PIN screen. "Choose a server" and the other sign-in screens share the same look.
- **Settings:** one floating glass sheet with a plain category list, a centred section title, compact cards, white switches and the search at the top right.
- **Desktop app:** the same home look, plus bigger posters.
