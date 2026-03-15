# 🌗 LightDark — Light/Dark Mode Toggle

A clean and minimal **React** application demonstrating a **Light/Dark mode toggle**, built with **Vite** for a fast and modern development experience.

---

## 🚀 Features

- 🌙 Toggle between Light and Dark themes seamlessly
- ⚡ Blazing-fast development with Vite + HMR (Hot Module Replacement)
- 🎨 CSS-driven theming with smooth transitions
- ♻️ Reusable React components
- 📱 Responsive and accessible UI
- 🧹 ESLint configured for clean code

---

## 🛠️ Tech Stack

| Technology   | Purpose                              |
|--------------|--------------------------------------|
| React        | UI component library                 |
| Vite         | Build tool & dev server              |
| JavaScript   | Primary language                     |
| CSS          | Styling & theme variables            |
| ESLint       | Code linting & quality enforcement   |

---

## 📁 Project Structure

```
LightDark/
├── public/             # Static assets
├── src/                # React source code
│   ├── components/     # Reusable UI components
│   ├── App.jsx         # Root component with theme logic
│   ├── main.jsx        # App entry point
│   └── index.css       # Global styles & CSS variables
├── index.html          # HTML entry point
├── vite.config.js      # Vite configuration
├── eslint.config.js    # ESLint configuration
└── package.json        # Project metadata & scripts
```

---

## ⚙️ Getting Started

### Prerequisites

- **Node.js** v18 or higher
- **npm** (comes with Node.js)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/rouamansour/LightDark.git
cd LightDark
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Open your browser**

Navigate to [http://localhost:5173](http://localhost:5173) to view the app.

---

## 📦 Available Scripts

| Script            | Description                        |
|-------------------|------------------------------------|
| `npm run dev`     | Start the development server       |
| `npm run build`   | Build the app for production       |
| `npm run preview` | Preview the production build       |
| `npm run lint`    | Run ESLint to check code quality   |

---

## 🎨 How It Works

The theme toggle works by switching a CSS class (e.g., `dark`) on the root element. CSS custom properties (variables) handle the color scheme for both modes:

```css
/* Light mode (default) */
:root {
  --background: #ffffff;
  --text-color: #111111;
}

/* Dark mode */
.dark {
  --background: #111111;
  --text-color: #ffffff;
}
```

The React component manages the current theme in state and applies the appropriate class on toggle.
