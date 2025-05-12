local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/DenDenZZZ/Kavo-UI-Library/main/Kavo.lua"))()
 
local Window = Library.CreateLib("pXxRupertxXp's Scripts hub", "Ocean")
 
local Tab = Window:NewTab("Dead-Rails")
 
local Section = Tab:NewSection("DeadRails")
 
Section:NewKeybind("F", "Toggles The Ui", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
 
Section:NewToggle("Superhuman (use in other game)", "see the flash ", function(state)
    if state then
        game.Players.LocalPlayers.Character.Humanoid.WalkSpeed = 120
        game.Players.LocalPlayers.Character.Humanoid.JumpPower = 120
    else
        game.Players.LocalPlayers.Character.Humanoid.JumpPower = 120
        game.Players.LocalPlayers.Character.Humanoid.WalkSpeed = 120
    end
end)
 
Section:NewSlider("Sliderp", "increase slide speed lol", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
 
=
 
Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()
	print("You just clicked the bind")
end)
 
 
 
local oldList = {
  "2019",
  "2020"
}
local newList = {
  "2021",
  "2022"
}
 
Section:NewButton("SpiderXHub", "useful script with no key", function()
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/SpiderScriptRB/V2.0.9/refs/heads/main/Dead%20Rails%20No%20key%20system%20V2.0.9.txt"))()
end)
 
 
Section:NewButton("Nathub", "Keyless autobonds", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdyBotzz/NatHub/refs/heads/master/NatHub.lua"))();
end)
 
Section:NewButton("Native Hub", "Good Script with key", function()
    script_key="PASTE YOUR KEY HERE"
 
loadstring(game:HttpGet("https://getnative.cc/script/loader"))()
end)
 
Section:NewButton("Markk Hub ", "Very op Hub idk if it has key", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Markklol/AnimalSimulator/refs/heads/main/DRails.lua"))()
end)
