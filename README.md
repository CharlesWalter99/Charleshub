
local GUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/aaaa"))()

local UI = GUI:CreateWindow("CharlesHub_ | Pet Simulator","UI made by Charles#4156")
-----------------------------------------------------
local lib = require(game.ReplicatedStorage:WaitForChild('Framework'):WaitForChild('Library'))
-----------------------------------------------------
local Credits = UI:addPage("Credits",1,true,6)
Credits:addLabel("|| Credits ||")
Credits:addButton(" Delete GUI ",function()
    game.CoreGui:FindFirstChild("fu8rj82n"):Destroy()
    lib.Message.New("Thanks For Using"); 
end)
Credits:addButton(" Discord ",function()
 setclipboard("Charles#4156")
game.StarterGui:SetCore("SendNotification",{
            Title = "Discord";
            Text = "copy successfully (Charles#4156)";
end)
Credits:addLabel("Update :")
Credits:addLabel("|| Anti AFK Always ON ||")
Credits:addLabel(" ","Credit by CharlesHub")

-----------------------------------------------------

local Main = UI:addPage("Main",2,true,6)

Main:addToggle("Auto Collect Lootbags",function(value)
    if value == false then
        loadstring(game:HttpGet"https://pastebin.com/raw/adqnNAZ3")()
    else
        loadstring(game:HttpGet"https://pastebin.com/raw/adqnNAZ3")()
    end
end)

--Anti AFK
loadstring(game:HttpGet"https://pastebin.com/raw/AEAK1HNY")()
