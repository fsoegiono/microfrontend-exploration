# Microfrontend Exploration

This repository explores microfrontend implementation using Webpack Module Federation. In this repository, the code is provided with dirty example of Webpack Module Federation as a leverage to create microfrontend architecture.

## Structure

- Dashboard (host page)
- Hello World (remote page to Dashboard)
- Kiwi (remote page to Dashboard and host to Image Caption)
- Image caption (remote page to Kiwi as nested Module Federation)

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

   Dashboard:
   ```
   cd dashboard
   npm install
   npm run build
   npm start
   ```

   Hello World:
   ```
   cd hello-world
   npm install
   npm run build
   npm start
   ```

   Kiwi:
   ```
   cd kiwi
   npm install
   npm run build
   npm start
   ```

   Image Caption
   ```
   cd image-caption
   npm install
   npm run build
   npm start
   ```

3. Open [http://localhost:9000](http://localhost:9000) in your browser to see the application.

## Available Scripts for Local Development

- `npm run build`: Transform code into bundles
- `npm start`: Run server application to load bundled code
