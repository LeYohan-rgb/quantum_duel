# Quantum Duel

This web game is a local two-player battle game where you have the ability to shoot an infinite amount of bullets at your opponent, and the first one to take the other down wins!
It was deliberately made to be under 3kb, as part of the program [Shrink](https://shrink.hackclub.com/) by Hack Club. 

## Inspiration

This was inspired by one of the first games I made to learn Godot called 'Space Duel'. It was about two spaceships which could only shoot 10 bullets before needing to recharge, and each one had a special ability.
Sadly, I couldn't include all of this without making the game way over 3kb.

# Features
<img width="1252" height="466" alt="image" src="https://github.com/user-attachments/assets/4c423ae6-77c8-48d6-88ff-873556d475d0" />
<br><br>
-<b>Eight-directional movement</b><br>
-<b>Bullet generator</b><br>
-<b>Health bar</b><br>
-<b>Winning detector</b><br>
-<b>Collision detector</b><br><br>
Each player has their own side of the map, being able to move in all eight directions. However, they cannot pass to the other side separated by the wall in the middle, which only bullets can pass through.
Each player has 10 HP at the start, each bullet dealing one HP. The first player to reach 0 loses the game. To play again, it suffices to restart the page.

## Controls

<strong>Red player</strong><br>
WASD — Movement<br>
E — Shoot<br>

<strong>Blue player</strong><br>
Arrow Keys — Movement<br>
Right Ctrl — Shoot

# Building

To make this project, I used <strong>VS Code, Node.js, and Git</strong>. All the code lies on the HTML file (`src/index.html`). By running
`git init`
`npm init -y`
`npm install --save-dev terser`
in the terminal I installed a terser, helping shrink down my JavaScript code. <br><br>
By making a `build.mjs` file I managed to shrink down the code to just a single line, which I can see through the file  `dist/uri.txt`. By running `node build.mjs` I could constantly check the
byte size of the files (I had to run this quite a few times to ensure it was under 3kb).

### Experience

As my first ever battle game on a website, I'm quite happy with the result. Even though at first it was challenging adapting all the code I had learned from Godot (and I often wrote GDScript mid-script), 
this was an enjoyable learning experience! While the size limitation ended up making a totally different game from what I expected, prioritizing the important features still made an enjoyable game as a whole,
which felt very rewarding.

## How to run locally
1- Click on Code -> Download ZIP<br>
2- After downloading, extract all the files.<br>
3- Open the folder and go to `src`.<br>
4- Open the `index` file with your browser, and done!<br>

Alternately, if you want to run this by pasting the code directly on your browser, then:<br>

1- Go to the `dist` folder in the repository.<br>
2- Go to `uri.txt`.<br>
3- Copy the first line and paste it onto your web broswer.<br>
4- Click Enter, and done!<br>

# AI Disclosure
AI was used for learning-purposes only. Specifically, it was mainly used for the movement and collision code.
