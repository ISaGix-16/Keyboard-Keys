# ⌨️ Event KeyCodes

A simple and interactive JavaScript project that detects keyboard input and displays information about the key pressed.

Press any key on your keyboard and the application will instantly display the **Key**, **KeyCode**, and **Code** associated with it.

---

## 🚀 Features

* ⌨️ Detects keyboard key presses in real time
* 🔑 Displays the pressed **Key**
* 🔢 Displays the **KeyCode**
* 💻 Displays the **Code**
* ⚡ Updates instantly whenever another key is pressed
* 🎨 Simple and clean user interface
* 📱 Responsive webpage structure

---

## 🛠️ Technologies Used

* **HTML5** — Structure of the webpage
* **CSS3** — Styling and layout
* **JavaScript** — Keyboard event handling and dynamic content

---

## 📂 Project Structure

```text
Event-KeyCodes/
│
├── index.html
├── style.css
└── keyboard.js
```

---

## ⚙️ How It Works

The application listens for keyboard events using JavaScript's `keydown` event.

Whenever a key is pressed, the event object provides information about that key.

The application extracts:

### 🔑 Key

`e.key` returns the value of the key that was pressed.

For example:

```text
a
Enter
Shift
ArrowUp
```

For the Space key, the project displays `Space` instead of an empty-looking space character.

### 🔢 KeyCode

`e.keyCode` returns the numeric key code associated with the pressed key.

> **Note:** `keyCode` is deprecated in modern JavaScript, but it is included in this project for learning and understanding keyboard events.

### 💻 Code

`e.code` identifies the physical key on the keyboard.

For example:

```text
KeyA
Enter
Space
ArrowUp
```

---

## 🧠 JavaScript Concepts Practiced

This project demonstrates several important JavaScript concepts:

* `addEventListener()`
* `keydown` events
* Event objects
* DOM manipulation
* `getElementById()`
* `innerHTML`
* Template literals
* Conditional expressions
* Accessing object properties
* Dynamic HTML generation
* Functions and callbacks

---

## ▶️ How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Press any key on your keyboard.
5. The information about the pressed key will appear on the screen.

---

## 🎯 Example

If you press the **A** key, the application will display information similar to:

| Key | KeyCode | Code |
| --- | ------: | ---- |
| a   |      65 | KeyA |

If you press the **Enter** key:

| Key   | KeyCode | Code  |
| ----- | ------: | ----- |
| Enter |      13 | Enter |

---

## 📖 What I Learned

Through this project, I learned how JavaScript can interact with keyboard input and respond to user actions in real time.

I also learned how to use the browser's event object to retrieve information about keyboard events and dynamically update HTML content using JavaScript.

---

## 📌 Important Note

The `keyCode` property used in this project is deprecated.

Modern JavaScript applications should generally use:

```javascript
event.key
event.code
```

instead of:

```javascript
event.keyCode
```

However, `keyCode` is intentionally used here as part of learning and understanding keyboard events.

---

## 👨‍💻 Author

**Aman Arya**

---

## ⭐ Acknowledgement

This project was created as part of my JavaScript learning journey to practice **DOM manipulation and browser events**.

