<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/gwicho38/lefv-io">
    <img src="./public/favicon.ico" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">a page for all</h1>

  <p align="center">
    <a href="https://github.com/gwicho38/lefv-io#readme">&#160docs&#160</a>
    <a href="https://github.com/gwicho38/lefv-io/issues">&#160bugs&#160</a>
    <a href="https://github.com/gwicho38/lefv-io/issues">&#160features&#160</a>
  </p>
</p>

  <div align="center">
    <a href="https://github.com/gwicho38" target="_blank">
    <img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
    </a>
    </a>
    <a href="https://www.linkedin.com/in/luis-fernandez-de-la-vara/" target="_blank">
    <img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
    </a>
    <a href="https://twitter.com/gwicho38" target="_blank">
    <img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
    </a>
  </div>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About</a>
    </li>
    <li>
      <a href="#installation-and-setup">Installation and Setup</a>
    </li>
    <li>
      <a href="#dependencies">Dependencies</a>
    </li>
    <li>
        <a href="#scripts">Scripts</a>
    </li>
    <li>
        <a href="#hooks">Hooks</a>
    </li>
    <li>
      <a href="#project-status">Project Status</a>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#References">References</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

A scalable and templeted website to host personal projects and fragmented ramblings.

## Installation and Setup

Clone [lefv-io](https://github.com/gwicho38/lefv-io).

You will need `node` and `npm` installed globally on your machine.

Installation:

`npm install`

To Start Dev Server:

`npm run dev`

To Visit App:

`localhost:3000`

## Dependencies

This is an example of how to list things you need to use the software and how to install them.

-   npm
    ```sh
    npm install npm@latest -g
    ```
-   onchange - used in the scripts to listen for changes in files and automatically format them for you.
    ```sh
    npm install -g onchange
    ```
-   rimraf - needed in the `clean` script. It's used to bypass issues with removing `node_modules` in Windows.
    ```sh
    npm install -g rimraf
    ```

## Scripts

-   `npm start`: Start production build. Dependent on `npm run build`.
-   `npm run dev`: Starts dev server, formats code, runs prettier in watch mode.
-   `npm run build`: Build your code for production.
-   `npm run lint`: Runs ESlint.
-   `npm run lint:fix`: Runs `lint` and error fix.
-   `npm run prettier`: Outputs prettier errors.
-   `npm run prettier:fix`: Fixes all prettier errors.
-   `npm run prettier-watch`: uses `onchange` to watch for changed files and formats them automatically.
-   `npm run format`: Formats all of your files based on both prettier and eslint configs.
-   `npm run prepare`: Prepares .husky
-   `npm run test`: Runs jest configuration.
-   `npm run test:watch`: Runs jest watch mode.
-   `npm run clean`: Removes node_modules and package-lock.json.
-   `npm run reinstall`: Creates a clean installation.

## Hooks

-   `pre-commit` hook: Checks for eslint errors and fixes them automatically for you when you are commiting. Once it has finished its job, your commit is finished.

Feel free to add more hooks. Read more about [husky](https://typicode.github.io/husky/#/).

## Project Status

### Current

Completely configured boilerplate.

## Support me

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/gbraad)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/LoretaKrasteva?locale.x=en_GB)

<!-- USAGE EXAMPLES -->

## Deployment

-   `npm run build` - Builds the app for production. It correctly bundles React in production mode and optimizes the build for the best performance. Your app is ready to be deployed!

Once you have ran `npm run build`, you can run the production build locally with `npm start`.

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/gwicho38/lefv-io/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See [LICENSE](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) for more information.

<!-- CONTACT -->

## Contact

### Author

<h1>lefv</h1>

<a href="https://github.com/lucky-lore" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
<a href="https://www.npmjs.com/~lucky-lore" target="_blank">
<img src=https://img.shields.io/badge/npm-%2324292e.svg?&style=for-the-badge&logo=npm&logoColor=red alt=npm style="margin-bottom: 5px;" />
</a>
<a href="https://linkedin.com/in/loretta-krasteva" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://twitter.com/_luckylore" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a>

Project Link: [nextjs-ts-rtl-jest-prettier-boilerplate](https://github.com/gwicho38/lefv-io)

<!-- ACKNOWLEDGEMENTS -->

## References

-   [React](https://reactjs.org/)
-   [NextJS](https://nextjs.org/)
-   [Typescript](https://www.typescriptlang.org/)
-   [SASS](https://sass-lang.com/)
-   [Redux Toolkit](https://redux-toolkit.js.org/)
-   [Jest](https://jestjs.io/)
-   [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
-   [Husky](https://typicode.github.io/husky/#/)
-   [Prettier](https://prettier.io/)
-   [package-json](https://docs.npmjs.com/cli/v8/configuring-npm/package-json)
-   [favicon](https://favicon.io/favicon-generator/)
-   [shields](https://shields.io/)
-   [next-js-ts-trl-boilerplate](https://github.com/lucky-lore/nextjs-ts-rtl-jest-prettier-boilerplate)
