# nade guides

clone this into your annotation folder - somewhere like:
`C:\SteamLibrary\steamapps\common\Counter-Strike Global Offensive\game\csgo\annotations`

## Create and save annotations
```
annotation_load <MAP_NAME>
annotation_create grenade "<WHERE THE NADE LANDS>" "<TYPE OF THROW>: <ANY OTHER INFO>" float faceplayer
annotation_save <MAP_NAME>
```


## other useful binds
add these to your config, customize keys if you want

```
bind p "sv_cheats 1; noclip"
bind k sv_rethrow_last_grenade

bind l .deleteNade; alias .deleteNade .deleteSmoke
alias .deleteSmoke	"ent_fire smokegrenade_projectile kill; .deleteFlash"
alias .deleteFlash	"ent_fire flashbang_projectile kill; .deleteHE"
alias .deleteHE		"ent_fire hegrenade_projectile kill; .deleteInc"
alias .deleteInc	"ent_fire incgrenade_projectile kill; .deleteMolo"
alias .deleteMolo	"ent_fire molotov_projectile kill; .deleteDecoy"
alias .deleteDecoy	"ent_fire decoy_projectile kill"
```