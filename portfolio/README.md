# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

# Scaffolding Vite Project
```sh
npm create vite@latest
```

- Install Tailwind CSS
 Install tailwindcss and @tailwindcss/vite via npm.
```bash
npm install tailwindcss @tailwindcss/vite
```
- Configure the Vite plugin
 Add the @tailwindcss/vite plugin to your Vite configuration.
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
  Add an @import to your CSS file that imports Tailwind CSS.
```bash
@import "tailwindcss";
```

- Start your build process
  Run your build process with npm run dev or whatever command is configured in your package.json file.
  ```bash
  npm run dev
  ```
  
  - Start using Tailwind in your HTML
    Make sure your compiled CSS is included in the <head> (your framework might handle this for you), then start using Tailwind’s utility classes to style your content.
```bash
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/src/styles.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```

👨‍💻 Author
 
- Kalana Yasassri  <a href="https://github.com/DarkFeed2005" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=github" alt="github" width="20" height="20"/> </a>
- LinkedIn <a href="https://www.linkedin.com/in/kalana-yasassri-684591251/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="linkedin" width="20" height="20"/> </a>
- Instagram <a href="https://www.instagram.com/kalana_yasassri/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=instagram" alt="instagram" width="20" height="20"/> </a> 
  
🎨 License
This project is open-source under the MIT License.

