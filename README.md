# Tailwind CSS with React App

Docs
https://tailwindcss.com/docs/guides/create-react-app

Github
https://github.com/tailwindlabs/prettier-plugin-tailwindcss

```bash
$ npx create-react-app my-project
$ cd my-project
$ npm install -D tailwindcss postcss autoprefixer
$ npm install -D prettier prettier-plugin-tailwindcss
$ npx tailwindcss init -p
```

`tailwind.config.js`

```js
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

`src/index.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
