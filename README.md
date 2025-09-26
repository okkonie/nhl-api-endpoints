# nhl api endpoints

### 📌 Base URL: https://api-web.nhle.com/

Every endpoint from https://api-web.nhle.com/application.wadl presented prettier

| parameter | format | e.g. |
| :--- | :--- | :--- |
| date | YYYY-MM-DD | 2025-04-24 |
| month | YYYY-MM | 2025-04 |
| year | YYYY | 2025 |
| season | start year + end year | 20242025 |
| team | team abbrev | COL, WSH... |
| game-type | 2 or 3 | 2 = regular, 3 = playoff |
| contry-code | 2 letter | fi, se, us, ca |
| player | player id | 8471214 |


##  Schedule for a week
- ```https://api-web.nhle.com/v1/schedule/now```
- ```https://api-web.nhle.com/v1/schedule/{date}```
## Team specific schedule
- ```https://api-web.nhle.com/v1/club-schedule/{team}/month/now```
- ```https://api-web.nhle.com/v1/club-schedule/{team}/month/{month}```
- ```https://api-web.nhle.com/v1/club-schedule/{team}/week/now```
- ```https://api-web.nhle.com/v1/club-schedule/{team}/week/{date}```
- ```https://api-web.nhle.com/v1/club-schedule-season/{team}/now```
- ```https://api-web.nhle.com/v1/club-schedule-season/{team}/{season}```
## Scores and details for games each day
- ```https://api-web.nhle.com/v1/score/now```
- ```https://api-web.nhle.com/v1/score/{date}```
## Scoreboard for multiple days
- ```https://api-web.nhle.com/v1/scoreboard/now```
- ```https://api-web.nhle.com/v1/scoreboard/{date}```
- ```https://api-web.nhle.com/v1/scoreboard/{team}/now```
## Standings
- ```https://api-web.nhle.com/v1/standings/now```
- ```https://api-web.nhle.com/v1/standings/{date}```
- ```https://api-web.nhle.com/v1/standings-season```
## Playoffs
- ```https://api-web.nhle.com/v1/playoff-series/carousel/{season}```
- ```https://api-web.nhle.com/v1/playoff-bracket/{year}```
## Team Info
- ```https://api-web.nhle.com/v1/club-stats/{team}/now```
- ```https://api-web.nhle.com/v1/club-stats/{team}/{season}/{game-type}```
- ```https://api-web.nhle.com/v1/club-stats-season/{team}```
## Roster
- ```https://api-web.nhle.com/v1/roster/{team}/current```
- ```https://api-web.nhle.com/v1/roster/{team}/{season}```
- ```https://api-web.nhle.com/v1/roster-season/{team}```
## Player Info
- ```https://api-web.nhle.com/v1/player/{player}/landing```
- ```https://api-web.nhle.com/v1/player/{player}/game-log/now```
- ```https://api-web.nhle.com/v1/player/{player}/game-log/{season}/{game-type}```
- ```https://api-web.nhle.com/v1/player-spotlight```
##  🔎 Player search
**Replace the string with a name and specify active={true/false}**
```
https://search.d3.nhle.com/api/v1/search/player?culture=en-us&active=true&limit=20&q=STRING
```

## Stats leaders
- ```https://api-web.nhle.com/v1/skater-stats-leaders/current```
- ```https://api-web.nhle.com/v1/skater-stats-leaders/{season}/{game-type}```
- ```https://api-web.nhle.com/v1/goalie-stats-leaders/current```
- ```https://api-web.nhle.com/v1/goalie-stats-leaders/{season}/{game-type}```
### Can specify categories and limit
- ```https://api-web.nhle.com/v1/skater-stats-leaders/current?categories=goals,points&limit=10```
## Gamecenter / Game Details
- ```https://api-web.nhle.com/v1/gamecenter/{game-id}/landing```
- ```https://api-web.nhle.com/v1/gamecenter/{game-id}/boxscore```
- ```https://api-web.nhle.com/v1/gamecenter/{game-id}/play-by-play```
- ```https://api-web.nhle.com/v1/gamecenter/{game-id}/right-rail```
## Play-by-Play (WSC)
- ```https://api-web.nhle.com/v1/wsc/play-by-play/{game-id}```
- ```https://api-web.nhle.com/v1/wsc/game-story/{game-id}```
## PPT Replay
- ```https://api-web.nhle.com/v1/ppt-replay/{game-id}/{event-number}```
- ```https://api-web.nhle.com//v1/ppt-replay/goal/{game-id}/{event-number}```
## Draft
- ```https://api-web.nhle.com/v1/draft-tracker/picks/now```
- ```https://api-web.nhle.com/v1/draft/picks/now```
- ```https://api-web.nhle.com/v1/draft/picks/{year}/all```
- ```https://api-web.nhle.com/v1/draft/picks/{year}/{round}```
- ```https://api-web.nhle.com/v1/draft/rankings/now```
- ```https://api-web.nhle.com/v1/draft/rankings/{year}/{category}```
- ```https://api-web.nhle.com/v1/prospects/{team}```
## TV Schedule
- ```https://api-web.nhle.com/v1/network/tv-schedule/now```
- ```https://api-web.nhle.com/v1/network/tv-schedule/{date}```
## Betting odds from nhl partners
- ```https://api-web.nhle.com/v1/partner-game/{country-code}/now```
## Every season id
- ```https://api-web.nhle.com/v1/season```

<br><br>
**[Back to top](#readme)**
