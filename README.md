# SteamConnect

**Amir Sadiev, Geoffrey Blech, Michael Burke, Jonathan Mills**  
**Univeristy of North Carolina - Greensboro**  
**CSC 495-01 Data Science Fall 2017**

## Goal
The overall goal of SteamConnect will be to examien and analyze Steam data gathered through various data sets and compare them to determine what genres or categories of games are more successful than others and why. This analysis will be done with mainly three major sources within Steam: early access game data, Steam's review system and the Steam Web API. Using these three, we will be able to answer questions regarding the success or failure of early access and standard release games and hopefully pinpoint the reasons behind either.

**Null Hypothesis:** There is no difference between the scores of early access games and games that have been fully released.

#### Early Access Games
SteamConnect will examine game applications listen on Steam as early access games and analyze data for each. Early access games have a somewhat negative reputation in the gaming community, as it is easy for developers to simply drop development on an early access game, leaving users with a permanently unfinished game. Our analysis will look at tags and genres of each early access game, overall and recent reviews, updates and so on. This information will be useful in finding what types of early access games are successful in comparison to others.

#### Steam Reviews
SteamConnect will actively examine and analyze Steam application reviews. Steam users may leave either a positive or negative review, with a text field open for them to further explain their thoughts on a specific game. These reviews may then be compared with application tags submitted for the games, allowing us to see which types of games are more successful than others. Steam Review Graphing will allow for specific dates to be specified, targetting large influx of reviews, reviews bombs and poorly/negatively received updates.

## Data
- Brigham Young University Steam User Data Set (2016)
- Steam Customer Review System
- Steam Web API
- SteamDB
- SteamSpy

#### Brigham Young University Data Set
The Brigham Young University data set contains information regarding applications data and user data for the year 2016. The data was gethered and used for the 2016 ACM Internet Measurement Conference article by Mark O'Neill, Justin Wu, Elham Vaziripour, and Daniel Zappala. The BYU website also has listed all of the table and attribute descriptions for the data set. It has an immense amount of information, totaling ~160gb of data.

#### Steam Customer Review System
Steam's customer review system allows users to rate games that they have played or purchased. These reviews consist of either a tumbs up or thumbs down review and a text field that allows the reviewer to further explain their reasoning. Other users are also allowed to vote whether the review is considered helpful or not to combat bogus reviews. Steam recently updated the review system, adding in a graph that depicts how reviews for games have changed over time using a bar graph. This will provide useful, as one of the intentions of SteamConnect is to examine these changes in reviews and determine the cause in the changes.

![alt text](https://i.imgur.com/EWp9Es4.png "Steam Review Graph for PUBG")

#### Steam Web API
Steam exposes an HTTP based Web API which can be used to access many Steamworks features. The API contains public methods that can be accessed from any application capable of making an HTTP request, such as game client or server. The API also contains protected methods that require authentication and are intended to be accessed from trusted back-end applications.
  
A link to the Steam Web API documentation can be found [here.](https://developer.valvesoftware.com/wiki/Steam_Web_API)

#### SteamDB Website
[SteamDB](https://steamdb.info/) is a third-party tool that was made to give better insight into the different applications that Steam has within its database. SteamDB updates in real time the moment that Steam sends its own updates to the Steam client. While SteamDB does not allow data scraping from its own website, it utilized the Steam Web API as well, so the data available on SteamDB can be manually gathered. However, SteamDB is an excellent resource for visualizations of the information given through the API. It contains many different types of graphs and statistics for applications on Steam, such as most played, trending this week, popular releases, price tracking, player count and more. It is a great resource for quick viewing and comparison of counts for specific applications, and it will prove to be useful when we inevitably begin comparing real-time current statistics for applications.
  
![alt text](https://i.imgur.com/zHwB8gi.png "Example of PUBG through SteamDB")

#### SteamSpy
[SteamSpy](https://steamspy.com/) is a third-party tool that works similarly to SteamDB, giving easy access to Steam application data through the Steam API. However, rather than focusing on visualization like SteamDB, SteamSpy focuses more on gathering relevant data and displaying it in a more accessable way, with download links for .csv files provided to use the data they gather. This makes gathering data for SteamConnect easier, as specifically tagged games, such as early access, can be filtered and downloaded using SteamSpy. The data pulled from SteamSpy is updated by the minute in a similar fashion as SteamDB, giving easy access to real-time updated data from Steam applications.

![alt text](https://i.imgur.com/cZaZmUJ.png "Example of PUBG through SteamSpy")

#### Results
To be updated.
