# LUDO GO

**3 Pieces. 4 Rolls. Race Home!**

A fast, Nigerian Ludo-inspired challenge game designed for Snapchat. This repo holds the browser prototype.

## Play it

Open `index.html` in any browser, or play it live at **https://khal33d-hub.github.io/Ludo-Go-v3/**.

## Rules

- Each player has **3 pieces**, scattered at random **1 to 6 spaces from home**. Both players start from the same spots.
- Each player gets **4 rolls** of one six-sided die. Move one piece by the number rolled.
- A 6 is a normal roll, the same as any other number.
- A piece needs the **exact number** to get home. Overshooting isn't allowed.
- If no piece can move, the roll is lost.
- Pieces only move forwards. There's no killing, and pieces can share a square.
- A round ends when all three pieces are home or all four rolls are used.
- **To win:** most pieces home. If that's level, fewest steps left wins. If that's level too, it's a draw.

## Playing a challenge

- **Same phone:** Player 1 (Red) plays a round, then passes the phone to Player 2 (Yellow), who sees the score to beat. Rematch scatters the pieces again and swaps who goes first.
- **Different phones:** after a round you get a challenge code such as `LG-2.4.6-1-3-Khaleed`. It holds the starting spots, your pieces home, your steps left and your name. Your friend pastes it into "Got a challenge code?" and plays the same starting spots with their own dice. On the live site the copied message also includes a link that opens the challenge directly.

Challenge codes aren't tamper-proof. The real Snapchat build should keep results on the server side.

## Odds

With best play, a perfect finish (all 3 home) happens about 8% of the time, and players average 1.4 to 1.6 pieces home, depending on the starting spots.
