# Base React Template

## Overview

This project is a starter template for building React applications. It follows a well-organized folder structure to separate concerns and improve maintainability. The template includes a basic setup for React components, Redux, API integration, and context management.

## Folder Structure

- **`public`**: Contains static files like `index.html`.
- **`src`**: The main source code directory.
  - **`assets`**: Includes styles, fonts, images, and other static assets.
  - **`components`**: Contains React components organized by functionality and domain (e.g., authentication).
  - **`context`**: React context files for managing global state and theme.
  - **`api`**: API service files for making HTTP requests.
  - **`config`**: Configuration files for API and application settings.
  - **`redux`**: Contains Redux setup including store, reducers, actions, and selectors.
  - **`utils`**: Utility components and functions used throughout the app.

## Getting Started

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd base-react-template
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

### Running the Application

Start the development server:
```bash
npm start
```

Visit `http://localhost:3000` in your browser to view the application.

### Folder Details

- **`public/index.html`**: The HTML template for the application.
- **`src/assets/styles`**: Contains global and theme-specific styles.
- **`src/components`**: React components are organized into common and authentication-specific directories.
- **`src/context`**: Provides context for authentication and theme.
- **`src/api`**: Service files for API calls.
- **`src/config`**: Configuration files for API endpoints and app settings.
- **`src/redux`**: Setup for Redux state management.
- **`src/utils`**: Reusable components and utility functions.

## Contributing

Feel free to submit issues, feature requests, or pull requests. Please follow the project's coding standards and guidelines.

## License
This project is licensed under the MIT License.
