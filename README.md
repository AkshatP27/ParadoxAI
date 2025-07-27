# ParadoxAI

ParadoxAI is a modern React application built with Vite that demonstrates an AI-powered interface with elegant animations and responsive design. It leverages Tailwind CSS for styling, React Router for navigation, and various modern libraries for enhanced user experience.

## Features

- **React + Vite**: Fast and efficient development environment with hot module replacement.
- **Tailwind CSS**: Utility-first CSS framework for sophisticated, responsive UI design.
- **React Router**: Seamless client-side navigation for a single-page application experience.
- **Parallax Effects**: Smooth scrolling animations using react-just-parallax.
- **SVG Components**: Dynamic, interactive graphical elements.
- **Modular Architecture**: Component-based structure for maintainability and scalability.
- **Mobile Responsive**: Fully responsive design with enhanced mobile navigation experience.

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## Project Structure

- `src/`: Contains the main application code.
  - `assets/`: Includes images, icons, SVGs, and other static resources.
  - `components/`: Reusable React components.
    - `design/`: UI-specific component elements.
  - `constants/`: Application-wide constant values and configuration.
- `public/`: Public assets served directly.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run lint`: Run ESLint to check for code issues.
- `npm run preview`: Preview the production build locally.

## Recent Updates

- Enhanced component modularity and structure.
- Improved navigation experience with smoother transitions.
- Optimized assets for better loading performance.
- Refined responsive design for various screen sizes.
- Added new visual effects and animations.

## Working

The project follows a modern React architecture:

1. **Routing and Navigation**:

   - Uses React Router (`react-router-dom`) for client-side navigation.
   - Navigation links and routes are defined in constants for easy management.
   - Smooth scrolling and navigation state management.

2. **Component Structure**:

   - Core components like Header, Hero, and Button are modular and reusable.
   - Design components are separated in the `components/design` folder for UI elements.
   - Component composition pattern for maximum reusability.

3. **State and Interactivity**:

   - Local component state with React's `useState` hook (e.g., navigation toggle in Header).
   - Scroll lock functionality (`scroll-lock` library) for better mobile experience.
   - Interactive UI elements with hover and click effects.

4. **Visual Effects**:

   - Parallax scrolling effects with `react-just-parallax` library.
   - SVG components for dynamic graphical elements.
   - Gradient effects and animations for modern UI appearance.

5. **Asset Organization**:
   - Centralized asset imports from `assets/index.js`.
   - Constants stored in `constants/index.js` for consistent data across components.
   - Tailwind CSS with custom configuration for responsive styling and design consistency.

## Development Status

The project development status: **In Development**.
