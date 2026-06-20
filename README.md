# Premier League 2024/25 — Team Dashboard

A full one-page analytical report card for any Premier League club — form, scoring trend, top scorers, discipline, and shot map, all in a single coordinated dashboard. Built from StatsBomb event data.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python) ![SVG](https://img.shields.io/badge/Viz-SVG%20%2B%20JS-orange?style=flat-square) ![Data](https://img.shields.io/badge/Data-StatsBomb-red?style=flat-square)

---

## Live Demo

**[Open Team Dashboard](https://leiderip.github.io/Premier-League-2024-25-Team-Dashboard/Team_Dashboard.html)**

---

## Features

- **KPI strip** — league position, points, W-D-L, goals for/against, goal difference
- **Recent form** — last 10 results as colour-coded chips, hoverable for score and opponent
- **Goals & xG trend** — a season-long line chart of goals for, goals against, and xG for by matchday
- **Top scorers** — every player who scored for the club, ranked
- **Discipline** — fouls committed, yellow and red cards
- **Style & output** — pass completion %, shots per game, shots on target, xG for/against per game
- **Season shot map** — every shot the club took, sized by xG, goals highlighted
- **Dark / Light theme toggle**

---

## Method

Every match is processed once per team to build a single match-level record (result, goals, shots, xG, fouls, cards, passes, scorers, shot locations), then aggregated across the season. The final league table is computed from points, then goal difference, then goals scored — the standard tie-break order.

**Match order** for the form/trend panels uses StatsBomb's internal `match_id`, the closest available proxy for real fixture order since the event export has no date column.

---

## Portfolio

| Project | Link |
|---|---|
| Title Race | [Live](https://leiderip.github.io/Premier-League-2024-25-Title-race/pl_position_race.html) |
| xG Race Explorer | [Live](https://leiderip.github.io/Premier-League-2024-25-xG-Title-race-/xG_Race_Explorer.html) |
| Season Shot Map | [Live](https://leiderip.github.io/Premier-League-2024-25-Shot-Map/Shot_Map.html) |
| Top Scorers vs xG | [Live](https://leiderip.github.io/Premier-League-2024-25-Top-Scorers-xG/Top_Scorers_xG.html) |
| Player Heatmap | [Live](https://leiderip.github.io/Premier-League-2024-25-Player-Heatmap/Player_Heatmap.html) |
| Scouting Radar | [Live](https://leiderip.github.io/Premier-League-2024-25-Scouting_Radar/Scouting_Radar.html) |
| Pass Network | [Live](https://leiderip.github.io/Premier-League-2024-25-Pass-Network/Pass_Network.html) |
| Match Momentum | [Live](https://leiderip.github.io/Premier-League-2024-25-Match-Momentum/Match_Momentum.html) |
| Goalkeeper Performance | [Live](https://leiderip.github.io/Premier-League-2024-25-Goalkeeper-Performance/Goalkeeper_Performance.html) |
| Attacking Bands | [Live](https://leiderip.github.io/Premier-League-2024-25-Attacking-Bands/Attacking_Bands.html) |
| Set Piece Threat | [Live](https://leiderip.github.io/Premier-League-2024-25-Set-Piece-Threat/Set_Piece_Threat.html) |
| Goal Rain | [Live](https://leiderip.github.io/Premier-League-2024-25-Goal-Rain/Goal_Rain.html) |
| Team Dashboard | This project |

---

*Data © StatsBomb.*
