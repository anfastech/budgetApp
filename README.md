# BudgetApp Personal Finance Tracker

A lightweight, privacy-focused budgeting tool built with React to help users track expenses and achieve financial freedom. BudgetApp leverages modern frontend technologies and stores data locally using the browser's `localStorage` to ensure user data remains private.

🌐 **Live Demo**: [budget-app-anfastech.vercel.app](https://budget-app-anfastech.vercel.app)

## Features
- **Intuitive Expense Tracking**: Easily add, categorize, and monitor your expenses.
- **Local Data Storage**: All data is stored in the browser's `localStorage` for maximum privacy.
- **Responsive Design**: Optimized for both desktop and mobile devices using Tailwind CSS.
- **Fast & Lightweight**: Built with Vite for a blazing-fast user experience.
- **Category-Based Insights**: Visualize spending patterns with categorized expense breakdowns.

## Tech Stack
- **React**: Frontend library for building the user interface.
- **React Router**: Handles client-side routing for seamless navigation.
- **LocalStorage**: Stores user data securely in the browser.
- **Tailwind CSS**: Utility-first CSS framework for responsive and modern styling.
- **Vite**: Next-generation frontend tooling for fast development and builds.

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/anfastech/budgetApp
   ```
2. Navigate to the project directory:
   ```bash
   cd budget-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
   or
   ```bash
   yarn dev
   ```
5. Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

### Building for Production
To create a production-ready build:
```bash
npm run build
```
The output will be in the `dist` folder.

## Usage
1. **Add Expenses**: Input expense details, including amount, category, and date.
2. **View Insights**: Check spending patterns through category-based summaries.
3. **Manage Data**: Edit or delete expenses as needed. All data is saved automatically to `localStorage`.
4. **Clear Data**: Reset all data via the settings page (use with caution).

---

Happy budgeting! 🚀
