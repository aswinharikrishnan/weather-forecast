# Weather Forecast Application 🌤️

## Overview
A high-performance, responsive Weather Forecasting application built to deliver real-time meteorological data. This project leverages the speed of **Next.js** for optimized rendering and the strict type safety of **TypeScript** to ensure a robust, scalable architecture. 

## 🏗️ Tech Stack
*   **Framework:** Next.js (React)
*   **Language:** TypeScript
*   **Styling:** Tailwind CSS
*   **Data Fetching:** Server-Side Rendering (SSR) / Static Site Generation (SSG) via Next.js
*   **API:** [Insert API Name, e.g., OpenWeatherMap API]

## ✨ Core Features
*   **Real-Time Data:** Fetches and displays accurate, up-to-the-minute weather conditions.
*   **Type-Safe Architecture:** Comprehensive TypeScript interfaces for API responses and React component props, eliminating runtime undefined errors.
*   **Optimized Performance:** Utilizes Next.js native optimization for lightning-fast page loads and superior Core Web Vitals.
*   **Responsive UI:** Fully mobile-optimized interface ensuring seamless user experience across all devices.
*   **Dynamic Routing:** Capable of handling search queries for different global locations instantly.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed on your local machine:
*   Node.js (v16.x or higher)
*   npm or yarn

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aswinharikrishnan/weather-forecast.git](https://github.com/aswinharikrishnan/weather-forecast.git)
    cd weather-forecast
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Environment Variables:**
    Create a `.env.local` file in the root directory and add your API credentials:
    ```env
    NEXT_PUBLIC_WEATHER_API_KEY=your_api_key_here
    ```

4.  **Run the Development Server:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 🧠 Architectural Decisions
*   **Why Next.js?** Chosen to bypass the traditional React client-side rendering bottlenecks, improving initial load times and providing built-in API routing capabilities if backend logic abstraction is needed.
*   **Why TypeScript?** To enforce strict data contracts when communicating with external weather APIs, ensuring the UI components always receive the exact data structures they expect.
