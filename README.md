# AegisCare

AegisCare is a feature-rich, privacy-conscious personal financial and health assistant web application. It is designed to help users track finances, analyze transaction data, manage debt, and query general health guidelines—all while keeping sensitive data securely on the local device.

## Features

### 📊 Financial & Spending Management
* **Spend Analysis & Rule-Based Flags**: Automatically parses CSV datasets or demo company data to detect unusual transactions, category breakdowns, and potential financial risks.
* **Simulated Live Record Feed**: Real-time incoming record simulation to test live-tracking workflows.
* **Quick Financial Calculators**: Built-in tools for loan payments, savings growth, BMI, daily caloric needs, and HSA tax savings.
* **Debt Payoff & Health Score Tools**: Evaluates overall financial health and compares avalanche vs. snowball debt payoff strategies.

### 🤖 Intelligent Assistant & Models
* **Model Selection**: Switch between specialized AI models such as *Architect 4*, *Architect 3.5*, and *Health-focused Altorz 1.5*.
* **Customizable Modes**: Tailor the assistant's behavior across Finance, Product Management, and Enterprise Search modes.
* **Auto-Notes**: Automatically captures key decisions, figures, and action items from chat conversations into structured note drafts.

### 🔒 Privacy & Local Storage
* **Local-First Architecture**: Chats, notes, profiles, and transaction data are stored locally in the browser (`localStorage`).
* **Data Export & Wipe**: Easily export all user data to a JSON file or securely wipe local storage at any time.

---

## Tech Stack
* **Frontend**: Vanilla HTML5, modern CSS3 (with responsive layouts, dark mode support, and smooth glassmorphism styling), and JavaScript.
* **Authentication**: Supports Google Identity Services (OAuth) and secure local account management.
* **Integration**: Optional backend worker connection for advanced AI inference and web-search capabilities.

---

## Getting Started

Because AegisCare is delivered as a single-page client-side application (`index.html`), getting started is simple:

1. Clone or download this repository.
2. Open `index.html.html` (or rename it to `index.html`) directly in any modern web browser.
3. *Optional*: Load the **Demo Co** dataset right from the interface to explore analytics, transaction flags, and calculators immediately.

---

## Responsible AI & Disclaimer
* AegisCare provides general financial and wellness guidance, not professional financial advice, tax planning, or medical diagnoses.
* Always consult a qualified professional for major financial, legal, or health-related decisions.
