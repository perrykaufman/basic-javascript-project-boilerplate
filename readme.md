# Basic Javascript Project Boilerplate

Get up and running with a basic single page javascript project that includes es6, stylus/sass, webpack, jasmine/karma, and eslint/prettier.

## How to Use

```
npm install

# dev server
npm run dev

# tests
npm run test

# build
npm run build
```

### File Structure

The basic project structure. Webpack aliases are included in parentheses.

* **src/** (@) project code
* **src/index.html** web page
* **src/index.js** root javascript file
* **src/public/** (@public) static assets copied to root directory 
* **src/styles/** (@styles) styles, each file must be imported into index.js
* **src/lib/** (@lib) javascript files
* **test/** (@test) test files ending with *.test.js