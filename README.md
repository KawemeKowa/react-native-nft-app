This project aims to be a strong foundation for react-native applications. It provides a clear and organized structure, core dependencies, and boilerplate to jumpstart development.

## Prerequisites

- [Node.js > 12](https://nodejs.org) and npm (Recommended: Use [nvm](https://github.com/nvm-sh/nvm))
- [expo go](https://expo.dev/client)
- [VS code](https://code.visualstudio.com)


## Base dependencies

- [react-navigation](https://reactnavigation.org/) navigation library.
- [expo].
- [metro].


## Usage

- Go to your project's root folder and run `npm install`.
- Run `npm start` or `expo start` to start your application!

(Using yarn: `yarn start`)

Note: Please read the Setup environments section that is below in this file for more information about the execution scripts.


DEV: `yarn ios` or `yarn android`

STG: `yarn ios:staging` or `yarn android:staging`

PROD: `yarn ios:prod` o `yarn android:prod`

Also, you can use npm following the same rule as before: `npm run ios:staging`

Modify the environment variables files in root folder (`.env.development`, `.env.production` and `.env.staging`)


## Screens

In this folder, you have the main objects to apply the composition architecture. Just create a folder for each screen you have in your application, call all the components and static resources you need to render the scene and finally use the corresponding hooks to interact with redux and create behaviors depending on the store.

To keep the structure, extract the styles from the main file and place it in a {namefile.styles.js} do the same for the set of tests needed for each screen with the file {namefile.test.js}
