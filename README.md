# Cursor Ball
by fishyramen

Cursor Ball is a minimal 2D reflex game where you deflect a ball using your cursor while managing pressure from a shrinking timer. The goal is to keep the ball from reaching your back wall and outlast the bot (I plan on adding multiplayer but maybe some other time).

## How to Run

1. Download or clone the repository.
2. Open index.html in any modern browser (Chrome, Edge, Firefox).
3. No build step or server required.

Optional (recommended for development):
npx serve

## How to Play

- Move your mouse to control the cursor dot.
- Hit the ball by touching it while it is on your side.
- You may hit the ball multiple times on your side as long as your timer is not empty.
- The timer only drains when the ball is inside your zone and recharges while the ball is away.
- If the ball touches your back wall or your timer reaches zero, you lose the point.

## Win Conditions

- First to 7 points wins.
- Win by 2.
- At 6–6, Sudden Death activates with faster ball speed and shorter timers.

## Controls

- Mouse: Move cursor
- P: Pause
- R: Restart
- Esc: Settings

## Settings

- Bot level: Controls reaction speed and accuracy
- Prediction: How well the bot reads your movement
- Playstyle: Defense to offense balance
- Sound and volume
- Fullscreen toggle

---

© 2026 fishyramen. All rights reserved.

