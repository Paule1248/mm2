# MM2 Coin Farmer Script

A simple but powerful **coin farming script** for **Murder Mystery 2**.

This script runs entirely without a UI — just configure the settings in the script, execute it, and let it do the work.  
It’s designed to use **very little CPU**, making it perfect for long farming sessions or running multiple accounts.

---

## 🔧 Features

- ✅ Fully automatic coin farming
- 💤 Built-in Anti-AFK
- 🧠 Smart, configurable behavior
- ♻️ Auto-rejoin support
- 💾 Super low CPU usage (perfect for background farming)
- 🛠️ No UI — fully config-based for performance

---

## ⚙️ Configuration Example

Simply paste the full script into your executor. You can adjust the config at the top:

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
		["Auto Craft"] = false, -- not implemented yet
	},
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/Paule1248/mm2/refs/heads/main/script.lua"))()
