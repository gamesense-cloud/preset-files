# gamesense.cloud preset files

Extra files for gamesense.cloud features that are too big to ship in the client.
Download them with the **Emote Pack** button on the website (it is this repo as a zip).

## Emote Pack (`emotes/`)

Everything the Fortnite dances and the emote wheel need:

| Folder | What it is |
|---|---|
| `emotes/csgo_addons/characters/kolka/fortnite_dance.vmdl_c` | The dance model: 44 dances and 38 emotes on the CS2 player skeleton |
| `emotes/music/` | The dance music (69 songs, `.wav`) |
| `emotes/icons/` | The emote wheel icons (75, `.png`) |

### Install

1. Download the Emote Pack and unzip it.
2. Copy the `emotes` folder into `Documents\gscloud`, so you end up with
   `Documents\gscloud\emotes\csgo_addons`, `...\emotes\music` and `...\emotes\icons`.
3. In game: **Misc → Emote wheel**, turn on **Fortnite dances**. Bind a key to the emote wheel,
   or pick **Fortnite dance** under **Misc → Animations** to make other players dance.

If the menu says *"The game did not load the dance model"*, copy the `characters` folder from
`emotes\csgo_addons` into `Counter-Strike Global Offensive\game\csgo\` as well and restart the game.

Only you see the dances; nothing is sent to the server.

### Credits

- Dance model: Kolka's CS2 port, from [Cruze03/FortniteEmotesNDances](https://github.com/Cruze03/FortniteEmotesNDances)
- Music: from the same project (sound events by GoldKingZ), converted to `.wav`
- Icons: [fortnite-api.com](https://fortnite-api.com)
- Fortnite, its emotes, music and icons are the property of Epic Games.
