---

# Albums List React App

This project is a React.js application that displays a list of albums. Users can view albums, add new albums, edit existing ones, and delete them. It utilizes technologies such as Redux Toolkit and RTK Query for state management, along with CSS for styling.

## Technologies Used:
- React.js
- Redux Toolkit
- RTK Query
- CSS

## Fake Server:
The project fetches album data from a fake server hosted at JSONPlaceholder (https://jsonplaceholder.typicode.com/albums).

## Hosted Link:
[![Netlify Status](https://api.netlify.com/api/v1/badges/f9d577cf-79c2-4dae-916c-e09970009a57/deploy-status)](https://app.netlify.com/sites/albums-list-react-app-p666r/deploys)

The live demo of the application can be accessed here: https://vermillion-basbousa-20cc6c.netlify.app.

## Screenshots:
![Screenshot 1](https://github.com/P666R/Albums-List-React-App/blob/main/public/alb.jpg)
![Screenshot 2](https://github.com/P666R/Albums-List-React-App/blob/main/public/alb1.jpg)

## Folder Structure:

- albumslistapp
  - node_modules
  - public
    - index.html
  - src
    - components
      - AlbumForm.js
      - AlbumModal.js
      - AlbumsList.js
    - store
      - apis
        - albumsApi.js
      - slice
        - albumsApiSlice.js
        - albumsLocalSlice.js
        - editSlice.js
        - formSlice.js
        - modalSlice.js
      - index.js
    - App.js
    - index.css
    - index.js
  - package-lock.json
  - package.json
  - README.md

## Installation And Usage:

1. Clone the repository:
   ```bash
   https://github.com/D-4-DIBAKAR/React.js-Skills-Test.git
   ```

2. Navigate to the project directory:
   ```bash
   cd react-album
   ```

3. Install all dependencies:
   ```bash
   npm install
   ```

4. Run the project:
   ```bash
   npm start
   ```

Now you can access the application at localhost:3000.

---
