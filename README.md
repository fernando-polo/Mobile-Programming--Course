# S192PM — Programación Móvil

Course repository for the Mobile Programming class. Contains exercises and practices developed throughout the semester using JavaScript and React Native with Expo.

## 📌 Description

This repository documents the progressive learning of mobile application development, starting from modern JavaScript fundamentals and advancing to building functional user interfaces with React Native core components.

Each folder corresponds to a specific practice, covering topics such as ES6+ syntax, component-based architecture, state management, styling with Flexbox, and native UI components.

## 📦 Tech Stack

- **Framework:** React Native
- **Runtime:** Expo CLI
- **Language:** JavaScript (ES6+)
- **Tools:** Node.js, npm, Expo Go

## 📁 Repository Structure

| Folder | Description |
|---|---|
| `Practica1` | Modern JS: variables, `let`/`const`, arrow functions |
| `Practica2` | Objects, arrays, and array methods |
| `Practica3` | Modules, promises, and async/await |
| `Practica4` | Expo environment setup and project templates |
| `Practica5` | Components, props, state with `useState` |
| `Practica6` | StyleSheet and Flexbox layout |
| `Practica8` | Switch and Button components |
| `Practica9` | TextInput and Alert API |
| `Practica10` | ImageBackground and SplashScreen |
| `Practica13` | ActivityIndicator and dynamic lists |

## 📋 Topics Covered

**Partial 1 — JavaScript Fundamentals**
- `let` and `const` vs `var`, and when to use each
- Traditional functions vs. arrow functions
- Object destructuring
- Array methods: `filter()`, `map()`, `find()`, `forEach()`, `reduce()`
- JavaScript modules with `import` / `export`
- Promises and async/await for asynchronous operations
- Simulating API calls with `setTimeout`
- Expo project setup with `blank` and `navigation` templates

**Partial 2 — React Native Components & UI**
- Core Components: `View`, `Text`, `Button`
- Reusable components with props and `children`
- Dynamic state management with `useState`
- Responding to events with `onPress`
- Styling with `StyleSheet.create()`
- Flexbox layout: `flex`, `flexDirection`, `justifyContent`, `alignItems`
- Interactive components: `Switch`, `Button`
- Form input with `TextInput` and native dialogs with `Alert`
- Visual backgrounds with `ImageBackground`
- Custom Splash Screen configuration
- Loading states with `ActivityIndicator`
- Dynamic list rendering with `FlatList`

## ⚙️ How It Works

The project uses Expo as the development environment, allowing the app to run on iOS, Android, and web from a single codebase. Each practice is structured as a self-contained Expo project or module.

Components are built following React Native's component-based architecture, using hooks like `useState` to manage dynamic data and `StyleSheet` with Flexbox for responsive layouts that adapt to different screen sizes.

## 🚀 Key Practices

- **Async data simulation:** Built promise-based functions that mimic real API calls with delays, then consumed them using `async/await`
- **Reusable component system:** Created a `Texto` component that accepts both props and children, used across multiple views with different styles
- **Interactive form:** Combined `TextInput`, `Button`, and `Alert` to build a functional input form with native feedback
- **Dynamic list with loading state:** Used `ActivityIndicator` to show a loader while data is being fetched, then rendered it using a list component

## 📚 What I Learned

- Modern JavaScript syntax and best practices (ES6+)
- Asynchronous programming with promises and `async/await`
- Component-based architecture in React Native
- Passing and consuming props, including `children`
- Managing UI state with the `useState` hook
- Designing responsive layouts with Flexbox
- Working with native components: inputs, alerts, switches, image backgrounds, and lists
- Setting up and running mobile projects with Expo CLI
