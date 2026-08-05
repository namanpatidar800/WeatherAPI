# MaterialUI Mini Project

A modern React application built with **Material-UI (MUI)** and **Vite** that showcases a responsive, feature-rich user interface.

## 🌟 Features

- ⚛️ **React 19** - Latest React with modern hooks
- 🎨 **Material-UI Components** - Professional and accessible UI components
- ⚡ **Vite** - Lightning-fast development and build tool
- 📱 **Responsive Design** - Mobile-first approach
- 🎯 **Type-Safe** - Built with TypeScript support
- 🧪 **ESLint** - Code quality and best practices

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher) - [Download](https://nodejs.org/)
- **npm** or **yarn** package manager

## 🚀 Getting Started

### 1. Install Dependencies

```bash
npm install
# or
yarn install
```

### 2. Run Development Server

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

### 3. Build for Production

```bash
npm run build
# or
yarn build
```

### 4. Preview Production Build

```bash
npm run preview
# or
yarn preview
```

## 📦 Project Structure

```
mini-project-react/
├── src/
│   ├── App.jsx          # Main application component
│   ├── App.css          # Global styles
│   ├── main.jsx         # Entry point
│   ├── components/      # Reusable components
│   └── pages/           # Page components
├── public/              # Static assets
├── index.html           # HTML template
├── vite.config.js       # Vite configuration
├── eslint.config.js     # ESLint configuration
└── package.json         # Project dependencies
```

## 🛠️ Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

## 📚 Technology Stack

- **React** - UI library
- **Material-UI (MUI)** - Component library
- **Vite** - Build tool and development server
- **Emotion** - CSS-in-JS styling
- **Roboto Font** - Material Design default font

## 🎨 Material-UI Components

This project includes access to all MUI components:

```javascript
import { Button, Card, TextField, AppBar, Box } from '@mui/material';
import { Search, Settings, Menu } from '@mui/icons-material';
```

## 📖 Resources

- [React Documentation](https://react.dev/)
- [Material-UI Documentation](https://mui.com/)
- [Vite Documentation](https://vitejs.dev/)
- [Material Design](https://material.io/design)

## 🔧 Configuration

### Vite Config
Edit `vite.config.js` to customize the Vite configuration.

### ESLint Config
Edit `eslint.config.js` to customize linting rules.

### MUI Theme
You can customize the Material-UI theme by creating a theme configuration:

```javascript
import { createTheme, ThemeProvider } from '@mui/material/styles';

const theme = createTheme({
  palette: {
    primary: {
      main: '#1976d2',
    },
  },
});

export default theme;
```

## 📱 Responsive Design

MUI provides excellent responsive design utilities:

```javascript
import { Box, Grid } from '@mui/material';

<Grid container spacing={2}>
  <Grid item xs={12} sm={6} md={4}>
    {/* Content */}
  </Grid>
</Grid>
```

## 🌐 Live Demo

Visit the live demo of this project:

🔗 **[Live Demo Link](#)** *(https://weatherapi-jqcr.onrender.com/)*

### Deployment Options:
- [Render](https://render.com/) - Recommended for this project
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)

### Deploy to Render (Recommended)

#### Step 1: Push your code to GitHub
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

#### Step 2: Connect to Render
1. Go to [Render.com](https://render.com)
2. Click **"New +"** → **"Static Site"**
3. Connect your GitHub repository
4. Fill in the deployment settings:

| Setting | Value |
|---------|-------|
| **Name** | `mini-project-react` |
| **Build Command** | `npm run build` |
| **Publish Directory** | `dist` |

#### Step 3: Deploy
- Click **"Create Static Site"**
- Render will automatically build and deploy your project
- Your site will be available at: `https://your-project-name.onrender.com`

#### Environment Variables (if needed)
Add any environment variables in the **Environment** section on Render dashboard.

---

### Build & Publish Details

```
Build Command:      npm run build
Publish Directory:  dist
Framework:          Vite + React
```

**What happens during build:**
- Vite compiles React components
- Optimizes assets and bundles files
- Outputs production-ready files to `dist/` directory

---

### Deploy to Vercel:
```bash
npm install -g vercel
vercel
```

### Deploy to Netlify:
```bash
npm run build
# Then drag & drop the 'dist' folder to Netlify
# Or connect your GitHub repository
```

## 🐛 Troubleshooting

### Port already in use
If port 5173 is already in use, Vite will automatically use the next available port.

### Module not found errors
```bash
# Clear node_modules and reinstall
rm -rf node_modules
npm install
```

### Build issues
```bash
# Clear build cache
rm -rf dist
npm run build
```

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Support

If you have any questions or need help, feel free to open an issue on GitHub.

---

**Made with ❤️ using React & Material-UI**
