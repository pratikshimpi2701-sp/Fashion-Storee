# GEMINI.md

## Project Overview

This is a frontend for a "Fashion Store" built with Next.js and Tailwind CSS. It features a home page, a product listing page, and a product details page. The application fetches data from a Strapi backend, which is expected to be running on `http://localhost:1337`.

**Technologies:**
* Next.js
* React
* Tailwind CSS
* Strapi (for the backend)

**Architecture:**
* The project follows the standard Next.js `app` directory structure.
* Components are located in the `app/components` directory.
* Pages are located in the `app` directory and its subdirectories.
* Data fetching logic is centralized in the `lib/api.js` file.

## Building and Running

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run the development server:**
   ```bash
   npm run dev
   ```
   The application will be available at [http://localhost:3000](http://localhost:3000).

3. **Build for production:**
    ```bash
    npm run build
    ```

4. **Run in production mode:**
    ```bash
    npm run start
    ```
5. **Lint the code:**
    ```bash
    npm run lint
    ```

## Development Conventions

* The project uses functional components with React Hooks.
* Code is formatted according to the default Next.js ESLint configuration.
* Data fetching is handled in a dedicated `lib/api.js` file, which makes it easy to manage API interactions.
* The application expects a Strapi backend to be running at `http://localhost:1337`.
