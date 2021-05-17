local ui = game:GetService("CoreGui"):FindFirstChild("FluxLib")
if ui then
    ui:Destroy()
end
local Flux = loadstring(game:HttpGet"https://raw.githubusercontent.com/DookDekDEE/gui/main/fairyhub.txt")()

local win = Flux:Window("Bitcoin Miner", "Kotaro HUB", Color3.fromRGB(199, 211, 70) ,Enum.KeyCode.RightAlt)
local tab = win:Tab("Warp", "http://www.roblox.com/asset/?id=6034989568")

tab: Button("bank","",function()
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(243.920776, 5.49768353, 81.3991241)
    end)            
    tab: Button("cave 1","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(132.778763 ,16.225565, -244.233521)
    end) 
    tab: Button("cave 2","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28.6981182, 16.3179283, -234.749008)
    end) 
    tab: Button("Alux","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-137.887878, 32.9293709, -233.855896)
    end) 
    tab: Button("DanT","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-160.835556, 33.0175858, -215.061813)
    end)
    tab: Button("Plot Shop","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(170.810501, 5.24790668, 225.491776)
    end)

    ----- HOME -----

    local tab = win:Tab("HOME", "http://www.roblox.com/asset/?id=6034989568")
    tab: Button("HOME 1 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(86.1605148, 7.33906269, 108.971672)
    end)    
    tab: Button("HOME 2 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(83.8635559, 7.33906269, 202.822754)
    end)    
    tab: Button("HOME 3 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9.90247345, 14.7354794, 205.031006)
    end)    
    tab: Button("HOME 4 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8.95652103, 7.33906269, 116.674469)
    end)   
    tab: Button("HOME 5 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8.54488087, 21.3408871, 34.0580788)
    end)     
    tab: Button("HOME 6 ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(86.3304596, 16.1863956, 28.075285)
    end)     
    local tab = win:Tab("MICS", "http://www.roblox.com/asset/?id=6034989568")
    tab:Slider("Walkspeed", "",16,200,0,function(value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value
    end)
    tab:Slider("JumpPower", "",50,200,0,function(value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = value
    end)    
    ------ EVENT ------
    local tab = win:Tab("EVENT", "http://www.roblox.com/asset/?id=6034989568")
    tab: Button("Fish GOD ","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-41.7222099, 8.39990234, -43.9591484)
    end)     
    tab: Button("BIT 2 EVENT","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(187.242218, 5.24800396, 177.212158)
    end)
    ----- Word 2 -----
    local tab = win:Tab("Word 2 ", "http://www.roblox.com/asset/?id=6034989568")
    tab: Button("Warp to Word 2 ","",function ()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3.78164053, -19.3132896, 326.091705)
    end)
