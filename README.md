# TaskGlitch

A robust task management dashboard built with React, TypeScript, and Material UI. This application allows users to track tasks, monitor revenue and time efficiency, and visualize performance metrics through an interactive dashboard.

## Features

-   **Task Management**: Create, read, update, and delete tasks with ease.
-   **Advanced Analytics**: Visualize data with charts for revenue trends, task status distribution, and more.
-   **Real-time Metrics**: Automatic calculation of ROI, Revenue per Hour, and Time Efficiency.
-   **Undo Capability**: Accidentally deleted a task? Restore it immediately with the undo snackbar.
-   **CSV Export**: Export your task data for external analysis.
-   **Responsive Design**: optimized for both desktop and mobile views.

## Tech Stack

-   **Frontend**: React 18
-   **Language**: TypeScript
-   **Build Tool**: Vite
-   **UI Library**: Material UI (MUI)
-   **Charts**: MUI X Charts
-   **Date Handling**: Day.js

## Getting Started

### Prerequisites

-   Node.js (v16 or higher recommended)
-   npm

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    cd Task-glitch
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

### Running the Application

Start the development server:

```bash
npm run dev
```

The app will generally be available at `http://localhost:5173`.

### Building for Production

Create a production-ready build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Project Structure

```text
src/
├── components/     # Reusable UI components (TaskTable, Charts, etc.)
├── context/        # React Context definitions (TasksContext, UserContext)
├── hooks/          # Custom hooks (useTasks)
├── utils/          # Helper functions and business logic
├── App.tsx         # Main application component
└── main.tsx        # Entry point
```
