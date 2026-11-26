# aiostreams-css

Custom CSS for the AIOStreams app on Android TV (NVIDIA Shield) and the desktop app.

The account's Custom CSS holds a single line that loads this file:

```css
@import url("https://iamslokker.github.io/aiostreams-css/aiostreams.css");
```

This file is not limited by the 20,000-character cap on the account's Custom CSS.

What it changes:

- **TV home:** a single glass top bar with icons only, and the avatar alone at the top left. The hero follows the focused card, with one row at a time.
- **Title page (TV and desktop):** the art and trailer sit on the right only. Everything else goes in one left column with no poster. Series show episode cards with the text over the picture.
- **Versions list:** a side sheet on the right with big cards and a white focus ring, without the filter bar.
- **Desktop app:** the same home look, plus bigger posters.
