# React Native Initial Project Setup

This React Native project is setup using [Expo](https://expo.dev/) and is using [Yarn](https://yarnpkg.com/) as the chosen package manager.

Simply download the ZIP of this repository to get started with your new project!

## Folder Structure

The folder structure for the project is shown below.

    .
    ├── __tests__              # Test files (follows same structure as source)
    │   ├── components
    │   │   ├── atoms
    │   │   ├── molecules
    │   │   └── organisms
    │   ├── navigations
    │   └── screens
    ├── src                    # Source code files
    │   ├── assets             # Non-code files
    │   │   ├── fonts          # Project fonts
    │   │   └── images         # Project images
    │   ├── components         # Reusable components
    │   │   ├── atoms          # Smallest possible components
    │   │   ├── molecules      # Composition of one or more atoms
    │   │   └── organisms      # Combination of molecules or atoms
    │   ├── navigations        # Navigation components (e.g. stacks, tabs, etc.)
    │   ├── screens            # Screen components (e.g. login, home, etc.)
    │   ├── store              # Redux related files
    │   │   ├── actions        # Dispatchable actions
    │   │   ├── reducers       # Handles dispatched actions and changes state
    │   │   └── index.js       # Store to handle state
    │   ├── styles             # Reusable component styling
    │   ├── utils              # Reusable helper methods and functions
    │   └── index.js           # Entry file for application
    ├── LICENCE
    ├── package.json
    ├── README.md
    └── yarn.lock

## State Management

## Testing
