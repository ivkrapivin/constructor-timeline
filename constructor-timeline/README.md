# Constructor University Interactive Timeline

An interactive horizontal-scrolling timeline visualizing the history of Constructor University (formerly IUB / Jacobs University) from 1936 to present.

## Features
- 6 historical periods with 23 events
- 4 thematic DNA-helix lines: Architecture, Academic Programs, People, Historical Events
- Animated wave pattern with convergence at multi-theme events
- Hover tooltips with historical photographs
- Auto-hint system that reveals tooltips during scroll
- Click-to-open modal with full event details
- Period navigation bar
- Theme filter toggles

## Tech Stack
- React (functional components + hooks)
- SVG for timeline rendering
- CSS transitions & animations
- Base64-embedded images (self-contained artifact version)

## Project Structure
```
constructor-timeline/
├── README.md
├── package.json
├── public/
│   ├── index.html
│   └── images/          # Extracted period photos
│       ├── 1.jpg        # Period 1 main
│       ├── 1.1.jpg      # Subperiod 1.1
│       └── ...
└── src/
    ├── index.jsx        # Entry point
    ├── Timeline.jsx     # Main component (self-contained with base64 images)
    └── Timeline.ext.jsx # Version using external image paths (for production)
```

## Quick Start
```bash
npm install
npm start
```

## Data Source
Historical data from "Structure + main data for the website" by Rüdiger Ritter (22.12.2025).
Photos from the Constructor University archive (Starter_pictures.zip).
