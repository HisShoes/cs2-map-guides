# nade guides

clone this into your annotation folder - somewhere like:
`C:\SteamLibrary\steamapps\common\Counter-Strike Global Offensive\game\csgo\annotations`

## Create and save annotations
```
sv_allow_annotations 1
annotation_load <MAP_NAME>
annotation_create grenade "<WHERE THE NADE LANDS>" "<TYPE OF THROW>: <ANY OTHER INFO>" float faceplayer
annotation_save <MAP_NAME>
```


## other useful binds
add these to your config, customize keys if you want

```
bind p "sv_cheats 1; noclip";
bind k sv_rethrow_last_grenade;
bind l ent_fire smokegrenade_projectile kill;
sv_allow_annotations 1;
```