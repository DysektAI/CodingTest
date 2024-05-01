# Installation Guide for the Web Language Proficiency Tester

This document provides detailed instructions on how to set up your development environment to work on the Web Language Proficiency Tester. These instructions assume a basic knowledge of software installation and command line operations.

## Prerequisites

Before you begin, ensure you have the following installed:
- **Git**: For cloning the repository and managing versions.
- **Node.js**: Required to run the backend if using Node.js, or to manage dependencies for the frontend.

`node -v` to check if its installed and working
- **npm**: Package managers for managing JavaScript dependencies. (Installed with Node.js)

`npm -v` to check if its installed and working

## Cloning the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/DysektAI/CodingTest
cd CodingTest
# Install dependencies
npm install
# Run the development server
npm start
```

## Verifying the Installation
To verify that everything is set up correctly, navigate to http://localhost:3000 (or whatever port your application uses) in your browser. You should see the application running.

## Troubleshooting
Problem: npm install fails.
Solution: Ensure Node.js and npm are installed and updated. Try deleting the `node_modules` folder and running npm install again.

### Need Help?
If you encounter problems not covered in this guide, please raise an issue in the GitHub repository: [GitHub issues](https://github.com/DysektAI/CodingTest/issues).
