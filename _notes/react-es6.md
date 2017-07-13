## Use es6 with React
    $npm install –save-dev babel-preset-es2015

    "scripts": {
        "compile": "babel src --presets react,es2015 --out-dir static",
        "watch": "babel src --presets react,es2015 --out-dir static --watch",
        "test": "echo \"Error: no test specified\" && exit 1"
    },

    ES2015 also comes with many built-in objects and extensions,
    which are not syntactic changes. For example, the Promise object is an ES2015
    specification, as is the array find() method. These are not supported by older browsers
    such as Internet Explorer 11 and earlier. And, a transpile is not enough to add these new
    capabilities.
    If you must support those browsers and want to use these built-in functions, you need
    to add support to the browser via a JavaScript library. These are called polyfills, things that
    supplement browser capabilities or global functions.