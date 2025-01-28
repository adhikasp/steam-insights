# Steam Catalog Insights (October 2024)
This repository contains CSV files exported from a SQL database of video game data, covering categories, descriptions, game details, genres, promotional materials, reviews, SteamSpy insights, and tags.

## File Description
Each CSV file corresponds to a table from the Steam catalog dataset. The files have been compressed into ZIP archives for easier download. You can unzip them and import these CSV files into any database or use them directly for data analysis.

- **games.csv**: Main table containing details about the games, such as title, release date, and other metadata.
- **genres.csv**: Genres assigned to each game.
- **tags.csv**: Tags associated with each game, such as "Indie", "Action", etc.
- **reviews.csv**: Review data for the games, including Steam ratings and review counts.
- **steamspy_insights.csv**: Insights gathered from SteamSpy, such as estimated sales, playtime, and more.
- **descriptions.csv**: Full and summary text descriptions of each game.
- **promotional.csv**: Links and metadata for promotional materials, such as trailers and screenshots.
- **categories.csv**: Information about the different Steam categories that games belong to (e.g., "Single-player", "Full controller support", etc.).

## Data Description

### categories.csv

**File Size**: 13.65 MB  
**Total Rows**: 522,582  
**Total Columns**: 2  

#### Columns

- **app_id**  
  - Type: int64  
  - Non-null values: 522,582  
  - Unique values: 134,393  
  - Range: 10 to 3298710  
  - Mean: 1619346.57  

- **category**  
  - Type: object  
  - Non-null values: 522,582  
  - Unique values: 315  
  - Sample values: Family Sharing, Multi-player, Online PvP  


### descriptions.csv

**File Size**: 472.44 MB  
**Total Rows**: 63,111  
**Total Columns**: 4  

#### Columns

- **app_id**  
  - Type: object  
  - Non-null values: 63,111  
  - Unique values: 62,418  
  - Sample values: 10, 20, 30  

- **summary**  
  - Type: object  
  - Non-null values: 62,232  
  - Unique values: 49,191  
  - Sample values: Play the world's number 1 online action game. Engage in an incredibly realistic brand of terrorist warfare in this wildly popular team-based game. Ally with teammates to complete strategic missions. Take out enemy sites. Rescue hostages. Your role affects your team's success. Your team's success affects your role., One of the most popular online action games of all time, Team Fortress Classic features over nine character classes -- from Medic to Spy to Demolition Man -- enlisted in a unique style of online team warfare. Each character class possesses unique weapons, items, and abilities, as teams compete online in a variety of game play modes., Enlist in an intense brand of Axis vs. Allied teamplay set in the WWII European Theatre of Operations. Players assume the role of light/assault/heavy infantry, sniper or machine-gunner class, each with a unique arsenal of historical weaponry at their disposal. Missions are based on key historical operations.  

- **extensive**  
  - Type: object  
  - Non-null values: 62,079  
  - Unique values: 49,913  
  - Sample values: Play the world's number 1 online action game. Engage in an incredibly realistic brand of terrorist warfare in this wildly popular team-based game. Ally with teammates to complete strategic missions. Take out enemy sites. Rescue hostages. Your role affects your team's success. Your team's success affects your role., One of the most popular online action games of all time, Team Fortress Classic features over nine character classes -- from Medic to Spy to Demolition Man -- enlisted in a unique style of online team warfare. Each character class possesses unique weapons, items, and abilities, as teams compete online in a variety of game play modes., Enlist in an intense brand of Axis vs. Allied teamplay set in the WWII European Theatre of Operations. Players assume the role of light/assault/heavy infantry, sniper or machine-gunner class, each with a unique arsenal of historical weaponry at their disposal. Missions are based on key historical operations. And, as war rages, players must work together with their squad to accomplish a variety of mission-specific objectives.  

- **about**  
  - Type: object  
  - Non-null values: 61,982  
  - Unique values: 49,818  
  - Sample values: Play the world's number 1 online action game. Engage in an incredibly realistic brand of terrorist warfare in this wildly popular team-based game. Ally with teammates to complete strategic missions. Take out enemy sites. Rescue hostages. Your role affects your team's success. Your team's success affects your role., One of the most popular online action games of all time, Team Fortress Classic features over nine character classes -- from Medic to Spy to Demolition Man -- enlisted in a unique style of online team warfare. Each character class possesses unique weapons, items, and abilities, as teams compete online in a variety of game play modes., Enlist in an intense brand of Axis vs. Allied teamplay set in the WWII European Theatre of Operations. Players assume the role of light/assault/heavy infantry, sniper or machine-gunner class, each with a unique arsenal of historical weaponry at their disposal. Missions are based on key historical operations. And, as war rages, players must work together with their squad to accomplish a variety of mission-specific objectives.  


### games.csv

**File Size**: 32.07 MB  
**Total Rows**: 134,016  
**Total Columns**: 7  

#### Columns

- **app_id**  
  - Type: object  
  - Non-null values: 134,016  
  - Unique values: 33  
  - Sample values: currency": "EUR, currency": "MXN, demo  

- **name**  
  - Type: object  
  - Non-null values: 70,268  
  - Unique values: 338  
  - Sample values: "final_formatted": "8, "final_formatted": "4, final_formatted": "Mex$ 113.99  

- **release_date**  
  - Type: object  
  - Non-null values: 70,268  
  - Unique values: 139  
  - Sample values: 19€", 99€", "discount_percent": 0  

- **is_free**  
  - Type: object  
  - Non-null values: 70,268  
  - Unique values: 48  
  - Sample values: "discount_percent": 0, initial_formatted": ""}, initial_formatted": "CDN$ 12.99"}  

- **price_overview**  
  - Type: object  
  - Non-null values: 70,268  
  - Unique values: 404  
  - Sample values: initial_formatted": ""}, English<strong>*</strong>, French<strong>*</strong>, German<strong>*</strong>, Italian<strong>*</strong>, Spanish - Spain<strong>*</strong>, Simplified Chinese<strong>*</strong>, Traditional Chinese<strong>*</strong>, Korean<strong>*</strong><br><strong>*</strong>languages with full audio support, English<strong>*</strong>, French<strong>*</strong>, German<strong>*</strong>, Italian<strong>*</strong>, Korean<strong>*</strong>, Spanish - Spain<strong>*</strong>, Russian<strong>*</strong>, Simplified Chinese, Traditional Chinese, Dutch, Danish, Finnish, Japanese, Norwegian, Polish, Portuguese - Portugal, Swedish, Thai<br><strong>*</strong>languages with full audio support  

- **languages**  
  - Type: object  
  - Non-null values: 70,268  
  - Unique values: 13,323  
  - Sample values: English<strong>*</strong>, French<strong>*</strong>, German<strong>*</strong>, Italian<strong>*</strong>, Spanish - Spain<strong>*</strong>, Simplified Chinese<strong>*</strong>, Traditional Chinese<strong>*</strong>, Korean<strong>*</strong><br><strong>*</strong>languages with full audio support, English, French, German, Italian, Spanish - Spain, Korean, Russian, Simplified Chinese, Traditional Chinese, English, French, German, Italian, Spanish - Spain  

- **type**  
  - Type: object  
  - Non-null values: 69,595  
  - Unique values: 1  
  - Sample values: game  


### genres.csv

**File Size**: 6.66 MB  
**Total Rows**: 353,339  
**Total Columns**: 2  

#### Columns

- **app_id**  
  - Type: int64  
  - Non-null values: 353,339  
  - Unique values: 122,458  
  - Range: 10 to 3298710  
  - Mean: 1714973.94  

- **genre**  
  - Type: object  
  - Non-null values: 353,339  
  - Unique values: 121  
  - Sample values: Action, Экшены, Free To Play  


### promotional.csv

**File Size**: 489.38 MB  
**Total Rows**: 106,600  
**Total Columns**: 5  

#### Columns

- **app_id**  
  - Type: object  
  - Non-null values: 10,609  
  - Unique values: 8,364  
  - Sample values: "path_thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/10/0000002542.600x338.jpg?t=1721932664"}, "path_thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1630/0000000396.600x338.jpg?t=1571166113"}, "max": "http://video.akamai.steamstatic.com/store_trailers/256787016/movie_max_vp9.webm?t=1590704292"}  

- **header_image**  
  - Type: object  
  - Non-null values: 10,567  
  - Unique values: 4,404  
  - Sample values: {"id": 12, "highlight": true, \N  

- **background_image**  
  - Type: object  
  - Non-null values: 8,234  
  - Unique values: 7,665  
  - Sample values: path_full": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/10/0000002543.1920x1080.jpg?t=1721932664, path_full": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1630/0000000393.1920x1080.jpg?t=1571166113, thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/256787016/movie.293x165.jpg?t=1590704292"}]  

- **screenshots**  
  - Type: object  
  - Non-null values: 2,831  
  - Unique values: 871  
  - Sample values: path_thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/10/0000002543.600x338.jpg?t=1721932664"}], path_thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1630/0000000393.600x338.jpg?t=1571166113"}], "highlight": false  

- **movies**  
  - Type: object  
  - Non-null values: 2,260  
  - Unique values: 1,963  
  - Sample values: \N, thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/5968/movie.293x165.jpg?t=1447353615"}], thumbnail": "https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/256682465/movie.293x165.jpg?t=1491021097"}]  


### reviews.csv

**File Size**: 13.45 MB  
**Total Rows**: 140,138  
**Total Columns**: 13  

#### Columns

- **app_id**  
  - Type: object  
  - Non-null values: 140,138  
  - Unique values: 140,116  
  - Sample values: 10, 20, 30  

- **review_score**  
  - Type: object  
  - Non-null values: 140,088  
  - Unique values: 26  
  - Sample values: 9, 8, 5  

- **review_score_description**  
  - Type: object  
  - Non-null values: 140,080  
  - Unique values: 29  
  - Sample values: Overwhelmingly Positive, Very Positive, Mixed  

- **positive**  
  - Type: object  
  - Non-null values: 140,077  
  - Unique values: 5,407  
  - Sample values: 235403, 7315, 6249  

- **negative**  
  - Type: object  
  - Non-null values: 140,073  
  - Unique values: 2,619  
  - Sample values: 6207, 1094, 672  

- **total**  
  - Type: object  
  - Non-null values: 140,073  
  - Unique values: 5,845  
  - Sample values: 241610, 8409, 6921  

- **metacritic_score**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 74  
  - Sample values: 88, \N, 79  

- **reviews**  
  - Type: object  
  - Non-null values: 140,066  
  - Unique values: 11,466  
  - Sample values: \N, “Современный многопользовательский шедевр.”<br>9.5/10 – Destructoid<br><br>“Стоит лишь начать постигать таинства игры, и вы обнаружите удивительное и волнующее игровое многообразие, которое не превосходят другие игры — даже конкуренты.”<br>9.4/10 – IGN<br><br>“Пожалуй, Dota 2 — единственная бесплатная соревновательная игра, на которую совершенно не влияет её бизнес-модель.”<br>90/100 – PC Gamer<br>, <strong>&quot;... RO is also one of the market's most unique new shooters&quot;</strong><br><br>4/5 Stars - Gamespy<br><strong>Tripwire's attention to accessible realism is unrivaled&quot;</strong><br><br>- Computer Gaming World<br><strong>&quot;Red Orchestra offers exactly the right mixture of action and realism&quot;</strong><br><br>- PC PowerPlay<br><strong>Red Orchestra scores &quot;Best Multiplayer Game&quot; for 2006 over at VooDoo Extreme.</strong><br>Read the full review here.  

- **recommendations**  
  - Type: object  
  - Non-null values: 140,059  
  - Unique values: 4,758  
  - Sample values: 153259, 6268, 4146  

- **steamspy_user_score**  
  - Type: object  
  - Non-null values: 140,058  
  - Unique values: 38  
  - Sample values: 0, \N, 78  

- **steamspy_score_rank**  
  - Type: object  
  - Non-null values: 140,056  
  - Unique values: 5  
  - Sample values: \N, 99, 98  

- **steamspy_positive**  
  - Type: object  
  - Non-null values: 140,055  
  - Unique values: 5,287  
  - Sample values: 235397, 7314, 6246  

- **steamspy_negative**  
  - Type: object  
  - Non-null values: 140,055  
  - Unique values: 2,569  
  - Sample values: 6207, 1092, 672  


### steamspy_insights.csv

**File Size**: 17.33 MB  
**Total Rows**: 140,068  
**Total Columns**: 14  

#### Columns

- **app_id**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 140,068  
  - Range: 10 to 3298710  
  - Mean: 1788660.38  

- **developer**  
  - Type: object  
  - Non-null values: 140,065  
  - Unique values: 53,866  
  - Sample values: Valve, Gearbox Software, Mark Healey  

- **publisher**  
  - Type: object  
  - Non-null values: 140,033  
  - Unique values: 47,583  
  - Sample values: Valve, Mark Healey, Tripwire Interactive  

- **owners_range**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 14  
  - Sample values: 10,000,000 .. 20,000,000, 5,000,000 .. 10,000,000, 2,000,000 .. 5,000,000  

- **concurrent_users_yesterday**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 1,160  
  - Range: 0 to 1180219  
  - Mean: 55.66  

- **playtime_average_forever**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 1  
  - Range: 0 to 0  
  - Mean: 0.00  

- **playtime_average_2weeks**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 1  
  - Range: 0 to 0  
  - Mean: 0.00  

- **playtime_median_forever**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 1  
  - Range: 0 to 0  
  - Mean: 0.00  

- **playtime_median_2weeks**  
  - Type: int64  
  - Non-null values: 140,068  
  - Unique values: 1  
  - Range: 0 to 0  
  - Mean: 0.00  

- **price**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 567  
  - Sample values: 999, 499, 0  

- **initial_price**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 342  
  - Sample values: 999, 499, 0  

- **discount**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 85  
  - Sample values: 0, 80, 67  

- **languages**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 13,975  
  - Sample values: English, French, German, Italian, Spanish - Spain, Simplified Chinese, Traditional Chinese, Korean, English, French, German, Italian, Spanish - Spain, Korean, Russian, Simplified Chinese, Traditional Chinese, English, French, German, Italian, Spanish - Spain  

- **genres**  
  - Type: object  
  - Non-null values: 140,068  
  - Unique values: 2,604  
  - Sample values: Action, Action, Free To Play, Action, Strategy, Free To Play  


### tags.csv

**File Size**: 36.43 MB  
**Total Rows**: 1,744,632  
**Total Columns**: 2  

#### Columns

- **app_id**  
  - Type: int64  
  - Non-null values: 1,744,632  
  - Unique values: 117,505  
  - Range: 10 to 3298710  
  - Mean: 1865601.13  

- **tag**  
  - Type: object  
  - Non-null values: 1,744,632  
  - Unique values: 447  
  - Sample values: 1980s, 1990's, Action  

