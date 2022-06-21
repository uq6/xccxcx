-- GUI to Lua
-----
-- Version: 2.0.
-- Made by chrisopdemobiel.

-- Instances:

local Notification = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local Text = Instance.new("TextLabel")

--Properties:

Notification.Name = "Notification"
Notification.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Notification.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Notification.BackgroundTransparency = 0.500
Notification.BorderSizePixel = 0
Notification.Position = UDim2.new(-1, 0, 0.99000001, -26)
Notification.Size = UDim2.new(0, 361, 0, 26)

TextLabel.Parent = Notification
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.017399583, 0, 0.115384616, 0)
TextLabel.Size = UDim2.new(0, 61, 0, 19)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Azure Ware"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0, Color3.fromRGB(255, 85, 0)), ColorSequenceKeypoint.new(0, Color3.fromRGB(85, 255, 255)), ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = TextLabel

Text.Name = "Text"
Text.Parent = Notification
Text.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Text.BackgroundTransparency = 1.000
Text.BorderSizePixel = 0
Text.Position = UDim2.new(0.186374649, 0, 0.115384616, 0)
Text.Size = UDim2.new(0, 264, 0, 19)
Text.Font = Enum.Font.SourceSans
Text.Text = ""
Text.TextColor3 = Color3.fromRGB(255, 255, 255)
Text.TextScaled = true
Text.TextSize = 14.000
Text.TextWrapped = true
