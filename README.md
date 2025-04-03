local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/Star-dos-scripts/OrionLibYellow/refs/heads/main/README.md')))()')))()
local Window = OrionLib:MakeWindow({Name = "Star Hub : Acesso Antecipado", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Beta Test",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "StarHub",
	Callback = function()
      		setclipboard("Em breve")
  	end    
})
