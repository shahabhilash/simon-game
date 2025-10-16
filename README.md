# simon-game
🧩 A fun and interactive Simon Says Game built using HTML, CSS, and JavaScript.
)

🎮 How to Play

Press any key to start the game.

Watch carefully as the game flashes a sequence of buttons (colors).

Click the buttons in the same order.

Each round adds one more color to the sequence — keep up as it gets harder!

If you make a mistake, the screen flashes red and the game restarts.

🧠 Game Logic Explained

When the player presses a key for the first time, the game starts and generates a random color sequence.

Each new level adds one random color to the gameSeq array.

The user’s clicks are stored in the userSeq array.

After each click, the game compares the player’s input with the generated sequence using checkAns().

If all inputs match, the level increases; if not, the game resets and shows the score.
)

🎮 How to Play

Press any key to start the game.

Watch carefully as the game flashes a sequence of buttons (colors).

Click the buttons in the same order.

Each round adds one more color to the sequence — keep up as it gets harder!

If you make a mistake, the screen flashes red and the game restarts.

🧠 Game Logic Explained

When the player presses a key for the first time, the game starts and generates a random color sequence.

Each new level adds one random color to the gameSeq array.

The user’s clicks are stored in the userSeq array.

After each click, the game compares the player’s input with the generated sequence using checkAns().

If all inputs match, the level increases; if not, the game resets and shows the score.
🧩 Key JavaScript Features

Dynamic level progression with levelUp()

Randomized color generation using arrays and Math.random()

Real-time user input validation

DOM manipulation for flashes and text updates

Restart mechanism with visual feedback

🎨 CSS Features

Flexbox layout for centering buttons

Color-coded .btn elements (red, green, yellow, blue/purple)

Smooth transitions for flashes and user clicks

Responsive design for smaller screens
