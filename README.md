# 💰 Investment Calculator

A simple yet functional **investment calculator** built with **React** and **Vite**, allowing users to estimate long-term investment growth based on customizable financial inputs.

---

## 🚀 Purpose

This project simulates how an investment grows over time, taking into account:
- Initial investment
- Annual contributions
- Expected annual return rate
- Duration in years

It was built to **practice core React concepts** in a hands-on project with real-world application.

---

## 🛠️ Technologies Used

| Tech            | Purpose |
|-----------------|---------|
| **React**       | Component-based UI and state management |
| **Vite**        | Fast development server and build tool |
| **JavaScript**  | App logic and DOM interaction |
| **HTML/CSS**    | Structure and styling |

---

## 🧠 What I Practiced

### 🔄 `useState` for dynamic UI
- Used to store and update user input dynamically.
- Triggered re-renders when the form changed.

### 📤 Props & Event Handling
- Passed input data and change handlers between components:
  - `App` → `UserInput`
  - `App` → `Results`
- Allowed separation of concerns between data logic and UI rendering.

### 📊 Custom calculation logic
- Implemented investment growth logic in a reusable function:  
  `calculateInvestmentResults(...)`
- Used arrays and math operations to compute year-by-year data.

### 🧩 Modular structure
- Split the app into focused components:
  - `App`
  - `Header`
  - `UserInput`
  - `Results`

---

## ✨ Features

- 📈 Real-time investment growth results
- 📬 Instant feedback when duration is invalid
- 🧠 Yearly breakdown of:
  - Interest earned
  - Invested capital
  - Total value
- 💻 Clean, responsive layout

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DanaTza/investment-calculator.git
cd investment-calculator
2. Install Dependencies
bash
npm install
3. Start the App
bash
npm run dev
4. Visit in Your Browser
http://localhost:5173

📚 Learning Goals
✅ Understand how to manage form input state in React
✅ Practice data flow between components
✅ Reinforce modular thinking in UI design
✅ Build logic-heavy functionality in a maintainable way



 Author,
 DanaTza
