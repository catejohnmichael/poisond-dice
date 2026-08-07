# Poison'd — The Dice

A dice roller for [*Poison'd*](http://lumpley.com/index.php/anyway/thread/198) by Vincent Baker (lumpley games),
built for a game played over Discord voice.

**Open it:** https://catejohnmichael.github.io/poisond-dice/

Poison'd dice are objects that stay on the table, not results. Escalating picks up only your 1s, 2s and 3s and
returns them to the 4s, 5s and 6s you let lie; a tie rerolls only the lowest die; spending Xs rolls dice into a
pool already standing. A generic roll bot can't do any of that, which is why this exists.

- **Fights** — persistent pools, escalation that rerolls only the low dice and rings the ones left lying,
  tie-breaks, the advance-to-a-tie rule, the ladder for the current level, fighting on a side
- **Success rolls** — the four pairings, with a switchable ruling for what the GM throws away
- **Xs** — a pool per pirate, and every spend from the fight rules as a clickable row
- **Sundries** — plunder (sums pips), urgency card matching, NPC Brinksmanship, the storm, disease

Single file, no build, no server, no network. State saves in your browser; a mid-fight refresh loses nothing.
Works offline — save the page and open it off disk.

Rules text quoted from the game is Vincent Baker's. This is a play aid for people who own it.
