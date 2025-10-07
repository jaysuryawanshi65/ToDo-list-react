# ToDo List React App

This is a simple and modern To-Do List application built with React, Vite, and Tailwind CSS. It allows you to add, complete, and delete tasks, with your list saved in your browser's local storage.

## Features

- Add new tasks to your to-do list
- Mark tasks as complete/incomplete
- Delete tasks
- Tasks are saved in local storage (persist after refresh)
- Responsive and clean UI with Tailwind CSS


## Demo

Live: [to-do-list-react-3r6e.vercel.app](https://to-do-list-react-3r6e.vercel.app)

![App Screenshot](./src/assets/todo_icon.png)

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/jaysuryawanshi65/ToDo-list-react.git
   cd ToDo-list-react
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:

```sh
npm run dev
```

Open your browser and go to the URL shown in the terminal (usually http://localhost:5173).

### Building for Production

To build the app for production:

```sh
npm run build
```

The output will be in the `dist` folder.

## Project Structure

- `src/` - Source code
  - `App.jsx` - Main app component
  - `Components/` - Contains `Todo.jsx` (main logic/UI) and `TodoItems.jsx` (individual task)
  - `assets/` - Icons and images
- `public/` - Static files
- `index.html` - HTML template
- `index.css` - Tailwind and custom styles

## Manual / How to Use

1. **Add a Task:**
   - Type your task in the input box and click the "ADD +" button.
2. **Mark as Complete:**
   - Click the circle/tick icon next to a task to mark it as complete or incomplete.
3. **Delete a Task:**
   - Click the trash/delete icon to remove a task from your list.
4. **Persistence:**
   - Your tasks are automatically saved in your browser. They will remain even if you refresh or close the tab.

## Technologies Used

- React
- Vite
- Tailwind CSS
- Local Storage API

## License

This project is open source and available under the [MIT License](LICENSE).
