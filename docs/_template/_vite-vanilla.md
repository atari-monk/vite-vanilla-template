## Vite Vanilla Application

This repository serves as a reusable starting template for Vite projects using TypeScript without a framework.

### 1. Create the Vite TypeScript project

Using `pnpm` as the package manager:

```sh
pnpm create vite@latest vite-vanilla -- --template vanilla
```

### 2. Remove the default Vite boilerplate

* Clear the contents of `index.html`
* Clear the contents of `styles.css`
* Remove everything from `main.ts` except the stylesheet import
* Delete the `assets` directory
* Keep `favicon` in the `public` directory

### 3. Add a minimal `index.html`

```html
[[include:/home/atari-monk/atari-monk/project/vite-vanilla/index.html]]
```

### 4. Add `styles.css` for an empty black page

```css
[[include:/home/atari-monk/atari-monk/project/vite-vanilla/src/style.css]]
```

### 5. Add `.gitignore`

```text
node_modules
dist
```

### 6. Initialize the Git repository

```sh
git init
git add .
git commit -m "feat: initialize Vite vanilla application"
```

### 7. Create the remote repository

Create repo on GitHub page and run commands:

```sh
git branch -M main
git remote add origin https://github.com/atari-monk/vite-vanilla
git push -u origin main
```