kalisblack = {
Targetthing = {

User = "user here",
Enabled = true
  }
}

local target = kalisblack.Targetthing.User

while kalisblack.Targetthing.Enabled == true do
    task.wait()


game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0, 8, 0)

game.Players.LocalPlayer.Character.Humanoid.Sit = true
end 
getgenv().u = true

local target = "Player Name"

while getgenv().u == true do
    task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0, 8, 0)
game.Players.LocalPlayer.Character.Humanoid.Sit = true
end 
