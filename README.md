# [WIP] HeroScape JSON

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
  wave        \\ Wave the unit was released
  abilities: [
    {
      name          \\ Ability name
      description   \\ Ability description
    }
  ]
}
```

## Todo

 - [ ] Add `wave` JSON
 - [ ] Add `general` JSON
 - [ ] Generate `unit` ids
