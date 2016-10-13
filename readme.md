# Arctic Web

Frontend web design.

## Development
To run the development environment, ensure you first have [NodeJS](https://nodejs.org/en/) 4.x installed and then run the following commands:

```bash
npm install
npm run local
```

This will install the required dependencies, start the [HarpJS](https://harpjs.com/) server and the start [Browser Sync](https://www.browsersync.io/). Starting Browser Sync will launch [Google Chrome](https://www.google.com/chrome/) and watch for file changes, automatically refreshing the page when files are updated and saved.

When local development is finished, you'll need to compile down to static files. To do this, use the following command:

```bash
npm run compile
```

This will compile down the code into static files and place them in the `dist` directory.
