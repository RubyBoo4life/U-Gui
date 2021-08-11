-- Ultimate Gui

-- Version 4.0.0

local UltimateGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TowerOfHell = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local AutoFarm = Instance.new("TextButton")
local RayCodeX = Instance.new("TextButton")
local RayCodeXCashDropper = Instance.new("TextButton")
local MurderMystery = Instance.new("TextButton")
local PetSimX1 = Instance.new("TextButton")
local PetSimX2 = Instance.new("TextButton")
local TextLabel_9 = Instance.new("TextLabel")
local VGHub = Instance.new("TextButton")

--Properties:

UltimateGui.Name = "UltimateGui"
UltimateGui.Parent = game.CoreGui
UltimateGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = UltimateGui
Main.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
Main.Position = UDim2.new(0.301464915, 0, 0.247852758, 0)
Main.Size = UDim2.new(0, 514, 0, 410)
Main.Draggable = true
Main.Active = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
TextLabel.Size = UDim2.new(0, 514, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Ultimate Gui"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.389105052, 0, 1, 0)
TextLabel_2.Size = UDim2.new(0, 114, 0, 30)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Version: 1.0.0"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
TextLabel_3.Position = UDim2.new(0, 0, 0.878048778, 0)
TextLabel_3.Size = UDim2.new(0, 514, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Made By RubyBoo4life"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

ScrollingFrame.Parent = Main
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
ScrollingFrame.Position = UDim2.new(0.023346303, 0, 0.141463414, 0)
ScrollingFrame.Size = UDim2.new(0, 490, 0, 293)

TowerOfHell.Name = "TowerOfHell"
TowerOfHell.Parent = ScrollingFrame
TowerOfHell.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
TowerOfHell.Position = UDim2.new(0.295243382, 0, 0.0772423074, 0)
TowerOfHell.Size = UDim2.new(0, 200, 0, 50)
TowerOfHell.Font = Enum.Font.SourceSans
TowerOfHell.Text = "GHUB  FREE"
TowerOfHell.TextColor3 = Color3.fromRGB(255, 255, 255)
TowerOfHell.TextScaled = true
TowerOfHell.TextSize = 14.000
TowerOfHell.TextWrapped = true
TowerOfHell.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/garfield%20hub", true))()
end)

TextLabel_4.Parent = ScrollingFrame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TextLabel_4.Position = UDim2.new(0, 0, 0.790243924, 0)
TextLabel_4.Size = UDim2.new(0, 477, 0, 50)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Adopt Me"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

TextLabel_5.Parent = ScrollingFrame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TextLabel_5.Position = UDim2.new(-0.00408163248, 0, 0.5597561, 0)
TextLabel_5.Size = UDim2.new(0, 477, 0, 50)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Pet Simulator X"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

TextLabel_6.Parent = ScrollingFrame
TextLabel_6.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TextLabel_6.Position = UDim2.new(0, 0, 0.408536583, 0)
TextLabel_6.Size = UDim2.new(0, 477, 0, 50)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "Murder Mystery 2"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextWrapped = true

TextLabel_7.Parent = ScrollingFrame
TextLabel_7.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TextLabel_7.Size = UDim2.new(0, 477, 0, 50)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Tower Of Hell"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextScaled = true
TextLabel_7.TextSize = 14.000
TextLabel_7.TextWrapped = true

TextLabel_8.Parent = ScrollingFrame
TextLabel_8.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TextLabel_8.Position = UDim2.new(0, 0, 0.171951219, 0)
TextLabel_8.Size = UDim2.new(0, 477, 0, 50)
TextLabel_8.Font = Enum.Font.SourceSans
TextLabel_8.Text = "Da Hood"
TextLabel_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.TextScaled = true
TextLabel_8.TextSize = 14.000
TextLabel_8.TextWrapped = true

AutoFarm.Name = "AutoFarm"
AutoFarm.Parent = ScrollingFrame
AutoFarm.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
AutoFarm.Position = UDim2.new(0.280957669, 0, 0.332120419, 0)
AutoFarm.Size = UDim2.new(0, 200, 0, 50)
AutoFarm.Font = Enum.Font.SourceSans
AutoFarm.Text = "Auto Farm"
AutoFarm.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoFarm.TextScaled = true
AutoFarm.TextSize = 14.000
AutoFarm.TextWrapped = true
AutoFarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/rapnz/scripts/master/DaHoodFarm.lua"))()
end)

RayCodeX.Name = "RayCodeX"
RayCodeX.Parent = ScrollingFrame
RayCodeX.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
RayCodeX.Position = UDim2.new(0.0462637804, 0, 0.250216335, 0)
RayCodeX.Size = UDim2.new(0, 200, 0, 50)
RayCodeX.Font = Enum.Font.SourceSans
RayCodeX.Text = "RAYCODEX"
RayCodeX.TextColor3 = Color3.fromRGB(255, 255, 255)
RayCodeX.TextScaled = true
RayCodeX.TextSize = 14.000
RayCodeX.TextWrapped = true
RayCodeX.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://5812737894")[1].Source)()
end)

RayCodeXCashDropper.Name = "RayCodeXCashDropper"
RayCodeXCashDropper.Parent = ScrollingFrame
RayCodeXCashDropper.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
RayCodeXCashDropper.Position = UDim2.new(0.523814797, 0, 0.250511408, 0)
RayCodeXCashDropper.Size = UDim2.new(0, 200, 0, 50)
RayCodeXCashDropper.Font = Enum.Font.SourceSans
RayCodeXCashDropper.Text = "RAYCODEX Cash Dropper"
RayCodeXCashDropper.TextColor3 = Color3.fromRGB(255, 255, 255)
RayCodeXCashDropper.TextScaled = true
RayCodeXCashDropper.TextSize = 14.000
RayCodeXCashDropper.TextWrapped = true
RayCodeXCashDropper.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/Raycodex/Exploiting/main/Roblox/Da%20Hood%20Auto%20Cash%20Drop"), true))()
end)

MurderMystery.Name = "MurderMystery"
MurderMystery.Parent = ScrollingFrame
MurderMystery.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
MurderMystery.Position = UDim2.new(0.295243382, 0, 0.480900824, 0)
MurderMystery.Size = UDim2.new(0, 200, 0, 50)
MurderMystery.Font = Enum.Font.SourceSans
MurderMystery.Text = "Vynixu's MM2 Script"
MurderMystery.TextColor3 = Color3.fromRGB(255, 255, 255)
MurderMystery.TextScaled = true
MurderMystery.TextSize = 14.000
MurderMystery.TextWrapped = true
MurderMystery.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

PetSimX1.Name = "PetSimX1"
PetSimX1.Parent = ScrollingFrame
PetSimX1.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
PetSimX1.Position = UDim2.new(0.280957639, 0, 0.635582268, 0)
PetSimX1.Size = UDim2.new(0, 200, 0, 50)
PetSimX1.Font = Enum.Font.SourceSans
PetSimX1.Text = "Pet Simulator X 1"
PetSimX1.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimX1.TextScaled = true
PetSimX1.TextSize = 14.000
PetSimX1.TextWrapped = true
PetSimX1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/95HthyJq"))()
end)

PetSimX2.Name = "PetSimX2"
PetSimX2.Parent = ScrollingFrame
PetSimX2.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
PetSimX2.Position = UDim2.new(0.276876062, 0, 0.710267484, 0)
PetSimX2.Size = UDim2.new(0, 200, 0, 50)
PetSimX2.Font = Enum.Font.SourceSans
PetSimX2.Text = "Pet Simulator X 2"
PetSimX2.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimX2.TextScaled = true
PetSimX2.TextSize = 14.000
PetSimX2.TextWrapped = true
PetSimX2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://system-exodus.com/scripts/PetSimulator/PetSimulatorX.lua", true))()
end)

TextLabel_9.Parent = ScrollingFrame
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.Position = UDim2.new(-0.00104820193, 0, 0.709047973, 0)
TextLabel_9.Size = UDim2.new(0, 139, 0, 50)
TextLabel_9.Font = Enum.Font.SourceSans
TextLabel_9.Text = "Recommended -->"
TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_9.TextScaled = true
TextLabel_9.TextSize = 14.000
TextLabel_9.TextWrapped = true

VGHub.Name = "VGHub"
VGHub.Parent = ScrollingFrame
VGHub.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
VGHub.Position = UDim2.new(0.295243382, 0, 0.866266727, 0)
VGHub.Size = UDim2.new(0, 200, 0, 50)
VGHub.Font = Enum.Font.SourceSans
VGHub.Text = "V.G Hub"
VGHub.TextColor3 = Color3.fromRGB(255, 255, 255)
VGHub.TextScaled = true
VGHub.TextSize = 14.000
VGHub.TextWrapped = true
VGHub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)
