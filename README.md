    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("MG's selling GUI!", "DarkTheme")

    -- MAIN

    local Tab = Window:NewTab("Drop")
    local TeleportSection = Tab:NewSection("Teleport")


    TeleportSection:NewButton("Admin base", "Teleports you to admin base", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-871, -32.6511879, -653, 1, 3.00921847e-08, -1.0841502e-13, -3.00921847e-08, 1, -6.15630498e-08, 1.0656245e-13, 6.15630498e-08, 1)
    end)

    TeleportSection:NewButton("Bank", "Teleports you to bank", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-374.8406066894531, 21.24999237060547, -338.3810119628906)

    end)

    TeleportSection:NewButton("School", "Teleports you to School", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-602.6137084960938, 21.24999237060547, 191.7030792236328)

    end)

    TeleportSection:NewButton("Island", "Teleports you to an Island", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(212.7666778564453, 38.2499885559082, 200024.328125)
    end)

    TeleportSection:NewButton("UFO", "Teleports you to UFO", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(70.93927001953125, 139, -692.035400390625)
    end)

    TeleportSection:NewButton("Basketball", "Teleports you to Basketball", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-865.0587158203125, 43.99983596801758, -482.22698974609375)
    end)

    TeleportSection:NewButton("Train", "Teleports you to train", function()
        local a={"OneMoreTime","CHECKER_1","TeleportDetect"}local b;b=hookmetamethod(game,"__namecall",function(...)local c={...}local self,d,e=c[1],getnamecallmethod(),getcallingscript()if d=="FireServer"and self==game.ReplicatedStorage.MainEvent and table.find(a,c[2])then return end;return b(...)end)
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(636.33740234375, 48, -86.77622985839844)
    end)

    local Tab = Window:NewTab("Cash stuff")
    local CashSection = Tab:NewSection("Cash")

    CahSection:NewDropdown("DropdownText", "DropdownInf", {"Option 1", "Option 2", "Option 3"}, function(currentOption)
        print(currentOption)
    end)
    
