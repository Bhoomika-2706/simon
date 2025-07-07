# simon
# 🎮 Simon Says Memory Game

This is a web-based **Simon Says memory game**, where the player must repeat an increasingly long sequence of color flashes. It's built using **HTML**, **CSS**, **JavaScript**, and **jQuery**.

---

## 📁 Project Structure

/simon-game
│
├── index.html # Main HTML page
├── style.css # Styling for the game
├── script.js # Game logic using JavaScript
└── /sounds # Folder containing sound effects
├── red.mp3
├── blue.mp3
├── green.mp3
├── yellow.mp3
└── wrong.mp3

---

## 🚀 How to Run the Project

1. **Clone or Download** the project folder.

2. Make sure you have the following files:
   - `index.html`
   - `style.css`
   - `script.js`
   - `sounds/` folder with the `.mp3` sound files

3. **Open `index.html` in a browser** (double-click or right-click → open with browser).

4. Click the **"Play" button** or press any key to start the game.

---

## 🎮 How to Play

- The game flashes a color pattern one step at a time.
- Repeat the sequence by clicking the colored boxes.
- Each level adds a new color to the sequence.
- If you click the wrong color, the game ends and shows a **"Game Over"** message.
- Press **"Play"** again to restart from level 0.

---

## 💻 Technologies Used

- HTML
- CSS
- JavaScript
- jQuery (via CDN)

---

## 📦 Dependencies

The game uses the jQuery library. It is included in the HTML via this CDN:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
No other external libraries are required.

📌 Notes
Ensure sound files are correctly named and placed in the sounds/ folder.

For mobile devices, you may need to tap a few times due to browser audio restrictions.
