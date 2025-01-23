 # keep-bags-for-qbx_core-and-ox_inventory
 Bag script made by SWKeep https://github.com/swkeep
 Edited by me (includes a dev bag)

 ![ingame](https://github.com/user-attachments/assets/b87ce5fd-6e93-46e7-89b1-0d75b6e0123d)
![bagingame](https://github.com/user-attachments/assets/385c4722-46af-4685-892b-028c73c81623)

Original source of the backpack i used for the devbag
https://www.lcpdfr.com/downloads/gta5mods/character/41637-release-eup-backpack/


How To Install

STEP1
INSERT THE ITEMS INTO OX_INVENTORY

["backpack1"] = {
    label = "backpack1",
    weight = 15,
    stack = false,
    close = true,
    description = "A stylish backpack"
},

["backpack2"] = {
    label = "backpack2",
    weight = 15,
    stack = false,
    close = true,
    description = "A stylish backpack"
},

["duffle1"] = {
    label = "Duffle bag",
    weight = 15,
    stack = false,
    close = true,
    description = "A stylish duffle bag"
},

["devbag"] = {
    label = "Dev bag",
    weight = 15,
    stack = false,
    close = true,
    description = "If Found Please Return To Staff"
},

["briefcase"] = {
    label = "Briefcase",
    weight = 10,
    stack = false,
    close = true,
    description = "A portable rectangular case used for carrying important documents, files, or other personal belongings."
},

["paramedicbag"] = {
    label = "Paramedic bag",
    weight = 5,
    stack = false,
    close = true,
    description = "A medical bag used by paramedics, containing essential supplies for emergency care."
},

["policepouches"] = {
    label = "Police Pouch",
    weight = 5,
    stack = false,
    close = true,
    description = "A pouch used by police officers to store and carry essential supplies such as handcuffs, pepper spray, and other tactical equipment."
},

["policepouches1"] = {
    label = "Police Pouch",
    weight = 5,
    stack = false,
    close = true,
    description = "A larger version of the police pouch used to store additional tactical gear and equipment."
},

["briefcaselockpicker"] = {
    label = "Briefcase Lockpicker",
    weight = 0.5,
    stack = true,
    close = true,
    description = "Briefcase Lockpicker"
},



STEP2
ADD THE IMAGES FROM THE IMAGES FOLDER

STEP3
Download Keep Harmony

https://swkeep.tebex.io/package/5592482

STEP4
copy & paste or
Make Sure keep-harmony is set up exaclty as follows

--                _
--               | |
--   _____      _| | _____  ___ _ __
--  / __\ \ /\ / / |/ / _ \/ _ \ '_ \
--  \__ \\ V  V /|   <  __/  __/ |_) |
--  |___/ \_/\_/ |_|\_\___|\___| .__/
--                             | |
--                             |_|
-- https://github.com/swkeep

Config = {} or Config

------------------------------------------------------------------
-- Config
------------------------------------------------------------------
-- 🧙‍♂️ keep-harmony
-- General settings
Config.MagicTouch = false
Config.use_progressbar = true
Config.language = 'en'

-- Framework and Resource settings
Config.framework = 'qb'           -- [qb / esx]
Config.inventory = 'ox_inventory' -- [qb-inventory /  qb-inventory-legacy / ps-inventory / ox_inventory]
Config.target = 'ox_target'       -- [qb-target / ox_target]
Config.menu = 'ox_lib'          -- [built-in / qb-menu / keep-menu / ox_lib]
Config.input = 'ox_lib'         -- [built-in / qb-input /keep-input / ox_lib]
Config.progressbar = 'ox_lib'         -- [qb / ox_lib]
Config.notification = 'ox_lib'        -- [built-in / qb / esx / ox_lib / custom
Config.emote = 'scully_emotemenu'         -- [dpemotes / rpemotes / scully_emotemenu]

-- Resource Name Mapping
-- If you are using qb-inventory with a different name for instance, if you renamed it to custom-inventory,
-- you probably need to update its name here to ensure it will work!
Config.resource_names = {
    -- This is the "Resource Name" okay!
    -- I saw people who are using esx set this as esx which is wrong!
    -- It should be es_extended instead!
    framework = 'qb-core',
    inventory = 'ox_inventory',
    target = 'ox_target',
    menu = '', -- leave it empty when using built-in
    input = '' -- leave it empty when using built-in
}

-- If these are active, the built-in menu and input will take over these resources
Config.providers = {
    ['qb-menu'] = {
        active = false,
        resource_name = 'qb-menu',
    },
    ['qb-input'] = {
        active = false,
        resource_name = 'qb-input',
    }
}

-- If set to true, it will disable the logos on other scripts of mine.
-- It shows the logo once when Harmony starts, and that's about it.
Config.silentMode = true

-- If `manualDatabaseCheck` is set to true, my scripts won't check the database.
-- Most of my scripts have some sort of auto-importing SQLs into that database,
-- that won't work either, and you'll have to do everything manually!
Config.manualDatabaseCheck = false

Step 5
Add the Bag file or use the downlaod link for the original (Link at the top of the read me)


