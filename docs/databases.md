NBA Stats Databases and Descriptions
===

Added? | Module | Table Title | Description | Raw Data Link
--- |-| ----------- | ----------- | -------------
- [ ] | |[Transaction History](http://stats.nba.com/transactions/) | Transactions for all teams | [Raw](http://stats.nba.com/feeds/NBAPlayerTransactions-559107/json.js)
yes| `draft.py`|Draft Combine - [Anthropometric](http://stats.nba.com/draftcombine/#!/anthro/)~ | | [Raw](http://stats.nba.com/stats/draftcombineplayeranthro?LeagueID=00&SeasonYear=2014-15)
yes | `draft.py`|Draft Combine - [Speed and Agility](http://stats.nba.com/draftcombine/#!/agility/) | | [Raw](http://stats.nba.com/stats/draftcombinedrillresults?LeagueID=00&SeasonYear=2014-15)
yes | `draft.py`| Draft Combine - [Non Stationary Shooting](http://stats.nba.com/draftcombine/#!/nonstationary/) | | [Raw](http://stats.nba.com/stats/draftcombinenonstationaryshooting?LeagueID=00&SeasonYear=2014-15)
yes | `draft.py`| Draft Combine - [Spot Shooting](http://stats.nba.com/draftcombine/#!/spotup/) | | [Raw](http://stats.nba.com/stats/draftcombinespotshooting?LeagueID=00&SeasonYear=2014-15)
yes | `draft.py`| Draft Combine - [General Statistics](http://stats.nba.com/draftcombine/#!/) | | [Raw](http://stats.nba.com/stats/draftcombinestats?LeagueID=00&SeasonYear=2014-15)
- [ ] | | [Franchise History](http://stats.nba.com/history/) | | [Raw](http://stats.nba.com/stats/franchisehistory?LeagueID=00)
- [ ] | | [Playoff Picture](http://stats.nba.com/playoffpicture/) | | [Raw](http://stats.nba.com/stats/playoffpicture?LeagueID=00&SeasonID=22014)
- [ ] | `playtype.py` | Play Type - [Transition](http://stats.nba.com/playtype/#!/transition/?dir=1) | When the possession-ending event comes before the defense sets following a possession change and a transition from one end of the court to the other | [Raw](http://stats.nba.com/js/data/playtype/player_Transition.js)
- [ ] | `playtype.py` |Play Type - [Isolation](http://stats.nba.com/playtype/#!/isolation/?dir=1) | When the possession-ending event is created during a “one-on-one” matchup. The defender needs to be set and have all of his defensive options at the initiation of the play. | [Raw](http://stats.nba.com/js/data/playtype/player_Isolation.js)
- [ ] | `playtype.py` |Play Type - [Pick & Roll: Ball Handler](http://stats.nba.com/playtype/#!/ball-handler/?dir=1) | A screen is set on the ball handler’s defender out on the perimeter. The offensive player can use the screen or go away from it and as long as the play yields a possession-ending event, it is tagged as a pick and roll. | [Raw](http://stats.nba.com/js/data/playtype/player_PRBallHandler.js)
- [ ] | `playtype.py` |Play Type - [Pick & Roll: Roll Man](http://stats.nba.com/playtype/#!/roll-man/?dir=1) | When a screen is set for the ball handler, and the screen setter then receives the ball for a possession-ending event. This action can include: pick and rolls, pick and pops and the screener slipping the pick. | [Raw](http://stats.nba.com/js/data/playtype/player_PRRollMan.js)
- [ ] | `playtype.py` |Play Type - [Post-Up](http://stats.nba.com/playtype/#!/post-up/?dir=1) | When an offensive player receives the ball with their back to the basket and is less than 15' from the rim when the possession-ending event occurs. | [Raw](http://stats.nba.com/js/data/playtype/player_Postup.js)
- [ ] | `playtype.py` |Play Type - [Spot-Up](http://stats.nba.com/playtype/#!/spot-up/?dir=1) | When the possession-ending event is a catch-and-shoot or catch-and-drive play. | [Raw](http://stats.nba.com/js/data/playtype/player_Spotup.js)
- [ ] | `playtype.py` |Play Type - [Hand-Off](http://stats.nba.com/playtype/#!/hand-off/?dir=1) | The screen setter starts with the ball and hands the ball to a player cutting close by. This enables the player handing the ball off to effectively screen off a defender creating space for the player receiving the ball. | [Raw](http://stats.nba.com/js/data/playtype/player_Handoff.js)
- [ ] | `playtype.py` | Play Type - [Cut](http://stats.nba.com/playtype/#!/cut/?dir=1) | An interior play where the finisher catches a pass while moving toward, parallel to or slightly away from the basket. This will include back screen and flash cuts as well as times when the player is left open near the basket. | [Raw](http://stats.nba.com/js/data/playtype/player_Cut.js)
- [ ] | `playtype.py` | Play Type - [Off Screen](http://stats.nba.com/playtype/#!/off-screen/?dir=1) | Identifies players coming off of screens (typically downs screens) going away from the basket toward the perimeter. This includes curl, fades, and coming off straight. | [Raw](http://stats.nba.com/js/data/playtype/player_OffScreen.js)
- [ ] | `playtype.py` | Play Type - [Offensive Rebound (putbacks)](http://stats.nba.com/playtype/#!/putbacks/?dir=1) | When the rebounder attempts to score before passing the ball or establishing themselves in another play type. | [Raw](http://stats.nba.com/js/data/playtype/player_OffRebound.js)
- [ ] | `playtype.py` | Play Type - [Miscellaneous](http://stats.nba.com/playtype/#!/misc/?dir=1) | When the action doesn't fit any of the other play types. This includes, but is not limited to, last second full court shots, fouls in the backcourt, or errant passes not out of a different play type, etc. | [Raw](http://stats.nba.com/js/data/playtype/player_Misc.js)
- [ ] | `playertracking.py` | Player Tracking - [Catch and Shoot](http://stats.nba.com/tracking/#!/player/catchshoot/) | Any jump shot outside of 10 feet where a player possessed the ball for 2 seconds or less and took no dribbles. | [Raw](http://stats.nba.com/js/data/sportvu/2014/catchShootData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Defensive Impact](http://stats.nba.com/tracking/#!/player/defense/) | Statistics measuring the impact a player has on defense, including blocks, steals and protecting the rim, which measures the opponent's field goal percentage at the rim while it is being defended. Rim protection is defined as the defender being within five feet of the basket and within five feet of the offensive player attempting the shot. | [Raw](http://stats.nba.com/js/data/sportvu/2014/defenseData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Drives](http://stats.nba.com/tracking/#!/player/drives/) | Any touch that starts at least 20 feet of the hoop and is dribbled within 10 feet of the hoop and excludes fast breaks. Measures the total number of drives as well as the points, assists and shooting percentages on drives to the basket. | [Raw](http://stats.nba.com/js/data/sportvu/2014/drivesData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Passing](http://stats.nba.com/tracking/#!/player/passing/) | The total number of passes a player makes and the scoring opportunities that come from those passes, whether they lead directly to a teammate scoring a basket or free throw, or if they set up an assist for another teammate. | [Raw](http://stats.nba.com/js/data/sportvu/2014/passingData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Touches/Possession](http://stats.nba.com/tracking/#!/player/possessions/) | The number of times a player touches and possesses the ball, where those touches occur on the court, how long the player possessed the ball and the number of points, assists and turnovers that occur with the ball in his possession. | [Raw](http://stats.nba.com/js/data/sportvu/2014/touchesData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Pull Up Shots](http://stats.nba.com/tracking/#!/player/pullup/) | Any jump shot outside 10 feet where a player took 1 or more dribbles before shooting. | [Raw](http://stats.nba.com/js/data/sportvu/2014/pullUpShootData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Rebounding Opportunities](http://stats.nba.com/tracking/#!/player/rebounding/) | The number of times player was within the vicinity (3.5 ft) of a rebound. Measures the number of rebounds a player recovers compared to the number of rebounding chances available as well as whether or not the rebound was contested by an opponent or deferred to a teammate. | [Raw](http://stats.nba.com/js/data/sportvu/2014/reboundingData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Shooting Efficiency](http://stats.nba.com/tracking/#!/player/shooting/) | Measures shooting percentages from different types of shots - Drives, Close Shots, Catch and Shoots and Pull Up Shots. | [Raw](http://stats.nba.com/js/data/sportvu/2014/shootingData.json)
- [ ] | `playertracking.py` |  Player Tracking - [Speed and Distance](http://stats.nba.com/tracking/#!/player/speed/) | Statistics that measure the distance covered and the average speed of all movements (sprinting, jogging, standing, walking, backwards and forwards) by a player while on the court. | [Raw](http://stats.nba.com/js/data/sportvu/2014/speedData.json)
- [ ] | `Team.py` | Team Stats - [Traditional](http://stats.nba.com/league/team/#!/) | `MeasureType=Base` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Advanced](URL) | `MeasureType=Advanced` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Advanced&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=Totals&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] |  `Team.py` |Team Stats - [Four Factors](http://stats.nba.com/league/team/#!/fourfactors/) | `MeasureType=Four+Factors` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Four+Factors&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=Totals&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Miscellaneous](http://stats.nba.com/league/team/#!/misc/) | `MeasureType=Misc` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Misc&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Scoring](http://stats.nba.com/league/team/#!/scoring/) | `MeasureType=Scoring` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Scoring&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Opponent](http://stats.nba.com/league/team/#!/opponent/) | `MeasureType=Opponent` | [Raw](http://stats.nba.com/stats/leaguedashteamstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Opponent&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Clutch Traditional](http://stats.nba.com/league/team/#!/clutch/) | These tables replicate the previous team tables except they add a clutch component to the data query. | [Raw](http://stats.nba.com/stats/leaguedashteamclutch?AheadBehind=Ahead+or+Behind&ClutchTime=Last+5+Minutes&DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&PointDiff=5&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Shooting](http://stats.nba.com/league/team/#!/shooting/) | **Going to the Actual Page for each stat and playing with filter options should give us an idea how to use the query strings to get exact data we want**. For example, the `DistanceRange` option can take the values `5ft Range`, `8ft Range`, or `By Zone`. **As of 3/26/15, the latter two options don't appear to be working** | [Raw](http://stats.nba.com/stats/leaguedashteamshotlocations?DateFrom=&DateTo=&DistanceRange=5ft+Range&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Opponent Shooting](http://stats.nba.com/league/team/#!/oppshooting/) | | [Raw](http://stats.nba.com/stats/leaguedashteamshotlocations?DateFrom=&DateTo=&DistanceRange=5ft+Range&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Opponent&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Team.py` | Team Stats - [Lineups](http://stats.nba.com/league/lineups/#!/) | `MeasureType` is key variable in this query to adjust | [Raw](http://stats.nba.com/stats/leaguedashlineups?DateFrom=&DateTo=&GameID=&GameSegment=&GroupQuantity=5&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&VsConference=&VsDivision=)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Defensive Impact](http://stats.nba.com/tracking/#!/team/defense/) | Statistics measuring the impact a player has on defense, including blocks, steals and protecting the rim, which measures the opponent's field goal percentage at the rim while it is being defended. Rim protection is defined as the defender being within five feet of the basket and within five feet of the offensive player attempting the shot. | [Raw](http://stats.nba.com/js/data/sportvu/2014/defenseTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Catch & Shoot](http://stats.nba.com/tracking/#!/team/catchshoot/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/catchShootTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Drives](http://stats.nba.com/tracking/#!/team/drives/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/drivesTeamData.json)
 Team Player Tracking - [Passing](http://stats.nba.com/tracking/#!/team/passing/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/passingTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Possessions](http://stats.nba.com/tracking/#!/team/possessions/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/touchesTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Pull up Shooting](http://stats.nba.com/tracking/#!/team/pullup/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/pullUpShootTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Rebounding](http://stats.nba.com/tracking/#!/team/rebounding/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/reboundingTeamData.json)
- [ ] | `TeamTracking.py` | Team Player Tracking - [Shooting Efficiency](http://stats.nba.com/tracking/#!/team/shooting/) | | [Raw]()
- [ ] | `TeamTracking.py` | Team Player Tracking - [Speed & Distance](http://stats.nba.com/tracking/#!/team/speed/) | | [Raw](http://stats.nba.com/js/data/sportvu/2014/speedTeamData.json)
- [ ] | | [Daily Standings](http://stats.nba.com/standings/#!/03/26/2015) | | [Raw](http://stats.nba.com/stats/scoreboard?DayOffset=0&LeagueID=00&gameDate=03%2F26%2F2015)
- [ ] | | [Player Database - All Time](http://stats.nba.com/players/) | Change `IsOnlyCurrentSeason` = `1` to return players who are/were on a roster during a specific season| [Raw](http://stats.nba.com/stats/commonallplayers?IsOnlyCurrentSeason=0&LeagueID=00&Season=2014-15)
- [ ] | `PlayerStats.py` | Player Stats - [Traditional](http://stats.nba.com/league/player/#!/) | Adjust the `MeasureType` variable to get max stats from this query.| [Raw](http://stats.nba.com/stats/leaguedashplayerstats?DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `PlayerStats.py` | Player Stats - [Clutch Traditional](http://stats.nba.com/league/player/#!/clutch/) | | [Raw](http://stats.nba.com/stats/leaguedashplayerclutch?AheadBehind=Ahead+or+Behind&ClutchTime=Last+5+Minutes&DateFrom=&DateTo=&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&PointDiff=5&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `PlayerStats.py` | Player Stats - [Shooting](http://stats.nba.com/league/player/#!/shooting/) | | [Raw](http://stats.nba.com/stats/leaguedashplayershotlocations?DateFrom=&DateTo=&DistanceRange=5ft+Range&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `PlayerStats.py` | Player Stats - [Opponent Shooting](http://stats.nba.com/league/player/#!/oppshooting/) | | [Raw](http://stats.nba.com/stats/leaguedashplayershotlocations?DateFrom=&DateTo=&DistanceRange=5ft+Range&GameScope=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Opponent&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerExperience=&PlayerPosition=&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StarterBench=&VsConference=&VsDivision=)
- [ ] | `Leaders.py` | [League Leaders](http://stats.nba.com/leaders/#!?StatCategory=PTS) | | [Raw](http://stats.nba.com/stats/leagueleaders?LeagueID=00&PerMode=PerGame&Scope=S&Season=2014-15&SeasonType=Regular+Season&StatCategory=PTS)
- [ ] | `Leaders.py` | [All-time Leaders](http://stats.nba.com/leaders/alltime/) | `Season=All+Time` | [Raw](http://stats.nba.com/stats/leagueleaders?LeagueID=00&PerMode=PerGame&Scope=S&Season=All+Time&SeasonType=Regular+Season&StatCategory=PTS)
- [ ] | `BoxScore.py` | Box Score - [Summary](http://stats.nba.com/game/#!/0021401060/) | All of the **Box Score** tables are for specific games. Should try and find a table of gameIDs| [Raw](http://stats.nba.com/stats/boxscoresummaryv2?GameID=0021401060)
- [ ] | `BoxScore.py` | Box Score - [Traditional](http://stats.nba.com/game/#!/0021401060/) | | [Raw](http://stats.nba.com/stats/boxscoretraditionalv2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Advanced](http://stats.nba.com/game/#!/0021401060/advanced/) | | [Raw](http://stats.nba.com/stats/boxscoreadvancedv2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Miscellaneous](http://stats.nba.com/game/#!/0021401060/misc/) | | [Raw](http://stats.nba.com/stats/boxscoremiscv2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Scoring](http://stats.nba.com/game/#!/0021401060/scoring/) | | [Raw](http://stats.nba.com/stats/boxscorescoringv2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Usage](http://stats.nba.com/game/#!/0021401060/usage/) | | [Raw](http://stats.nba.com/stats/boxscoreusagev2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Four Factors](http://stats.nba.com/game/#!/0021401060/fourfactors/) | | [Raw](http://stats.nba.com/stats/boxscorefourfactorsv2?EndPeriod=10&EndRange=28800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Play by Play](http://stats.nba.com/game/#!/0021401060/playbyplay/) | | [Raw](http://stats.nba.com/stats/playbyplayv2?EndPeriod=10&EndRange=55800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | `BoxScore.py` | Box Score - [Player Tracking](http://stats.nba.com/game/#!/0021401060/playertracking/) | | [Raw](http://stats.nba.com/stats/boxscoreplayertrackv2?EndPeriod=10&EndRange=55800&GameID=0021401060&RangeType=2&Season=2014-15&SeasonType=Regular+Season&StartPeriod=1&StartRange=0)
- [ ] | | [SportVU XY](URL) | per game per eventid. Data is specific to an animation program that runs on the NBA Website. It does not correspond to XY Coordinates from Shot Charts. Can potentially derive an algorithm that converts distance on animation to distance on court. We have some outcomes and an unknown conversion ratio. Once that is computed, we theoretically have nearly raw sportVU data| [Raw](http://stats.nba.com/stats/locations_getmoments/?eventid=1&gameid=0021401060)
- [ ] | | [Team Information] No URL | | [Raw](http://stats.nba.com/stats/teaminfocommon?LeagueID=00&SeasonType=Regular+Season&TeamID=1610612751&season=2014-15)
- [ ] | `.py` | Team-Specific - [Game Logs](http://stats.nba.com/team/#!/1610612751/gamelogs/) | | [Raw](http://stats.nba.com/stats/teamgamelog?LeagueID=00&Season=2014-15&SeasonType=Regular+Season&TeamID=1610612751)
- [ ] |  `.py` | Team-Specific - [Seasons](http://stats.nba.com/team/#!/1610612751/seasons/) | | [Raw](http://stats.nba.com/stats/teamyearbyyearstats?LeagueID=00&PerMode=Totals&SeasonType=Regular+Season&TeamID=1610612751)
- [ ] | `.py` | Team-Specific - [Year-Over-Year](http://stats.nba.com/team/#!/1610612751/yearoveryear/) | | [Raw](http://stats.nba.com/stats/teamyearbyyearstats?LeagueID=00&PerMode=Totals&SeasonType=Regular+Season&TeamID=1610612751)
- [ ] |  `.py` |Team-Specific - [SportVU Shooting](http://stats.nba.com/team/#!/1610612751/tracking/shots/) | | [Raw](http://stats.nba.com/stats/teamdashptshots?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] |  `.py` | Team-Specific - [SportVU Rebounds](http://stats.nba.com/team/#!/1610612751/tracking/rebounds/) | | [Raw](http://stats.nba.com/stats/teamdashptreb?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | `.py` | Team-Specific - [SportVU Passing](http://stats.nba.com/team/#!/1610612751/tracking/passes/) | | [Raw](http://stats.nba.com/stats/teamdashptpass?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | `.py` | Team-Specific - [On/Off Court](http://stats.nba.com/team/#!/1610612751/onoffcourt/) | `MeasureType` | [Raw](http://stats.nba.com/stats/teamplayeronoffdetails?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=Per48&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | `.py` | Team-Specific - [Player Stats](http://stats.nba.com/team/#!/1610612751/players/) | `MeasureType` | [Raw](http://stats.nba.com/stats/teamplayerdashboard?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | `.py` | Team-Specific - [Lineups](http://stats.nba.com/team/#!/1610612751/lineups/) | `MeasureType` | [Raw](http://stats.nba.com/stats/teamdashlineups?DateFrom=&DateTo=&GameID=&GameSegment=&GroupQuantity=5&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | `.py` | Team-Specific - [Split Statistics](http://stats.nba.com/team/#!/1610612751/stats/) | | [Raw](http://stats.nba.com/stats/teamdashboardbygeneralsplits?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | | Team-Specific - [Profile/General Info](http://stats.nba.com/team/#!/1610612751/) | | [Raw](http://stats.nba.com/feeds/teams/profile/1610612751_TeamProfile.js)
- [ ] | | Team-Specific - [Roster/Coaches](http://stats.nba.com/team/#!/1610612751/) | | [Raw](http://stats.nba.com/stats/commonteamroster?LeagueID=00&Season=2014-15&TeamID=1610612751)
- [ ] | | Team-Specific - [RotoWire](http://stats.nba.com/team/#!/1610612751/) | | [Raw](http://stats.nba.com/feeds/RotoWirePlayers-583598/1610612751.json)
- [ ] | | Player-Specific - [Bio](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/feeds/players/bios/2207.json)
- [ ] | | Player-Specific - [Database Details](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/stats/commonplayerinfo?GraphEndSeason=2013-14&GraphStartSeason=2013-14&GraphStat=PTS&LeagueID=00&MeasureType=Base&PerMode=PerGame&PlayerID=2207&SeasonType=Regular+Season&SeasonType=Playoffs)
- [ ] | | Player-Specific - [Fantasy Feeds](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/feeds/RotoWirePlayers-583598/2207.json)
- [ ] | | Player-Specific - [Awards](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/feeds/players/awards/2207_Award.js)
- [ ] | | Player-Specific - [Career Stats 1](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/stats/playercareerstats?LeagueID=00&PerMode=PerGame&PlayerID=2207)
- [ ] | | Player-Specific - [Career Stats 2](http://stats.nba.com/player/#!/2207/) | | [Raw](http://stats.nba.com/stats/playerprofilev2?GraphEndSeason=2013-14&GraphStartSeason=2013-14&GraphStat=PTS&LeagueID=00&MeasureType=Base&PerMode=PerGame&PlayerID=2207&SeasonType=Regular+Season&SeasonType=Playoffs)
- [ ] | | Player-Specific - [Season Splits](http://stats.nba.com/player/#!/2207/) | `MeasureType`| [Raw](http://stats.nba.com/stats/playerdashboardbygeneralsplits?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerID=2207&PlusMinus=N&Rank=N&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [Game Logs](http://stats.nba.com/player/#!/2207/gamelogs/) | | [Raw](http://stats.nba.com/stats/playergamelog?LeagueID=00&PlayerID=2207&Season=2014-15&SeasonType=Regular+Season)
- [ ] | | Player-Specific - [SportVU Shots](http://stats.nba.com/player/#!/2207/tracking/shots/) | | [Raw](http://stats.nba.com/stats/playerdashptshots?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=PerGame&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [SportVU Rebounds](http://stats.nba.com/player/#!/2207/tracking/rebounds/) | | [Raw](http://stats.nba.com/stats/playerdashptreb?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=PerGame&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [SportVU Passing](http://stats.nba.com/player/#!/2207/tracking/passes/) | | [Raw](http://stats.nba.com/stats/playerdashptpass?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=PerGame&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [SportVU Defense](http://stats.nba.com/player/#!/2207/tracking/defense/) | | [Raw](http://stats.nba.com/stats/playerdashptshotdefend?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=PerGame&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [SportVU Shot Logs](http://stats.nba.com/player/#!/2207/tracking/shotslogs/) | | [Raw](http://stats.nba.com/stats/playerdashptshotlog?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [SportVU Rebound Logs](http://stats.nba.com/player/#!/2207/tracking/reboundslogs/) | | [Raw](http://stats.nba.com/stats/playerdashptreboundlogs?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&Period=0&PlayerID=2207&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&TeamID=0&VsConference=&VsDivision=)
- [ ] | | Player-Specific - Shot Charts (Link NA)| | [Raw](http://stats.nba.com/stats/shotchartdetail?&ContextFilter=&ContextMeasure=FGA&DateFrom=&DateTo=&EndPeriod=10&EndRange=28800&GameID=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&Period=0&PlayerID=2207&Position=&RangeType=2&RookieYear=&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StartPeriod=1&StartRange=0&TeamID=1610612751&VsConference=&VsDivision=)
- [ ] | | Player-Specific - [Video details](URL) | Unsure what this is or if it's important| [Raw](http://stats.nba.com/stats/videodetails?AheadBehind=&CFID=33&CFPARAMS=2014-15&ClutchTime=&ContextFilter=&ContextMeasure=FGA&DateFrom=&DateTo=&EndPeriod=10&EndRange=0&GameID=&GameSegment=&LastNGames=0&LeagueID=00&Location=&MeasureType=Base&Month=0&OpponentTeamID=0&Outcome=&PaceAdjust=N&PerMode=PerGame&Period=0&PlayerID=2207&PlusMinus=N&PointDiff=&Position=&RangeType=1&Rank=N&RookieYear=&Season=2014-15&SeasonSegment=&SeasonType=Regular+Season&StartPeriod=1&StartRange=0&TeamID=0&VsConference=&VsDivision=)