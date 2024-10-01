
Navigation Menu

Code
Issues
Pull requests
Breadcrumbsalx-frontend-javascript
/0x00-ES6_basic/
Directory actionsMore options
Latest commit
Gedeonobae
Gedeonobae
2 years ago
History
Breadcrumbsalx-frontend-javascript
/0x00-ES6_basic/
Folders and files
Name	Last commit date
parent directory
..
image
2 years ago
0-constants.js
2 years ago
1-block-scoped.js
2 years ago
10-loops.js
2 years ago
11-createEmployeesObject.js
2 years ago
12-createReportObject.js
2 years ago
2-arrow.js
2 years ago
3-default-parameter.js
2 years ago
4-rest-parameter.js
2 years ago
5-spread-operator.js
2 years ago
6-string-interpolation.js
2 years ago
7-getBudgetObject.js
2 years ago
8-getBudgetCurrentYear.js
2 years ago
9-getFullBudget.js
2 years ago
README.md
2 years ago
README.md
0x00. ES6 Basics
Concepts
For this project, we expect you to look at these concepts:

Software Linter
Definition

A software linter also known as a “linter” is a tool used to identify and report potential issues (syntax errors, undeclared variables, etc.) in a program. It can even report convention or style inconsistencies. It does so by highlighting them so that the programmer is aware, so changes can be made. There are a wide variety of linters as well as lint rules for specific programming languages and even for software frameworks.

There are typically two ways to lint code:

Actively
Passively
Active

Active checking is typically achieved by running a monitor tool that is constantly checking the file that your working on in order to spot inconsistencies and possible errors (e.g., having a specific linter along with some lint rules installed as a plug-in in your Code Editor). Passive

Passive checking is done by taking a piece of code, and manually running it through a tool to identify potential issues. For example, copying and pasting your code into a specific linter tool, or running the linter against a specific file using the command line. This tool can be installed locally or be available as a service (e.g., website on the Internet). Examples

Screenshot of an active linter pycodestyle (Python) integrated into Visual Studio Code

Resources
Read or Watch
ECMAScript 6 - ECMAScript 2015
Statements and declarations
Arrow functions
Default parameters
Rest parameter
Javascript ES6 — Iterables and Iterators
Requirements
All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
Allowed editors: vi, vim, emacs, Visual Studio Code
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the js extension
Your code will be tested using the Jest Testing Framework
Your code will be analyzed using the linter ESLint along with specific rules that we’ll provide
All of your functions must be exported
Setup
Install NodeJS 12.11.x
(in your home directory):

curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y


$ nodejs -v
v12.11.1
$ npm -v
6.11.3


Install Jest, Babel, and ESLint
in your project directory:

Install Jest using: npm install --save-dev jest

nstall Babel using: npm install --save-dev babel-jest @babel/core @babel/preset-env

Install ESLint using: npm install --save-dev eslint

Configuration files
package.json
package.json
babel.config.js
.eslintrc.js
Finally…

Don’t forget to run npm install from the terminal of your project folder to install all necessary project dependencies.
