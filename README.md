# PokéIdle Hunt Atlas

Standalone Tampermonkey userscript for **https://pokeidle.io/**.

## Install

Install `hunt-atlas.user.js` with Tampermonkey. The userscript points its update/download metadata at this repository, so future versions can update from here.

## Features

- Search and filter hunts by region, level, type, weakness, availability, and collection status.
- Direct travel to available hunts.
- Personalized trainer XP/hour estimates from observed combat data.
- Bidirectional type matchup indicators for the current lead Pokémon.
- Recent completed-sale Market averages for non-shiny Pokémon, sampled from PokéIdle's global Market history.
- Sorting by XP/hour, Market value, matchup, encounter rate, hunt level, Pokédex number, or name.
- Persistent filters and cached combat/Market data.

## Market values

Market values are **recent observed averages**, not fixed prices. Hunt Atlas samples completed **gold** sales of non-shiny Pokémon from PokéIdle's global Market history and caches the result. Species with no sufficiently recent observed sale may show no Market value until one appears in the sampled history.

## Author

MOTHblank
