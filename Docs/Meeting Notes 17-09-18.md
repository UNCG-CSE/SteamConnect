Meeting 9/18/2017
======

### Discussion
Group discussion about [BYU data set](https://steam.internet.byu.edu/)'s size. The BYU data set was originally thought to be only 17GB, which turned out to be compressed, and was actually ~160GB. This led to searching for possible alternatives due to not being sure if we could handle going through that amount of data. Discovered the [Steam Web API](https://developer.valvesoftware.com/wiki/Steam_Web_API) which allows access to Steam information. We applied for and received a Steam Web API key that we can use to gather the information we need, however we would then be gathering all data ourselves, which would be time consuming. 

### Steam Web API Example
Using http://api.steampowered.com/ISteamUser/GetPlayerSummaries/v0002/?key=XXXXXXXXXXXXXXXXXXXXXXX&steamids=76561197960435530 with provided key

```JSON
{
	"response": {
		"players": [
			{
				"steamid": "76561197960435530",
				"communityvisibilitystate": 3,
				"profilestate": 1,
				"personaname": "Robin",
				"lastlogoff": 1505978423,
				"profileurl": "http://steamcommunity.com/id/robinwalker/",
				"avatar": "https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/f1/f1dd60a188883caf82d0cbfccfe6aba0af1732d4.jpg",
				"avatarmedium": "https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/f1/f1dd60a188883caf82d0cbfccfe6aba0af1732d4_medium.jpg",
				"avatarfull": "https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/f1/f1dd60a188883caf82d0cbfccfe6aba0af1732d4_full.jpg",
				"personastate": 0,
				"realname": "Robin Walker",
				"primaryclanid": "103582791429521412",
				"timecreated": 1063407589,
				"personastateflags": 0,
				"loccountrycode": "US",
				"locstatecode": "WA",
				"loccityid": 3961
			}
		]
		
	}
}
```

### Goals
1. Determine if we can host the BYU data set somehow				(Geoff)
2. Practice using the Steam Web API to gather data needed		(Everyone)
3. Possibly find a Web API implementation we can use				(Geoff/Jonathan)
4. Work on the presentation for Wednesday's class						(Jonathan/Michael)
5. Continue brainstorming ideas for definite goals					(Everyone)


