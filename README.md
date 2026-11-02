# Hand-Cricket

A real-time two-player hand cricket game built with plain HTML, CSS, and JavaScript.

Players can play on one device or connect from separate devices using a room code/link. Choices stay hidden until both players reveal their hands.


## How to play

1. Open the game link.
2. Choose **Create an online room**.
3. Enter Player 1's name.
4. Share the generated room link or four-character room code with Player 2.
5. Player 2 opens the link, enters their name, and joins.
6. Both players play rock-paper-scissors for the toss.
7. The toss winner chooses to bat or bowl first.
8. During every ball, both players choose a number from 0 to 6.
9. Choices remain private until the reveal.
10. If batter and bowler choose the same number, the batter is out. Otherwise, the batter scores their selected number.

## Features

- Two-player real-time online rooms
- One-device local mode
- Rock-paper-scissors toss
- Private selections until reveal
- Animated hand gestures for numbers, rock, paper, and scissors
- Ball-by-ball commentary
- Scoreboard, innings, target, wickets, and winner screen
- Optional Player 2 AI mode
- Keyboard controls and sound effects
- Responsive design for desktop and mobile

## Controls

### Player 1

- Number keys `0–6` to choose a hand
- `1`, `2`, `3` during toss for Rock, Paper, and Scissors
- `Space` or `Enter` to begin the next ball when applicable

### Player 2

- `A S D F G H J` for hand numbers `0–6`
- `A`, `S`, `D` during toss for Rock, Paper, and Scissors

## Technology

- HTML
- CSS
- Vanilla JavaScript
- PeerJS
- WebRTC
- GitHub Pages

## Important note about online rooms

The game uses WebRTC through PeerJS for free browser-to-browser multiplayer. The player who creates the room is the host, so their game tab must remain open while the match is active.

No account, database, or paid backend is required.
