# 💱Currency Converter

## Description
This is a simple Currency Converter web application built with React and Tailwind Css It allows users to convert an amount from one currency to another based on real-time exchange rates fetched from an API.
- **🔄Real-time currency conversion**  
- **🌎Supports multiple currencies**
## Link(https://verdant-mochi-1900ae.netlify.app/)
![Screenshot 2024-12-25 224142](https://github.com/user-attachments/assets/5ef036bd-abc3-4c20-8021-20c459bb84c2)


## 🌟Features
- Convert between multiple currencies.
- Swap Option to swap 'From' to 'To'
- Real-time exchange rate updates using the [ExchangeRate-API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.json).
- Easy-to-use interface.

## 🚀Technologies Used
- **React**: For the structure and functionality of the webpage.
- **Tailwind CSS**: For the styling of the page.
- **API**: [ExchangeRate-API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.json) for real-time currency exchange rates.

  ##  🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abhishek526-star/Currency_Converter.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Currency_Converter
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Install Tailwind CSS:**
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init
   ```
5. **Configure Tailwind CSS in `tailwind.config.js`:**
   ```javascript
   module.exports = {
     content: ["./src/**/*.{js,jsx,ts,tsx}", "./public/index.html"],
     theme: { extend: {} },
     plugins: [],
   };
   ```
6. **Add Tailwind to your CSS file (e.g., `src/index.css`):**
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```
7. **Start the app:**
   ```bash
   npm start
   ```
