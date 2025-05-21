# PassOp - Your Own Password Manager

PassOp is a simple, modern password manager built with React, Vite, and Tailwind CSS. It allows you to securely store, view, edit, and delete your passwords locally in your browser using `localStorage`. The project features a clean UI, responsive design, and instant feedback using toast notifications.

## Features

- **Add Passwords:** Save website, username, and password entries.
- **View Passwords:** See all your saved passwords in a table.
- **Edit Passwords:** Update any saved password entry.
- **Delete Passwords:** Remove any password entry with confirmation.
- **Show/Hide Password:** Toggle password visibility in the input field.
- **Persistent Storage:** All data is stored in your browser's `localStorage`.
- **Responsive Design:** Works well on desktop and mobile devices.
- **Modern UI:** Built with Tailwind CSS and React.

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [UUID](https://www.npmjs.com/package/uuid)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or above)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd Passmanager
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```sh
npm run build
```

### Preview Production Build

```sh
npm run preview
```

## Project Structure

```
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Manager.jsx      # Main password manager logic and UI
│   │   └── Navbar.jsx       # Top navigation bar
│   ├── App.jsx              # Main app component
│   ├── App.css              # Custom styles and responsive tweaks
│   ├── index.css            # Tailwind CSS imports
│   └── main.jsx             # Entry point
├── icons/                   # SVG icons used in the UI
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── README.md
```

## Usage

1. Enter the website URL, username, and password in the input fields.
2. Click **Save Password** to add it to your list.
3. View, edit, or delete your saved passwords in the table below.
4. Use the eye icon to toggle password visibility while entering.

## Security Note

This project stores passwords in plain text in your browser's `localStorage`. **Do not use real or sensitive passwords.** This is for learning/demo purposes only.

## License

This project is open source .

---

Made with ❤️ using React and Tailwind CSS.
