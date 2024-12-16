# TypeScript Todos

A Vite-app using the Vanilla TypeScript template.

## Reproduce

### Step 1

Create a new Vite-app using the `vanilla-ts` template with the following command:

```bash
npm create vite@latest . -- --template vanilla-ts
```

This creates a new app **in the current folder**.

### Step 2

Run `npm install`.

### Step 3

* Delete `public/vite.svg`.
* Delete `src/counter.ts`.
* Empty `src/main.ts`.
* Empty `src/style.css`.
* Delete `src/typescript.svg`.

### Step 4

Create empty file `public/.gitkeep`, either in VS Code or using the command `touch public/.gitkeep`.

### Step 5

Fix `index.html` so it uses tabs instead of spaces 🤩. Also change the favicon as we deleted the previous one.

### Step 6

Import `style.css` in `main.ts`:

```ts
import "./style.css";
```

### Step 7

Run the development server to confirm that everything works.

```bash
npm run dev
```

The above command has to be run from the **root** folder for the app! For this app the root folder is named `42-typescript-todos`.

## Step 8

Install `bootstrap` with the following command from the **root** folder:

```bash
npm install bootstrap
```

Edit `src/main.ts` and add a new line *before* `import "./style.css";`:

```ts
import "bootstrap/dist/css/bootstrap.css";
```

The resulting file should look like this:

```ts
import "bootstrap/dist/css/bootstrap.css";
import "./style.css";
```

### Bonus - Activate Dark Mode 🦇🌘

Add `data-bs-theme="dark"` to the `<body>` tag in `index.html`.
