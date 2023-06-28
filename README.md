local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/huy9999xxx/huy9999xxx/main/hub')))()
local Window = OrionLib:MakeWindow({Name = "All - Hub | Version 1", HidePremium = false, SaveConfig = true, ConfigFolder = "All - Hub"})
	
---credit
local Tab = Window:MakeTab({
	Name = "Credit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Admin | 9999xyz"," ")

Tab:AddParagraph("# Developer | Leoxion"," ")


Tab:AddParagraph("# Hub | 52 ","        ")

Tab:AddColorpicker({
	Name = "Color Change",
	Default = Color3.fromRGB(255, 0, 0),
	Callback = function(Value)
		print(Value)
	end	  
})


---main
local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "Infinite Yield",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
  	end    
})

---bloxfruit
local Tab = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})



Tab:AddParagraph("# Blox Fruit Hub","Click In Open Script !")


Tab:AddButton({
	Name = "Mukuro Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/quart"))()
  	end    
})

Tab:AddButton({
	Name = "Domadic Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
  	end    
})

Tab:AddButton({
	Name = "Mama Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/MAMAhub1/Mmahub/main/README.md"))()
  	end    
})

Tab:AddButton({
	Name = "FTSX Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet('https://raw.githubusercontent.com/tufreescript/FTS-X-Hub/main/FTSXHUB%20V1'))()	
  	end    
})

Tab:AddButton({
	Name = "CFrame Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/minded102/dokinbog/main/README.md", true))()	
  	end    
})

Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/flares"))()	
  	end    
})

Tab:AddButton({
	Name = "BLCK Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/BLCK"))()
  	end    
})

Tab:AddButton({
	Name = "MODZ Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/modz"))()
  	end    
})

Tab:AddButton({
	Name = "HoHo Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()	
  	end    
})

Tab:AddButton({
	Name = "Zen Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/Loader", true))()	
  	end    
})

Tab:AddButton({
	Name = "Switch Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/Augustzyzx/UraniumX/main/src_.lua.txt"))()	
  	end    
})

Tab:AddButton({
	Name = "Thunder Z Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-05/HUB/main/Mobile-Loader"))()	
  	end    
})

Tab:AddButton({
	Name = "Uranium Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/Augustzyzx/UraniumMobile/main/NewVersion.lua"))()	
  	end    
})

Tab:AddButton({
	Name = "BlackTrap Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet('https://raw.githubusercontent.com/S4nZz/bt_project/main/Games/BlacktrapScript.txt'))()
  	end    
})

Tab:AddButton({
	Name = "Pado Hub",
	Callback = function()
      		print("button pressed")
      	loadstring(game:HttpGet('https://raw.githubusercontent.com/REWzaKunGz1/premium/main/PadoHub'))()
  	end    
})

Tab:AddButton({
	Name = "Neva Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
  	end    
})

---GPO

local Tab = Window:MakeTab({
	Name = "GPO",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# GPO Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Xno Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/a3b7e5c6a09c14385deaf6d0350929b8.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Lazer Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/lazer"))()
  	end    
})

---Project Slayer
local Tab = Window:MakeTab({
	Name = "Project Slayers",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Project Slayers Hub ","Click In Open Script !")

Tab:AddButton({
	Name = "Versaware Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/asterionnn/versaware_free/main/VersawareFree.lua", true))()
  	end    
})

Tab:AddButton({
	Name = "Sylveon Hub",
	Callback = function()
      		print("button pressed")
        local LoaderUrl = "https://raw.githubusercontent.com/ogamertv12/SylveonHub/main/Mobile.lua"
        
        repeat wait() until game:IsLoaded()
        
        loadstring(game:HttpGet(LoaderUrl))()
  	end    
})

Tab:AddButton({
	Name = "Oni Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/01471f12f9adfd4537f4cc0b3b7bba14.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Skeereddo Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Skeereddo/name/main/krnl', true))()
  	end    
})

Tab:AddButton({
	Name = "Nuke Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/NukeVsCity/Scripts2023/main/projslayerthingy', true))()
  	end    
})

Tab:AddButton({
	Name = "Zyrc Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/mugentr"))()
  	end    
})


---pet x siuulator

local Tab = Window:MakeTab({
	Name = "Pet X Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Pet X Simulator Hub","Click In Open Script !")

Tab:AddButton({
	Name = "BlackTrap Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://blacktrap.org/blacktrap/users/checkpoint/Auth.txt"))()
  	end    
})

Tab:AddButton({
	Name = "Cloud Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/BadScripters/CloudHub/main/hub"))()
  	end    
})
Tab:AddButton({
	Name = "Huge Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://hugegames.io/psx"))()
  	end    
})

Tab:AddButton({
	Name = "Milk Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/a82cd5447cbbc4c7be0e8db405555787.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Project Z Hub",
	Callback = function()
      		print("button pressed")
        getgenv().boothsnipe = false
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Muhammad6196/Project-WD/main/Mainstring.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Changer Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/Changer"))()
  	end    
})


--all star
local Tab = Window:MakeTab({
	Name = "All Star Defense",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# All Star Tower Defense Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Karmapanda Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://script.karmapanda.dev/'))()
  	end    
})

---anime adventure
local Tab = Window:MakeTab({
	Name = "Anime Adventures",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Anime Adventures Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Arpon Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ArponAG/Scripts/main/AnimeAdventures_v2__Beta.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Trap Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/TrapstarKSSKSKSKKS/Main/main/TrapHub.lua"))()
  	end    
})

---shindo life 2
local Tab = Window:MakeTab({
	Name = "Shindo life 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Shindo life 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "ProjectNexus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/IkkyyDF/ProjectNexus/main/Loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Ski Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/Yousuck780/shindo-life/main/life"), true))()
  	end    
})

Tab:AddButton({
	Name = "Speed X Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/ahmadsgamer2/Speed-Hub-X/main/SpeedHubX"))()
  	end    
})

---King Legacy
local Tab = Window:MakeTab({
	Name = "King Legacy",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# King Legacy Hub","Click In Open Script !")

Tab:AddButton({
	Name = "BlackTrap Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://blacktrap.org/blacktrap/users/checkpoint/Auth.txt"))()
  	end    
})

Tab:AddButton({
	Name = "Speed Z Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/ahmadsgamer2/Speed-Hub-X/main/SpeedHubX"))()
  	end    
})

--- Adopt Me
local Tab = Window:MakeTab({
	Name = "Adopt Me",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Adopt Me Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Prodigy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://gitfront.io/r/ReQiuYTPL/wFUydaK74uGx/hub/raw/ReQiuYTPLHub.lua'))()
  	end    
})

Tab:AddButton({
	Name = "V.G Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
  	end    
})

Tab:AddButton({
	Name = "Ice Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://icehub.cf/IceHubLoader'))()
  	end    
})

Tab:AddButton({
	Name = "Speed Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/ahmadsgamer2/Script--Game/main/Script%20Game"))()
  	end    
})

--- Shadow Boxing Battles
local Tab = Window:MakeTab({
	Name = "Shadow Boxing Battles",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Shadow Boxing Battles Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Trey's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xtrey10x/xtrey10x-hub/main/shadow"))()
  	end    
})

Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/ShadowBoxing"))()
  	end    
})



--- Anime Warriors Simulator 2
local Tab = Window:MakeTab({
	Name = "Anime Warriors Simulator 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Anime Warriors Simulator 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Platinum Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ZaRdoOx/Loader/main/PlatiniumLoader"))()
  	end    
})

Tab:AddButton({
	Name = "Unnamed Hub",
	Callback = function()
      		print("button pressed")
        getgenv().key = "GoGetALife";
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Ner0ox/sexy-script-hub/main/Loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Verny Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/666dasdlolok/VernyHubV2/main/Main"))()
  	end    
})

Tab:AddButton({
	Name = "Jumble Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://jumblescripts.com/AnimeWarriorsSimulator2.lua"))()
  	end    
})


--- Wisteria 2
local Tab = Window:MakeTab({
	Name = "Wisteria 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Wisteria 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Kidachi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/KidichiHB/Kidachi/main/Scripts/Wisteria", true))()
  	end    
})

Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/wisteria2script"))()
  	end    
})

Tab:AddButton({
	Name = "Jumble Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://jumblescripts.com/JumbleHub.lua"))()
  	end    
})



--- The Strongest Battlegrounds
local Tab = Window:MakeTab({
	Name = "The Strongest Battlegrounds",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# The Strongest Battlegrounds Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Nicuse Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/SaitamaBattlegrounds.lua"))()
  	end    
})

Tab:AddButton({
	Name = "LHYT Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/blobgord"))()
  	end    
})

Tab:AddButton({
	Name = "Nex Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CopyReal/NexHub/main/NexHubLoader"))()
  	end    
})



--- MM2 
local Tab = Window:MakeTab({
	Name = "MM2 ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# MM2  Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Kidachi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/KidichiHB/Kidachi/main/Scripts/MM2", true))()
  	end    
})



--- Door
local Tab = Window:MakeTab({
	Name = "Door ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Door  Hub","Click In Open Script !")

Tab:AddButton({
	Name = "MSDOORS Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/mstudio45/MSDOORS/main/MSDOORS.lua"),true))()
  	end    
})

Tab:AddButton({
	Name = "Entity Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/plamen6789/UtilitiesHub/main/UtilitiesGUI'))()
  	end    
})

Tab:AddButton({
	Name = "Nerd Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/MrNeRD0/Doors-Hack/main/DoorsV3_ByNerd.lua"))()
  	end    
})



--- My Restaurant
local Tab = Window:MakeTab({
	Name = "My Restaurant",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# My Restaurant  Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Restaurant Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Rafacasari/roblox-scripts/main/mr.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Entity Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/plamen6789/UtilitiesHub/main/UtilitiesGUI'))()
  	end    
})

Tab:AddButton({
	Name = "wYn's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://system-exodus.com/scripts/MyRestaurant/MyRestaurant.lua", true))()
  	end    
})


Tab:AddButton({
	Name = "Milk Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://pastebin.com/raw/uBpUr2vU"))()
  	end    
})

Tab:AddButton({
	Name = "Project WD Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Muhammad6196/Project-WD/main/Mainstring.lua"))()
  	end    
})



--- Bizarre Adventure
local Tab = Window:MakeTab({
	Name = "Bizarre Adventure",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Bizarre Adventure Hub","Click In Open Script !")

Tab:AddButton({
	Name = "CuHub Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ItachiPvPUchiha/CuHub/main/yba.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Yba Cus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/TheFarowHywolf/YBA-Midnight-script/master/YBA.lua"))()
  	end    
})

Tab:AddButton({
	Name = "YBA 3 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/zakater5/LuaRepo/main/YBA/v3.lua"))()
  	end    
})


--- FRUIT WARRIORS
local Tab = Window:MakeTab({
	Name = "FRUIT WARRIORS",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# FRUIT WARRIORS Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Noob Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/NOOBHUBX/Game/main/Loading"))()
  	end    
})

Tab:AddButton({
	Name = "Yba Cus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/TheFarowHywolf/YBA-Midnight-script/master/YBA.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Hyper Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/DookDekDEE/All-Script/main/fw.lua"))()
  	end    
})


Tab:AddButton({
	Name = "Project Nexus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/IkkyyDF/ProjectNexus/main/Loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Zaque Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Mei2232/ZaqueHub/main/Fruit%20Warrior"))()
  	end    
})


Tab:AddButton({
	Name = "Enhanced Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/XO-3S-CL-VCK-jf-3HDM/Products/main/Fruit-Warriors.lua"))()
  	end    
})

Tab:AddButton({
	Name = "PurpleCat Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SmellLikeHacker/MyEdit/main/Hub"))()
  	end    
})


--- Fruit Battlegrounds
local Tab = Window:MakeTab({
	Name = "Fruit Battlegrounds",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Fruit Battlegrounds Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Jumble Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JumbleBumble/Scripts/main/FruitBattlegrounds.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Kater Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/KATERGaming/Roblox/main/KaterHub.Lua"))()
  	end    
})

Tab:AddButton({
	Name = "Red Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/54ef37f65a9ce1ee8f1936718a90d656.lua"))()
  	end    
})


--- Bloxburg 
local Tab = Window:MakeTab({
	Name = "Bloxburg",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Bloxburg Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Vedrox Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://vedrox.hold4564.de/new/merge/loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Scar Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/PainfulDestroyer/Roblox/main/Bloxburg"))()
  	end    
})

Tab:AddButton({
	Name = "Lux Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://luxhub.cc/script.lua'))()
  	end    
})

Tab:AddButton({
	Name = "Dev Hub",
	Callback = function()
      		print("button pressed")
        loadstring(http_request({Url="https://projectillusion.dev/beta/illusion/script.lua",Method="GET"}).Body)()
  	end    
})




--- Tower Defense Simulator 
local Tab = Window:MakeTab({
	Name = "Tower Defense Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Tower Defense Simulator Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Nicuse Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/TowerDefenseSimulator.lua', true))()
  	end    
})

Tab:AddButton({
	Name = "Scow's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/scowscripts/scowsscripts/main/TDS_PlaceAnything/Script", true))()
  	end    
})

Tab:AddButton({
	Name = "Vtds Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://pastebin.com/raw/DhTUJt1q"))()
  	end    
})

Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/TDSSS"))()
  	end    
})





--- Bee Swarm
local Tab = Window:MakeTab({
	Name = "Bee Swarm",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Bee Swarm Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Kometa Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://s.kometa.ga/kometa.lua'))()
  	end    
})

Tab:AddButton({
	Name = "Pepsi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:GetObjects("rbxassetid://4384103988")[0X1].Source)("Pepsi Swarm")
  	end    
})

Tab:AddButton({
	Name = "Histy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Histy"))()
  	end    
})




--- Arcane Odyssey
local Tab = Window:MakeTab({
	Name = "Arcane Odyssey",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Arcane Odyssey Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Muimi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/bunnynwy/games/main/main.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Kidachi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://kidachi.xyz/Odyssey', true))()
  	end    
})

Tab:AddButton({
	Name = "Auto Fish Hub",
	Callback = function()
      		print("button pressed")
        getgenv().toggle=true
        getgenv().fixedloc=true
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Disttt/-Arcane-Odyssey/main/AutoFish.lua"))()
  	end    
})


Tab:AddButton({
	Name = "Anya's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyouranya/free/main/arcaneodyssey.lua'),true))()
  	end    
})

Tab:AddButton({
	Name = "Jumble Hub",
	Callback = function()
      		print("button pressed")
        _G.wl_key = '26fd35f8f5e1046e9015a1435282b3b6a8e31383'
        loadstring(game:HttpGet('https://jumblescripts.com/JumbleHub.lua'))()
  	end    
})




--- Breaking Point
local Tab = Window:MakeTab({
	Name = "Breaking Point",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Breaking Point Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Buster Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ColdStep2/Breaking-Point-Funny-Squid-Hax/main/Breaking%20Point%20Funny%20Squid%20Hax",true))()
  	end    
})

Tab:AddButton({
	Name = "Outlaws Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/MostafaXc00dy/MostafaXc00dy/main/Outlaws%20Hub/Breaking%20Point%20V7.lua"))()
  	end    
})


--- ZO ぞ
local Tab = Window:MakeTab({
	Name = "ZO ぞ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# ZO ぞ Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Best Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://github.com/VanillaDeveloper/ZoDestroyer/blob/main/ZoWareV3.lua?raw=true"))():Init();
  	end    
})

Tab:AddButton({
	Name = "Xgamer626 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xgamerman626/ZO/main/Source/Runtime.lua"))()
  	end    
})



---  Slap Battles
local Tab = Window:MakeTab({
	Name = "Slap Battles",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Slap Battles Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Dizzy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/rbx_scripts/main/dizzy_hub/scripts/slap_battles.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Rogue Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Kitzoon/Rogue-Hub/main/Main.lua", true))()
  	end    
})



---  Build A Boat
local Tab = Window:MakeTab({
	Name = "Build A Boat",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Build A Boat Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Boat Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "NooVSter's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/NooVster/v1.1/main/Source'))()
  	end    
})

Tab:AddButton({
	Name = "Exe Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/XRoLLu/UWU/main/BUILD%20A%20BOAT%20FOR%20TREASURE.lua'))()
  	end    
})

Tab:AddButton({
	Name = "Rogue Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Kitzoon/Rogue-Hub/main/Main.lua", true))()
  	end    
})



--- Bedwars 
local Tab = Window:MakeTab({
	Name = "Bedwars",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Bedwars Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Amberware Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Technoraids/Amberware/main/RobloxTelanthricBedwars"))()
  	end    
})

Tab:AddButton({
	Name = "Vape V4 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
  	end    
})



--- Pls Donate 
local Tab = Window:MakeTab({
	Name = "Pls Donate",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Pls Donate Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Best Farm Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/tzechco"))()
  	end    
})

Tab:AddButton({
	Name = "Fake Donations Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/o5u3/PLS-Donate/main/Fake-Donate.lua")))()
  	end    
})


Tab:AddButton({
	Name = "Trolling Features Sign Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://pastebin.com/Z2smW4z5"))()
  	end    
})




--- Da Hood 
local Tab = Window:MakeTab({
	Name = "Da Hood",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Da Hood Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Nyula Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/nyulachan/nyula/main/nyuladhm", true))()
  	end    
})

Tab:AddButton({
	Name = "Paradox Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/para"))()
  	end    
})


Tab:AddButton({
	Name = "Venom v1.0 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Venomscript/Venom/main/1.0'))()
  	end    
})

Tab:AddButton({
	Name = "Space Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/spacexrandom/Lua/main/DaHood", true))()
  	end    
})

Tab:AddButton({
	Name = "Enclosed Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Haihellos/skidded-enclosed-gui/main/message.txt"))()
  	end    
})


--- Pixel Piece 
local Tab = Window:MakeTab({
	Name = "Pixel Piece",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Pixel Piece Hub","Click In Open Script !")

Tab:AddButton({
	Name = "MUIMI Hub",
	Callback = function()
      		print("button pressed")
        _G.Auto_Load_Config = false
        loadstring(game:HttpGet("https://raw.githubusercontent.com/bunnynwy/games/main/pixelpiece"))()
  	end    
})

Tab:AddButton({
	Name = "Amanize Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Kiriko-Protection/Scripts/main/Pixel-Piece.lua'))() 
  	end    
})

Tab:AddButton({
	Name = "Winnable Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xlostpexz/tyuiop/Fps/Loading.lua"))()
  	end    
})

Tab:AddButton({
	Name = "SoggyWare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://soggy-ware.cf"))()
  	end    
})



--- Big Paintball
local Tab = Window:MakeTab({
	Name = "Big Paintball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Big Paintball Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Eternity Hub",
	Callback = function()
      		print("button pressed")
        local a="https://eternityhub.xyz/Script"local b=a.."/Eternity.lua"loadstring(game:HttpGet(b))()
  	end    
})

Tab:AddButton({
	Name = "BEST Big Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/radjahfromdiscord/iNEXT/main/source"))()
  	end    
})

Tab:AddButton({
	Name = "Dark Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/LeakMaster/Dark-Hub-V4.1/main/Big_Paintball.lua"))()
  	end    
})

Tab:AddButton({
	Name = "SoggyWare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://soggy-ware.cf"))()
  	end    
})



--- Project New World
local Tab = Window:MakeTab({
	Name = "Project New World",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Project New World Hub","Click In Open Script !")

Tab:AddButton({
	Name = "SoggyWare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://www.soggy-ware.cf"))()
  	end    
})

Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/PJNewWorld"))()
  	end    
})

Tab:AddButton({
	Name = "Verny Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/666dasdlolok/PNW/main/Main",true))();
  	end    
})

Tab:AddButton({
	Name = "Platnum Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ZaRdoOx/Platinium/main/Loader"))()
  	end    
})


Tab:AddButton({
	Name = "Winnable Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xlostpexz/tyuiop/Fps/Loading.lua"))()
  	end    
})



--- Phantom Forces
local Tab = Window:MakeTab({
	Name = "Phantom Forces",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Phantom Forces Hub","Click In Open Script !")

Tab:AddButton({
	Name = "BEST ESP Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ic3w0lf22/Unnamed-ESP/master/UnnamedESP.lua"))()
  	end    
})

Tab:AddButton({
	Name = "AIMWARE Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Wheeleee/AIMWARE/main/Startup"))()
  	end    
})

Tab:AddButton({
	Name = "Ski Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Yousuck780/phantom-forces-new/main/noob"))()
  	end    
})

Tab:AddButton({
	Name = "V.G Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
  	end    
})


Tab:AddButton({
	Name = "Unlock All Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/VoidMasterX/Releases/main/PF_UnlockAll.lua"))();
  	end    
})



--- Driving Empire
local Tab = Window:MakeTab({
	Name = "Driving Empire",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Driving Empire Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Midnight Racing Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync'https://raw.githubusercontent.com/GXNATION/Main-script/main/Main%20hub')();
  	end    
})

Tab:AddButton({
	Name = "Pearl Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://ppearl.vercel.app'))()
  	end    
})

Tab:AddButton({
	Name = "SoggyWare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://www.soggy-ware.cf"))()
  	end    
})




--- Anime Dimensions Simulator
local Tab = Window:MakeTab({
	Name = "Anime Dimensions Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Anime Dimensions Simulator Hub","Click In Open Script !")

Tab:AddButton({
	Name = "PhanTom Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/destylol/masterhubv311/itachi/Main.lua"))()
  	end    
})


Tab:AddButton({
	Name = "Intruders Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://www.intruders.ga/AutoExec.html"))()
  	end    
})



--- Funky Friday
local Tab = Window:MakeTab({
	Name = "Funky Friday",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Funky Friday Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Infinite Points Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/botbrostopusing/NEW-HUB/main/README.md'))()
  	end    
})


Tab:AddButton({
	Name = "Winstreak Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ZoinkyPoinkie/FunkyFridayDevTools/main/Un-Obfuscated",true))()
  	end    
})


Tab:AddButton({
	Name = "Purple Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://pastebin.com/raw/eQXzG0EB"))()
  	end    
})


Tab:AddButton({
	Name = "Wally Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/funkyfriday"))()
  	end    
})



--- Islands 
local Tab = Window:MakeTab({
    Name = "Islands",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Islands Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Project Z Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://scripts.luawl.com/12802/IslandsScriptFREE.lua'))()
  	end    
})


Tab:AddButton({
	Name = "Neko Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://nekoscripts.xyz/neko/Scripts/Key.lua"))()
  	end    
})



--- Flee The Facility 
local Tab = Window:MakeTab({
    Name = "Flee The Facility",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Flee The Facility Hub","Click In Open Script !")

Tab:AddButton({
	Name = "V.G Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
  	end    
})


Tab:AddButton({
	Name = "Arctic Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://paste.ee/r/Q2ekT/0"))()
  	end    
})

Tab:AddButton({
	Name = "Fleeware Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifty96/ftfgui/main/ftfgui", true))()
  	end    
})


Tab:AddButton({
	Name = "TheScriptBoi Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/khoaScript/scripts/master/flee-the-facility.lua"))()
  	end    
})



--- KAT
local Tab = Window:MakeTab({
    Name = "KAT",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# KAT Hub","Click In Open Script !")

Tab:AddButton({
	Name = "King Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/zReal-King/King-Hub-v2/main/Loader.lua'))()
  	end    
})


Tab:AddButton({
	Name = "Unfair Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/unfair/main/rblxhub.lua'),true))()
  	end    
})

Tab:AddButton({
	Name = "DG Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Margman/whynot/main/Knife%20Ability%20Test%202022"))()
  	end    
})


Tab:AddButton({
	Name = "Lime Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/lxnnydev/PublicScripts/main/limexkat.lua'),true))()
  	end    
})


--- Sharkbite 2
local Tab = Window:MakeTab({
    Name = "Sharkbite 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Sharkbite 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Shattered Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://shattered-gang.lol/scripts/sharkbite_2.lua"))()
  	end    
})


Tab:AddButton({
	Name = "VIPE Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/SleeksScripts/Sharkbite-2-script/main/Script'))()
  	end    
})

Tab:AddButton({
	Name = "Bruh Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/samuelrblx/Bruhnhe/main/Hub"))()
  	end    
})


Tab:AddButton({
	Name = "Catware Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://catware.vercel.app", true))()
  	end    
})


--- Booga Booga
local Tab = Window:MakeTab({
    Name = "Booga Booga",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Booga Booga Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Booga WW Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/booga-booga12/main/waterwalk"))()
  	end    
})


Tab:AddButton({
	Name = "Onion Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://pastebin.com/raw/MGDBXaS7',true))()
  	end    
})

Tab:AddButton({
	Name = "Flushed Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CheeseOnGithub/scripts/main/bb2019.lua",true))()
  	end    
})


Tab:AddButton({
	Name = "HaXx Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/ooga-booga/main/2019%20booga"))()
  	end    
})


-- Football Fusion 2
local Tab = Window:MakeTab({
    Name = "Football Fusion 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Football Fusion 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "FF2 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/FootbalFusion2/main/NewFusion2"))()
  	end    
})


Tab:AddButton({
	Name = "Lazzy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/LonleyWolf1988/http-www.lazzyexploits.tk-/main/FF2"), true))()
  	end    
})

Tab:AddButton({
	Name = "FF2 Black Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/SlimLegoHacks/Scripts/main/FootballFusion.lua')))()
  	end    
})

-- Mining Simulator 2
local Tab = Window:MakeTab({
    Name = "Mining Simulator 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Mining Simulator 2 Hub","Click In Open Script !")

Tab:AddButton({
	Name = "PhanTom Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/destylol/masterhubv311/itachi/Main.lua"))()
  	end    
})


Tab:AddButton({
	Name = "Beluse Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/beliveri12/BeluseHub/main/Loader.lua', true))()
  	end    
})

Tab:AddButton({
	Name = "Project Lightning Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ProjectLightningDev/Project-Lightning-Loader/main/Loader.Lua"))()
  	end    
})

Tab:AddButton({
	Name = "System Exodus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://system-exodus.com/scripts/MiningSimulator/MiningSimulator2.lua", true))()
  	end    
})


Tab:AddButton({
	Name = "Vestra Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xandudiscord/vestra/main/loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Zeerox Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet'https://raw.githubusercontent.com/RunDTM/miningsim2/main/rewrite.lua')()

  	end    
})

Tab:AddButton({
	Name = "Galaxy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptsByJoel/Galaxy-Hub-Scripts/main/Hub-Loadstring-Places",true))()
  	end    
})


Tab:AddButton({
	Name = "Versus Airlines Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://gitlab.com/Ner0ox/versus/-/raw/main/LoaderV2/Loader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Adminus Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/flerci42/AdminusKeySystem/main/Obfuscated"))()
  	end    
})


-- Evade 
local Tab = Window:MakeTab({
    Name = "Evade",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# Evade Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Evade Hydra Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/Robobo2022/script/main/Main.lua"), true))()
  	end    
})


Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/nocturno"))()
  	end    
})

Tab:AddButton({
	Name = "Hamsta Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Babyhamsta/RBLX_Scripts/main/Evade/main.lua"))()
  	end    
})


-- SHADOVIS RPG 
local Tab = Window:MakeTab({
    Name = "SHADOVIS RPG",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("# SHADOVIS RPG Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Bruh SounDeffect Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/BruhSoundEffect2081/BruhScripts/main/ShadovisRPG.lua'))()
  	end    
})


Tab:AddButton({
	Name = "Flare Hub",
	Callback = function()
      		print("button pressed")
      	repeat wait() until game:IsLoaded()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/LioK251/RbScripts/main/shadovis_rpg.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Soggy Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://soggyhubv2.vercel.app"))()
  	end    
})


--  A One Piece Game 
local Tab = Window:MakeTab({
    Name = "A One Piece Game",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  A One Piece Game Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Mukuro Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/quart"))()
  	end    
})


Tab:AddButton({
	Name = "6Foot Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://www.6footscripts.com/Scripts/6FootHub/Hub.lua'))();
  	end    
})

Tab:AddButton({
	Name = "UZU Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://rawscripts.net/raw/loader_1038"))()
  	end    
})

Tab:AddButton({
	Name = "LAZY Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/laff"))()
  	end    
})


--  Race Clicker 
local Tab = Window:MakeTab({
    Name = "Race Clicker",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  Race Clicker Hub","Click In Open Script !")

Tab:AddButton({
	Name = "BEST Farm Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/boomcacas/androminome/main/hub"))()
  	end    
})


Tab:AddButton({
	Name = "Red Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe2/ToraIsMe2/main/%40race", true))()
  	end    
})

Tab:AddButton({
	Name = "Ultra Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ZaRdoOx/Ultra-Hub/main/Main"))()
  	end    
})

Tab:AddButton({
	Name = "LAZY Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/laff"))()
  	end    
})


--  A Universal Time 
local Tab = Window:MakeTab({
    Name = "A Universal Time",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  A Universal Time Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Flamz Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/GodClass/EpicScripts/main/AUT%20GUI")))()
    end
})

Tab:AddButton({
	Name = "Tobias Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Tobias020108Back/YBA-AUT/main/HUB.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Spotify Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ewyzu/ewyzu-scripts/main/ewyzu-AUT"))()
  	end    
})

Tab:AddButton({
	Name = "Ball Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/johnbruhno/zzz/main/g")))()
  	end    
})

Tab:AddButton({
	Name = "Bilada Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://gist.githubusercontent.com/femboyScripting/765d76f7892ed99f332ab17b35df0f0a/raw"))()
  	end    
})


Tab:AddButton({
	Name = "Kranzyo Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Kranzyo/Scripts/main/aut%20autofarm.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Muz's Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/muzrblx/nanocores/main/Loader/HubLoader.lua"))()
  	end    
})

Tab:AddButton({
	Name = "LAZY Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Sosejikira/Sosejianaki/main/Loader'))()
  	end    
})

Tab:AddButton({
	Name = "God Mode Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(("https://aizen.ml/uploads/aut.lua")))()

  	end    
})


--  Arsenal
local Tab = Window:MakeTab({
    Name = "Arsenal",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  Arsenal Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Vestra Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/xandudiscord/vestra/main/loader.lua"))()
    end
})

Tab:AddButton({
	Name = "V.G Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
  	end    
})

Tab:AddButton({
	Name = "Unfair Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/unfair/main/rblxhub.lua'),true))()
  	end    
})

Tab:AddButton({
	Name = "Bolts Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/fusiongreg/BoltsHubV5/main/BoltsHubV5"))()
  	end    
})



--  AFS
local Tab = Window:MakeTab({
    Name = "Anime Fighter Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  Anime Fighter Simulator Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Zer0 Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Discord0000/Zer0Hub/main/MainScript.lua"))()
    end
})

Tab:AddButton({
	Name = "AFS V Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/pspboy08/dollhouse/main/AFSGUI.lua')))()
  	end    
})


--  Clicker Simulator
local Tab = Window:MakeTab({
    Name = "Clicker Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("#  Clicker Simulator Hub","Click In Open Script !")

Tab:AddButton({
	Name = "Volatile Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/tbitw2549/TbitLoader/main/Hub"))()
    end
})

Tab:AddButton({
	Name = "Mint Hub",
	Callback = function()
      		print("button pressed")
        loadstring(game:HttpGet("https://raw.githubusercontent.com/TrustsenseDev/UnknownHub-V1/main/Loader.lua"))()
  	end    
})

OrionLib:Init()
