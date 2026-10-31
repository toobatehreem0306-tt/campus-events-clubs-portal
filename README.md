# Campusly — Campus Events & Clubs Portal

A beginner-friendly React app for discovering campus events and student clubs. It was created as a Group 7 project for an eight-student team.

## What it does

- Browse sample campus events and clubs.
- Filter and search events by name, club, venue, or category.
- Mark yourself as interested in an event and join clubs (the buttons update locally in your browser).
- View a responsive dashboard that works on desktop and mobile.

This is a front-end prototype: the sample content is stored in the app, and registrations are not saved to a server.

## Run it on your computer

1. Install Node.js (the LTS version) from [nodejs.org](https://nodejs.org/).
2. Open a terminal in this project folder.
3. Run `npm install` once, then `npm run dev`.
4. Open the local address printed in the terminal, usually `http://localhost:5173`.

To make a production build, run `npm run build`. The generated website files will be in `dist/`.

## Upload this project using the GitHub website

1. Sign in at [github.com](https://github.com/) and choose **+ → New repository**.
2. Name it `campus-events-clubs-portal`, choose **Public** or **Private**, and create the repository. For an empty upload, leave “Add a README” unchecked.
3. If you downloaded this project as a ZIP, extract it first. Open the project folder and select its contents—not the outer folder and not `node_modules`.
4. On the new repository page, choose **Add file → Upload files**. Drag the project files and the `src` folder into the upload area, or use the file chooser. Include `README.md`, `package.json`, `index.html`, `.gitignore`, and `src/`.
5. Enter a commit message such as `Add Campusly React project`, then click **Commit changes**.

Do not upload `node_modules` or `dist`; they are ignored and can be recreated. GitHub's website uploads source code but does not run the app. To preview the project online later, connect the repository to a hosting service such as GitHub Pages or Vercel.

## Suggested team split (8 students)

1. Project coordination and README; 2. dashboard and navigation; 3. event data and event cards; 4. search and filters; 5. club cards and join interactions; 6. visual design and responsive styling; 7. accessibility and testing; 8. presentation and future feature planning.

## Tech

React, JavaScript, Vite, and CSS. No external UI library is required.
