# My Todo App

A simple and elegant todo list application built with Next.js 16, TypeScript, and Tailwind CSS.

## Features

- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Delete individual tasks
- ✅ Clear all tasks at once
- ✅ Persistent storage using localStorage
- ✅ Dark mode support
- ✅ Responsive design
- ✅ Real-time task counter

## Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd to-do
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality checks

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4
- **Fonts:** Geist Sans & Geist Mono
- **State Management:** React useState & useEffect
- **Persistence:** Browser localStorage

## Project Structure

```
to-do/
├── app/
│   ├── globals.css      # Global styles and Tailwind imports
│   ├── layout.tsx       # Root layout component
│   └── page.tsx         # Main todo app component
├── public/              # Static assets
├── package.json         # Dependencies and scripts
├── tsconfig.json        # TypeScript configuration
├── tailwind.config.*    # Tailwind CSS configuration
└── eslint.config.mjs    # ESLint configuration
```

## Usage

1. **Adding Tasks:** Type in the input field and press Enter or click "Add Task"
2. **Completing Tasks:** Click the checkbox next to any task
3. **Deleting Tasks:** Click the trash icon next to a task
4. **Clearing All:** Use the "Clear All" button in the footer when tasks exist

Your tasks are automatically saved to your browser's localStorage and will persist between sessions.

## Dark Mode

The app automatically respects your system's dark mode preference. You can toggle dark mode in your browser or OS settings.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run `npm run lint` to ensure code quality
5. Test your changes
6. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).
