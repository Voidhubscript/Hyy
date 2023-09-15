repo = "https://scripts.luawl.com/hosted/5055/21534/load_er.lua'))()
if game.PlaceId == 2753915549 or game.PlaceId == 4442272183 or game.PlaceId == 7449423635 then
loadstring(game:HttpGet('https://'..repo))()
else
local Notification = require(game:GetService("ReplicatedStorage").Notification)
Notification.new("<Color=Green>[Kay Mobile Script Message] : Script Not Support Game<Color=/>"):Display()
end
