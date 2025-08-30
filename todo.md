# TODO

## BACKLOG

- [ ] API(not) really just need to have the proper groups
- [ ] maybe raycast depending on what tool/item the player is holding?
  - reason 1:(liquids) if the item requires liquid it can raycast liquids.
  - reason 2:(tool reach) some tools/items may have a different reach
- [ ] settings
  - reach
  - colors
  - features on/off 

## DOING

- [.] (still needs more work) create banner image

## DONE

- [x] #bug crash when looking at some entities or nodes (age of mending)
- [x] looking at an unknown node causes crashing
- [x] correct tool used on node or not
- [x] (this is the best I can do, overriding the item breaks other mods) show 'usable on self' crosshair even if not right_click
- [x] engine deprecated things.. look at logs

- [x] something seems to be broken for multiplayer
  - may need to remove the player's "hud" when they leave the server
- [x] (craeted a script for this) on release make sure to exclude .aseprite files
- [x] (gif) create demo
- [x] README file
- [x] fix the reach
  - [x] (survival,creative) mcl gamemode reach
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
