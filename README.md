# Roblox Studio TweenService git/OpenSource
> Copy n paste or download the script if you dont know how to tween yet. This might be usefull for you.
**Made this easy to use so you can just change few texts and it should work.**
-
`If you have an issue feel free to comment.` / I am doing this to help smaller people learn and get this type of stuff quickly and for free.

![TIP]
If you wish me to script you a tweenservice for your script dont be lame and comment or ping me. I will try to help you as i am not even busy anymore.

> The script if you want to copy paste instead of downloading.
``` lua
-- Published to github by v3lvics
-- https://github.com/v3lvics/roblox-st-tween-pack-git
--[[
░█▀▀▀░░▀░░▀█▀░█░░░░█░▒█░█▀▀▄░░░░█▀▄░▄▀▀▄░█▀▄▀█░░░▄░░░▄░█▀▀█░█░░▄░░░▄░░▀░░█▀▄░█▀▀
░█░▀▄░░█▀░░█░░█▀▀█░█░▒█░█▀▀▄░▄▄░█░░░█░░█░█░▀░█░░░░█▄█░░░▒▀▄░█░░░█▄█░░░█▀░█░░░▀▀▄
░▀▀▀▀░▀▀▀░░▀░░▀░░▀░░▀▀▀░▀▀▀▀░▀▀░▀▀▀░░▀▀░░▀░░▒▀░░░░░▀░░░█▄▄█░▀▀░░░▀░░░▀▀▀░▀▀▀░▀▀▀
--]]

-- lua
local tweenservice = game:GetService("TweenService")
local tweeninfo = TweenInfo.new(3, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut)
-- how long?, How to move?, Smooth Start/End
-- Using CFrame to move.

-- Locations
local finish = {workspace.EndingPart.CFrame}
local start = {workspace.StartingPart.CFrame} -- Change to your parts.


-- Creating the tween.
local MyTweenStart = tweenservice:Create(workspace.YourPart, tweeninfo, finish)
-- Delete this if you dont want the return tween.
local MyTweenFinished = tweenservice:Create(workspace.YourPart, tweeninfo, start)

-- Your function etc.
-- Use this to start the tween - MyTweenStart:Play
```
