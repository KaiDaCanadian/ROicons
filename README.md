ROicons is an easy-to-use module for Roblox. It contains the Asset ID for plenty of Instance icons.  
Let's suppose we want the icon for the `Workspace` service.
```lua
local IconModule = require(ModulePath)

local assetId = IconModule:GetIcon(game.Workspace)

print(assetId)
```
Output:
```
rbxassetid://2672148178
```
Badda-boom, badda-bang. You can use this ID inside of an ImageLabel if you so please.
![kaboom](https://i.imgur.com/sAfAEzo.png)

***

# Usage
## GetIcon ( userdata Object | string ClassName )
> Accepts an Instance or string with the specified ClassName as its one argument.  
Returns: string
## GetClass ( string AssetId )
> Returns the ClassName of a specified AssetId (must be one of the images). Elsewise, returns "Unknown".  
Returns: string

***

Right now, I cannot guarantee that every icon is included. This is only the beginning of this project and everything is subject to change.  
You can find the module [here](https://www.roblox.com/library/2673116933/Roblox-Icon-Module). Feel free to use any assets you like!
