# ARCHIVED
This plugin has been archived as the features it adds are now made redundant by the built-in classlimit cvars of Open Fortress:

`of_classlimit_mercenary`  
`of_classlimit_demoman`  
`of_classlimit_engineer`  
`of_classlimit_heavy`  
`of_classlimit_medic`  
`of_classlimit_pyro`  
`of_classlimit_scout`  
`of_classlimit_sniper`  
`of_classlimit_soldier`  
`of_classlimit_spy`  
`of_classlimit_civilian`  
`of_classlimit_juggernaut`  

# Open Fortress Class Restrictions

Open Fortress port of TF2 Class Restrictions plugin by Tsunami: https://forums.alliedmods.net/showthread.php?p=642353

## Configuration

Enable/disable restricting classes in OF.  
`sm_classrestrict_enabled` (0/1, default 1)

For all cvars below, the default is -1 (no limit). Anything higher will be the limit for that class.

Limits for *any* team's classes in OF. Use this for FFA or if both teams should have the same limits. Team-specific limits will *override* this value if they are set.  
`sm_classrestrict_demomen`  
`sm_classrestrict_engineers`  
`sm_classrestrict_heavies`  
`sm_classrestrict_medics`  
`sm_classrestrict_pyros`  
`sm_classrestrict_scouts`  
`sm_classrestrict_snipers`  
`sm_classrestrict_soldiers`  
`sm_classrestrict_spies`  
`sm_classrestrict_mercenaries`  
`sm_classrestrict_civilians`  
`sm_classrestrict_juggernauts`  

Limits for Blu classes in OF.  
`sm_classrestrict_blu_demomen`  
`sm_classrestrict_blu_engineers`  
`sm_classrestrict_blu_heavies`  
`sm_classrestrict_blu_medics`  
`sm_classrestrict_blu_pyros`  
`sm_classrestrict_blu_scouts`  
`sm_classrestrict_blu_snipers`  
`sm_classrestrict_blu_soldiers`  
`sm_classrestrict_blu_spies`  
`sm_classrestrict_blu_mercenaries`  
`sm_classrestrict_blu_civilians`  
`sm_classrestrict_blu_juggernauts`  

Limits for Red classes in OF.  
`sm_classrestrict_red_demomen`  
`sm_classrestrict_red_engineers`  
`sm_classrestrict_red_heavies`  
`sm_classrestrict_red_medics`  
`sm_classrestrict_red_pyros`  
`sm_classrestrict_red_scouts`  
`sm_classrestrict_red_snipers`  
`sm_classrestrict_red_soldiers`  
`sm_classrestrict_red_spies`  
`sm_classrestrict_red_mercenaries`  
`sm_classrestrict_red_civilians`  
`sm_classrestrict_red_juggernauts`  

You can put any of these cvars in server.cfg or sourcemod.cfg, and then if you want map specific cvars you can make a file called mapname.cfg (for example cp_dustbowl.cfg) and put those cvars in there.
