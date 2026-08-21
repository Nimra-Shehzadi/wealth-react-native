# React Native Project — Progress Log

## 21 August 2026

### Project Setup

- Started the React Native project using Expo.
- Created the project with `create-expo-app`.
- Opened the project in VS Code.
- Confirmed the project structure and `package.json`.

### Dependencies & Configuration

- Installed the required Expo Babel preset:
  `npm install babel-preset-expo@~54.0.10`
- Added the required `content` configuration for the `app` and `components` directories.

### Expo Router Structure

- Set up the root group layout using `Slot`.
- Created the authentication layout using `Stack`.
- Configured the tab layout using `NativeTabs`.
- Added Home and Settings tab triggers.
- Created the following screens:
  - Home
  - Profile
  - Add Transaction
  - Assistant
  - Transactions
  - Sign In

### Navigation

- Added the initial Expo Router navigation structure.
- Configured native tab styling with the project colors.
- Added platform detection for native tabs.

### Authentication Setup

- Added Clerk Expo imports.
- Added `ClerkProvider` and `tokenCache`.
- Set up authentication-aware routing with `useAuth`.
- Added redirects for signed-in and signed-out users.
- Created the initial Sign In screen placeholder.

### Files/Screens Worked On

- `app/_layout.tsx`
- `app/(root)/_layout.tsx`
- `app/(root)/(tabs)/_layout.tsx`
- `app/(root)/(tabs)/index.tsx`
- `app/(root)/(tabs)/profile.tsx`
- `app/(root)/(tabs)/add-transaction.tsx`
- `app/(root)/(tabs)/assistant.tsx`
- `app/(root)/(tabs)/transactions.tsx`
- Sign-in related routing/screen files

### Notes

- The project is still under development.
- This repository will be used continuously for the same project until the project is completed.
- Future daily progress will be documented in separate Markdown progress files.
