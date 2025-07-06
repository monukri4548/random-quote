# 🎲 Boredom Buster App

This is a fun Node.js web application that suggests random activities to help you beat boredom! It uses the [Bored API](https://www.boredapi.com/) to fetch activity suggestions based on type and number of participants.

---

## 🧠 How It Works

- When you visit the home page (`/`), the app shows a random activity suggestion.
- You can filter activities by **type** (e.g. education, recreational, cooking) and **number of participants**.
- If no activity matches your filters, the app gracefully handles the error and informs the user.

---

## 🚀 Features

- Fetches a random activity on page load
- Users can select:
  - Type of activity
  - Number of participants
- Displays a random match from the filtered results
- Error handling for empty or invalid results

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Templating**: EJS
- **HTTP Client**: Axios
- **Middleware**: body-parser

---

## 📁 Project Structure

boredom-buster-app/
│
├── public/ # Static assets (e.g., CSS)
├── views/
│ └── index.ejs # Main HTML template
├── app.js # Main Express application
├── package.json
└── README.md

---

## ▶️ Getting Started

### 1. Clone the repository
git clone https://github.com/your-username/boredom-buster-app.git
cd boredom-buster-app

2. Install dependencies
npm install

3. Run the app
node app.js
Then open your browser and visit:
http://localhost:3000
