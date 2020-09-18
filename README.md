## Installation

Install the latest version of node and npm to get started.

Run the following command in the base directory to install all the dependencies:

```shell
npm install
```

## How to run/build

Run in development mode:

```shell
npm run dev
```

Generate a production build:

```shell
npm run build
```

You will be able to upload the 'dist/' folder created after running the above command to a host like Netlify so everyone can access it.

## What is Parcel.js?

The website is being bundled using Parcel.js

Parcel will bundle all your assets HTML, CSS and JS out of the box. You can also install plugins if you want to use anything extra. By default Parcel is performs code transformations using Babel, PostCSS and PostHTML (e.g. you can write es6 code directly). It is watching for code changes and replaces modules automatically in the browser if needed.

You can read more about it here: https://parceljs.org/

## VScode Live Server extension

If you don't want to use parcel then just install the 'Live Server' (https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VSCODE and get started right away

## What is a package.json file?

If you want to know about the package.json file: https://dev.to/easybuoy/understanding-the-package-json-file-3fdg#:~:text=json%20file-,A%20package.,and%20a%20whole%20lot%20more.
