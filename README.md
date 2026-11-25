# Soham Vijay Mhatre Election Website

Campaign website for the West Zone 2 Zonal Representative election for the IIM Bangalore BBA in Digital Business and Entrepreneurship program.

## What is included

- Complete React and TypeScript source code
- Vite configuration
- Tailwind CSS styling
- Candidate photo and IIMB logo assets
- Package configuration and lockfile

## Run the website locally

### Requirements

Install Node.js 22 or newer and pnpm.

### Commands

```bash
pnpm install
pnpm dev
```

Open the local address shown in the terminal, normally `http://localhost:5173`.

## Create a production build

```bash
pnpm build
```

The production files will be created in the `dist` folder.

## Upload to GitHub using the website

1. Sign in at GitHub.
2. Select **New repository**.
3. Enter a repository name such as `soham-election-website`.
4. Keep the repository public or private according to your preference.
5. Do not add another README because this package already includes one.
6. Create the repository.
7. Select **uploading an existing file**.
8. Extract this ZIP file on your computer.
9. Drag all extracted files and folders into the GitHub upload area.
10. Select **Commit changes**.

## Upload to GitHub using Git

Create an empty GitHub repository first, then run these commands from the extracted project folder:

```bash
git init
git add .
git commit -m "Add election campaign website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY` with your GitHub details.

## Deploy online

### Vercel

1. Sign in to Vercel with GitHub.
2. Select **Add New Project**.
3. Import your GitHub repository.
4. Vercel will detect Vite automatically.
5. Select **Deploy**.

### Netlify

1. Sign in to Netlify with GitHub.
2. Select **Add new site** and **Import an existing project**.
3. Choose the GitHub repository.
4. Use `pnpm build` as the build command.
5. Use `dist` as the publish directory.
6. Select **Deploy**.

## Main files

- `src/App.tsx` contains the website sections and text.
- `src/index.css` contains the complete visual styling.
- `public/assets` contains the candidate photo and IIMB logo.
- `package.json` contains the project commands and dependencies.
