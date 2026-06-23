# React Redux Movies App

A React application focused on movie list management, Redux state flow, component-based frontend structure, and add/remove interaction logic.

The project demonstrates how Redux can be used to manage shared application state in a React frontend.

## Overview

This project is a movie-focused React application built to demonstrate Redux-based state management.

The application structure focuses on managing movie-related data through a centralized Redux store, dispatching actions from React components, updating state with reducer logic, and rendering the updated UI based on shared application state.

The main focus is understanding how React components interact with Redux to create predictable frontend behavior.

## Tech Stack

* React
* Vite
* JavaScript
* Redux
* React Redux
* Tailwind CSS
* HTML
* CSS
* Component-based architecture
* State management

## Core Concepts

* Redux store setup
* Reducer-based state updates
* Action dispatching
* Movie list rendering
* Add/remove interaction logic
* Shared frontend state management
* Component-based UI structure
* React data flow
* Predictable state updates
* Frontend application structure

## Features

* Movie list interface
* Redux-powered state management
* Add movie interaction flow
* Remove movie interaction flow
* Dynamic UI updates
* Centralized store usage
* Reducer logic for state changes
* Reusable React components
* Tailwind-based styling
* Frontend deployment-ready structure

## Application Flow

```text
User Interaction
↓
React Component
↓
Redux Action Dispatch
↓
Reducer Updates Movie State
↓
Store Provides Updated Data
↓
UI Re-renders
```

## Redux State Flow

Redux is used to keep movie-related state in a centralized store.

This makes the application easier to follow because state changes are handled through actions and reducers instead of being scattered across multiple components.

Example flow:

```text
Button Click
↓
dispatch(action)
↓
Reducer processes the action
↓
Redux store updates
↓
React UI displays the new state
```

## Project Structure

```text
src/
 ├── components/
 ├── store/
 ├── App.jsx
 └── main.jsx
```

## What This Project Demonstrates

* Building a React frontend with Redux
* Managing shared application state
* Creating reducer logic
* Dispatching actions from components
* Rendering dynamic movie data
* Handling add/remove UI interactions
* Structuring React components clearly
* Using Tailwind CSS for interface styling
* Understanding predictable frontend state flow

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/emreyildirim-33/react-redux-movies-app.git
cd react-redux-movies-app
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

The application will run locally at:

```text
http://localhost:5173
```

## Notes

This project focuses on React, Redux, centralized state management, reducer logic, action dispatching, and movie-list based frontend interaction flow.

The main purpose is to demonstrate how Redux can be used to manage predictable UI state in a React application.

## Repository

GitHub: https://github.com/emreyildirim-33/react-redux-movies-app
