# TODO

## BACKLOG


## DOING

- [ ] fix the reach
  - [ ] (allow for modification in settings) base game reach
  - [ ] (survival,creative) mcl gamemode reach
 
## DONE

- [.] (engine limitation... I can't fix this) check if pointed thing is self..
- [x] MOD NAME (Adaptive Crosshair)
  - adaptive crosshair
  - dynamic crosshair
  - better crosshair
  - crosshair+
  - conditional crosshair
- [x] tool priorities
- [x] take into account the wielded item
  - [x] tool (attack,mine... etc)
  - [x] usable item (food, potion... etc)
- [x] some interactions may be conditional... (holding specific item/tool)
- [x] create two huds
  - [x] hud -> action (leftclick)
  - [x] hud -> interact (rightclick)
    - external interaction should take priority

## NOTES

- all tools, should use that square icon thing

there are so many groups being used:
- **nodes:** cracky, stone, pickaxey [[#node breakable levels:]]
- **tools:** pickaxe, shovel, axe

### node breakable levels:
- tool_capabilities (max_drop_level=3)
- _mcl_diggroups (for checking mcl tool groups) -> tool -> level
