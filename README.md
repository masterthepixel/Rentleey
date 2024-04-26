# Rentleey
 Rentleey Prelaunch Sign Up Form

## Setup 
# Setting Up the Rentleey Repository

Follow these steps to clone and set up the Rentleey project using Yarn and Gulp.

## Standup the Repository

Clone the Rentleey repository to your local machine using the following command:

git clone https://github.com/masterthepixel/Rentleey.git
cd Rentleey

npm install -g yarn
npm install --global gulp-cli


Navigate to the project directory (if you are not already there) and use Yarn to install all dependencies:

bash
yarn install

Finally, start the development environment using Gulp. This command will start a local development server and watch for any changes in your code, automatically reloading your browser:

bash
Copy code
gulp


### Structure:
├── HTML
    ├── dist - Compiled version (Production Version)
    ├── src directory
        ├── assets
            ├── HTML Pages
            ├── images
            ├── js
            └── scss
                └── tailwind.scss (main css file)
    ├── tailwind.config.js
    ├── gulpfile.js
    ├── package.json
    └── yarn.lock




- Make sure to replace `https://your-repository-url.git` with your actual GitHub repository URL.
- Adjust any specific version numbers or additional steps as necessary for your project's requirements.
- Consider adding a `CONTRIBUTING.md` file if you're inviting others to contribute to the project.

This README should provide a clear guide for setting up and running your project, along with a basic overview of the project structure.
