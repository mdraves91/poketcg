# Meta Decks

This is a minor mod of Pokémon TCG, based on the disassembly project. 

Features: 
- Changes the decks of the 24 club members to be based on 'meta' decks. Reference links to the decks used can be found in `trainer deck names reference.csv`.
- Skips the tutorial battle vs Sam when starting the game.

To create a BPS patch of this hack, build it using the normal disassembly project's instructions below, then use the ROM Patcher at (https://www.romhacking.net/patch/). Make sure to select `Creator mode` and `BPS` for the patch type.

NOTE: When building this project, you will a LOT of deprecated warnings, and 1 error at the end because the checksum does not match the checksum of the vanilla rom. You'll see an error message like this:

```
poketcg.gbc: FAILED
sha1sum: WARNING: 1 computed checksum did NOT match
make: *** [Makefile:60: compare] Error 1
```

# Pokémon TCG [![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon TCG.

It builds the following ROM:

- Pokémon Trading Card Game (U) [C][!].gbc `sha1: 0f8670a583255cff3e5b7ca71b5d7454d928fc48`

To assemble, first download RGBDS (https://github.com/gbdev/rgbds/releases) and extract it to /usr/local/bin.
Run `make` in your shell.

This will output a file named "poketcg.gbc".


## See also

- [**Symbols**][symbols]
- **Discord:** [pret][discord]
- **IRC:** [libera#pret][irc]

Other disassembly projects:

- [**Pokémon TCG 2**][poketcg2]
- [**Pokémon Red/Blue**][pokered]
- [**Pokémon Yellow**][pokeyellow]
- [**Pokémon Gold/Silver**][pokegold]
- [**Pokémon Crystal**][pokecrystal]
- [**Pokémon Pinball**][pokepinball]
- [**Pokémon Ruby**][pokeruby]
- [**Pokémon FireRed**][pokefirered]
- [**Pokémon Emerald**][pokeemerald]

[poketcg2]: https://github.com/pret/poketcg2
[pokered]: https://github.com/pret/pokered
[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[symbols]: https://github.com/pret/poketcg/tree/symbols
[discord]: https://discord.gg/d5dubZ3
[irc]: https://web.libera.chat/?#pret
[ci]: https://github.com/pret/poketcg/actions
[ci-badge]: https://github.com/pret/poketcg/actions/workflows/main.yml/badge.svg
