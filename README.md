# pinball-vision

### Description

Detects, stores, visualizes, and analyzes pinball gameplay data via a camera and logic device such as a Raspbery Pi.

Aims to improve a players skill by finding trends and correlations in their gameplay. Also helps understand the nature of the game their are playing.

### Data Detected and Tracked

T2FP means time-to-first/next-point 

- Ball saved, per ball
- Date/time of game
- Duration of ball
- Duration of ball, not including T2FP
- Duration of game
- Duration of game, not including T2FP
- GamePlayedID
- Highscore obtained
- Is valid game
- Match / free game
- Points per minute, not including T2FP
- Score after each ball
- Tilt, per ball
- Tilt warn, per ball
- Time to first/next point, per ball (T2FP)

### Features

1. Web-based GUI

### Features under Consideration

1. Auto-detect game based on backglass and/or playfield
1. Multiplayer
1. Post stats online through `pinside-vision` public website (via Pinside username, etc)

### Supported Games

This section is highly dependant on having access to actual access to a table where the camera and logic device can be tested.

#### Meteor (Stern 1979 / original ROM)

WIP.

- Balls per game: 5
- Validators 1 and 00
- End of game 00..90
