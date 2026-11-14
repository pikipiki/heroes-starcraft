# Heroes StarCraft

Separate GitHub Pages publication of Heroes Goonk × StarCraft.

Play: https://pikipiki.github.io/heroes-starcraft/play.html

The workflow builds the reviewed source commit in `source-ref` from
[pikipiki/heroes3-goonks-and-magic](https://github.com/pikipiki/heroes3-goonks-and-magic/tree/codex/heroes-starcraft-crossover).
Only the dedicated crossover branch is used. The original game's `main` branch
and Pages deployment are managed independently.

Update `source-ref` to a verified crossover commit and push this repository's
`codex/heroes-starcraft-crossover` branch to publish an update.

The first launch installs and verifies StarCraft data before opening Heroes.
Battles reuse a prepared map and compiled RTS engine; completed archives stay
on the device, and interrupted chunk downloads can resume.
