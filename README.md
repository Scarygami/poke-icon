# \<poke-icon\>

Element to display (generation 1) Pokémon.

Pokémon can be specified by number or by name.

```
<poke-icon nr="130"></poke-icon>
<poke-icon name="Gyarados"></poke-icon>
```

`poke-icon` can be sized and styled using normal CSS. The image will be sized to fit inside of the `poke-icon` container.

```
poke-icon {
  display: inline-block;
  width: 32px;
  height: 32px;
}
```

The images included are transparent png with a size of 35x35, so you can't display them too large.
If you know of a source for SVG files of all Pokémon, I'd be happy to replace them.

The source icons are (c) Nintendo/Creatures Inc./GAME FREAK Inc./The Pokémon Company and used here under fair use in a non-commerical, open-source project.

Use at your own risk when including this element on your own website, especially for commercial purposes.
