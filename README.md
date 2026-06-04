# 📜 Quote of the Day Generator

A simple and interactive web application that fetches inspirational quotes from an online API and displays them in a beautifully designed quote card. Users can generate new quotes instantly and share them on Twitter/X.

---

## 🚀 Features

✅ Fetches random quotes dynamically from the Quotable API

✅ Displays quote author information

✅ Generate a new quote with a single click

✅ Share quotes directly on Twitter/X

✅ Responsive and modern UI

✅ Built using pure HTML, CSS, and JavaScript

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API
- Quotable API
- Google Fonts

---

## 📂 Project Structure

```text
quote-generator-repo/
│
├── index.html
├── style.css
├── twitter.jpg
└── README.md
```

---

## ⚙️ How It Works

1. The application loads.
2. JavaScript sends a request to the Quotable API.
3. A random quote is retrieved.
4. The quote and author are displayed inside the quote box.
5. Clicking **New Quote** fetches another quote.
6. Clicking **Tweet** opens Twitter/X with the quote pre-filled.

---

## 🔄 Workflow

```text
User Opens Website
        │
        ▼
Fetch Request Sent
        │
        ▼
Quotable API
        │
        ▼
Random Quote Received
        │
        ▼
Display Quote + Author
        │
        ▼
User Actions
 ├── New Quote
 └── Tweet Quote
```

---

## 🧠 Key Concepts Demonstrated

### DOM Manipulation
Updating quote and author content dynamically.

### Fetch API
Retrieving data from an external REST API.

### Async/Await
Handling asynchronous API requests.

### Event Handling
Responding to button clicks.

### Responsive Design
Creating a clean user experience across devices.

---


## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/lekhanaUdata/quote-generator-repo.git
```

Navigate to the project directory:

```bash
cd quote-generator-repo
```

Run the application by opening:

```text
index.html
```

in your browser.

---

## 🎯 Learning Outcomes

This project helped in understanding:

- REST APIs
- JavaScript Fetch API
- Async Programming
- DOM Manipulation
- Event Handling
- Responsive UI Design

---

## 🔮 Future Enhancements

- Add quote categories
- Dark/Light mode toggle
- Copy quote to clipboard
- Save favorite quotes
- Download quote as image
- Multiple social media sharing options

---

## 💡 Interview Questions

### Why did you use Fetch API?

Fetch API provides a modern and promise-based way to retrieve data from external APIs.

### Why use async/await?

It makes asynchronous code easier to read and maintain compared to traditional promise chaining.

### What is DOM Manipulation?

DOM manipulation allows JavaScript to dynamically update webpage content without reloading the page.

### How does the Tweet feature work?

The application opens a Twitter/X share URL containing the generated quote and author.

### What happens when the API is unavailable?

The application would fail to load quotes. Error handling can be added using try-catch blocks.

---

## 👨‍💻 Author

**Udata Lekhana Surya Bhanu**

GitHub:
https://github.com/lekhanaUdata

---

## 📄 License

This project is open-source and available under the MIT License.
