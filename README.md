# Climatracker - Natural Events Tracker

A modern React + Vite web application for exploring and tracking natural events around the globe. This application displays real-time data on natural disasters, volcanic eruptions, hurricanes, wildfires, and other significant events using NASA's EONET (Earth Observation Natural Event Tracker) API.

## Features

- **Real-Time Event Data**: Fetches current natural events from NASA's EONET API
- **Category Filtering**: Browse events by category (wildfires, hurricanes, volcanoes, etc.)
- **Earth Image Viewer**: Visual representation of event locations on Earth
- **Event Details**: View comprehensive information about each event including location, date, and imagery
- **Pagination**: Navigate through large datasets of events efficiently
- **Time-Based Filtering**: Filter events by specific date ranges
- **Color-Coded Categories**: Each event category is assigned a distinct color for easy identification
- **Responsive Design**: Built with Bootstrap for seamless experience across devices

## Tech Stack

- **Frontend Framework**: React 19.1.0
- **Build Tool**: Vite 7.0.4
- **UI Components**: React Bootstrap 2.10.10
- **Routing**: React Router 7.6.3
- **Styling**: Bootstrap 5.3.7 + Custom CSS
- **Linting**: ESLint with React plugin support

## Project Structure

```
src/
├── App.jsx                    # Main app component
├── NaturalEventsTracker.jsx   # Core events tracking functionality
├── NavBar.jsx                 # Navigation bar component
├── CategoryFilter.jsx         # Category selection filter
├── CategoryKey.jsx            # Category legend/key display
├── EventCard.jsx              # Individual event card component
├── ImageDisplay.jsx           # Event imagery display
├── EarthImageViewer.jsx       # Earth visualization component
├── InfoCarousel.jsx           # Event information carousel
├── PaginationControl.jsx      # Pagination controls
├── TimeInput.jsx              # Date range selection
├── Home.jsx                   # Home page component
├── main.jsx                   # React entry point
└── assets/                    # Static assets
```

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vihanvdalvi/Climatracker.git
   cd Climatracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server with hot module replacement:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

Create an optimized production build:
```bash
npm run build
```

Preview the production build locally:
```bash
npm run preview
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint to check code quality
- `npm run preview` - Preview production build locally

## Data Source

This application uses the NASA EONET (Earth Observation Natural Event Tracker) API:
- **Categories Endpoint**: `https://eonet.gsfc.nasa.gov/api/v2.1/categories`
- **Events Endpoint**: `https://eonet.gsfc.nasa.gov/api/v2.1/events`

## Key Components

- **NaturalEventsTracker**: Main component managing event data, filtering, and pagination
- **EventCard**: Displays individual event information with imagery and details
- **CategoryFilter**: Allows users to filter events by type
- **PaginationControl**: Enables navigation through paginated results
- **EarthImageViewer**: Visualizes event locations on Earth

## License

This project is part of an academic assignment (CS571).
