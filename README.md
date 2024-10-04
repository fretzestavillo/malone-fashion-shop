# Malone Shop Center

This project combines React and Vite for front end, Google App Script for back end also for handling API and Google Sheet for data persistent.

## Getting Started

To set up the project, follow these steps:

### Clone the Repository

```bash
git clone https://github.com/fretzestavillo/malone-fashion-shop.git
```

### Change directory

```
cd malone-fashion-shop/
```

### Remove the existing git

```
rm -rf .git
```

### Install the dependencies

```
npm install
```

### For development

```
npm run dev
```

### For deployment

```
Create repository in Github
```

### vite.config.ts

```
 base: mode === "production" ? "/<replace with your  repository name>/" : "/", // Set base for GitHub Pages in production
```

### Command to connect local repository to remote repository

```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <replace with your github repository>
git push -u origin main
```

### Run command

```
npm run deploy
```
