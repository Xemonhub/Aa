game:GetService("RunService").RenderStepped:connect(function()
for i,v in next, (game:GetService("Players"):GetPlayers()) do
    if v.Name ~= game:GetService("Players").LocalPlayer.Name then
    v.Character.HumanoidRootPart.Size = Vector3.new(25,25,25)
    v.Character.HumanoidRootPart.Transparency = 0.5
    v.Character.HumanoidRootPart.CanCollide = false
    end
end
