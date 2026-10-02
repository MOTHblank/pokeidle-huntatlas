# PokéIdle Hunt Atlas

Standalone Tampermonkey userscript for **https://pokeidle.io/**.

## Install

Install `hunt-atlas.user.js` with Tampermonkey. The userscript points its update/download metadata at this repository, so future versions can update from here.

## Features

- Replaces PokéIdle's default **Mapa** view with an integrated Hunt Atlas inside the native modal.
- Includes a persistent **Atlas on/off** toggle in the map header; disabling it instantly restores PokéIdle's native map.
- Search and filter hunts by region, level, type, weakness, availability, and collection status.
- Direct travel to available hunts.
- Personalized trainer XP/hour recommendations, with a clearly labeled best hunt and Top 5 ranking from the current filters.
- Bidirectional type matchup indicators for the current lead Pokémon.
- **MKT** values for estimated NPC sale price at each species' visible hunt level(s).
- **RMT** values for recent completed player-Market averages for non-shiny Pokémon.
- Sorting by a compact field selector (XP/hour, Name, Pokédex number, Level, MKT, RMT, Matchup, Encounter rate) plus a separate ↑/↓ direction toggle.
- Wide responsive layout with compact filters and multi-column results on desktop.
- MOTHblank/social/source links are displayed beside the Hunt Atlas title.
- English and **pt-BR** UI localization. Hunt Atlas follows PokéIdle's selected interface language automatically.
- Persistent filters and cached combat/Market data.

## Prices

**MKT** is the estimated sale value to the NPC for a Pokémon caught at the visible hunt level, using PokéIdle's NPC formula with reference quality **1.0**. Actual captured Pokémon vary with quality, and shiny Pokémon sell for more.

**RMT** is the observed player-market value. Hunt Atlas samples recent completed **gold** sales of non-shiny Pokémon from PokéIdle's global player Market history and caches the result. Both MKT and RMT badges stay visible; unavailable values are shown as `—`.

## Author

**MOTHblank**

- Google Play: https://play.google.com/store/apps/developer?id=MOTHblank
- X: https://x.com/MOTHblank
- WhatsApp / Pix: https://wa.me/+5537999933376
- Source code: https://github.com/MOTHblank/pokeidle-huntatlas
