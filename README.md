# React Currency Converter

A web application that provides real-time currency exchange rates, built with React.js. It fetches live data from an exchange rate API and utilizes a custom hook for clean and reusable conversion logic.

[**Live Demo**](https://debasishsasmal.github.io/React-Currency-Converter/)
---

## Tech Stack

- **Framework:** React.js
- **Styling:** Tailwind CSS
- **Language:** JavaScript (ES6)

---

## Screenshot

<img width="1279" height="881" alt="image" src="https://github.com/user-attachments/assets/abae90cf-a0b5-44df-903e-c29408a0c4ef" />

---

## Features

- **Live Exchange Rates:** Fetches up-to-date currency conversion rates from a live API.
- **Custom Hook:** Encapsulates API logic into a reusable custom hook, promoting a clean and modular codebase.
- **Dynamic Conversion:** Instantly calculates and displays the converted amount as the user types.
- **Currency Swapping:** A user-friendly "swap" button to easily reverse the 'from' and 'to' currencies.
- **Responsive Design:** A simple and intuitive interface that works on any device.

---

## Core Concepts & Hooks Implemented

This project showcases a practical application of custom hooks and state management in React:

- **Custom Hook (`useCurrencyInfo`):** A custom hook was created to handle the logic for fetching and processing currency data from the API. This makes the main component cleaner and the logic reusable.
- **`useState`:** Manages state for the 'from' currency, 'to' currency, input amount, and the final converted amount.
- **`useEffect`:** Triggers the API call within the custom hook whenever the selected currency dependency changes.
- **API Fetching:** Interfaces with a live currency exchange API to provide accurate, real-time data.

---

## Getting Started / How to Run Locally

To get a local copy up and running, follow these simple steps.

1.  Clone the repository:
    ```sh
    git clone [https://github.com/debasishsasmal/React-Currency-Converter.git](https://github.com/debasishsasmal/React-Currency-Converter.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd React-Currency-Converter
    ```
3.  Install NPM packages:
    ```sh
    npm install
    ```
4.  Run the application:
    ```sh
    npm run dev
    ```
