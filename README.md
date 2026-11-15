# Heroes StarCraft

Separate GitHub Pages publication of Heroes Goonk × StarCraft.

Play: https://pikipiki.github.io/heroes-starcraft/battle.html

The workflow builds the reviewed source commit in `source-ref` from
[pikipiki/heroes3-goonks-and-magic](https://github.com/pikipiki/heroes3-goonks-and-magic/tree/codex/heroes-starcraft-crossover).
Only the dedicated crossover branch is used. The original game's `main` branch
and Pages deployment are managed independently.

Update `source-ref` to a verified crossover commit and push this repository's
`codex/heroes-starcraft-crossover` branch to publish an update.

The first launch installs and verifies StarCraft data before opening Heroes.
Battles reuse a prepared map and compiled RTS engine; completed archives stay
on the device, and interrupted chunk downloads can resume.

Combat audio is activated from Heroes touch controls. Attack mode shows a target
reticle and confirms submitted orders; the launch checks for a newer release
before entering the game.

The shared battlefield targets 50 fps. Native positions and original sprite
frames are interpolated without changing simulation speed or combat outcomes.
The hidden RTS renderer updates once per simulation tick.

Selecting a troop and tapping an enemy issues an attack directly; the first move
or attack starts the fight. Heroes troops use their original attack, wound and
death sounds from installed game data, normalized to PCM before combat.
StarCraft simulation stand-ins no longer provide Heroes creature voices.

The demo fields seven final Heroes faction creatures in full army slots, five
members each, against twelve Terran, Zerg and Protoss units with maximum upgrades.
Hero and creature spells use the native Heroes rules, with original spell,
wound and death animations on the shared battlefield. Protoss shields absorb
spell damage before health.

Before combat, prepare five spell shortcuts from the complete hero and creature
catalogue. Preferences stay on the device. Touch a shortcut or press 1–5 to enter
paused targeting; the full book remains available. The command card uses the
original Heroes spell icons in a steel RTS console, with five shortcuts across
the bottom in portrait and a 3×3 grid on the right in landscape.

The same five saved references also work in native Heroes combat, in both Classic
view and Vertical view. Native shortcuts respect hero mana, creature charges,
active creature turns and contextual target legality. Preparation preserves the
current turn, and portrait/landscape rotation keeps the selected loadout.

During a solo field battle, **▶ Temps réel** switches the current classic or
vertical battle to RTS while preserving casualties, wounds, mana and effects.
**Tous les sorts** reuses the classic spellbook component, with school tabs,
pages, descriptions, target confirmation and a creature-caster selector.
The game pauses while choosing a spell.

Portrait combat keeps creatures upright at a comparable visible size. Original
Heroes detail, edge-aware StarCraft sprite enlargement, cached backdrops and
adaptive canvas resolution keep the battlefield readable while targeting 50 fps.
These are smoothed original sprites, not replacement HD artwork.

**↩ Classique** continues the same battle under Heroes III turn-based rules.
All six StarCraft creature types have original movement, attack and death
animations and attack audio in classic combat. Casualties, total health, mana,
spell effects and summoned creatures persist in both directions. Protoss
classic durability includes shields; the real-time engine splits shields and HP.
