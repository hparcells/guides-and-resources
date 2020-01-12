# Portal 2
> Portal 2 resources and speedrunning.

## Table of Contents
- [Portal 2](#portal-2)
  - [Table of Contents](#table-of-contents)
  - [Commands](#commands)
  - [Speedrunning](#speedrunning)
    - [Commands](#commands-1)
    - [Tutorials](#tutorials)
    - [Resources](#resources)

## Commands
- `mat_ambient_light_r 0.5;mat_ambient_light_g 0.5;mat_ambient_light_b 0.5;`: Makes everything brighter.
  
**Co-op**
- `bind KEY "+remote_view;+remote_view;";`: Binds a key to open and keep open partner view. Must press at the start of every map.
- `bind KEY "-forward;-back;-moveleft;-moveright;-attack;-attack2;incrementvar in_forceuser 0 1 1";`: For **Solo Co-op Only**, Toggles the control of each player.
- `bind KEY +mouse_menu_playtest;`: Binds a KEY to open the DLC ping tool menu.
- `mp_mark_all_maps_incomplete;mp_lock_all_taunts;`: Resets all progress. Must be in a non-local match. Resets both players.

## Speedrunning
### Commands
- `bind mwheeldown +jump;`: Bind scroll wheel down to jump for bhopping.
- `bind KEY "toggle sensitivity 3 0.01";`: Makes a KEY toggle between normal sensitivity and low sensitivity.
- `bind KEY "incrementvar sv_player_funnel_into_portals 0 1 1";`: Makes a KEY toggle portal funneling.

**Co-op**
- `bind KEY taunt;`: Binds a KEY to air tuant for taunt skips.

**SAR**
- `ui_loadingscreen_transition_time 0;ui_loadingscreen_fadein_time 0;ui_loadingscreen_mintransition_time 0;`: Makes loading times faster.
- `sar_autorecord 1;`: Starts recording a demo at the start of every new level.
- `sar_record_at 1;`: Records at the first tick of the level.
- `sar_record_at_demo_name DEMO_NAME;`: Records demos as a new name.
- `sar_speedrun_offset NUMBER`: Sets the speedrun offset. Use `16868` for container ride save.

### Tutorials
- Cant Even's Single Player Tutorial Playlist: https://www.youtube.com/playlist?list=PLc4Y8DtiFCXDcrbhmmnObxw7n7GoiTIwn

### Resources
**SAR**
- SourceAutoRecord: https://github.com/NeKzor/SourceAutoRecord
- Blenderiste09 SourceAutoRecord Fork: https://github.com/Blenderiste09/SourceAutoRecord

**Leaderboards**
- Full-game Leaderboard: https://www.speedrun.com/portal_2
- iVerb's CM Leaderboard: https://board.iverb.me/

**Other Links**
- Speedrun Mod: https://github.com/Krzyhau/Portal2SpeedrunMod/
- Speedrunning Discord Server: https://discord.gg/ps96xEy
