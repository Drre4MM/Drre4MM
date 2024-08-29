local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "DRE4M HUB", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]
local Tab = Window:MakeTab({ Name = "BLOX FRUIT", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]  Tab:AddButton({ Name = "AUTO FARM 1", Callback = function() loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-BEST-FREE-AUTOFARM-16383"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "AUTO FARM 2", Callback = function() loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-Stingray-Keyless-Autofarm-11278"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "AUTO FARM 3", Callback = function() loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-Stingray-Keyless-Autofarm-17241"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "HOHO HUB", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "OMG HUB", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ORG-hubb/ORG/main/ORG-Hub.lua"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "HIRU HUB", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NGUYENVUDUY1/V3PRO/main/main.lua"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "REDZ HUB", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "YTB HUB", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/KhanhTranVan/Guest/main/thankforbuying"))() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "BLADE BALL", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]
Tab:AddButton({ Name = "AUTO PARRY", Callback = function() loadstring(game:HttpGet("https://scriptblox.com/raw/UPD-Blade-Ball-op-autoparry-with-visualizer-8652"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "TRASH REAL", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mc4121ban/trashscript/main/chaotic.lua"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "GHOSTWARE", Callback = function() 
loadstring(game:HttpGet(('https://raw.githubusercontent.com/Exohacks/Ghostware-/main/Ghostware-V1'),true))()
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
local Tab = Window:MakeTab({ Name = "PRISON LIFE", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]] 
Tab:AddButton({ Name = "PRISONWARE v1.3 (THE BEST)", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "PC COMMAND", Callback = function()
loadstring(game:HttpGet('https://freenote.biz/raw/ZcYw0XR8lW'))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "NEXUS HUB", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GwnStefano/NexusHub/main/Main", true))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "TIGER ADMIN", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/dalloc2/Roblox/main/TigerAdmin.lua"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
local Tab = Window:MakeTab({ Name = "BROOK HAVEN", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]
Tab:AddButton({ Name = "SANDER X", Callback = function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/kigredns/sanderXNewVersion/main/sanderX')))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "G HUB", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/exterauser/exteraHub/main/Loader", true))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "ICE HUB", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
local Tab = Window:MakeTab({ Name = "MM2", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]
Tab:AddButton({ Name = "X HUB", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "NEXUS", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/s-0-a-b/nexus/main/loadstring"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "R3TH PRIV", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/zxclua/m/main/script"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "AUTO FARM EGG", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/eggs/main/MM2"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "ATHER HUB(NEED KEY)", Callback = function() 
loadstring(game:HttpGet("https://rawscripts.net/raw/Murder-Mystery-2-AtherHub-17204"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
local Tab = Window:MakeTab({ Name = "TPS", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]
Tab:AddButton({ Name = "تحذير فقط شغل الريتش لا تشغل شي ثاني لتجنب الباند!", Callback = function() end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
Tab:AddButton({ Name = "STREET SOCCER HUB", Callback = function() 
loadstring(game:HttpGet('https://raw.githubusercontent.com/hussain1323232234/My-Scripts/main/Street%20Soccer'))()end
Tab:AddButton({ Name = "WERSTON HUB", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Wreston00/tpsreach/main/tpsreach.lua"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]
local Tab = Window:MakeTab({ Name = "PIT SIMULATOR", Icon = "rbxassetid://4483345998", PremiumOnly = false }) --[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]
Tab:AddButton({ Name = "REDZ HUB", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()end
}) --[[ Name = - The name of the button. Callback = - The function of the button. ]]

