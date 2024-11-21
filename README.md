local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()

local window = DrRayLibrary:Load("Realms", "Default")

local tab = DrRayLibrary.newTab("spawns de sukunas", "ImageIdHere")

tab.newButton("Localização 1 ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(1399.80786, 208.634399, 244.210449, 0, 0, 1, 0, 1, -0, -1, 0, 0)


end)


tab.newButton("Localização 2 ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(953.485718, 151.55249, 764.883362, 1, 0, 0, 0, 1, 0, 0, 0, 1)


end)


tab.newButton("Localização 3 ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-1091.63513, 52.5531311, 248.785355, 1, 0, 0, 0, 1, 0, 0, 0, 1)


end)



tab.newButton("Localização 4  ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-726.785217, 75.5533905, 417.265808, 1, 0, 0, 0, 1, 0, 0, 0, 1)

end)


tab.newButton("Localização 5", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-451.975983, 75.8533936, 201.065796, 1, 0, 0, 0, 1, 0, 0, 0, 1)


end)



tab.newButton("Localização 6 ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-599.835144, 75.95327, 724.71582, 1, 0, 0, 0, 1, 0, 0, 0, 1)


end)



tab.newButton("Localização 7 ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-674.385193, 75.3533936, 558.765808, 1, 0, 0, 0, 1, 0, 0, 0, 1)

end)

local tab = DrRayLibrary.newTab("Orbs quase infinita", "ImageIdHere")

tab.newButton("orb infinita ", "", function()
    
local player = game.Players.LocalPlayer
local character = player.Character

character.HumanoidRootPart.CFrame = CFrame.new(-6787.4917, 906.900085, 326.271973, 1, 0, 0, 0, 1, 0, 0, 0, 1)

end)




local tab = DrRayLibrary.newTab("Outros", "ImageIdHere")



tab.newButton("Infinite yield ", "", function()
    
loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()

end)



