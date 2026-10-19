# Pocket Games

Four classic games in one app for Android phones and tablets: Sudoku, Solitaire, Spider Solitaire and Minesweeper. Works offline.

**Current version: 2.2**

## Games

**Sudoku**
- Easy, Medium, Hard, Expert and Extreme 9×9 puzzles built to standard difficulty, plus a quick Fast 6×6 mode, each with exactly one solution
- Kids 9×9 and Kids 6×6: extra-easy puzzles that cheer the child on by name, with sounds, vibration and fireworks
- Notes, auto notes, undo, erase, hints, auto-finish, encouraging words, saved games
- Stats for today, this week, month, year or all time, with Brain Activity scores, backup codes and Clear history

**Solitaire (Klondike)**
- Draw 1 or Draw 3, unlimited passes through the stock; build down in alternating colours; only Kings fill empty columns
- Tap a card to send it to the best spot, or drag it; undo, hints, and auto-finish once every card is face up
- Standard scoring: +10 to a foundation, +5 waste to column, +5 for turning a card, −15 foundation to column, time bonus of 700,000 ÷ seconds

**Spider Solitaire**
- 1, 2 or 4 suits; two decks, ten columns (four of 6 cards, six of 5), 50 cards in the stock for 5 deals
- Only same-suit runs move together; full King-to-Ace runs clear automatically; no dealing while a column is empty
- Microsoft scoring: start at 500, −1 per move, deal or undo, +100 per cleared run

**Minesweeper**
- Beginner 9×9 with 10 mines, Intermediate 16×16 with 40, Expert 30×16 with 99 (upright on a phone)
- The first tap always opens an area; long-press or Flag mode to flag; tap a number to open its neighbours once its flags are placed

Each game has its own home page, like Sudoku: continue a game in progress, pick a level, see your stats, read how to play. Games save as you go, pause when you leave, and keep their stats on the device.

## Install

Open https://kasemsleman1989-cyber.github.io/sudoku-by-claude/ in Chrome on Android, then tap **Install app** (or menu ⋮ → **Add to Home screen**).

## Changes

### 2.2
- Smoother Solitaire and Spider: every move, lift, flip and deal now runs on the phone's graphics chip, so nothing is redrawn while cards move
- Snappier timing: moves take 0.2 s, flips 0.28 s, and a new deal is about twice as fast
- Every tap on the deck counts, even fast ones (2.1 ignored taps for a moment after each draw)
- The deck no longer shimmers when you draw, and its top card lines up with the row
- Dragging follows your finger frame by frame, with no repainting behind the cards
- Cards are prepared while the game's home page is open and reused between games, so the first deal no longer freezes
- Lighter card faces (suits drawn as masks instead of SVG copies) and a faster score display

### 2.1
- Solitaire, Spider and Minesweeper each get a home page like Sudoku's: continue card, levels with your best result, a stats summary, and How to play
- Full stats for each game: Today, Week, Month, Year or All, filtered by level, with win rate, streaks, best and average times, best score, recent games and Clear history (stats from 2.0 carry over)
- Card games on a felt table with a fine grain texture; choose Emerald, Ocean, Wine or Slate felt and one of four card backs; optional four-colour suits
- New cards: crisp corner indices, court cards with crowns, full pip layouts on tablets, and a deck that shows its thickness
- 3D flips when cards turn over, cards that lift as they fly, an animated deal, glowing drop spots while you drag, pulsing hints, and the classic bouncing-card cascade when you win
- Minesweeper: raised tiles, a press effect, a growing ring while you long-press to flag, reveals that ripple out from your tap, flags that drop in, a blast and a mine-by-mine reveal when you hit one, and a Dig/Flag switch
- The status bar takes the felt colour while a card game is on screen

### 2.0
- Renamed to Pocket Games, with a new icon
- New games home showing all four games and any game in progress
- New: Solitaire (Klondike), Spider Solitaire and Minesweeper
- Sudoku moved to its own page with everything it had before
- The phone back button works across every game


### 1.25
- Kids levels about 30% easier: Kids 9×9 now has about 20 cells to fill (61 starting numbers), Kids 6×6 has 10 (26 starting numbers)
- Praise words 50% bigger, on screen 50% longer, with a 50% see-through bubble and a soft blur behind it
- More praise in the regular levels: words can come closer together, plus "Nice rhythm!" at 3 in a row and "Row done!", "Column done!", "Box complete!"
- Kids hear their name more: "Let's go, name!" at the start and in 2 of every 5 praise words
- Gentle named notes for kids' wrong numbers, for example "Oops, Sara! This row already has a 7, and each row can only have one 7."
- Kids Sound and Skip buttons moved next to Undo, Erase and Hint, leaving room for the notes in the top bar
- Fireworks last about 7 seconds and end with a big three-burst finale

### 1.2
- Clear history: removes every finished game and resets stats and Brain Activity, with an option to copy a backup code first; a game in progress stays
- Kids 9×9 (52 starting numbers) and Kids 6×6 (22 starting numbers), using only the easiest techniques
- Kids games ask "Who's playing?" and remember names
- Praise for every correct number, with the child's name every few numbers and at the halfway point
- A short buzz and a chime for each number (the chime rises as the board fills), and a speaker button to mute
- No mistakes counter and no game over for kids: a wrong number shows why in the top bar (for example "There's already a 5 in this row."), outlines the clashing number, then fades away
- Unlimited hints, a Skip button for a fresh puzzle, and fireworks with "Congratulations, name!" at the end
- Kids games are a sandbox: they're never recorded in stats and never touch a grown-up's game in progress

### 1.1
- Difficulty now follows the usual community ladder: Easy 38–42 starting numbers (box scanning), Medium 33–37 (row and column scanning), Hard 28–32 (pairs and locked candidates), Expert 24–28 (triples, X-Wing, Swordfish, Y-Wing, never guessing)
- New Extreme level: 22–26 starting numbers, beyond Expert techniques
- Auto-finish fills the last numbers one by one, with the number lit on the pad; tap the board to skip
- Encouraging words: Amazing! for real deductions, Sharp eye! for hard-to-spot singles, Great streak! / On fire! / Unstoppable! / Legendary run! for mistake-free streaks, and All 7s done!
- The phone back button closes stats and the question box, and leaves a game for the home screen
- Brain Activity redesigned around a move-by-move timeline:
  - Stamina: best sessions, daily play spread across the period, and holding your level late in a session
  - Sharpness: accuracy and mistake-free streaks only, speed doesn't count
  - Explosiveness: pace, peak 20-second bursts and fastest five numbers; mistakes count only lightly
  - Creativity: insight points for every number based on how hidden it was, fewer hints is better
  - Consistency: days played, day streak, finishing games and steady times
- Tap any Brain Activity score to see what goes into it

### 1.01
- New home screen: Continue your game, New game, and Your stats in one place
- In-game Home button; leaving a game pauses and saves it
- Starting a new game while one is in progress asks first, since the unfinished game counts as a loss
- End-of-game card offers Play another and Home

### 1.0
- First release
