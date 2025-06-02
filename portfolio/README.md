# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

# Scaffolding Vite Project
```sh
npm create vite@latest my-project -- --template react
cd my-project
```

- Install Tailwind CSS
 Install tailwindcss and @tailwindcss/vite via npm.
```bash
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p
```
- Configure the Vite plugin
Install tailwindcss and its peer dependencies, then generate your tailwind.config.js and postcss.config.js files.
```bash
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'
export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})
```

- Import Tailwind CSS
  Add the paths to all of your template files in your tailwind.config.js file.
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

- Add the Tailwind directives to your CSS
 Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file
  ```bash
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  ```
  
- Start your build process
  Run your build process with npm run dev or whatever command is configured in your package.json file.
  ```bash
  npm run dev
  ```
  
  - Start using Tailwind in your project
   Start using Tailwind’s utility classes to style your content.
```bash
export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}
```

👨‍💻 Author
 
- Kalana Yasassri  <a href="https://github.com/DarkFeed2005" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=github" alt="github" width="20" height="20"/> </a>
- LinkedIn <a href="https://www.linkedin.com/in/kalana-yasassri-684591251/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="linkedin" width="20" height="20"/> </a>
- Instagram <a href="https://www.instagram.com/kalana_yasassri/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=instagram" alt="instagram" width="20" height="20"/> </a> 
  
🎨 License
This project is open-source under the MIT License.

