local textureId = "140155130942333"

function replaceTextures()
    for _, part in pairs(game.Workspace:GetDescendants()) do
        if part:IsA("BasePart") then
            local decal = Instance.new("Decal")
            decal.Texture = textureId
            decal.Parent = part
        end
    end
end

replaceTextures()
