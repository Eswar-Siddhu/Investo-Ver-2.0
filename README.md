# Investo Family Portfolio Tracker

A secure, offline-first, mobile-responsive web application designed to track, visualize, and analyze your family's investment portfolio directly from your `Investo.xlsx` Excel file. 

The application runs 100% locally in your browser. Your financial data never leaves your device.

## Features

*   **Dual Portfolio Views:** Instantly toggle between the "Overall Portfolio" (Combined) and "Nivedha's Portfolio" (Exclusive assets and tagged Mutual Funds).
*   **Zero Server Architecture:** Uses `SheetJS` to parse complex Excel matrices directly in browser memory. 
*   **Dynamic Visualizations:** Interactive asset allocation, liquidity, and ownership donut charts using `Chart.js`.
*   **Cumulative Growth Tracking:** Automatically generates chronological trend lines combining SIP and Lumpsum transaction ledgers.
*   **Goal Planner & Insights:** Interactive sliders to project future corpus growth, alongside automated insights calculating your 3M, 6M, and 12M average investment rates based on raw transaction data.
*   **Smart Tables:** Sortable, auto-formatted data tables that automatically detect Rupee (₹) and Percentage (%) contexts.
*   **Dark Mode Integration:** Built-in floating toggle to seamlessly switch between light and dark themes.

## Setup Instructions (GitHub Pages)

1. Create a new repository on GitHub.
2. Create a file named `index.html` in the root of the repository.
3. Copy the entire HTML code block below and paste it into `index.html`.
4. Go to your repository **Settings** > **Pages**.
5. Under **Build and deployment**, set the source to deploy from the `main` branch.
6. Open your live GitHub Pages URL on your mobile or desktop browser and upload your `Investo.xlsx` file.

---
