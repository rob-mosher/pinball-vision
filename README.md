# pinball-vision

### Description

Detects, stores, visualizes, and analyzes pinball gameplay data via a camera and logic device such as a Raspbery Pi.

Aims to improve a players skill by finding trends and correlations in their gameplay. Also helps understand the nature of the game they are playing.

### Analytics

T2FP means time-to-first/next-point 

- Date/time of game
- Duration, per session, game, and ball (with and without T2FP)
- GamePlayedID
- Games played, per session
- Is ball saved, per ball
- Is highscore obtained
- Is valid game
- Match / free game
- Points, per game, and ball
- Points per minute, not including T2FP
- Set timeout to first/fresh game (default to 30 mins)
- Tilt, per ball
- Tilt warn, per ball
- Time to first/next point, per ball (T2FP)

### Perspectives

Sortable by all, last x games, last x sessions, last 30 days, etc.

- Averages
- Box plot
- Calendar (similar to GitHub's contribution calendar)
- First/last 1 or 5 game scores
- Omitting first, last, and only games
- Stacked distributions

### Features

1. Web-based GUI

### Features under Consideration

1. Timezone support
1. Auto-detect game based on backglass and/or playfield
1. Multiplayer
1. Post stats online through `pinball-vision` public website (via Pinside username, etc)
1. Real-time score accumulation, by point
1. Gather data via data lines (opposed to camera)

### Supported Games

This section is highly dependant on having access to actual access to a table where the camera and logic device can be tested.

#### Meteor (Stern 1979 / original ROM)

WIP.

- Balls per game: 5
- Validators 1 and 00
- End of game 00..90
