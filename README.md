# Expo CLI: Module Import Error

This repository demonstrates a common issue in Expo projects where importing modules results in errors like 'Cannot find module' even if the module appears to be installed.  The problem usually stems from incompatibilities between the module and Expo's build system or missing native modules.

## Problem

The `bug.js` file contains a module import that causes an error during the Expo build process.  This might be due to the module not being compatible with Expo's managed workflow, or a missing dependency.

## Solution

The `bugSolution.js` file shows how to resolve the error, usually by replacing the incompatible module with a suitable alternative or by correctly configuring the module within the Expo environment.  This often requires investigating the module's documentation for Expo compatibility instructions or finding an Expo-compatible replacement.

## Setup

1. Clone the repository.
2. Navigate to the project directory using your terminal.
3. Run `npm install` or `yarn install` to install project dependencies.
4. Attempt to run the app via `expo start`. You will observe the error in `bug.js`. 
5. To fix it, look at `bugSolution.js`