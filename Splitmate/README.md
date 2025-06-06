# Splitmate Frontend

Frontend for **Splitmate**, an app to track and split shared expenses with friends.

## 🧰 Stack

- React
- TypeScript
- Vite

## ⚙️ Setup

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/splitmate-frontend
cd splitmate-frontend
```

### 2. Create Vite App

If not done yet:

```bash
npm create vite@latest
# Choose React + TypeScript
cd <project-name>
npm install
```

### 3. Folder Structure

```css
splitmate-frontend/
├── src/
│   └── main.tsx / App.tsx
├── .gitignore
├── LICENSE
├── package.json
└── README.md
```

### 4. Dev Script

Run the development server:

```bash
npm run dev
```

Your `package.json` should include:

```json
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview"
}
```

### 📄 .gitignore Example

```bash
node_modules/
dist/
.env
```

### 📝 License

MIT — see `LICENSE` file.
