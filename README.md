<h1 align="center">RichPresence - RichPresence fivem </h1>
<em><h5 align="center">(Programming Language - lua)</h5></em>

## Installation

## Add To Shared.lua
```
['gym_membership'] 					 = {['name'] = 'gym_membership', 			 	  	  	['label'] = 'Gym membership', 						['weight'] = 0, 		['type'] = 'item', 		['image'] = 'gym_membership.png', 				['unique'] = true, 		['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = nil,   ['description'] = 'Carnet del gym fachero'},
```

## Configuration
```

Config = {}

Config.UpdateFrequency = 3600 
Config.DeleteStats = true 

Config.MmbershipCardPrice = 200

Config.Skills = {
    ["resistance"] = { 
        ["Current"] = 20, 
        ["RemoveAmount"] = -0.3, 
        ["Stat"] = "MP0_STAMINA" 
    },

    ["strength"] = {
        ["Current"] = 10, ["RemoveAmount"] = -0.3, ["Stat"] = "MP0_STRENGTH"
    },

    ["diving"] = {
        ["Current"] = 0, ["RemoveAmount"] = -0.3, ["Stat"] = "MP0_LUNG_CAPACITY"
    },

    ["shooting"] = {
        ["Current"] = 0, ["RemoveAmount"] = -0.1,["Stat"] = "MP0_SHOOTING_ABILITY"
    },

    ["driving"] = {
        ["Current"] = 0, ["RemoveAmount"] = -0.5, ["Stat"] = "MP0_DRIVING_ABILITY"
    },

    ["Raise front wheel"] = {
        ["Current"] = 0, ["RemoveAmount"] = -0.2, ["Stat"] = "MP0_WHEELIE_ABILITY"
    }
}
```
```
Config.Locations = {
    [1] = {--pull-ups
        coords = vector3(-1200.02, -1571.18, 4.61), heading = 215.53, type = "pull-ups",
        animation = "prop_human_muscle_chin_ups", skill = "resistance", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Do Pull-ups]", viewDistance = 2.5,
    },
    [2] = {--arms
        coords = vector3(-1202.9837, -1565.1718, 4.63115), heading = 212.78, type = "arms",
        animation = "world_human_muscle_free_weights", skill = "strength", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Use weights]", viewDistance = 2.5,
    },
    [3] = {--pushup
        coords = vector3(-1203.3242, -1570.6184, 4.631155), heading = 212.78, type = "pushup",
        animation = "world_human_push_ups", skill = "strength", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Do push-ups]", viewDistance = 2.5,
    },
    [4] = {--yoga
        coords = vector3(-1204.7958, -1560.1906, 4.63115), heading = 212.78, type = "yoga",
        animation = "world_human_yoga", skill = "resistance", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Do yoga]", viewDistance = 2.5,
    },
    [5] = {--yoga
        coords = vector3(-1221.04, -1545.01, 4.69), heading = 212.78, type = "yoga",
        animation = "world_human_yoga", skill = "resistance", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Do yoga]", viewDistance = 3.5,
    },
    [6] = {--yoga
        coords = vector3(-1217.09, -1543.43, 4.72), heading = 212.78, type = "yoga",
        animation = "world_human_yoga", skill = "resistance", SkillAddQuantity = 1,
        Text3D = "~b~E~w~ - [Do yoga]", viewDistance = 3.5,
    },
}
```
* Drag and drop the resource into your [qb] folder and ensure it in your server.cfg `ensure qb-core`

## Issues ? 
 * [telegram](https://t.me/ATLAS_TEAMM)
 * [Issues Page](https://github.com/EBLISYALME/qb-gym/issues)
#### Like the project? Leave a star on the repository!

## Video Tutorial
* [youtube](https://www.youtube.com/channel/UCXfAdwGy2uE7qpXOpNENa1g)

## 💰 Donation Links:
#### Donate Links

<b>BTC</b>: <code>bc1q83jrdllxtsmx8r83hgtlz5m7drfwts4ykmc8su</code></br>
<b>TRX TRC20</b>: <code>TLKtBYGBt9ECbQjumAN1ms9V3TCFUw2XpB</code></br></br>
