# Next.js + Electron + Bootstrap Project

This project is a sample Next.js application integrated with Electron and Bootstrap. It demonstrates how to set up a development environment and build a production-ready desktop application using these technologies.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Prerequisites

- Node.js (recommended version: 14.x or higher)
- NPM (recommended version: 6.x or higher) or Yarn (recommended version: 1.x or higher)

## Getting Started

To get started, follow these steps:

1. Clone the repository:

https://github.com/Mojtaba-Hassan-Erfani/NextJs-Electron-Setup.git


2. Change into the project directory:

cd NextJs-Electron-Setup


3. Install the dependencies:

npm install

4. Start the development server:

npm run dev


5. Start Electron in development mode:

npm run electron

6. Or start both nextjs and electron dev concurrently. No need for step 4 and 5 then.

npm run electron-dev


Now, the Next.js app should be running in an Electron window.

## Available Scripts

The following scripts are available in the `package.json` file:

- `dev`: Starts the Next.js development server
- `build`: Builds the Next.js application for production
- `start`: Starts the Next.js production server
- `lint`: Lints the code using Next.js Lint
- `electron`: Starts Electron using the `electron.js` configuration file
- `electron-build`: Builds the Electron application for production
- `electron-rebuild`: Rebuilds the native modules for Electron
- `electron-dev`: Starts the Next.js app and Electron concurrently in development mode
- `package`: Packages the Electron application without publishing it

## Building the Application for Production

To build the application for production, run the following command:

npm run build


After the build is complete, you can start the Next.js production server by running:

npm run start


To package the Electron application for production, run:

npm run electron-build


You will find the packaged application in the `dist` directory.
