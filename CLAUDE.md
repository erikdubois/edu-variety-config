# edu-variety-config — Project Notes

## What This Is
Default skel configuration for the [Variety](https://peterlevi.com/variety/) wallpaper changer,
deployed to `etc/skel/.config/variety/` for Kiro/ArcoLinux.

## Key Files
- `etc/skel/.config/variety/variety.conf` — main Variety config
- `etc/skel/.config/variety/scripts/set_wallpaper_kiro` — custom set-wallpaper script
- `etc/skel/.config/variety/scripts/get_wallpaper_kiro` — custom get-wallpaper script
- `setup.sh` — install script
- `up.sh` — update/sync script

## Current State
Stable. Wallhaven sources (space, minimal, scifi, simple, abstract) enabled.
Custom kiro scripts wired via `set_wallpaper_script` / `get_wallpaper_script` in variety.conf.

## Next Steps
- See TODO.md
