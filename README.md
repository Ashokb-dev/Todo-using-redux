# 📝 Redux Toolkit Task Manager

A state management application built with React 19 and Redux Toolkit showcasing predictable global state container patterns.

![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-2.9-764ABC?style=flat-square&logo=redux)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-38BDF8?style=flat-square&logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-6.x-646CFF?style=flat-square&logo=vite)

---

## Overview

This project demonstrates centralized global state management using **Redux Toolkit (`@reduxjs/toolkit`)** and **React-Redux**. It highlights the Redux slice pattern, immutable state mutations using Immer under the hood, unique ID generation via `nanoid()`, and explicit action dispatching.

---

## Key Features

- **Redux Slice Architecture**: Organizes state reducers and actions cleanly inside `todoSlice.js`.
- **Global Store Provider**: Wraps the React application in `<Provider store={store}>` (`src/app/store.js`).
- **Action Dispatching**: Utilizes `useDispatch()` to trigger `addTodo` and `removeTodo` actions.
- **State Selection**: Uses `useSelector()` for declarative, reactive UI updates.
- **Tailwind CSS Integration**: Clean interactive UI components (`AddTodo.jsx`, `Todos.jsx`).

---

## Project Structure

```
Todo-using-redux/
├── src/
│   ├── app/
│   │   └── store.js              # Redux store configuration
│   ├── features/
│   │   └── todo/
│   │       └── todoSlice.js       # Redux Toolkit slice & reducers
│   ├── components/
│   │   ├── AddTodo.jsx           # Task creation form component
│   │   └── Todos.jsx             # Task list component
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js
```

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Ashokb-dev/Todo-using-redux.git
cd Todo-using-redux

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## Author

**Ashok K.**  
Contact: [AshokB8910@gmail.com](mailto:AshokB8910@gmail.com)  
GitHub: [Ashokb-dev](https://github.com/Ashokb-dev)
