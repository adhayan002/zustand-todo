# Zustand Tutorial Project

This project demonstrates the use of **Zustand** for state management in a React application. It features a user-friendly task management interface with drag-and-drop functionality, enabling seamless organization of tasks across columns representing various statuses.

## Features

- **Task Management**: Effortlessly add, update, and delete tasks.
- **Drag-and-Drop**: Intuitive drag-and-drop interface for moving tasks between columns.
- **Persistent State**: Zustand's middleware ensures state persistence across sessions.
- **Lightweight & Efficient**: Minimal boilerplate with direct state access for a smooth developer experience.

## Getting Started

Follow these steps to set up and run the application:

1. **Install Dependencies**:
   ```bash
   pnpm install
   ```
2. **Start Development Server**:
   ```bash
   pnpm dev
   ```
3. **Build for Production**:
   ```bash
   pnpm build
   ```

## Project Structure

- **`components/`**: React components used throughout the application.
- **`lib/`**: Utility functions and Zustand store definitions.
- **`app/`**: Main application layout and styling.

## Why Zustand?

**Zustand** is a lightweight alternative to traditional state management libraries like Redux. Here’s why it’s a great choice:

- **Minimal Boilerplate**: Simple setup with less code, reducing complexity.
- **Direct State Access**: Access state directly without selectors or mapping functions.
- **Simplified Asynchronous Handling**: No need for middleware to handle asynchronous actions.
- **Performance-Optimized**: Efficient updates with minimal re-renders.

## Drag-and-Drop Functionality

The drag-and-drop feature enhances task management by allowing users to reorganize tasks visually:

- **Drag Events**: The `Column` component handles drag events to update task status upon drop.
- **State Management**: Zustand manages the task state, including drag status.
- **UI Feedback**: Clear visual cues highlight draggable tasks and valid drop zones.

## Technologies Used

- **React**: Component-based library for building user interfaces.
- **Zustand**: Lightweight state management solution.
- **Tailwind CSS**: Utility-first CSS framework for styling.

