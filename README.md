# rn-assignment5-11066506

## Overview

This project is a React Native mobile application featuring a multi-screen interface with a theme-switching function between light and dark modes. The application is designed to closely replicate the provided UI mockup, utilizing custom components and tailored styling.

## Features

- **Bottom Tab Navigation**: The app includes a bottom tab navigator with the following screens:
  - **Home**
  - **My Cards**
  - **Statistics**
  - **Settings**
- **Theme Switching**: Users can toggle between light and dark themes, with the app dynamically updating styles and colors.
- **Custom Components**: The app employs custom components and icons to match the specified UI design.

## Development Process

### Technologies and Libraries Used

- **React Native**: The primary framework for building the mobile application.
- **React Navigation**: Used for handling navigation and the tab bar.
- **AsyncStorage**: Employed to save user theme preferences.
- **Expo-Blur**: Provides blur effects for certain UI elements.
- **Custom Components**: Created to fulfill the design specifications.
- **Context API**: Utilized for managing theme state and switching between themes.

### Development Steps

1. **Project Initialization**: Set up a new React Native project and organized the folder structure.
2. **State Management with Context**: Established a `ThemeContext` to manage the theme state and toggle functionality, with persistence via `AsyncStorage`.
3. **Navigation Configuration**: Implemented bottom tab navigation using `react-navigation`, setting up the Home, My Cards, Statistics, and Settings screens.
4. **UI Design and Implementation**: Styled each screen to adhere to the provided mockup, ensuring dynamic theme adjustments and using custom icons and components.
5. **Theme Toggle Implementation**: Added a switch in the Settings screen to toggle between light and dark themes.
6. **Polishing and Testing**: Refined the styles and tested the app on various devices for consistency.

### UI Components

- **Home Screen**: Features a welcome message, user profile picture, several action buttons, and a transaction history section.
- **My Cards Screen**: Placeholder for future functionalities related to user cards.
- **Statistics Screen**: Placeholder for displaying user statistics.
- **Settings Screen**: Includes options for additional settings and a toggle switch for changing themes.

### Screenshots

Below are some screenshots showcasing the application in both light and dark themes:

**Home Screen (Light Theme)**
![Home Light](myapp/screenshots/Screenshot 1.png)

**Home Screen (Dark Theme)**
![Home Dark](myapp/screenshots/Screenshot 3.png)

**Settings Screen (Light Theme)**
![Settings Light](myapp/screenshots/Screenshot 2.png)

**Settings Screen (Dark Theme)**
![Settings Dark](myapp/screenshots/Screenshot 4.png)

## Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pnllaryea/rn-assignment5-11066506.git

