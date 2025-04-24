# nhl api documentation

### 📌 Base URL: https://api-web.nhle.com/


### ✔️ Notes
### - date: YYYY-MM-DD (2025-04-24)
### - year: current year in 4 digit (2025)
### - season: season start year + season end year (20242025)
### - team: team abbreviation (COL, WSH...)
### - game-type: 2 = regular season, 3 = playoff game


### 🔹 Player Info

-     https://api-web.nhle.com/v1/player-spotlight
-     https://api-web.nhle.com/v1/player/{player}/landing
-     https://api-web.nhle.com/v1/player/{player}/game-log/now
-     https://api-web.nhle.com/v1/player/{player}/game-log/{season}/{game-type}


### 🔹 Schedule

-     https://api-web.nhle.com/v1/schedule/now
-     https://api-web.nhle.com/v1/schedule/{date}

### 🔹 Score

-     https://api-web.nhle.com/v1/score/now
-     https://api-web.nhle.com/v1/score/{date}

### 🔹 Standings

-     https://api-web.nhle.com/v1/standings-season
-     https://api-web.nhle.com/v1/standings/now
-     https://api-web.nhle.com/v1/standings/{date}

### 🔹 Skater Stats

-     https://api-web.nhle.com/v1/skater-stats-leaders/current
-     https://api-web.nhle.com/v1/skater-stats-leaders/{season}/{game-type}

### 🔹 Goalie Stats

-     https://api-web.nhle.com/v1/goalie-stats-leaders/current
-     https://api-web.nhle.com/v1/goalie-stats-leaders/{season}/{game-type}

### 🔹 Team Info

-     https://api-web.nhle.com/v1/club-stats/{team}/now
-     https://api-web.nhle.com/v1/club-stats/{team}/{season}/{game-type}
-     https://api-web.nhle.com/v1/club-stats-season/{team}

### 🔹 Roster

-     https://api-web.nhle.com/v1/roster/{team}/current
-     https://api-web.nhle.com/v1/roster/{team}/{season}
-     https://api-web.nhle.com/v1/roster-season/{team}

### 🔹 Schedule (Team-specific)

-     https://api-web.nhle.com/v1/club-schedule/{team}/month/now
-     https://api-web.nhle.com/v1/club-schedule/{team}/month/{month}
-     https://api-web.nhle.com/v1/club-schedule/{team}/week/now
-     https://api-web.nhle.com/v1/club-schedule/{team}/week/{date}
-     https://api-web.nhle.com/v1/club-schedule-season/{team}/now
-     https://api-web.nhle.com/v1/club-schedule-season/{team}/{season}

### 🔹 Gamecenter / Game Details

-     https://api-web.nhle.com/v1/gamecenter/{game-id}/landing
-     https://api-web.nhle.com/v1/gamecenter/{game-id}/boxscore
-     https://api-web.nhle.com/v1/gamecenter/{game-id}/play-by-play
-     https://api-web.nhle.com/v1/gamecenter/{game-id}/right-rail

### 🔹 Scoreboard

-     https://api-web.nhle.com/v1/scoreboard/now
-     https://api-web.nhle.com/v1/scoreboard/{date}
-     https://api-web.nhle.com/v1/scoreboard/{team}/now

### 🔹 Draft

-     https://api-web.nhle.com/v1/draft-tracker/picks/now
-     https://api-web.nhle.com/v1/draft/picks/now
-     https://api-web.nhle.com/v1/draft/picks/{year}/all
-     https://api-web.nhle.com/v1/draft/picks/{year}/{round}
-     https://api-web.nhle.com/v1/draft/rankings/now
-     https://api-web.nhle.com/v1/draft/rankings/{year}/{category}
-     https://api-web.nhle.com/v1/prospects/{team}

### 🔹 Where to Watch

-     https://api-web.nhle.com/v1/where-to-watch?include={string}
 
### 🔹 Location & Postal Info

-     https://api-web.nhle.com/v1/location
-     https://api-web.nhle.com//v1/postal-lookup/{postalCode}

### 🔹 Meta Info

-     https://api-web.nhle.com/v1/meta?players=&teams=&seasonStates=
-     https://api-web.nhle.com/v1/meta/playoff-series/{year}/{series_letter}
-     https://api-web.nhle.com/v1/meta/game/{game-id}

### 🔹 Playoffs

-     https://api-web.nhle.com/v1/playoff-series/carousel/{season}
-     https://api-web.nhle.com/v1/playoff-bracket/{year}

### 🔹 TV Schedule

-     https://api-web.nhle.com/v1/network/tv-schedule/now
-     https://api-web.nhle.com/v1/network/tv-schedule/{date}

### 🔹 PPT Replay

-     https://api-web.nhle.com//v1/ppt-replay/{game-id}/{event-number}
-     https://api-web.nhle.com//v1/ppt-replay/goal/{game-id}/{event-number}

### 🔹 Play-by-Play (WSC)

-     https://api-web.nhle.com/v1/wsc/play-by-play/{game-id}
-     https://api-web.nhle.com/v1/wsc/game-story/{game-id}

### 🔹 Partner Games

-     https://api-web.nhle.com//v1/partner-game/{country-code}/now

### 🔹 Season Info

-     https://api-web.nhle.com/v1/season

### 🔹 Schedule Calendar

-     https://api-web.nhle.com/v1/schedule-calendar/now
-     https://api-web.nhle.com/v1/schedule-calendar/{date}
