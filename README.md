# 🧾 Red Hamd — Receipt App

A modern, full-featured **receipt management application** built with **React 19**, **Redux Toolkit**, and **Vite**. The app supports multiple languages, smooth animations, and a clean UI powered by Chakra UI, MUI, and Tailwind CSS.

🔗 **Live Demo:** [red-hamd.vercel.app](https://red-hamd.vercel.app)

---

## ✨ Features

- 📋 **Receipt management** — create, view, and manage receipts
- 🌐 **Multi-language support** — internationalization via `i18next` and `react-i18next`
- 🗂️ **Global state management** — powered by Redux Toolkit and React-Redux
- 🎨 **Rich UI components** — Chakra UI, MUI, and Tailwind CSS
- 🎞️ **Smooth animations** — Framer Motion for fluid transitions
- 🔔 **Toast notifications** — React Toastify and Sonner
- 🌍 **Client-side routing** — React Router DOM v7
- ⚡ **Blazing fast dev experience** — Vite with HMR

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | React 19 |
| State Management | Redux Toolkit, React-Redux |
| Build Tool | Vite 7 |
| Styling | Tailwind CSS 4, Chakra UI 3, MUI 7 |
| Animations | Framer Motion |
| Routing | React Router DOM 7 |
| i18n | i18next, react-i18next |
| HTTP Client | Axios |
| Notifications | React Toastify, Sonner |
| Icons | Lucide React |
| Linting | ESLint 9 |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** v18 or higher
- **npm** v9 or higher (or yarn / pnpm)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Diyor-Khasanov/red-hamd.git

# 2. Navigate into the project
cd red-hamd

# 3. Install dependencies
npm install
```

### Running Locally

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

---

## 📁 Project Structure

```
red-hamd/
├── public/             # Static assets
├── src/                # Application source code
│   ├── components/     # Reusable UI components
│   ├── pages/          # Route-level page components
│   ├── store/          # Redux store, slices
│   ├── locales/        # i18n translation files
│   └── main.jsx        # Application entry point
├── index.html          # HTML template
├── vite.config.js      # Vite configuration
├── eslint.config.js    # ESLint configuration
└── package.json        # Project metadata & dependencies
```

---

## 🌐 Internationalization

The app uses `i18next` with the browser language detector, supporting automatic language detection and easy addition of new languages by adding translation files to the `src/locales/` directory.

---

## 📦 Deployment

This project is deployed on **Vercel**. To deploy your own instance:

1. Fork this repository.
2. Import the repo into [Vercel](https://vercel.com).
3. Vercel will auto-detect the Vite framework — no extra config needed.
4. Click **Deploy**.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Diyor Khasanov**
- GitHub: [@Diyor-Khasanov](https://github.com/Diyor-Khasanov)
