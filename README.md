# PokéIdle Hunt Atlas

Standalone Tampermonkey userscript for **https://pokeidle.io/**.

## Install

Install `hunt-atlas.user.js` with Tampermonkey. The userscript points its update/download metadata at this repository, so future versions can update from here.

## Features

- Search and filter hunts by region, level, type, weakness, availability, and collection status.
- Direct travel to available hunts.
- Personalized trainer XP/hour estimates from observed combat data.
- Bidirectional type matchup indicators for the current lead Pokémon.
- NPC sell-value estimates at each species' visible hunt level(s).
- Recent completed player-Market averages for non-shiny Pokémon.
- Sorting by XP/hour, NPC sell value, player Market value, matchup, encounter rate, hunt level, Pokédex number, or name.
- Persistent filters and cached combat/Market data.

## Prices

**NPC** is the estimated sale value of a Pokémon caught at the visible hunt level, using PokéIdle's NPC formula with reference quality **1.0**. Actual captured Pokémon vary with quality, and shiny Pokémon sell for more.

**Players** is a separate observed value. Hunt Atlas samples recent completed **gold** sales of non-shiny Pokémon from PokéIdle's global player Market history and caches the result. Species with no recent observed sale may show no player-Market value.

## Author

**MOTHblank**

- Google Play: https://play.google.com/store/apps/developer?id=MOTHblank
- X: https://x.com/MOTHblank
- WhatsApp / Pix: https://wa.me/+5537999933376
- Source code: https://github.com/MOTHblank/pokeidle-huntatlas
