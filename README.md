# [WIP] HeroScape JSON

Heroscape data in JSON format for use in Heroscape related apps.

## Units
```
{
  name        \\ Unit name
  image       \\ Image name
  general     \\ General the unit falls under
  race        \\ Unit race
  type        \\ Squad or Hero
  cardClass   \\ Unit class
  personality \\ Unit personality
  height      \\ Unit height
  life        \\ Unit hit points
  move        \\ Unit movement per turn
  range       \\ Unit attack range
  attack      \\ Number of attack dice
  defense     \\ Number of defense dice
  points      \\ Unit poiint value
  figures     \\ Number of figures
  hexes       \\ Number of hexes each figure takes up
  set         \\ Set the unit was released
  abilities: [
    {
      name          \\ Ability name
      description   \\ Ability description
    }
  ]
}
```

## Sets
```
{
  ids           \\ Set ID
  name          \\ Set name
  alternateName \\ Alternate set name
  type          \\ Set type
  universe      \\ Set universe
  released      \\ Date of release
}
```

## Generals
```
{
  ids        \\ General ID
  name       \\ General name
  alignment  \\ Army alignment
  set        \\ Set the general was released
}
```

## Todo

 - [x] Add `units` JSON
 - [x] Add `sets` JSON
 - [x] Add `generals` JSON
 - [ ] Add `packs` JSON
 - [ ] Add `terrain` JSON
 - [ ] Add `glyphs` JSON
 - [ ] Generate `unit` ids
 - [ ] Update `unit` set to match `set` name
 - [ ] Add `unit` spaces (`figures * hexes`)
 - [ ] Add `unit` species
 - [ ] Add `unit` planet
 - [ ] Add `unit` size
