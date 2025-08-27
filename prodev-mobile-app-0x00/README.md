# Prodev Mobile Setup

This repository contains my first mobile application built with React Native and Expo.

## Scaffolding Steps

1.  **Navigate to Project Directory**: I navigated to the `prodev-mobile-setup` directory.
2.  **Initialize Expo Project**: I ran `npx create-expo-app@latest .` and selected the "tabs (TypeScript)" template.
3.  **Modify Home Screen**: I updated the text in `app/(tabs)/index.tsx` from "Welcome!" to "First App Created".
4.  **Run Application**: I started the server with `npx expo start` and tested the app by scanning the QR code with Expo Go.

## Observations from `reset-project`

The `npm run reset-project` command is a powerful script that effectively cleans and resets the project environment. When executed, it automatically performs the following actions:

* Deletes the `node_modules` directory.
* Deletes the `package-lock.json` file.
* Clears the local npm cache.
* Re-installs all project dependencies by running `npm install`.

This command is invaluable for troubleshooting dependency-related issues and for ensuring a clean, consistent build environment across different development setups.


