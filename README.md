# Coffee Talk Episode Registry

Tracks every stat and topic used in **Coffee Talk with Tim & D.J.** episodes.

Used by the script generator as a pre-run check to prevent stat or topic
repetition across episodes.

## How to update

After each episode airs, add a row to `registry.md` with:
- Episode date
- Episode title
- Central hook stat (the number D.J. opens with)
- All supporting stats cited
- Topic category

The script generator fetches `registry.md` via raw URL before every script.

## Raw URL for system prompt
```
https://raw.githubusercontent.com/delfinparis/coffeetalk-episode-registry/main/registry.md
```
