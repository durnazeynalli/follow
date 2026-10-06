# follow

Frontend web application for the `follow-az` service, built with React, Redux, and styled-components.

**Demo:** [https://follow-az.herokuapp.com/](https://follow-az.herokuapp.com/)

## Features

- **Card & Account Tracking:** Components for displaying card information (`CardInfo`), user details (`UserInfo`), and operations history (`Operation`).
- **Interactive UI Components:** Includes FAQ accordions, custom visual cards, loading spinners, and empty/inactive state views (`NotActive`, `NoResult`, `NotFound`).
- **State Management:** Centralized application state management using Redux and Redux Thunk middleware.
- **Component Styling:** Modular UI design utilizing `styled-components` alongside `react-bootstrap`.

## Tech Stack

- **Frontend Framework:** React (v17)
- **State Management:** Redux, React-Redux, Redux Thunk, Redux DevTools Extension
- **Routing:** React Router DOM (v5)
- **Styling:** Styled Components, React Bootstrap
- **Build Tool:** Create React App (`react-scripts`)

## Project Structure

```text
follow/
├── client/
│   ├── public/             # Static files and HTML template
│   ├── src/
│   │   ├── asset/          # Icons, card graphics, and brand images
│   │   ├── components/     # Reusable React components (CardInfo, Header, Operation, etc.)
│   │   ├── pages/          # Application views (Homepage)
│   │   ├── reducers/       # Redux state reducers
│   │   ├── styles/         # Style constants (colors)
│   │   ├── App.js          # Main app entry
│   │   ├── index.js        # DOM render root
│   │   └── store.js        # Redux store configuration
│   └── package.json        # Dependencies and scripts
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/durnazeynalli/follow.git
   cd follow/client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running Locally

To run the app in development mode:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Building for Production

To build the static production bundle:

```bash
npm run build
```