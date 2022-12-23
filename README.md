if game.PlaceId == 6839658013 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-355.6297, 383.437683, 17.6561031, -0.99110955, -4.69867665e-08, -0.133048356, -5.42349952e-08, 1, 5.08540978e-08, 0.133048356, 5.76178572e-08, -0.99110955)
wait(10)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-355.991, 383.535, 13.8414)
wait(10)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-355.991, 383.535, 13.8414)
end

if game.PlaceId == 6840269184 then
wait(10)
local args = {
    [1] = "Vote",
    [2] = "2"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(10)
local args = {
    [1] = "Vote",
    [2] = "StartNow"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(10)
local args = {
    [1] = "Vote",
    [2] = "2"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(10)
local args = {
    [1] = "Vote",
    [2] = "StartNow"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(27)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(29)
local args = {
    [1] = "SkipWaveYes"
}

game:GetService("ReplicatedStorage").Others.Game:FireServer(unpack(args))
wait(45)
game:GetService("TeleportService"):Teleport(6839658013)
end
if game.PlaceId == 11495830780 then
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Puro hub",
    Text = "want to close gui press rightctrl",
})

wait(0.5)
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Puro Script",
    Text = "hub is loading pls wait",
})
wait(1)
-- Library

local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("AUTOFARM")

local b = w:CreateFolder("Main")
local c = w:CreateFolder("Credits")
local m = w:CreateFolder("mics")

-- Main



b:Toggle("Autofarm",function(bool)
    getgenv().Farm = bool
    
    task.spawn(function()
        while task.wait() do
            if Farm then
game:GetService("ReplicatedStorage").Remotes.DunkRequest:FireServer()
            end
        end
    end)
end)

b:Toggle("hatch one egg",function(bool)
    getgenv().hatchs = bool
    
    task.spawn(function()
        while task.wait() do
            if hatchs then
local args = {
    [1] = 1,
    [2] = {}
}

game:GetService("ReplicatedStorage").Remotes.BuyEgg:InvokeServer(unpack(args))
            end
        end
    end)
end)

b:Toggle("hatch two egg",function(bool)
    getgenv().hatchone = bool
    
    task.spawn(function()
        while task.wait() do
            if hatchone then
local args = {
    [1] = 2,
    [2] = {}
}

game:GetService("ReplicatedStorage").Remotes.BuyEgg:InvokeServer(unpack(args))
            end
        end
    end)
end)

b:Toggle("equip all pet",function(bool)
    getgenv().equip = bool
    
    task.spawn(function()
        while task.wait() do
            if Farm then
game:GetService("ReplicatedStorage").Remotes.EquipBestPets:InvokeServer()
            end
        end
    end)
end)

m:DestroyGui()


c:Label("UI : Wally UI V3",{
    TextSize = 20; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

c:Label("Made by : puro#4730",{
    TextSize = 15; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})
end
if game.PlaceId == 11656036986 then
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Puro hub",
    Text = "want to close gui press rightctrl",
})

wait(0.5)
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Puro Script",
    Text = "hub is loading pls wait",
})
wait(1)
-- Library

local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("AUTOFARM")

local b = w:CreateFolder("Main")
local c = w:CreateFolder("Credits")
local m = w:CreateFolder("mics")

-- Main



b:Toggle("Autofarm",function(bool)
    getgenv().Farm = bool
    
    task.spawn(function()
        while task.wait() do
            if Farm then
local args = {
    [1] = {
        [1] = "Release"
    }
}

game:GetService("ReplicatedStorage").Events.Game:FireServer(unpack(args))

            end
        end
    end)
end)

b:Toggle("Upgrade game Quality",function(bool)
    getgenv().GAMEQ = bool
    
    task.spawn(function()
        while task.wait() do
            if GAMEQ then
local args = {
    [1] = {
        [1] = "Buy",
        [2] = "Quality"
    }
}

game:GetService("ReplicatedStorage").Events.Upgrade:FireServer(unpack(args))
            end
        end
    end)
end)

b:Toggle("Wifi Ampifier",function(bool)
    getgenv().WIFI = bool
    
    task.spawn(function()
        while task.wait() do
            if WIFI then
local args = {
    [1] = {
        [1] = "Buy",
        [2] = "Wifi"
    }
}

game:GetService("ReplicatedStorage").Events.Upgrade:FireServer(unpack(args))
            end
        end
    end)
end)

b:Toggle("Friend Knowledge",function(bool)
    getgenv().Friend = bool
    
    task.spawn(function()
        while task.wait() do
            if Friend then
local args = {
    [1] = {
        [1] = "Buy",
        [2] = "Knowledge"
    }
}

game:GetService("ReplicatedStorage").Events.Upgrade:FireServer(unpack(args))

            end
        end
    end)
end)

m:DestroyGui()


c:Label("UI : Wally UI V3",{
    TextSize = 20; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

c:Label("Made by : puro#4730",{
    TextSize = 15; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})
end
