# Google Flights Clone ✈️

A React.js and Material-UI-based clone of Google Flights that enables users to search, filter, and sort flights using real-time data from the Rapid API Sky Scraper.

[Demo Video](https://www.loom.com/share/ac4f359f041147b0858c21a49a254800?sid=65769379-8aa2-4970-8fd5-164c26fb5c03) 

![image](https://github.com/user-attachments/assets/8cf7dd13-8c93-4feb-9557-4768b57c9564)




## Features ✨

- **🌍 Nearby Airports Detection**: Auto-fetches airports near your geolocation.
- **🔍 Flight Search**: Search by origin, destination, date, class, and passengers.
- **🎚️ Filters & Sorting**: Filter by class (Economy/Business/First) and sort by price, duration, or stops.
- **📱 Responsive Design**: Optimized for all devices with Material-UI.
- **🔄 Clear Search**: Reset all parameters with one click.

## Installation 🛠️

### Prerequisites
- Node.js ≥ v14 & npm ≥ v6

### Steps:
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/google-flights-clone.git
   cd google-flights-clone
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a .env file in your root folder and Add your Rapid API key in it:
    ```bash
    REACT_APP_RAPID_API_KEY=your_api_key_here
   ```
4. Start the app:
   ```bash
    npm start
   ```
Open http://localhost:3000 to view.

## Tech Stack 💻

- **Frontend**: React.js, Material-UI
- **API Integration**: Rapid API Sky Scraper
- **Utilities**: 
  - date-fns (date formatting)

## Project Structure 📂
 ```bash
/src
├── components/       # Reusable components (FlightSearch, DatePicker, etc.)
├── utils/            # API helpers (getNearByAirports, searchFlights)
├── images/           # Static assets (Google flights image)
├── App.js            # Main app component
└── index.js          # Entry point
   ```

## How It Works 🔧

1. **Geolocation**: The app detects your location and fetches nearby airports via the Sky Scraper API.
2. **Search Parameters**: Users select origin/destination airports, dates, class, and passenger count.
3. **API Call**: On search, the app fetches flight data from Rapid API and displays it in a sortable/filterable table.
4. **Results**: Flight details (airline, price, duration, stops) are shown. Users can reset filters or start a new search.

## API Reference 🌐

This project uses the **Rapid API Sky Scraper** endpoint. You’ll need to:

1. **Sign up** at [RapidAPI](https://rapidapi.com/apiheya/api/sky-scrapper).
2. **Subscribe** to the **Sky Scraper API**.
3. Add your **API key** to `.env` as `REACT_APP_RAPID_API_KEY`.


   
