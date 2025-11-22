# CONFIG
```lua
Config = {
    Storage = "json", -- oxmysql/json

    Identifier = "steam", -- discord/steam/license

    Json = { -- if Storage = oxmysql ignore this
        File = "data.json", -- location of json
        AutoCreate = true -- auto creates if file isn't there
    },

    MySQL = {
        AutoInsert = false, -- Auto Inserts SQL so you don't need to add the tables or if there not found
    },

    SaveTimer = {
        SaveEvery = 30 -- How long before you want the players load out to save.
    },

    Debug = false -- Normally do not touch
}
```
