## Alpine
```
### Add script in HTML boilerplate `<script defer src="https://unpkg.com/alpinejs@3.x.x/dist/cdn.min.js"></script>`
```

### Tailwind CLI Installation Steps
```
npm install -D tailwindcss
```
npx tailwindcss init
```

### npx tailwindcss init
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}

```

### Create a tailwind.css folder with these inside
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Run this tailwind watch command to spin up your tailwind
```
npx tailwindcss -i ./tailwind.css -o ./css/style.css --watch
```

Enjoy :palm_tree:
