# StocksTrack

## Description  
A simple stock tracking app that integrates the **Alpha Vantage API** to fetch real-time stock data. This project explores API integration, app structure, and design principles.  

## Features  

### 🔹 Tab Bar Controller  
- Added an **Edit Profile** tab to modify stock preferences.  
- **Auto-refresh**: Updates stock lists when preferences change or Watchlist is modified.  

### 🔹 Core Graphics  
- Implemented a **toast notification** that appears when the add/delete button is pressed multiple times.  
- Uses `CGRect` to create a **non-intrusive alert** when a stock is already added or removed.  

### 🔹 Gesture Recognizer  
- Multi-touch gestures for **gamified security** before login:  
  - **Triple tap** to proceed.  
  - **Swipe** in any direction to segue to the Profile screen.  

### 🔹 Alpha Vantage API  
- Fetches **real-time stock data** in JSON format.  
- Updates stock details dynamically when a stock is selected.  

### 🔹 URLSession  
- Uses `URLSession` to make API calls and parse JSON data.  
- Implements **Codable struct** to easily handle API responses.  
- Optimized API usage: Calls are made **only when needed** to prevent exceeding free-tier limits.  

## Tech Stack  
- **Swift**  
- **UIKit**  
- **Core Graphics**  
- **Alpha Vantage API**  

## How to Run  
1. Clone the repo.   
2. Add your **Alpha Vantage API key**.  
3. Run the project in Xcode.  

---
📌 *This project is for learning purposes and API exploration.*  
