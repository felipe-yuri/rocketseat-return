# Rocketseat Return

## HandsOn

## Libs
### 1. TailWindCSS
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```
#### postcss.config.js
```bash
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}
```
#### tailwind.config.js
```bash
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
#### global.css
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

