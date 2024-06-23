# Workout Timer

## Overview

Workout Timer is a React-based web application that helps you plan and time your workouts. It dynamically updates workout routines based on the time of day and provides a customizable interface for selecting different workout plans, adjusting the number of sets, speed per exercise, and break durations. The app also includes an option to toggle workout sounds on and off.

## Features

- Dynamic workout plans based on the time of day (AM/PM).
- Real-time clock updating every second.
- Customizable workout parameters:
  - Type of workout
  - Number of sets
  - Speed per exercise
  - Break duration between sets
- Sound toggle option to enable/disable workout sounds.
- Duration calculation and display for the total workout.
- Responsive UI with interactive elements.

## Getting Started

### Prerequisites

To run this project locally, you need to have:

- Node.js (version 14.x or higher)
- npm (version 6.x or higher)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/osama206/workout-timer.git
   ```

2. Navigate to the project directory:

   ```sh
   cd workout-timer
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

### Running the Application

To start the application locally, run:

```sh
npm start
```

This will start the development server, and you can view the application by navigating to `http://localhost:3000` in your web browser.

### Building for Production

To create a production build, run:

```sh
npm run build
```

This will generate optimized static files in the `build` directory, which can be served by any static hosting service.

## Project Structure

- `src/`
  - `App.js`: Main application component.
  - `Calculator.js`: Component for configuring and calculating workout durations.
  - `ToggleSounds.js`: Component for toggling workout sounds.
  - `index.js`: Entry point for the React application.
  - `index.css`: Global CSS styles.
  - `ClickSound.m4a`: Audio file for workout click sounds.

## Usage

### Interface

- **Type of Workout**: Select the type of workout from the dropdown menu. The number of exercises will update accordingly.
- **Number of Sets**: Adjust the number of sets using the range input.
- **Speed per Exercise**: Adjust the speed per exercise in seconds using the range input.
- **Break Duration**: Adjust the break duration between sets in minutes using the range input.
- **Sound Toggle**: Click the sound button to toggle workout sounds on or off.
- **Duration Display**: The total workout duration is displayed and updated dynamically.

## Credits

- React documentation: [React](https://react.dev)
- MDN Web Docs for JavaScript and Web APIs: [MDN Web Docs](https://developer.mozilla.org/)
- ClickSound.m4a: Audio clip used for workout sounds from [freesound](https://freesound.org/)

---
