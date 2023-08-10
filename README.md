# React Project 1 Documentation

<img src="https://github.com/Ningsang-Jabegu/Learning-React-1/blob/main/Screenshot%20without%20hover.png" alt="Project Screenshots" height="400">


## Overview

This documentation provides an insight into **React Project 1**, a simple project developed for learning purposes using the React library. The project aims to demonstrate fundamental concepts of React and is intended for educational purposes.

## Project Description

**React Project 1** serves as a practical exploration of React's core principles and features. The project showcases the creation of a web application using React, allowing learners to grasp essential concepts in a hands-on manner.

## Deployment

The actual code that is ready for deployment can be found in the `build` folder of the project. To access the live version of the project, visit [https://react-project-1-by-ningsang-jabegu.netlify.app](https://react-project-1-by-ningsang-jabegu.netlify.app). This live version offers an opportunity to interact with the application.

## Project Creation

The project was initiated using the following steps:

1. **Create React App**: The project setup was accomplished using the Create React App tool. This streamlined the creation of a React application with the necessary configurations.

   ```terminal
   npx create-react-app react-project-1
2. **Folder Structure Adjusted**: The project adheres to a specific folder structure for organization and maintainability. (build folder is what actually renders in the browser)
   ```terminal
   ├── build
       ├── static
         ├── js
            ├── main.3284944c.js
            ├── main.3284944.js.LICENCE.txt
            ├── main.3284944c.js.map
         ├── asset-manifest.json
         ├── index.css
         ├── index.html
         ├── manifest.json
         ├── robots.txt
   ├── public
      ├── index.css
      ├── index.html
      ├── manifest.json
      ├── robots.txt
   └── src
      ├── .gitignore
      ├── README.md
      ├── package-lock.json
      ├── package.json
   ```
3.**Initializing and pushing Git**: For the documentation purposes this project is uploaded into the github
   ```terminal
      git init
      git add README.md
      git commit -m "First commit"
      git branch -M main
      git remote add origin https://github.com/{username}/{repository-name}.git
      git push -u origin main
   ```
   + With this your command your project is linked with your github repo. This will only create the README.md file in your github repo and also in the local file (that is in your computer).
   + To upload all the file now you need to add following command in terminal
   ```terminal
      git add .
      git commit -m "uploading my project file"
      git push
   ```

   + After this your project files will be upload into your github repo. and every time you want to changes the file in your system, you can only use the 3 line (above second code) code to push your updated file. Add something that describes your change in the second line of the code inside the "...".
   
4.  **Usage**: The project is designed to illustrate the core concepts of React, making it an excellent resource for React beginners. By exploring the project's source code, learners can gain insights into:

   - familiarize with the jsx syntax
   - Deployment of React applications
5. **Contributing**: This project is intended as a learning exercise and is not actively seeking contributions. However, suggestions and feedback are always welcome.
6. **License**: This project is licensed under the MIT License.

**Disclaimer**: This project was created solely for educational purposes, and the actual code may have limited functionality or features. It is not intended for production use.
