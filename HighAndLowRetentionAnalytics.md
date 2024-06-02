# High and low retention games analysis
This analysis aimed to evaluate the effectiveness of gamification techniques in boosting player retention for Vanilla. Due to the absence of specific data, the study focused on puzzle genre mobile games with over 25k downloads in the last two months. By dissecting games with high and low day 30 retention rates, the aim was to identify and compare gamification strategies that influenced player engagement and longevity.

## Games
I analysed the following 10 games with D30 retention rates ranging from 21.55% - 27.67% from highest to lowest;
- Block Puzzle Legend
- Coin Master
- Mahjong 3
- Family Island™ — Farming game
- Harry Potter: Puzzles & Spells
- Love & Pies - Merge Mystery
- Block Puzzle
- Homescapes
- Jigsawscapes® - Jigsaw Puzzles
- Hay Day

And the following ten games with D30 retention rates ranging from 1.83% - 2.53% from lowest to highest;
- Hero Clash: Playtime Go
- Teacher Simulator: School Days
- Camo Sniper
- Help Me: Tricky Story
- Cube Solver
- Impossible Date 2: Fun Riddle
- Cashier 3D
- Epic War-Unlock Screws
- Super Slime - Black Hole Game
- Cooking Live - Cooking games

## Categories
To organise the mechanics I make use of seven categories; temporal, social, progression, ownership, luck, resources, and accomplishments. Learn more about them here: [Gamification categories](https://github.com/NickVanGerwen/GamificationForPlayerRetention/blob/Readme/GamificationCategories.md)

## Results

| Retention | temporal                                                                                               | social                                                                                | progression                                                                                                        | ownership                                                                                    | luck                                                       | resources                                                          | accomplishments                                      |
|-----------|--------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|------------------------------------------------------------|--------------------------------------------------------------------|------------------------------------------------------|
| High      | 7 x daily rewards  <br />2 x daily quests  <br />5 x energy/lives  <br />2 x appointment crafting/bulding/farms  <br />2 x events | 5 x leaderboards  <br />1 x antagonist  <br />3 x gifts  <br />3 x teams  <br />2 x friends  <br />1 x trading  <br />1 x chats |  2 x town building  <br />3 x simplified town building  <br />4 x worlds  <br />3 x levels  <br />4 x quests  <br />3 x level up  <br />6 x unlocks  <br />2 x story | 3 x customize play area  <br />2 x collections  <br />3 x custom name  <br />1 x character creator  <br />2 x game modes | 4 x random rewards  <br />2 x spin wheel  <br />2 x chance for minigames | 4 x coins  <br />4 x gems  <br />2 x stars  <br />2 x multiplayer currency  <br />2 x boosters | 3 x points  <br />2 x achievements  <br />1 x ingame gratification |
| Low       | 1 x daily rewards  <br />1 x events  <br />1 x energy  <br />1 x appointments                                               |                                                                                       | 1 x unlocks  <br />1 x story  <br />2 x simplified town building  <br />2 x upgrade something  <br />3 x levels  <br />1 x level up                   | 1 x customize play area  <br />1 x skins                                                            | 3 x reward multiplier wheel (watch ad)  <br />1 x spin wheel      | 3 x coins  <br />2 x boosters  <br />2 x gems  <br />1x stars                           | 1 x boss fights                                      |

## Observations
1. Higher retention games often hide certain mechanics until a certain level or playtime is reached. This ensures the players aren’t overwhelmed during their first play sessions.
2. Higher retention games have a total of 109 gamification mechanics, while low retention games have only 33. Which is an average of ~11 compared to ~4 per game. This signifies an increased amount of gamification techniques could boost retention rates.
3. The selected low retention games have zero social gamification mechanics. The demand for social features likely goes up as a game acquires more long term players. This could also indicate social mechanics are a good choice for boosting retention.
4. The most common mechanic in high retention games is daily rewards, this makes sense as daily rewards always provide a trigger / motivation to come back to the game. This could be a good starting point for implementing gamification into games.
5. While gamification is often associated with “points, badges & leaderboards” or PBL, both points and badges are uncommon in both high and low retention games.
6. All low retention games apply some form of progression mechanics. This could mean these do not affect retention much on their own.
7. The most common progression mechanics in high retention games are worlds and quests, while they are absent from the low retention games. This indicates they might be more effective than other progression mechanics. The fewer implementations could be due to their relatively longer development time. 
8. Town building, and its simplified versions, are common in both high and low retention games. Though their implementations differ. High retention games tend to use building mechanics as an extension of the main gameplay, where 1 level completed = 1 star gained = 1 thing built. While low retention games allow the player to build their “town” with coins instead. The one exception to this is Hay Day, which also its in-game currency.
9. There is only one true luck-based mechanic in the low retention games. These are a good option for potentially boosting player retention.
10. Lives and energy are commonly used in high retention games while being used only once in the selected low retention games. This indicates they could boost retention.
11. Five of the low retention games have many ads in them, to the point where you spend more time looking at ads than playing the game. This likely contributes to the low retention rates. Although, this monetization strategy was possibly implemented as a last ditch effort to make money after the game was already failing.

## Conclusion
This approach relies on the assumption that retention of the games is related to the gamification techniques applied. While there was an attempt to remove variables by sticking exclusively to mobile puzzle games, there are many factors which likely had an impact on the retention rates, ex. monetization strategy, advertising, implementation of gamification mechanics, core gameplay, replayability. 

Even still, this analysis did provides us with a list of gamification techniques that are likely to increase retention rates;

### Temporal mechanics
- Daily / weekly rewards
- Daily / weekly quests
- Lives / energy
### Social mechanics
- Leaderboards
- Teams
- Friends 
- Gifts
### Progression mechanics
- Quests
- Worlds
- Simplified town building
### Ownership mechanics
- Customisation
- Collections 
### Luck-based mechanics
- Loot chests
- Random rewards
- Spin a wheel
- Chance for minigames
### Resources mechanics 
- Gems
- Coins 
### Accomplishment mechanics
- Achievements

