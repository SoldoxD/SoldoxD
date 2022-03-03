--Made By Cyber MoDz

--Beta

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Label = Instance.new("TextLabel")
local Esp = Instance.new("TextButton")
local Aimbot = Instance.new("TextButton")
local TR1V5 = Instance.new("TextButton")
local Gamepass = Instance.new("TextButton")
local BLACKGAMER = Instance.new("TextButton")
local MadLads = Instance.new("TextButton")
local TurkOyuncu = Instance.new("TextButton")
local GodMode = Instance.new("TextButton")
local AutoRob = Instance.new("TextButton")
local XpFarm = Instance.new("TextButton")
local infiniteyield = Instance.new("TextButton")
local Test = Instance.new("TextButton")
local Exit = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(139, 17, 19)
Main.Position = UDim2.new(0.637965679, 0, 0.493573248, 0)
Main.Size = UDim2.new(0, 468, 0, 237)
Main.Active = true
Main.Draggable = true


Label.Name = "Label"
Label.Parent = Main
Label.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Label.Size = UDim2.new(0, 468, 0, 26)
Label.Font = Enum.Font.SciFi
Label.Text = "Cyber MoDz  Mad City Gui"
Label.TextColor3 = Color3.fromRGB(255, 116, 118)
Label.TextSize = 14.000

Esp.Name = "Esp"
Esp.Parent = Main
Esp.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Esp.Position = UDim2.new(0.027777778, 0, 0.219409287, 0)
Esp.Size = UDim2.new(0, 93, 0, 29)
Esp.Font = Enum.Font.SciFi
Esp.Text = "ESP"
Esp.TextColor3 = Color3.fromRGB(255, 116, 118)
Esp.TextSize = 14.000
Esp.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/2dgeneralspam1/cheatx/main/cheatx%20loader'))()
end)


Aimbot.Name = "Aimbot"
Aimbot.Parent = Main
Aimbot.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Aimbot.Position = UDim2.new(0.252136767, 0, 0.219409287, 0)
Aimbot.Size = UDim2.new(0, 93, 0, 29)
Aimbot.Font = Enum.Font.SciFi
Aimbot.Text = "Aimbot"
Aimbot.TextColor3 = Color3.fromRGB(255, 116, 118)
Aimbot.TextSize = 14.000
Aimbot.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)


TR1V5.Name = "TR1V5"
TR1V5.Parent = Main
TR1V5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TR1V5.Position = UDim2.new(0.027777778, 0, 0.493670881, 0)
TR1V5.Size = UDim2.new(0, 93, 0, 29)
TR1V5.Font = Enum.Font.SciFi
TR1V5.Text = "TR1V5"
TR1V5.TextColor3 = Color3.fromRGB(255, 116, 118)
TR1V5.TextSize = 14.000
TR1V5.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/tr1vvvv/main/README.md",true))()
end)


Gamepass.Name = "Gamepass"
Gamepass.Parent = Main
Gamepass.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Gamepass.Position = UDim2.new(0.68589741, 0, 0.219409287, 0)
Gamepass.Size = UDim2.new(0, 93, 0, 29)
Gamepass.Font = Enum.Font.SciFi
Gamepass.Text = "Gamepass"
Gamepass.TextColor3 = Color3.fromRGB(255, 116, 118)
Gamepass.TextSize = 14.000
Gamepass.MouseButton1Down:connect(function()
	local gamepasses = {5275404, 5275406, 5275408, 5283883, 5285945, 5786950,5945566,5981868}
	for _,v in next, gamepasses do
		if not game.Players.LocalPlayer:FindFirstChild(tostring(v)) then
			local l = Instance.new("BoolValue", game.Players.LocalPlayer)
			l.Name = tostring(v)
			l.Value = true
		end
	end
end)


BLACKGAMER.Name = "BLACKGAMER"
BLACKGAMER.Parent = Main
BLACKGAMER.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BLACKGAMER.Position = UDim2.new(0.252136767, 0, 0.493670881, 0)
BLACKGAMER.Size = UDim2.new(0, 93, 0, 29)
BLACKGAMER.Font = Enum.Font.SciFi
BLACKGAMER.Text = "Blackgamer"
BLACKGAMER.TextColor3 = Color3.fromRGB(255, 116, 118)
BLACKGAMER.TextSize = 14.000
BLACKGAMER.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/devpulco/bandlans/main/README.md"))()
end)


MadLads.Name = "Mad Lads"
MadLads.Parent = Main
MadLads.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MadLads.Position = UDim2.new(0.467948735, 0, 0.493670881, 0)
MadLads.Size = UDim2.new(0, 93, 0, 29)
MadLads.Font = Enum.Font.SciFi
MadLads.Text = "Mad-Lads"
MadLads.TextColor3 = Color3.fromRGB(255, 116, 118)
MadLads.TextSize = 14.000
MadLads.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/DevPuclo/Mad-ladsvv7/main/README.md",true))()
end)


TurkOyuncu.Name = "TurkOyuncu"
TurkOyuncu.Parent = Main
TurkOyuncu.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TurkOyuncu.Position = UDim2.new(0.68589741, 0, 0.493670881, 0)
TurkOyuncu.Size = UDim2.new(0, 93, 0, 29)
TurkOyuncu.Font = Enum.Font.SciFi
TurkOyuncu.Text = "TurkOyuncu"
TurkOyuncu.TextColor3 = Color3.fromRGB(255, 116, 118)
TurkOyuncu.TextSize = 14.000
TurkOyuncu.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/811e25ec8cfcdaa9ae7026353288783c/raw/4b073a5c1a0a4e2ed7e2304c2e769eb440a371a9/h", true))()
end)


GodMode.Name = "God Mode"
GodMode.Parent = Main
GodMode.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GodMode.Position = UDim2.new(0.467948735, 0, 0.219409287, 0)
GodMode.Size = UDim2.new(0, 93, 0, 29)
GodMode.Font = Enum.Font.SciFi
GodMode.Text = "God Mode"
GodMode.TextColor3 = Color3.fromRGB(255, 116, 118)
GodMode.TextSize = 14.000
GodMode.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/DevPuclo/Choupremev4.1/main/README.md",true))()
end)


AutoRob.Name = "Auto Rob"
AutoRob.Parent = Main
AutoRob.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoRob.Position = UDim2.new(0.0277777314, 0, 0.763713062, 0)
AutoRob.Size = UDim2.new(0, 93, 0, 29)
AutoRob.Font = Enum.Font.SciFi
AutoRob.Text = "Auto-Rob"
AutoRob.TextColor3 = Color3.fromRGB(255, 116, 118)
AutoRob.TextSize = 14.000
AutoRob.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://system-exodus.com/scripts/madcity/MadLadsAR.lua",true))()
end)


XpFarm.Name = "Xp Farm"
XpFarm.Parent = Main
XpFarm.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
XpFarm.Position = UDim2.new(0.252136737, 0, 0.763713062, 0)
XpFarm.Size = UDim2.new(0, 93, 0, 29)
XpFarm.Font = Enum.Font.SciFi
XpFarm.Text = "Xp Farm"
XpFarm.TextColor3 = Color3.fromRGB(255, 116, 118)
XpFarm.TextSize = 14.000
XpFarm.MouseButton1Down:connect(function()
	game:GetService("ReplicatedStorage").RemoteFunction:InvokeServer("SetTeam", "Police")
	wait(.75)
	game:GetService("RunService").RenderStepped:Connect(function()
		for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
			if v.Name == "Handcuffs" then v.Parent = game:GetService("Players").LocalPlayer.Character
			end
		end
		game:GetService("ReplicatedStorage").Event:FireServer("Eject", game:GetService("Players").LocalPlayer)
	end)
end)


infiniteyield.Name = "infinite yield"
infiniteyield.Parent = Main
infiniteyield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
infiniteyield.Position = UDim2.new(0.467948675, 0, 0.763713062, 0)
infiniteyield.Size = UDim2.new(0, 93, 0, 29)
infiniteyield.Font = Enum.Font.SciFi
infiniteyield.Text = "infinite yield"
infiniteyield.TextColor3 = Color3.fromRGB(255, 116, 118)
infiniteyield.TextSize = 14.000
infiniteyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)



Test.Name = "Test"
Test.Parent = Main
Test.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Test.Position = UDim2.new(0.68589741, 0, 0.763713062, 0)
Test.Size = UDim2.new(0, 93, 0, 29)
Test.Font = Enum.Font.SciFi
Test.Text = "Test print"
Test.TextColor3 = Color3.fromRGB(255, 116, 118)
Test.TextSize = 14.000
Test.MouseButton1Down:connect(function()
	print(test)
end)


Exit.Name = "Exit"
Exit.Parent = Main
Exit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Exit.Position = UDim2.new(0.91452992, 0, 0, 0)
Exit.Size = UDim2.new(0, 40, 0, 26)
Exit.Font = Enum.Font.SciFi
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(255, 0, 4)
Exit.TextSize = 14.000
Exit.MouseButton1Down:connect(function()
	Main:Destroy()
end)
