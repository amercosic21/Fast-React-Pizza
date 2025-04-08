# Fast React Pizza 🍕

A modern React application built with Vite, designed to streamline pizza restaurant management, with a focus on responsive design, user-friendly interfaces, and efficient state handling.

## Features

- **Dynamic Menu Management**: Add, display, and customize pizza menu items effortlessly.
- **Order Tracking**: Manage orders and monitor their status in real-time.
- **Responsive Design**: Optimized for both desktop and mobile devices, ensuring a seamless user experience.
- **User-Friendly Interface**: Intuitive design for easy navigation and interaction.
- **Cart Management**: Add, update, and remove items from the cart with ease.
- **Geolocation Integration**: Automatically fetch user addresses using geolocation APIs.

## Libraries Used

This project leverages the following libraries:

- **React**: For building the user interface.
- **Redux Toolkit**: For state management.
- **React Router**: For routing and navigation.
- **Redux Persist**: For persisting the Redux state.
- **TailwindCSS**: For styling and responsive design.
- **BigDataCloud API**: For reverse geocoding and address fetching.

## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/amercosic21/Fast-React-Pizza.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fast-react-pizza
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`.

## Folder Structure

The project is organized as follows:

```
src/
├── features/         # Feature-specific components and logic
│   ├── cart/         # Cart management
│   ├── menu/         # Menu management
│   ├── order/        # Order management
│   └── user/         # User-related features
├── services/         # API service files
├── ui/               # Reusable UI components
├── utils/            # Utility functions
├── App.jsx           # Main application component
├── main.jsx          # Entry point for the application
└── store.js          # Redux store configuration
```

## Scripts

The following scripts are available in the project:

- `npm run dev`: Start the development server.
- `npm run build`: Build the application for production.
- `npm run preview`: Preview the production build locally.
- `npm run lint`: Run ESLint to check for code quality issues.

## Acknowledgments

This project was inspired by modern pizza ordering systems and built for learning purposes. Special thanks to the creators of the libraries and tools used in this project.
