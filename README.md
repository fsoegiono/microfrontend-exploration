# Microfrontend Exploration

This repository demonstrates a microfrontend architecture using Webpack Module Federation. It provides examples of leveraging Webpack Module Federation to enable a microfrontend structure.

## Structure

- Dashboard: Acts as the host page
- Hello World: Remote page integrated into the Dashboard
- Kiwi: remote page for the Dashboard and a host for the Image Caption module
- Image Caption: Remote page to Kiwi, using nested Module Federation

## Prerequisites

Ensure you have the following installed:

- Node.js (v18.0.0 or later)
- npm (v10.8.2 or later)

## Local Development

1. Clone the repository:

   ```
   git clone https://github.com/fsoegiono/zipurl-frontend.git
   cd zipurl-frontend
   ```

2. Run each microfrontend application:

   **Dashboard:**
   ```
   cd dashboard
   npm install
   npm run build
   npm start
   ```

   **Hello World:**
   ```
   cd hello-world
   npm install
   npm run build
   npm start
   ```

   **Kiwi:**
   ```
   cd kiwi
   npm install
   npm run build
   npm start
   ```

   **Image Caption:**
   ```
   cd image-caption
   npm install
   npm run build
   npm start
   ```

3. Open [http://localhost:9000](http://localhost:9000) in your browser to see the application.

## Available Scripts for Local Development

- `npm run build`: Builds the code into bundles
- `npm start`: Starts the server to serve bundled code
