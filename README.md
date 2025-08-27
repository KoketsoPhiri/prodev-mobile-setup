# prodev-mobile-setup

This repository contains a series of projects for learning React Native and Expo development. Each project builds upon the last, exploring core concepts, components, and best practices.

## Project 0x00: First Mobile App

This project demonstrates the initial setup of a React Native application using the **Expo Router** template. It covers the basic scaffolding process and introduces the fundamental file structure of an Expo project.

### What was learned:
- How to initialize a new Expo project with `npx create-expo-app`.
- The purpose of the `package.json` file.
- How to start the development server with `npx expo start`.
- The function of the `npm run reset-project` command, which cleans and reinstalls project dependencies.

## Project 0x01: Core Components and Styling

This project focuses on the core building blocks of a React Native application. It implements basic components like `<View>` and `<Text>` and introduces the `StyleSheet` API for styling.

### What was learned:
- The distinction between native components (`<View>`, `<Text>`) and their web equivalents (`<div>`, `<p>`).
- How to create and apply styles using `StyleSheet.create`.
- The basics of component-based UI design in React Native.

## Project 0x02: Safe Areas, Images, and Touchable Components

This project builds a simple landing screen to explore more advanced components. It demonstrates how to handle different screen sizes and create interactive elements.

### What was learned:
- The use of **`SafeAreaView`** to handle device notches and screen insets.
- How to display images using `Image` and `ImageBackground`.
- Creating interactive buttons with **`TouchableOpacity`**.
- Handling server errors related to module resolution and aliasing (`@/assets`).

## Project 0x03: Building a Login Screen

This project combines all previously learned concepts to create a complete login screen. It showcases the use of various core components, external icon libraries, and a more complex layout.

### What was learned:
- Building complex layouts using nested `<View>` components.
- Implementing form elements with **`TextInput`**.
- Integrating third-party icon libraries like `@expo/vector-icons`.
- Using `TouchableOpacity` for a variety of button styles.
- Creating a modular and organized codebase by separating styles into a dedicated file.