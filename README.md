## MSFW-CustomWeapons

# CUSTOM WEAPONS FOR YOUR FIVEM SERVER 

## JOIN OUR DISCORD FOR UPDATES AND SUPPORT
# DISCORD - https://discord.gg/Kz9YBjPA2U

## ADD THIS IN qb-core/shared/items.lua

```
        --GD-WEAPONS
    weapon_browning 		     = {name = 'weapon_browning', 			label = 'BROWNING', 		weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
	weapon_glock22 		     	 = {name = 'weapon_glock22', 			label = 'GLOCK-20', 		weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_glock20.png', 		unique = true, 		useable = false, 	description = 'Police Glock'},
    weapon_dp9 				     = {name = 'weapon_dp9', 			 	label = 'DP9', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_dp9.png', 			unique = true, 		useable = false, 	description = 'POW POW'},
    weapon_uzi 				     = {name = 'weapon_uzi', 			 	label = 'UZI', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SMG',			image = 'weapon_uzi.png', 			unique = true, 		useable = false, 	description = 'USE THIS IN A WAR , LMAO YOU GOT NO AIM'},
    weapon_mac10 				 = {name = 'weapon_mac10', 			 	label = 'MAC-10', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SMG',			image = 'weapon_mac10.png', 		unique = true, 		useable = false, 	description = 'SMALL UZI?'},
    weapon_mp9 				     = {name = 'weapon_mp9', 			 	label = 'MP9', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SMG',			image = 'weapon_mp9.png', 			unique = true, 		useable = false, 	description = 'SMOKE EM'},
	weapon_mp5 				     = {name = 'weapon_mp5', 			 	label = 'MP5', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SMG',			image = 'weapon_mp5.png', 			unique = true, 		useable = false, 	description = 'A BETTER VERSION OF SMG'},
    weapon_dildo 				 = {name = 'weapon_dildo', 			 	label = 'DILDO', 			weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_dildo.png', 		unique = true, 		useable = false, 	description = 'YOU CAN GIVE THIS TO YOUR GIRLFRIEND'},
    weapon_sledgehammer 				 = {name = 'weapon_sledgehammer', 			 	label = 'Sledgehammer', 			weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_dildo.png', 		unique = true, 		useable = false, 	description = 'A BIG HAMMER'},
    weapon_groza 				 = {name = 'weapon_groza', 			 	label = 'GROZA', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_RIFLE',		image = 'weapon_groza.png', 		unique = true, 		useable = false, 	description = 'LETS PLAY PUBG WITH THIS'},
    weapon_katana 				 = {name = 'weapon_katana', 			label = 'KATANA', 			weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_katana.png', 		unique = true, 		useable = false, 	description = 'A BIG SWORD TO CUT PEOPLE HEAD OR PP'},
	weapon_keyboard 			 = {name = 'weapon_keyboard', 			label = 'KEYBOARD', 		weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_keyboard.png', 		unique = true, 		useable = false, 	description = 'YOU CAN USE THIS TO HIT YOUR SON xD'},
    weapon_m4a1 				 = {name = 'weapon_m4a1', 			 	label = 'M4A1', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_m4a1.png', 			unique = true, 		useable = false, 	description = 'PISTOLLLLL'},
	weapon_g18c 				 = {name = 'weapon_g18c', 			 	label = 'GLOCK-18C', 		weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_g18c.png', 			unique = true, 		useable = false, 	description = 'A SMALL ASSAULT PISTOL'},
    weapon_riftedge 			 = {name = 'weapon_riftedge', 			label = 'RIFTEDGE', 		weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_riftedge.png', 		unique = true, 		useable = false, 	description = 'VERY BIG THING TO CUT PEOPLE UP'},
	weapon_krambit 			 	 = {name = 'weapon_krambit', 			label = 'KRAMBIT', 			weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_krambit.png', 		unique = true, 		useable = false, 	description = 'LMAO CSGO'},
	weapon_draco 				 = {name = 'weapon_draco', 			 	label = 'DRACO', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_RIFLE',		image = 'weapon_draco.png', 		unique = true, 		useable = false, 	description = 'A SMALL ASSAULT RIFLE LIKE YOUR PP'},
	weapon_gepard 				 = {name = 'weapon_gepard', 			label = 'GEPARD', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_RIFLE',		image = 'weapon_gepard.png', 		unique = true, 		useable = false, 	description = 'A SMALL ASSAULT RIFLE LIKE YOUR PP'},
    weapon_sword 		         = {name = 'weapon_sword', 			    label = 'SWORD', 		    weight = 1000, 		type = 'weapon', 	ammotype = 'nil',			    image = 'weapon_sword.png', 		unique = true, 		useable = false, 	description = 'A BIG SWORD BIGGER THAN YOUR PP'},
	weapon_flashbang 			 = {name = 'weapon_flashbang', 		    label = 'FLASHBANG', 		weight = 1000, 		type = 'weapon', 	ammotype = 'nil',				image = 'weapon_flashbang.png', 	unique = true, 		useable = false, 	description = 'BLINDED'},
	weapon_beanbag 			     = {name = 'weapon_beanbag', 	 	  	label = 'BEANBAG', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SHOTGUN',		image = 'weapon_beanbag.png', 		unique = true, 		useable = false, 	description = 'A shotgun? no!'},
	weapon_m67 				 	 = {name = 'weapon_m67', 		    	label = 'M67', 				weight = 1000, 		type = 'weapon', 	ammotype = nil,					image = 'weapon_m67.png', 			unique = true, 		useable = false, 	description = 'A GRENADEEE'},
    weapon_m4 				 = {name = 'weapon_m4', 			label = 'M4', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_RIFLE',		image = 'weapon_gepard.png', 		unique = true, 		useable = false, 	description = 'Police M4'},
    weapon_m45a1 				 = {name = 'weapon_m45a1', 			 	label = 'M45A1', 			weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_PISTOL',		image = 'weapon_m4a1.png', 			unique = true, 		useable = false, 	description = 'HMM THIS LOOKS POWERFULL!!'},
    weapon_vector 				     = {name = 'weapon_vector', 			 	label = 'KRISS VECTOR', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_SMG',			image = 'weapon_vector.png', 			unique = true, 		useable = false, 	description = 'A BETTER VERSION OF SMG'},
    weapon_tec9 				     = {name = 'weapon_tec9', 			 	label = 'Tec 9', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_pistol',			image = 'weapon_tec9.png', 			unique = true, 		useable = false, 	description = ''},
    weapon_p226 				     = {name = 'weapon_p226', 			 	label = 'Pistol P226', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_pistol',			image = 'weapon_p226.png', 			unique = true, 		useable = false, 	description = ''},
    weapon_hk416b 				     = {name = 'weapon_hk416b', 			 	label = 'HK416-B', 				weight = 1000, 		type = 'weapon', 	ammotype = 'AMMO_RIFLE',			image = 'weapon_hk416b.png', 			unique = true, 		useable = false, 	description = ''},
```

## OX INVENTORY (ADD THIS IN ox_inventory/data/weapons.lua)

```
--THROWABLES
['WEAPON_M67']              = {label = 'M67',          weight = 149,    throwable = true,},
-- MELEE
['WEAPON_DILDO']            = {label = 'Dildo',        weight = 500,    durability = 0.1,},
['WEAPON_SLEDGEHAMMER']     = {label = 'Sledgehammer', weight = 500,    durability = 0.1,},
['WEAPON_KATANA']           = {label = 'Katana',       weight = 500,    durability = 0.1,},
['WEAPON_KEYBOARD']         = {label = 'keyboard',     weight = 500,    durability = 0.1,},
['WEAPON_RIFTEDGE']         = {label = 'Riftedge',     weight = 500,    durability = 0.1,},
['WEAPON_KRAMBIT']          = {label = 'Krambit',      weight = 500,    durability = 0.1,},
['WEAPON_SWORD']            = {label = 'Sword',        weight = 500,    durability = 0.1,},
-- WEAPONS
['WEAPON_BEANBAG'] 			= { label = 'Bean Bag',    weight = 1000,	durability = 0.0,	ammoname = 'ammo-shotgun',},
['WEAPON_BROWNING'] 	    = { label = 'Browing',	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_GLOCK22'] 	        = { label = 'GLOCK-22',	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_DP9'] 	            = { label = 'DP9',	       weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_M4A1'] 	        = { label = 'M4A1',	       weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_M45A1'] 	        = { label = 'M45A1',	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_P226'] 	        = { label = 'P226',	       weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
['WEAPON_UZI'] 			    = { label = 'UZI', 		   weight = 1000,	durability = 0.0,	ammoname = 'ammo-9',},
['WEAPON_TEC9'] 			= { label = 'TEC-9', 	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-9',},
['WEAPON_MAC10'] 			= { label = 'MAC-10', 	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-9',},
['WEAPON_MP9'] 			    = { label = 'MP9', 		   weight = 1000,	durability = 0.0,	ammoname = 'ammo-9',},
['WEAPON_G18C'] 		    = { label = 'G18-C', 	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-9',},
['WEAPON_MP5'] 				= { label = 'MP5', 	       weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_GROZA'] 		    = { label = 'GROZA', 	   weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_HK416B'] 		    = { label = 'HK416B',      weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_VECTOR'] 		    = { label = 'VECTOR',      weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_M4'] 		        = { label = 'M4',          weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_GEPARD'] 		    = { label = 'GEPARD',      weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},
['WEAPON_DRACO'] 		    = { label = 'DRACO',       weight = 1000,	durability = 0.0,	ammoname = 'ammo-rifle',},          
```

## ADD THIS IN qb-core/shared/weapons.lua

```
	-- GD-WEAPONS
	[`weapon_dildo`] 				 = {['name'] = 'weapon_dildo', 			['label'] = 'Dildo', 				['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_katana`] 				 = {['name'] = 'weapon_katana', 		['label'] = 'katana', 				['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_riftedge`] 			 = {['name'] = 'weapon_riftedge', 		['label'] = 'riftedge', 			['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
    [`weapon_sledgehammer`] 			 = {['name'] = 'weapon_sledgehammer', 		['label'] = 'Sledgehammer', 			['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_browning`] 			 = {['name'] = 'weapon_browning', 		['label'] = 'BROWNING', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_dp9`] 				 	 = {['name'] = 'weapon_dp9', 			['label'] = 'DP9', 				   	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_p226`] 				 	 = {['name'] = 'weapon_p226', 			['label'] = 'PISTOL P226', 				   	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_tec9`] 				 	 = {['name'] = 'weapon_tec9', 			['label'] = 'TEC-9', 				   	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m4a1`] 				 = {['name'] = 'weapon_m4a1', 			['label'] = 'M4A1', 				['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_groza`] 		 		 = {['name'] = 'weapon_groza', 	 		['label'] = 'GROZA', 				['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_uzi`] 			 		 = {['name'] = 'weapon_uzi', 			['label'] = 'UZI', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mac10`] 			 	 = {['name'] = 'weapon_mac10', 			['label'] = 'MAC-10', 				['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mp9`] 			 		 = {['name'] = 'weapon_mp9', 			['label'] = 'MP9', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    [`weapon_mp5`] 			 		 = {['name'] = 'weapon_mp5', 			['label'] = 'MP5', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    [`weapon_glock22`] 				 = {['name'] = 'weapon_glock22', 		['label'] = 'GLOCK-20', 				['weapontype'] = 'Pistol',	['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_g18c`] 				 = {['name'] = 'weapon_g18c', 			['label'] = 'GLOCK-18C', 				['weapontype'] = 'Pistol',	['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_gepard`] 		 		 = {['name'] = 'weapon_gepard', 	 		['label'] = 'GEPARD', 						['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_krambit`] 			 	 = {['name'] = 'weapon_krambit', 		['label'] = 'KRAMBIT', 				['weapontype'] = 'Melee',	['ammotype'] = nil, ['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_keyboard`] 			 = {['name'] = 'weapon_keyboard', 		['label'] = 'KEYBOARD', 			['weapontype'] = 'Melee',	['ammotype'] = nil, ['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
    [`weapon_sword`] 			     = {['name'] = 'weapon_sword', 		['label'] = 'SWORD', 			['weapontype'] = 'Melee',	['ammotype'] = nil, ['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
    [`weapon_m67`] 		        	= {['name'] = 'weapon_m67', 			['label'] = 'M67', 				['weapontype'] = 'Throwable',	['ammotype'] = nil,				['damagereason'] = 'Bombed / Exploded / Detonated / Blew up'},
    [`weapon_m4`] 		 		 = {['name'] = 'weapon_m4', 	 		['label'] = 'M4', 						['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_hk416b`] 		 		 = {['name'] = 'weapon_hk416b', 	 		['label'] = 'HK416-B', 						['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_m45a1`] 				 = {['name'] = 'weapon_m45a1', 			['label'] = 'M45A1', 				['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'}
    [`weapon_vector`] 			 		 = {['name'] = 'weapon_vector', 			['label'] = 'KRISS VECTOR', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},

```

## ADD THIS IN qb-smallresources/client/weapdraw.lua

```
	-- GD-Weapons
	'WEAPON_uzi',
	'WEAPON_mac10',
	'WEAPON_groza',
	'WEAPON_mp9',
	'WEAPON_dp9',
	'WEAPON_browning',
	'WEAPON_dildo',
	'WEAPON_riftedge',
	'WEAPON_m4a1',
	'WEAPON_katana',
    'WEAPON_keyboard',
    'WEAPON_krambit',
    'WEAPON_gepard',
    'WEAPON_draco',
    'WEAPON_g18c',
    'WEAPON_glock22',
    'WEAPON_mp5',
    'weapon_sword',
    'WEAPON_M67',
    'WEAPON_BEANBAG',
    'WEAPON_M4',
    'WEAPON_M45A1',
    'weapon_vector',
    'weapon_p226',
    'weapon_hk416b',
    'weapon_tec9',
    'weapon_sledgehammer',
```

# ADD THIS IN qb-weapons/config.lua

```
['WEAPON_uzi'] 			    = 0.15,
['WEAPON_mac10'] 	        = 0.15,
['WEAPON_groza'] 			= 0.15,
['WEAPON_mp9'] 		        = 0.15,
['WEAPON_dp9'] 			    = 0.15,
['WEAPON_browning'] 	    = 0.15,
['WEAPON_dildo'] 		    = 0.15,
['WEAPON_riftedge'] 	    = 0.15,
['WEAPON_katana'] 	        = 0.15,
['WEAPON_keyboard'] 	    = 0.15,
['WEAPON_krambit'] 	        = 0.15,
['WEAPON_gepard'] 			= 0.15,
['WEAPON_draco'] 		    = 0.15,
['WEAPON_g18c'] 		    = 0.15,
['weapon_sword'] 	        = 0.15,
['WEAPON_BEANBAG'] 	        = 0.15,
['WEAPON_mp5'] 		        = 0.15,
['WEAPON_M67'] 		        = 0.15,
['WEAPON_m45a1'] 		    = 0.15,
['WEAPON_m4'] 		        = 0.15,
['WEAPON_m4a1'] 		    = 0.15,
['weapon_vector']           = 0.15,
['weapon_tec9']             = 0.15,
['weapon_hk416b']           = 0.15,
['weapon_p226']             = 0.15,
['weapon_glock22']          = 0.15,
['weapon_sledgehammer']     = 0.15,

```

## ADD THIS IN qb-smallresources/client/recoil.lua (LINE AROUND 108)

```
	-- GD-WEAPONS
	[GetHashKey("weapon_groza")] = 0.5,
    [GetHashKey("weapon_gepard")] = 0.5,
    [GetHashKey("weapon_m4")] = 0.4,
	[GetHashKey("weapon_browning")] = 0.3,
	[GetHashKey("weapon_dp9")] = 0.3,
	[GetHashKey("weapon_m4a1")] = 0.3,
    [GetHashKey("weapon_m45a1")] = 0.3,
    [GetHashKey("weapon_glock22")] = 0.3,
   	[GetHashKey("weapon_g18c")] = 0.3,
	[GetHashKey("weapon_uzi")] = 0.4,
	[GetHashKey("weapon_mac10")] = 0.4,
	[GetHashKey("weapon_mp9")] = 0.4,
    [GetHashKey("weapon_mp5")] = 0.4,
    [GetHashKey("weapon_beanbag")] = 0.1,
    [GetHashKey("weapon_vector")] = 0.3,
	[GetHashKey("weapon_draco")] = 0.3,
	[GetHashKey("weapon_hk416b")] = 0.3,
	[GetHashKey("weapon_p226")] = 0.1,
	[GetHashKey("weapon_tec9")] = 0.1,

```
## REPLACE THE NEXT CODE IN QB-JEWELERY/CONFIG.LUA

```

Config.WhitelistedWeapons = {
    [`weapon_assaultrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_carbinerifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pumpshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_sawnoffshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_compactrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_microsmg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_autoshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol_mk2`] = {
        ["timeOut"] = 10000
    },
    [`weapon_combatpistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_appistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol50`] = {
        ["timeOut"] = 10000
    },
    [`weapon_uzi`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mac10`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mp9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_groza`] = {
        ["timeOut"] = 10000
    },
    [`weapon_gepard`] = {
        ["timeOut"] = 10000
    },
    [`weapon_draco`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mp5`] = {
        ["timeOut"] = 10000
    },
    [`weapon_browning`] = {
        ["timeOut"] = 10000
    },
    [`weapon_dp9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m4a1`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m45a1`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m4`] = {
        ["timeOut"] = 10000
    },
    [`weapon_vector`] = {
        ["timeOut"] = 10000
    },
    [`weapon_hk416b`] = {
        ["timeOut"] = 10000
    },
    [`weapon_sledgehammer`] = {
        ["timeOut"] = 10000
    },
    [`weapon_p226`] = {
        ["timeOut"] = 10000
    },
    [`weapon_tec9`] = {
        ["timeOut"] = 10000
    },
}

```
## ADD THIS IN qb-ambulancejob/config.lua

```
    --[[ HIGH CALIBER ]]
    [`WEAPON_groza`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_gepard`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_draco`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_m4`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_hk416b`] = Config.WeaponClasses['HIGH_CALIBER'],
    --[[ MEDIUM CALIBER ]]
    [`WEAPON_uzi`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mac10`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mp9`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mp5`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`weapon_vector`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    --[[ SMALL CALIBER ]]
    [`WEAPON_browning`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M4a1`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M45a1`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_dp9`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_g18c`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_glock22`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_p226`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_tec9`] = Config.WeaponClasses['SMALL_CALIBER'],
    --[[ CUTTING ]]
    [`WEAPON_riftedge`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KATANA`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_krambit`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_sword`] = Config.WeaponClasses['CUTTING'],
    --[[ HEAVY IMPACT ]]
    [`WEAPON_dildo`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`WEAPON_keyboard`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`weapon_sledgehammer`] = Config.WeaponClasses['HEAVY_IMPACT'],
    --[[Explosives]]--
    [`WEAPON_M67`] = Config.WeaponClasses['EXPLOSIVE'],
    --[[ Shotguns ]]--
    [`WEAPON_BEANBAG`] = Config.WeaponClasses['SHOTGUN'],
```
# ADD THIS IN BACKITEMS.LUA IF USING DEVYN-BACKITEMS 

```
    ["weapon_groza"] = {
        model="w_ar_groza",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_draco"] = {
        model="w_ar_draco",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_uzi"] = {
        model="w_sb_uzi",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_mp9"] = {
        model="w_sb_mp9",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_gepard"] = {
        model="w_ar_gepard",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_mac10"] = {
        model="w_sb_mac10",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_katana"] = {
	model="w_me_katana",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_sword"] = {
	model="w_me_sword",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_dildo"] = {
	model="w_me_dildo",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_sledgehammer"] = {
	model="w_me_sledgehammer",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_riftedge"] = {
	model="w_me_riftedge",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_keyboard"] = {
	model="w_me_keyboard",
	back_bone = 24818,
	x = -0.2,
	y = -0.15,
	z = 0.12,
	x_rotation = 0.0,
	y_rotation = -120.0,
	z_rotation = 180.0,
    },
    ["weapon_beanbag"] = {
        model="w_sg_beanbag",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_m4"] = {
        model="w_ar_m4",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["WEAPON_HK416B"] = {
        model="w_ar_HK416B",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    
```

## ADD THIS IN ps-dispatch/client/cl_events.lua (IF USING OLD PS-DISPATCH)

```
-- GD-Weapons
    [GetHashKey("weapon_groza")] = "CLASS 3: GROZA",
    [GetHashKey("weapon_hk416b")] = "CLASS 3: GROZA",
    [GetHashKey("weapon_gepard")] = "CLASS 3: GEPARD",
    [GetHashKey("weapon_draco")] = "CLASS 3: DRACO",
    [GetHashKey("weapon_browning")] = "CLASS 2: BROWNING",
    [GetHashKey("weapon_dp9")] = "CLASS 2: DP9",
    [GetHashKey("weapon_g18c")] = "CLASS 2: GLOCK-18C",
    [GetHashKey("weapon_glock22")] = "CLASS 2: GLOCK-20",
    [GetHashKey("weapon_m4a1")] = "CLASS 1: M4A1"
    [GetHashKey("weapon_m45a1")] = "CLASS 1: M4A1",
    [GetHashKey("weapon_mac10")] = "CLASS 2: Mac-10",
    [GetHashKey("weapon_uzi")] = "CLASS 2: Uzi",
    [GetHashKey("weapon_mp9")] = "CLASS 2: MP9",
    [GetHashKey("weapon_mp5")] = "CLASS 2: MP5",
    [GetHashKey("weapon_m67")] = "CLASS 69: M67 GRENADE",
    [GetHashKey("weapon_vector")] = "CLASS 2: KRISS VECTOR",
    [GetHashKey("weapon_hk416b")] = "CLASS 3: HK416-B",
    [GetHashKey("weapon_hk416b")] = "CLASS 1: P226",
    [GetHashKey("weapon_hk416b")] = "CLASS 1: TEC9",

```
## Drop the next code in qb-weapons/config.lua (about line 209)

```
    ['WEAPON_m45a1'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M45A1_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_M45A1_CLIP_02',
            item = 'pistol_extendedclip',
            type = 'clip',
        },
        ['suppressor'] = {
            component = 'COMPONENT_M45A1_SUPP_01',
            item = 'pistol_suppressor',
        },
        ['flashlight'] = {
            component = 'COMPONENT_M45A1_FLSH_01',
            item = 'pistol_suppressor',
        },
    },

```

## ADD THIS IN QB-CORE/SHARED/ITEMS.LUA                      (ADD THIS IF YOU USING COMPONENTS)

```
['m45a1_defaultclip'] 			 = {['name'] = 'm45a1_defaultclip', 			['label'] = 'M45A1 Clip', 				['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pistol_extendedclip.png', 	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'm45a1 Default Clip'},

['m45a1_extendedclip'] 		 = {['name'] = 'm45a1_extendedclip', 			['label'] = 'M45A1 EXT Clip', 			['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pistol_extendedclip.png', 	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'm45a1 Extended Clip'},

['m45a1_flashlight'] 			 = {['name'] = 'm45a1_flashlight', 			['label'] = 'M45A1 Flashlight', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'smg_flashlight.png', 		['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'm45a1 Flashlight Attachment'},

['m45a1_suppressor'] 			 = {['name'] = 'm45a1_suppressor', 			['label'] = 'M45A1 Suppressor', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'pistol_suppressor.png', 	['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'm45a1 Suppressor Attachment'},
```