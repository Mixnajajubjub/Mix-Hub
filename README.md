-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Textlabel = Instance.new("TextLabel")
local TextButton_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")

--Properties:

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.Position = UDim2.new(0, 0, 0.0666666701, 0)
TextLabel.Size = UDim2.new(0, 420, 0, 50)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "None"
TextLabel.TextColor3 = Color3.fromRGB(85, 255, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true


ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
Frame.BackgroundTransparency = 0.050
Frame.Position = UDim2.new(0.144942641, 0, 0.161520183, 0)
Frame.Size = UDim2.new(0, 420, 0, 450)

UICorner.Parent = Frame

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 49, 49)
TextButton.Position = UDim2.new(0.928571463, 0, -0.0222222228, 0)
TextButton.Size = UDim2.new(0, 40, 0, 40)
TextButton.Font = Enum.Font.Jura
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextWrapped = true

TextButton.MouseButton1Click:Connect(function()
	ScreenGui:Destroy()
end)

UICorner_2.CornerRadius = UDim.new(0, 26)
UICorner_2.Parent = TextButton

Textlabel.Name = "Text label"
Textlabel.Parent = Frame
Textlabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Textlabel.BackgroundTransparency = 1.000
Textlabel.Size = UDim2.new(0, 118, 0, 30)
Textlabel.Font = Enum.Font.SourceSans
Textlabel.Text = "Mix Hub"
Textlabel.TextColor3 = Color3.fromRGB(255, 255, 255)
Textlabel.TextScaled = true
Textlabel.TextSize = 14.000
Textlabel.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(111, 111, 111)
TextButton_2.Position = UDim2.new(0, 0, 0.226666674, 0)
TextButton_2.Size = UDim2.new(0, 420, 0, 50)
TextButton_2.Font = Enum.Font.Unknown
TextButton_2.Text = "King lagacy"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_3.Parent = TextButton_2

TextButton_2.MouseButton1Click:Connect(function()
	TextLabel.Text = "King lagacy"
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(111, 111, 111)
TextButton_3.Position = UDim2.new(0, 0, 0.808888853, 0)
TextButton_3.Size = UDim2.new(0, 420, 0, 50)
TextButton_3.Font = Enum.Font.Unknown
TextButton_3.Text = "All star"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UICorner_4.Parent = TextButton_3

TextButton_3.MouseButton1Click:Connect(function()
	TextLabel.Text = "All star"
	pcall(function()
		loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
	end)
end)

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(111, 111, 111)
TextButton_4.Position = UDim2.new(0, 0, 0.617777765, 0)
TextButton_4.Size = UDim2.new(0, 420, 0, 50)
TextButton_4.Font = Enum.Font.Unknown
TextButton_4.Text = "Pet sim x"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_5.Parent = TextButton_4
TextButton_4.MouseButton1Click:Connect(function()
	TextLabel.Text = "Pet sim x Key:Mango_RAINDROPW" 
	getgenv().WaterMark = true
	loadstring(game:HttpGet("https://gitlab.com/L1ZOT/mango-hub/-/raw/main/Mango-Bloxf-Fruits-Beta"))()
end)

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(111, 111, 111)
TextButton_5.Position = UDim2.new(0, 0, 0.422222197, 0)
TextButton_5.Size = UDim2.new(0, 420, 0, 50)
TextButton_5.Font = Enum.Font.Unknown
TextButton_5.Text = "Blox fruit"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true

UICorner_6.Parent = TextButton_5

TextButton_5.MouseButton1Click:Connect(function()
	TextLabel.Text = "Blox fruit"
	loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
end)

local UIS = game:GetService('UserInputService')
local frame = Frame
local dragToggle = nil
local dragSpeed = 0.2
local dragStart = nil
local startPos = nil

local function updateInput(input)
	local delta = input.Position - dragStart
	local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
		startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
end

frame.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
		dragToggle = true
		dragStart = input.Position
		startPos = frame.Position
		input.Changed:Connect(function()
			if input.UserInputState == Enum.UserInputState.End then
				dragToggle = false
			end
		end)
	end
end)

UIS.InputChanged:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
		if dragToggle then
			updateInput(input)
		end
	end
end)
