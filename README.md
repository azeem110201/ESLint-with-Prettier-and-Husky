# Getting Started with ESLint with Prettier and Husky for pre-commit checks

This starter-project demonstrate the use of style guide (here we are using specific style guide of AirBnb) which ensures that whatever the code is written/committed matches the coding styles or not. If the code styles are not properly followed, then the commit will fail.

## Available Scripts

Clone the project and then install the libraries, you can run:

### `npm install`

then run

### `npm run lint`

This will display the error messages along with the file name, line number where the code styles are not followed. Either fix them manually or you can run the below command which fixes all eslint styles autmatically

### `npm run lint:fix`

