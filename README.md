# Laravel Vite Configuration

This repository contains the standard Vite configuration file used by ArtPort's Laravel applications.

## Installation

Simply add the package to `package.json` like so:

```bash
"devDependencies": {
    "@artport/laravel-vite-configuration": "github:artport/laravel-vite-configuration"
},
```

Then add it to the `package.json` file's "scripts" section:

```js
"scripts": {
    "dev": "vite --config node_modules/@artport/laravel-vite-configuration/laravel-vite-configuration.js",
    "production": "vite build --config node_modules/@artport/laravel-vite-configuration/laravel-vite-configuration.js"
},
```
