                                    Counter Value Application

## Overview
This is a NextJs Application that allows usera to increment and decrement values while storing the history of the values.It has a debounced functionality that allows users to search through a list and its only triggered after a duration of seconds. To add on it has the lazy loading functionality to improve performance.

## Prerequisites
- Node.js
- npm
### Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/BitByteSavvy/Counter-App.git>


## Getting Started
Navigate to your project directory
run npm install : #To load the necessary dependencies
npm run dev : #run the development server:
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Testing
Writing test cases is a crucial part to ensure your application works as expected.This application uses the Jest Framework
* npm install --save-dev jest @testing-library/react @testing-library/jest-dom jest-environment-jsdom #installs the necessary libraries for testing.
Next, create a jest.config.js file in the root of your project to configure Jest

## On Testing
You may encounter an error regarding the JSX syntax, so resolve this by create a .babelrc file in your root directory and add this code 
{
    "presets": ["@babel/preset-env", "@babel/preset-react"]
}
once done rerun the npm test

Ensure you clear cache before testing by running npm cache clean --force






