# Safe Room

A short, gory *Left 4 Dead*–style survivor tale written in Inform 6.

You are TIM, the last of the four, holed up in a safehouse while the horde
beats on the boards outside. Find the room key, fuel the escape van, crack
the rusted gate, and get out before the door gives.

## Building

Requires the Inform 6 compiler (`inform`) and its standard library.

```
inform -D game.inf game.z5
```

## Playing

Any Z-machine interpreter works, e.g. [frotz](http://frotz.sourceforge.net/):

```
dfrotz game.z5
```

Type `HELP` in-game if you get stuck.

## Files

- `game.inf` — Inform 6 source.
- `game.z5` — compiled Z-machine story file (built from `game.inf`).

This game also runs on the [hermes-zmux-bot](https://github.com/DiscoTex/hermes-zmux-bot)
Discord bot, which drives a `dfrotz` session per channel with an
auto-generated map.
