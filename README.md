# ⌨️ Event KeyCodes

A simple JavaScript project that detects keyboard input and displays useful information about the key pressed.

Press any key on your keyboard and the page will instantly show:

* 🔑 **Key** — The actual key that was pressed
* 🔢 **KeyCode** — The numeric key code
* 💻 **Code** — The physical key code provided by the browser

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript

## 🧠 Concepts Practiced

This project helped me practice:

* Keyboard events
* `keydown` event
* Event listeners
* DOM manipulation
* Template literals
* Conditional expressions
* Dynamic HTML generation
* Working with event object properties such as `key`, `keyCode`, and `code`

## ⚙️ How It Works

The project listens for the `keydown` event on the entire window.

Whenever a key is pressed, JavaScript retrieves information from the event object and dynamically updates the page.

```javascript
window.addEventListener('keydown', (e) => {
    console.log(e.key)
    console.log(e.keyCode)
    console.log(e.code)
})
```

The displayed information updates every time another key is pressed.

## ▶️ How to Run

1. Clone the repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Press any key on your keyboard.
5. See the key information displayed on the screen.

## 📸 Preview

*Add a screenshot or GIF of the project here.*

## 📚 What I Learned

This project helped me understand how JavaScript can listen for user keyboard interactions and use the event object to access information about the event.

---

⭐ If you found this project useful, consider giving the repository a star!
