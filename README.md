# Chef Menu App
A modern React Native mobile application designed for private chefs to manage and display their menus professionally. Built with TypeScript for type safety and cross-platform compatibility.

## 📱 App Overview
This application serves as a digital menu management system that allows:

Clients to browse menu items, apply filters, and see pricing

Chefs to easily manage their menu offerings

Real-time price calculations for selected items

## 🎯 Features
For Customers
Browse available dishes with detailed descriptions

Filter menu items by various criteria

View real-time total pricing

Intuitive and user-friendly interface

For Chefs (Admin)
Add new menu items effortlessly

Edit existing menu details

Remove items from the menu

Professional menu presentation

# 📁 Project Structure
text
chef-menu-app/
├── App.tsx
├── package.json
├── tsconfig.json
├── src/
│   ├── types.ts
│   ├── HomeScreen.tsx
│   ├── AddMenuScreen.tsx
│   ├── MenuListScreen.tsx
│   └── FilterScreen.tsx 
🛠️ Technical Stack
Framework: React Native

Language: TypeScript

Navigation: React Navigation

Platforms: iOS & Android compatible

🚀 Installation & Setup
Prerequisites
Node.js (v14 or higher)

## React Native development environment

Android Studio (for Android) or Xcode (for iOS)

Quick Start
Clone and install

bash
cd chef-menu-app
npm install
Install navigation dependencies

bash
npm install @react-navigation/native @react-navigation/stack
npm install react-native-screens react-native-safe-area-context
Run the application

bash
# For Android
npx react-native run-android

# For iOS
npx react-native run-ios
📱 Screen Descriptions
HomeScreen (HomeScreen.tsx)
Main landing page with menu overview

Navigation hub to other screens

Displays featured menu items

AddMenuScreen (AddMenuScreen.tsx)
Administrative interface for menu management

Add new dishes with name, description, and price

Edit existing menu items

MenuListScreen (MenuListScreen.tsx)
Customer-facing menu display

Shows selected items and running total

Clean, scrollable item list

FilterScreen (FilterScreen.tsx)
Advanced search and filtering

Category-based filtering

Price range filters

Dietary preference options

🎨 Type Definitions
The types.ts file contains all TypeScript interfaces for type-safe development, including:

MenuItem - Structure for menu items

FilterOptions - Search and filter parameters

Navigation types and props

# 📦 Dependencies
Core Dependencies
react-native - Mobile framework

typescript - Type safety

@react-navigation/native - Navigation solution

@react-navigation/stack - Stack navigation

Development Dependencies
TypeScript type definitions

React Native development tools

🔧 Development
Building for Production
Android:

bash
cd android && ./gradlew assembleRelease
iOS:

bash
cd ios && xcodebuild -workspace ChefMenuApp.xcworkspace -scheme ChefMenuApp -configuration Release
Code Structure
Components: Reusable UI components

Screens: Main application screens

Types: TypeScript type definitions

Navigation: Stack-based screen navigation

🤝 Contributing
Fork the repository

Create a feature branch

Commit your changes

Push to the branch

Create a Pull Request

# YouTube link
 https://youtube.com/shorts/kNvpwcbXQi0?si=bEREYnFai42cFOmG

# 📚 References
React Native Documentation
React Native (2024) Getting Started. Available at: https://reactnative.dev/docs/getting-started (Accessed: 11 November 2025).

React Native (2024) Components and APIs. Available at: https://reactnative.dev/docs/components-and-apis (Accessed: 11 November 2025).

React Native (2024) TypeScript in React Native. Available at: https://reactnative.dev/docs/typescript (Accessed: 11 November 2025).

Navigation
React Navigation (2024) Getting Started with React Navigation. Available at: https://reactnavigation.org/docs/getting-started/ (Accessed: 11 November 2025).

React Navigation (2024) Stack Navigator Guide. Available at: https://reactnavigation.org/docs/stack-navigator/ (Accessed: 11 November 2025).

Core Components
React Native (2024) View Component Documentation. Available at: https://reactnative.dev/docs/view (Accessed: 11 November 2025).

