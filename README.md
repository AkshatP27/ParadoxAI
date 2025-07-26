# ParadoxAI

ParadoxAI is a React-based project built with Vite. It leverages modern tools like Tailwind CSS for styling, ESLint for code quality, and a modular component-based architecture for scalability.

## Features

- **React + Vite**: Fast and efficient development environment.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **ESLint**: Ensures code quality and consistency.
- **Reusable Components**: Modular and reusable React components for scalability.
- **Dynamic Assets Management**: Includes a variety of assets like images, SVGs, and icons for building a rich user interface.

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
  - `assets/`: Includes images, icons, and other static resources.
  - `components/`: Reusable React components.
  - `pages/`: Application pages.
- `public/`: Public assets served directly.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run lint`: Run ESLint to check for code issues.

## Recent Updates

- Improved component modularity for better scalability.
- Enhanced Tailwind CSS integration for more efficient styling.
- Added dynamic asset management for better resource handling.
- Fixed known bugs and improved overall stability.


## Working

The project follows a modern React architecture:

1. **Routing and Navigation**:

   - Uses React Router (`react-router-dom`) for client-side navigation
   - Navigation links and routes are defined in constants for easy management

2. **Component Structure**:

   - Core components like Header, Hero, and Button are modular and reusable
   - Design components are separated in the `components/design` folder for UI elements

3. **State and Interactivity**:

   - Local component state with React's `useState` hook (e.g., navigation toggle in Header)
   - Scroll lock functionality (`scroll-lock` library) for better mobile experience

4. **Visual Effects**:

   - Parallax scrolling effects with `react-just-parallax` library
   - SVG components for dynamic graphical elements
   - Gradient effects for modern UI appearance

5. **Asset Organization**:
   - Centralized asset imports from `assets/index.js`
   - Constants stored in `constants/index.js` for consistent data across components
   - Tailwind CSS for responsive styling and design consistency

## Development Status

The project development status: **In Development**.