# Tailwind CSS Classes Not Applying in Vite Project

This repository demonstrates a bug where Tailwind CSS classes are not being applied correctly in a Vite project, even after properly configuring PostCSS.  The issue arises specifically with some, but not all, classes.  The solution involves ensuring proper configuration and build process.

## Bug Report

The bug is described in `bug.js` and `bugSolution.js` . The solution is in `bugSolution.js`

## Setup

1. Clone this repository.
2. Run `npm install`
3. Run `npm run dev` to start the development server.  Observe that some classes are not being applied.
4. Run `npm run build` and open the `dist` folder in your browser. Observe again the same behavior.

## Solution

The solution is provided in `bugSolution.js` and requires carefully reviewing your `vite.config.js` and making sure the correct paths and configurations are included for Tailwind.