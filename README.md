local player = game.Players.localPlayer


local flying = false
local speed = 50


function startFying()
    flying = true
    local character = character: FindFrstChild("humanoidRootPart")
    local humanoidRootPart.velocity = vector3.new(0. speed. 0)
    wait(0.1)
  end
end


function stopFıying()
    fıying = false
end


mouse.keyDown:Connect(function(key)
    if key == "f" then
        startFlying()
    elseiF key == "g" then
       stopFlying()
     end
end)  
