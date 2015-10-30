## Browserify + TypeScript

This is a minimum working example of [browserify](https://www.npmjs.com/package/browserify) with [tsify](https://www.npmjs.com/package/tsify), used to bundle `.tsx` files into a single `main.js` file.

#### Folder structure:

 - `/`: configs
 - `/src/`: TypeScript files
 - `/public/`: files accessed in browser 

### Usage

1. Clone this project.
2. `npm install` to get dependencies.
3. `npm run build` to compile `.tsx` files into `public/main.js`.
4. Open `public/index.html` in your browser to see the results.
