
# 🔐 Simple Login Page (HTML + CSS + JavaScript)

A clean and minimal login interface built using HTML, CSS, and JavaScript. This project uses simple client-side logic with JavaScript promises to validate user credentials.

---

## 📁 Project Structure

```

simple-login/
├── index.html      # The main login form layout
├── style.css       # Styling for the login UI
├── index.js        # JavaScript for login validation
├── README.md       # Project documentation

````

---

## 🚀 Features

- 📱 Phone number and password input fields
- ✅ Basic client-side login validation
- 🛡️ Displays a success or error message based on input
- 🎨 Styled with modern, responsive CSS
- ⚡ Instant feedback without page reload

---
## 🧪 How to Use

1. **Clone or download** this repository.
2. Open `index.html` in any modern browser.
3. Enter:
   - Phone: `1234`
   - Password: `1234`
4. Press the **Login** button to test the validation.

---

## 🧠 How It Works

- The `login()` function retrieves input values and uses a Promise to simulate authentication.
- If the phone and password match `1234`, it shows a success message.
- Otherwise, it shows an error message — all handled in `index.js`.

```js
function checkCredentials(phone, password) {
    return new Promise((resolve, reject) => {
        if (phone === "1234" && password === "1234") {
            resolve("Login successful!");
        } else {
            reject("Invalid phone or password.");
        }
    });
}
````

---

## 🛠️ Technologies Used

* ✅ HTML5
* 🎨 CSS3 (no frameworks)
* ⚙️ Vanilla JavaScript

---

## 📌 Note

> This is a **frontend-only demo**. No actual backend or database integration is used.

---


