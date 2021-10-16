# Portfolio Generator
Generate a portfolio of your GitHub projects by answering some questions from the command line.

## Installation
Use of this program requires that the user have installed [node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
1. Clone this repository to your local computer
```
git clone git@github.com:Qcent/portfolio-generator.git
```

2. Navigate to project directory and install required node packages
```
cd portfolio-generator
npm install
```

## Usage
```
node app.js
```
This will run a script that will prompt you for the required information to generate your portfolio. Once the questionaire is completed an `index.html ` and a `style.css` file, that make up your newly created portfolio, will be saved in the project's `/dist` folder.

![The Command Line]('./assets/app-screenshot1.png')
![The Output]('./assets/app-screenshot2.png')