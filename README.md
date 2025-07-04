# MM2 Coin Farmer Script

A powerful and simple coin farming script for **Murder Mystery 2**.  

## 🔧 Features

- Automatic Farming
- Anti-AFK included
- Easy to use and configure
- Supports auto-rejoin after rounds

## 📁 Script Example

```lua
getgenv().Config = {
	--["Script_Key"] = "",
	["CPU Saver"] = true,
	["Coin Farm Mode"] = 2,

	["Auto Open"] = {
		["Enabled"] = false,
		["Crate"] = "MysteryBox2",
	},

	["Webhook"] = {
		["URL"] = "",
		["UserID"] = "",
	},

	["Other"] = {
		["Auto Prestige"] = true,
		["Auto Restart on Update"] = false,
		["Auto Craft"] = false, --not implemented yet
	},
}
```
