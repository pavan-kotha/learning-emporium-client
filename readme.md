# UH Manoa College of Natural Sciences Learning Emporium Website

## To-do

## Documentation


### -- Stack -- 

React (Front end framework), Webpack (Compiles TypeScript), Vercel (hosting & deployment)

### -- Getting started -- 

#### INSTALL DEPENDENCIES
1. Make sure you have node installed on your computer
2. In a new terminal, run "npm install"

#### RUN THE APPLICATION

1. Run "npm run dev" to start development mode or run "npm run build" to create a production build
2. Download live server VSCode extension then in HTML folder, right click index.html and open with live server

### -- Development & Production Life Cycle --

#### TASK ASSIGNMENT & COMPLETION

- For issues and completing tasks, we will use GitHub issues and pull request
- An issue will be assigned to someone and in that issue, the assigned person can create a branch for the issue
- After completing your task and pushing your changes in the branch you made, make a pull request to main and assign someone else to review your changes
- Vercel will have automatically check for merge conflicts and will give you a deployment preview for your branch, use these to test changes
- After the pull request reviewer reviews the changes and tests changes in deployment preview and all is good, pull request reviewer can merge the changes to main

#### DEVELOPMENT

- Run "npm run dev" in a new terminal, this will run webpack in development mode and your changes will be re-built upon every save
- Webpack compiles the JavaScript and TypeScript in our react code into a static javaScript file that an HTML page can take as a script
- Webpack is configured to compile to a folder called dist
- Before you push your changes, make sure to run prettier to format all you code, You can install prettier as a VS Code extension : https://www.digitalocean.com/community/tutorials/how-to-format-code-with-prettier-in-visual-studio-code

#### PRODUCTION

- A production build can be ran with command "npm run build"
- No need to worry about creating production builds as Vercel is configured to run a production build on the cloud upon a deploy


#### VERCEL

- The repo is connected to Vercel and automatically re-delopys with changes to main
- Vercel is configured to run a production build upon a new deploy




