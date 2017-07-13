## React transform
    $ npm install -g babel-cli                               # 
    $ npm install --save-dev babel-cli babel-preset-react    # for num run

    # Transform all jsx files under folder "src" into js and put them to folder "static" 
    $ babel src --presets react --out-dir static
    or
    $ node_modules/.bin/babel src --presets react --out-dir static
    or use npm script
    "scripts": {
        "compile": "babel src --presets react --out-dir static",
        "watch": "babel src --presets react --out-dir static –watch",
        "test": "echo \"Error: no test specified\" && exit 1"
    }
    $ npm run compile