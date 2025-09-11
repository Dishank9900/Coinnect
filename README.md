# 🌍 Cryptoverse - Explore the World of Cryptocurrency  

![Cryptoverse](https://i.ibb.co/8gh5Jc8/image.png)  

### [⚡ Learn React & Redux Toolkit the right way](https://react.dev/)  
### [🚀 Build real-world projects with APIs](https://rapidapi.com/)  

## Introduction  
This is the code repository for the **Cryptoverse App**.  

In this project, we build a modern cryptocurrency application using **React, Redux Toolkit, Axios, RapidAPI, HeroUI, and React Charts**.  
The app allows users to explore real-time crypto market data, track prices, view detailed coin stats, and read the latest news.  

By the end of this project, you will have hands-on experience working with APIs, managing state efficiently, building professional UIs, and visualizing financial data with charts.  

---

## 🔧 Tech Stack Explained  

- **Redux Toolkit** ⚡  
  Used for state management to handle global data like crypto lists, coin details, and news.  
  It helps keep the app scalable and makes API data accessible across multiple components.  

- **Axios** 🌐  
  A promise-based HTTP client for making API requests.  
  We use Axios to fetch cryptocurrency data and news from RapidAPI endpoints.  

- **RapidAPI** 🚀  
  Provides access to powerful APIs such as **CoinRanking API** (for crypto data) and **Crypto News API**.  
  This allows the app to display live prices, stats, and news articles.  

- **HeroUI** 🎨  
  A modern UI component library used to style the app.  
  It ensures a clean, responsive, and user-friendly interface with ready-to-use components.  

- **React Charts (Recharts)** 📈  
  Used to visualize historical crypto prices and trends in an interactive way.  
  Provides line charts, area charts, and tooltips for a better user experience.  

---

## 🚀 Setup  

```bash
# Clone the repo
git clone https://github.com/Dishank9900/project_cryptoverse.git

# Navigate into the project
cd project_cryptoverse

# Install dependencies
npm install

# Create .env file and add your RapidAPI key
echo "VITE_RAPIDAPI_KEY=your_api_key" > .env

# Run the application
npm run dev
