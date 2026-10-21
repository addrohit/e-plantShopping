# Paradise Nursery Shopping Application

An e-commerce plant shopping web application built with **React**, **Redux Toolkit**, and **Vite** as part of the IBM Front-End Developer Professional Certificate coursework.

## Project Overview

**Paradise Nursery** is an online platform for plant enthusiasts to explore and purchase a variety of indoor houseplants. The application provides an intuitive user interface to browse plant collections, view plant details, manage a shopping cart, and calculate totals in real-time.

## Key Features

- **Landing Page**: An inviting landing page with background imagery, brand mission statement, and a "Get Started" call-to-action button.
- **Product Catalog**: Categorized plant listings (Air Purifying Plants, Aromatic Fragrant Plants, and Insect Repellent Plants) showcasing plant names, images, descriptions, and pricing.
- **Dynamic Shopping Cart**:
  - Global state management using **Redux Toolkit** (`CartSlice.jsx`).
  - Add plants to cart with instant visual feedback (button states and dynamic badge counter).
  - Adjust item quantities (increment/decrement) with automatic subtotal and grand total recalculation.
  - Remove items from cart.
  - Seamless navigation between the cart and plant catalog ("Continue Shopping").
  - Checkout prompt and confirmation.

## Technology Stack

- **Frontend Framework**: React 18
- **State Management**: Redux Toolkit & React-Redux
- **Build Tool & Dev Server**: Vite
- **Styling**: Vanilla CSS3 (CSS modules & responsive layouts)
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/addrohit/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```