local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/huy9999xxx/huy9999xxx/main/hub')))()
local Window = OrionLib:MakeWindow({Name = "Key System Advanced", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})



local Tab = Window:MakeTab({
	Name = "Check",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "Enter Key",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		KeyInput = Value
	end	  
})



Tab:AddButton({
	Name = "Check Key",
	Callback = function()
        Checkkey()
  	end    
})

Tab:AddParagraph("Auto Anti By Fron | Pass"," ")

getgenv().KeyInput = "string"

function CheckKey()
    if sf_key == KeyInput then
        local Window = OrionLib:MakeWindow({Name = "Key System Advanced", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
        end
end
loadstring(game:HttpGet("https://raw.githubusercontent.com/allhubz/huy9999xxx/main/..lua", true))()
