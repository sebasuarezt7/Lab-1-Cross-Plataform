# Project Structure - MyFirstApp

This document describes the folder and file structure of the React Native project.

MyFirstApp/
├── android/        # Android-specific files and configuration (Gradle, SDK, builds)
├── ios/            # iOS-specific files and configuration (Xcode, builds)
├── node_modules/   # Installed dependencies and libraries
├── src/            # Source folder for custom components, screens, and logic (created manually)
├── App.js          # Main app component (root React Native component)
├── index.js        # Entry point of the application, registers the root component
├── package.json    # Project configuration, dependencies, and scripts
├── README.md       # Project documentation

## Explanation

- **android/**  
  Contains all the files required to build and run the app on Android. Includes Gradle configuration and native code.

- **ios/**  
  Contains all the files required to build and run the app on iOS. Includes Xcode project files and native code.

- **node_modules/**  
  Automatically generated folder that stores all the installed dependencies and libraries.

- **src/**  
  A custom folder created by the developer to organize app code such as components, screens, and utility functions.

- **App.js**  
  Main React Native component where the UI and logic of the app start.

- **index.js**  
  Entry point of the app. Registers the main component (`App`) with the React Native runtime.

- **package.json**  
  Defines project metadata, dependencies, and scripts used to run and build the app.

- **README.md**  
  Provides documentation for the project such as setup instructions, usage, and notes.

