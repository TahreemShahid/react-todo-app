# React Todo List App

A modern, dark-mode todo list application built with React. Features a clean, responsive UI, reusable components, and vibrant accent colors.

## Features
- Add, complete, and delete todos
- Responsive, accessible, and stylish dark mode UI
- Reusable `TodoItem` and `TodoList` components
- Modern CSS with vibrant accent colors

In the project directory, you can run:

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Start the development server:**
   ```bash
   npm start
   ```
3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure
```
todo-list-app/
├── src/
│   ├── components/
│   │   ├── TodoItem.jsx
│   │   ├── TodoItem.css
│   │   ├── TodoList.jsx
│   │   └── TodoList.css
│   ├── App.js
│   ├── App.css
│   └── ...
├── public/
├── package.json
└── README.md
```

## Component Architecture

- **App**: Main component, manages todo state and input
- **TodoList**: Renders a list of todos
- **TodoItem**: Represents a single todo (checkbox, text, delete button)

```
App
 └── TodoList
      └── TodoItem (multiple)
```

## Customization
- Easily change colors in `App.css` and `TodoItem.css`
- Adjust layout and size via CSS variables or class styles

## License
MIT
