# Let me ask

A modern web application for creating rooms, asking questions, and receiving AI-generated answers. Users can create rooms, submit questions, and record audio questions, all in a clean and accessible interface.

## Features

- Create and list rooms
- Ask questions and receive AI-generated answers
- Record and upload audio questions
- Real-time updates with optimistic UI
- Accessible and responsive design

## Technologies Used

- **React 19** – UI library
- **TypeScript** – Type safety
- **Vite** – Fast build tool
- **React Router DOM** – Routing
- **@tanstack/react-query** – Data fetching and caching
- **React Hook Form** – Form management
- **Zod** – Schema validation
- **Tailwind CSS** – Utility-first CSS framework
- **clsx** and **tailwind-merge** – Class name utilities
- **class-variance-authority** – Variant-based styling
- **Lucide React** – Icon library
- **Day.js** – Date formatting
- **@radix-ui/react-label** and **@radix-ui/react-slot** – Accessible UI primitives

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

### Build for Production

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

## Project Structure

- `src/` – Source code
  - `components/` – UI components
  - `http/` – API hooks and types
  - `lib/` – Utility libraries (e.g., dayjs config)
  - `pages/` – Page components
  - `index.css` – Global styles
  - `main.tsx` – App entry point

## Notes

- The backend API should be running at `http://localhost:3333`.
- Audio recording uses the browser's MediaRecorder API (supported in most modern browsers).

---

Made with ❤️ using React, TypeScript,