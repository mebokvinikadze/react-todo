# React todo application quiz from my university course

![Demo](![image](https://github.com/user-attachments/assets/8f83e9cd-728e-4119-8ed0-5b24be976c6c))

A minimal, theme-switching todo list with drag & drop

---

## Features
- **Dark/Light Mode** - Toggle between themes with persistent preference
- **Drag & Drop** - Reorder tasks intuitively
- **Local Storage** - Tasks persist between sessions
- **Mobile Friendly** - Responsive across all devices
- **Fast Animations** - Smooth UI interactions

---


## Installation
1. Clone the repository:
```bash
git clone https://github.com/mebokvinikadze/react-todo.git
cd react-todo
npm install
npm run dev

## Project Source
src/
├── components/
│   ├── TaskItem.tsx
│   ├── TaskList.tsx
│   └── ThemeToggle.tsx
├── hooks/
│   └── useLocalStorage.ts
├── styles/
│   └── global.css
└── App.tsx
